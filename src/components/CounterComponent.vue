<template>
  <span v-if="loaded" class="counter">
    <span v-if="displayDays != 0" class="number">{{ displayDays }}:</span>
    <span class="number">{{ displayHours }}:</span>
    <span class="number">{{ displayMinutes }}</span>
  </span>
</template>

<script>
export default {
  data: () => ({
    displayDays: 0,
    displayHours: 0,
    displayMinutes: 0,
    displaySeconds: 0,
    loaded: false,
  }),
  computed: {
    _seconds: () => 1000,
    _minutes() {
      return this._seconds * 60;
    },
    _hours() {
      return this._minutes * 60;
    },
    _days() {
      return this._hours * 24;
    },
  },
  mounted() {
    this.showRemaining();
  },
  methods: {
    formatNum: (num) => (num < 10 ? "0" + num : num),

    showRemaining() {
      const timer = setInterval(() => {
        const currentDate = new Date();
        const endDate = new Date(2023, 7, 4, 0, 0, 0, 0);
        const distance = endDate.getTime() - currentDate.getTime();

        if (distance < 0) {
          clearInterval(timer);

          this.displayHours = this.formatNum(0);
          this.displayMinutes = this.formatNum(0);
          this.loaded = true;
          return;
        }

        const days = Math.floor(distance / this._days);
        const hours = Math.floor((distance % this._days) / this._hours);
        const minutes = Math.floor((distance % this._hours) / this._minutes);
        const seconds = Math.floor((distance % this._minutes) / this._seconds);
        this.displayDays = this.formatNum(days);
        this.displayHours = this.formatNum(hours);
        this.displayMinutes = this.formatNum(minutes);
        this.displaySeconds = this.formatNum(seconds);

        this.loaded = true;
      }, 1000);
    },
  },
};
</script>

<style lang="less" scoped>
.counter {
  display: inline-flex;
}
</style>

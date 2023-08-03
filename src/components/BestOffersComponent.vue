<template>
  <div class="best">
    <div class="container">
      <div class="best-wrap">
        <span class="best-title"> Choose what’s best for you </span>
        <span class="best-timer">
          Your approval is reserved for
          <counter-component-vue></counter-component-vue>
        </span>
        <div class="best-offers">
          <div class="best-block">
            <div
              @click.stop="chooseOffer(offer)"
              class="best-item"
              :class="{ active: offer.offerStatus}"
              v-for="offer in offers"
              :key="offer.id"
            >
              <div class="best-item__icon"></div>
              <div class="best-item__desc">
                <div class="best-item__sell">
                  <span class="best-item__title"> {{ offer.name }} </span>
                  <span v-if="offer.sellStatus" class="best-item__off">
                    <span class="number">{{ offer.sell }}</span
                    >% OFF
                  </span>
                </div>
                <span class="best-item__info">
                  Pay $<span class="number">{{ offer.pay }}</span> today
                </span>
              </div>
              <div class="best-item__price">
                <span v-if="offer.oldPrice" class="best-item__old">
                  $<span class="number">{{ offer.oldPrice }}</span>
                </span>
                <span class="best-item__value">
                  $<span class="number">{{ offer.perMonth }}</span>
                </span>
                <span class="best-item__text"> Per Month </span>
              </div>
            </div>
          </div>
          <button class="best-offers__btn btn">
            <span> Checkout </span>
            <svg
              width="17"
              height="12"
              viewBox="0 0 17 12"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16.14 6.71875L12.14 10.7188C11.765 11.125 11.1087 11.125 10.7337 10.7188C10.3275 10.3438 10.3275 9.6875 10.7337 9.3125L13.015 7H1.4525C0.889999 7 0.452499 6.5625 0.452499 6C0.452499 5.40625 0.889999 5 1.4525 5H13.015L10.7337 2.71875C10.3275 2.34375 10.3275 1.6875 10.7337 1.3125C11.1087 0.90625 11.765 0.90625 12.14 1.3125L16.14 5.3125C16.5462 5.6875 16.5462 6.34375 16.14 6.71875Z"
                fill="white"
              />
            </svg>
          </button>
        </div>
        <div class="best-award">
          <div class="best-award__img">
            <img src="../assets/images/best/Badge.png" alt="" />
          </div>
          <div class="best-award__desc">
            <span class="best-award__title"> 5-Mo Weight Loss Guarantee </span>
            <p class="best-award__text">
              If for any reason you’re not 100% satisfied with the G-Plans Pro
              plan, we will give you a full refund, no guestions asked.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import CounterComponentVue from './CounterComponent.vue';

export default {
  components: {
    CounterComponentVue,
  },
  data: () => ({
    offers: [
      {
        id: 0,
        name: "In full",
        pay: 495,
        oldPrice: 129,
        perMonth: 99,
        sell: 30,
        sellStatus: true,
        offerStatus: true
      },
      {
        id: 1,
        name: "Monthly",
        pay: 129,
        oldPrice: 0,
        perMonth: 129,
        sell: 0,
        sellStatus: false,
        offerStatus: false
      },
    ],
  }),
  methods: {
    chooseOffer(item) {
      this.offers.forEach((offer) => {
        if (offer === item) {
          offer.offerStatus = true;

          return offer.perMonth;
        } else {
            offer.offerStatus = false;
        }
      });
    },
  },
};
</script>

<style></style>

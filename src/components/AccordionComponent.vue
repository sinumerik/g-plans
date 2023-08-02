<template>
  <div class="accordion">
    <div class="container">
      <div class="accordion-wrap">
        <span class="accordion-title"> Frequently asked questions </span>
        <div class="accordion-item" v-for="item in questions" :key="item.id">
          <div
            class="accordion-head"
            @click="openClose(item.id)"
            :class="{ active: item.active }"
          >
            <div class="accordion-head__icon">
              <svg
                width="12"
                height="6"
                viewBox="0 0 12 6"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M10.6875 1.71875L6.71875 5.71875C6.5 5.90625 6.25 6 6 6C5.71875 6 5.46875 5.90625 5.28125 5.71875L1.3125 1.71875C1 1.4375 0.90625 1 1.0625 0.625C1.21875 0.25 1.59375 0 2 0H9.96875C10.375 0 10.7188 0.25 10.875 0.625C11.0312 1 10.9688 1.4375 10.6875 1.71875Z"
                  fill="#B18FFF"
                />
              </svg>
            </div>
            <span class="accordion-head__title">
              {{ item.title }}
            </span>
          </div>
          <div class="accordion-body" :class="{ open: item.active }">
            {{ item.text }}
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    questions: [
      {
        id: 0,
        active: false,
        title: "How does G-Plans Metabolic Meal delivery service work?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 1,
        title: "Can I choose my own meals?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 2,
        active: false,
        title:
          "Is the food really fresh and how long does the food take to arrive?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 3,
        active: false,
        title:
          "Does G-Plans give nutrition and calorie information on these meals?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 4,
        active: false,
        title:
          "Why should I use these G-Plans Metabolic Meals if I am on this diet plan?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 5,
        active: false,
        title: "Can I skip a week of delivery?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 6,
        active: false,
        title: "Who is putting these meals together?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
      {
        id: 7,
        active: false,
        title: "What if I have allergies or dislike some specific foods?",
        text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia, molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum numquam blanditiis harum quisquam eius sed odit fugiat iusto fuga praesentium optio, eaque rerum! Provident similique accusantium nemo autem. Veritatis",
      },
    ],
  }),
  methods: {
    openClose(id) {
      this.questions.forEach((item) => {
        if (id === item.id && !item.active) {
          item.active = true;
        } else {
          item.active = false;
        }
      });
    },
  },
};
</script>

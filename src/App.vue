<script setup>
import AccordionComponentVue from "./components/AccordionComponent.vue";
import BestOffersComponentVue from "./components/BestOffersComponent.vue";
import CounterComponentVue from "./components/CounterComponent.vue";
import VideoComponentVue from "./components/VideoComponent.vue";

</script>

<template>
  <div class="g-plan-page">
    <div class="head">
      <div class="container">
        <div class="head-logo">
          <svg
            width="67"
            height="20"
            viewBox="0 0 67 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M5.62359 12.3261C4.23397 12.3261 3.23515 11.413 3.23515 9.95651C3.23515 8.52173 4.23397 7.60868 5.62359 7.60868C6.99151 7.60868 7.96856 8.52173 7.96856 9.95651C7.96856 11.413 6.99151 12.3261 5.62359 12.3261ZM10.9432 4.8913H8.51135C8.31595 4.8913 8.18567 5.02175 8.18567 5.21738L8.14226 6.04352C7.46918 5.15219 6.44866 4.63041 4.97222 4.63041C1.97588 4.63041 0 6.84786 0 9.95651C0 13.1087 1.97588 15.3043 4.95052 15.3043C6.40525 15.3043 7.42577 14.7826 8.09885 13.913V14.7576C7.6554 17.5525 4.85818 17.2871 3.50062 16.9834C3.17016 16.867 2.83641 16.7211 2.49696 16.5435C2.23639 16.3913 2.04099 16.5 1.9107 16.7391L1.23763 18.0652C1.10734 18.2826 1.12905 18.5652 1.34621 18.7173C2.45355 19.5652 3.99516 20 5.60189 20C8.18567 20 11.1373 18.4525 11.1373 14.5178L11.2689 5.21738C11.2689 5.02175 11.1386 4.8913 10.9432 4.8913ZM14.0806 8.7432C13.3538 8.7432 12.7647 9.33309 12.7647 10.0608C12.7647 10.7884 13.3538 11.3783 14.0806 11.3783C14.8075 11.3783 15.3966 10.7884 15.3966 10.0608C15.3966 9.33309 14.8075 8.7432 14.0806 8.7432ZM64.6538 9.41306L63.0471 8.78262C62.5694 8.58692 62.2002 8.30436 62.2002 7.91303C62.2002 7.58695 62.3956 7.2174 63.0471 7.2174C63.6333 7.2174 64.2195 7.52175 64.9143 8.0652C65.1097 8.19565 65.2618 8.21738 65.4138 8.0652L66.521 6.76087C66.6079 6.63043 66.673 6.45652 66.5428 6.30435C65.6092 5.21738 64.2847 4.63041 62.8733 4.63041C60.8324 4.63041 59.0519 5.82609 59.0519 7.91303C59.0519 9.39126 59.9639 10.3043 61.3535 10.8478L62.743 11.413C63.4596 11.6956 63.6985 11.9347 63.6985 12.3478C63.6985 12.8261 63.3077 13.0435 62.7214 13.0435C61.9614 13.0435 61.2449 12.7174 60.3113 12.0434C60.1376 11.9347 59.9422 11.8695 59.7685 12.1522L58.9 13.3696C58.748 13.5869 58.7262 13.8478 58.8348 14C59.725 15.0652 61.1363 15.8043 62.9385 15.8043C65.0881 15.8043 66.9771 14.6739 66.9987 12.4782C67.0422 10.8696 65.9782 9.93478 64.6538 9.41306ZM53.8584 4.63041C52.3385 4.63041 51.3397 5.39129 50.71 6.45652L50.6232 5.23911C50.6232 4.97828 50.4929 4.8913 50.2975 4.8913H47.7355C47.5399 4.8913 47.4097 5.02175 47.4097 5.21738V15.2174C47.4097 15.4131 47.5399 15.5434 47.7355 15.5434H50.3844C50.5798 15.5434 50.7318 15.4131 50.7318 15.2174V9.82606C50.7318 8.41308 51.4266 7.67393 52.5773 7.67393C53.7498 7.67393 54.3578 8.41308 54.3578 9.82606V15.2174C54.3578 15.4131 54.5097 15.5434 54.7051 15.5434H57.3323C57.5278 15.5434 57.6798 15.4131 57.6798 15.2174V9.04345C57.6798 6.26088 56.0731 4.63041 53.8584 4.63041ZM40.0217 12.7826C38.6104 12.7826 37.5465 11.7826 37.5465 10.2174C37.5465 8.67391 38.6104 7.6522 40.0217 7.6522C41.4764 7.6522 42.4753 8.67391 42.4753 10.1957C42.4753 11.7608 41.4764 12.7826 40.0217 12.7826ZM45.4281 4.8913H43.018C42.8227 4.8913 42.6707 5.02175 42.6707 5.21738L42.6273 6.23909C41.9324 5.23911 40.8468 4.63041 39.3052 4.63041C36.3522 4.63041 34.3113 7.06523 34.3113 10.2174C34.3113 13.3913 36.3522 15.8043 39.3052 15.8043C40.8251 15.8043 41.9107 15.1956 42.6273 14.1956L42.6707 15.2174C42.6707 15.4131 42.8227 15.5434 43.018 15.5434H45.4064C45.6018 15.5434 45.7755 15.4131 45.7755 15.2174V5.21738C45.7755 5.02175 45.6235 4.8913 45.4281 4.8913ZM32.6557 0H29.9851C29.7896 0 29.6593 0.130445 29.6593 0.326083V15.2174C29.6593 15.4131 29.7896 15.5434 29.9851 15.5434H32.6557C32.8511 15.5434 33.003 15.4131 33.003 15.2174V0.326083C33.003 0.130445 32.8511 0 32.6557 0ZM22.6187 12.7826C21.164 12.7826 20.1869 11.7608 20.1869 10.1957C20.1869 8.67391 21.164 7.6522 22.6187 7.6522C24.03 7.6522 25.094 8.67391 25.094 10.2174C25.094 11.7826 24.03 12.7826 22.6187 12.7826ZM23.3352 4.63041C21.7936 4.63041 20.708 5.23911 20.0132 6.26088L19.9697 5.21738C19.9697 5.02175 19.8178 4.8913 19.6224 4.8913H17.2123C17.0169 4.8913 16.8866 5.02175 16.8866 5.21738V19.2857C16.8866 19.4814 17.0169 19.6118 17.2123 19.6118H19.8829C20.0783 19.6118 20.2303 19.4814 20.2303 19.2857V14.4347C20.9251 15.3043 21.9456 15.8043 23.3352 15.8043C26.3098 15.8043 28.3509 13.3913 28.3509 10.2174C28.3509 7.06523 26.3098 4.63041 23.3352 4.63041Z"
              fill="#4E00FF"
            />
          </svg>
        </div>
      </div>
    </div>

    <div class="timer">
      <div class="container">
        Your approval expires in
        <counter-component-vue></counter-component-vue>
      </div>
    </div>

    <div class="hero">
      <div class="container">
        <div class="hero-wrap">
          <div class="hero-plan">
            <span class="hero-plan__text">
              Jessica’s 5-month prescription plan has been
              <span class="italic">approved</span>!
            </span>
            <div class="hero-plan__info">
              <svg
                width="68"
                height="13"
                viewBox="0 0 68 13"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M7.40625 0.921875L8.95312 4.03906L12.375 4.53125C12.9844 4.625 13.2422 5.375 12.7969 5.82031L10.3125 8.21094L10.8984 11.6094C10.9922 12.2188 10.3594 12.6875 9.79688 12.4062L6.75 10.8125L3.67969 12.4297C3.11719 12.7109 2.48438 12.2422 2.57812 11.6328L3.16406 8.23438L0.679688 5.82031C0.234375 5.375 0.492188 4.625 1.10156 4.53125L4.52344 4.03906L6.07031 0.921875C6.35156 0.359375 7.14844 0.382812 7.40625 0.921875ZM20.9062 0.921875L22.4531 4.03906L25.875 4.53125C26.4844 4.625 26.7422 5.375 26.2969 5.82031L23.8125 8.21094L24.3984 11.6094C24.4922 12.2188 23.8594 12.6875 23.2969 12.4062L20.25 10.8125L17.1797 12.4297C16.6172 12.7109 15.9844 12.2422 16.0781 11.6328L16.6641 8.23438L14.1797 5.82031C13.7344 5.375 13.9922 4.625 14.6016 4.53125L18.0234 4.03906L19.5703 0.921875C19.8516 0.359375 20.6484 0.382812 20.9062 0.921875ZM34.4062 0.921875L35.9531 4.03906L39.375 4.53125C39.9844 4.625 40.2422 5.375 39.7969 5.82031L37.3125 8.21094L37.8984 11.6094C37.9922 12.2188 37.3594 12.6875 36.7969 12.4062L33.75 10.8125L30.6797 12.4297C30.1172 12.7109 29.4844 12.2422 29.5781 11.6328L30.1641 8.23438L27.6797 5.82031C27.2344 5.375 27.4922 4.625 28.1016 4.53125L31.5234 4.03906L33.0703 0.921875C33.3516 0.359375 34.1484 0.382812 34.4062 0.921875ZM47.9062 0.921875L49.4531 4.03906L52.875 4.53125C53.4844 4.625 53.7422 5.375 53.2969 5.82031L50.8125 8.21094L51.3984 11.6094C51.4922 12.2188 50.8594 12.6875 50.2969 12.4062L47.25 10.8125L44.1797 12.4297C43.6172 12.7109 42.9844 12.2422 43.0781 11.6328L43.6641 8.23438L41.1797 5.82031C40.7344 5.375 40.9922 4.625 41.6016 4.53125L45.0234 4.03906L46.5703 0.921875C46.8516 0.359375 47.6484 0.382812 47.9062 0.921875ZM61.4062 0.921875L62.9531 4.03906L66.375 4.53125C66.9844 4.625 67.2422 5.375 66.7969 5.82031L64.3125 8.21094L64.8984 11.6094C64.9922 12.2188 64.3594 12.6875 63.7969 12.4062L60.75 10.8125L57.6797 12.4297C57.1172 12.7109 56.4844 12.2422 56.5781 11.6328L57.1641 8.23438L54.6797 5.82031C54.2344 5.375 54.4922 4.625 55.1016 4.53125L58.5234 4.03906L60.0703 0.921875C60.3516 0.359375 61.1484 0.382812 61.4062 0.921875Z"
                  fill="#FFE786"
                />
              </svg>
              <span class="hero-plan__reviews"> 5.4k reviews </span>
            </div>
          </div>
          <div class="hero-description">
            <div class="hero-description__tab">
              <span class="hero-description__text"> Age </span>
              <span class="hero-description__value"> 35 </span>
            </div>
            <div class="hero-description__tab">
              <span class="hero-description__text"> Metabolism </span>
              <span class="hero-description__value"> Fat & Protien Eff. </span>
            </div>
            <div class="hero-description__tab">
              <span class="hero-description__text"> Sex </span>
              <span class="hero-description__value"> Female </span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="chart">
      <div class="container">
        <p class="chart-text">
          You’ll get personalized care for your unique biology with
          <span class="bold">prescribed medication</span>, 1:1 dietician
          guidance, an
          <span class="bold">expert-designed weekly meal plan</span>, and
          community support.
        </p>
      </div>

      <div class="chart-shedule">
        <div class="chart-start">
          <span class="chart-start__value" data-counter="180"> 180 </span>
          <span class="chart-start__text"> LBS </span>
        </div>
        <div class="chart-end">
          <div class="chart-end__info">
            <span class="chart-end__value" data-counter="145"> 145 </span>
            <span class="chart-end__text">LBS</span>
          </div>
          <span class="chart-end__goal"> Goal Weight </span>
          <div class="chart-end__firework">
            <img src="./assets/images/chart/firework.png" alt="firework" />
          </div>
        </div>

        <svg
          width="394"
          height="126"
          viewBox="0 0 394 126"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path d="M0.5 84.5H393.5" stroke="#32264A" stroke-linecap="square" />
          <path d="M0.5 44.5H393.5" stroke="#32264A" stroke-linecap="square" />
          <path d="M0.5 4.5H393.5" stroke="#32264A" stroke-linecap="square" />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M50.5 124.5V1.5C50.5 1.5 74.0481 25.1091 103.446 34C132.844 42.8909 180.5 50.5 180.5 50.5L314.5 70.6607V124.5H50.5Z"
            fill="url(#paint0_linear_1_10)"
          />
          <path
            d="M50.5 1.5V124.5"
            stroke="#4E00FF"
            stroke-width="2"
            stroke-linecap="square"
            stroke-dasharray="10 10"
          />
          <path
            d="M314.5 59.5V124.5"
            stroke="#4E00FF"
            stroke-width="2"
            stroke-linecap="square"
            stroke-dasharray="10 10"
          />
          <path
            d="M180.5 50.5V124.5"
            stroke="#4E00FF"
            stroke-width="2"
            stroke-linecap="square"
            stroke-dasharray="10 10"
          />
          <path
            d="M51 3.22412C82.2946 34.9775 138.466 44.9775 190 51.6368C241.534 58.2962 288.537 67 329 80.0496"
            stroke="url(#paint1_linear_1_10)"
            stroke-width="4"
          />
          <defs>
            <linearGradient
              id="paint0_linear_1_10"
              x1="133.303"
              y1="52.4692"
              x2="131.418"
              y2="122.664"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#B900FF" stop-opacity="0.43562" />
              <stop offset="1" stop-color="#4E00FF" stop-opacity="0.01" />
            </linearGradient>
            <linearGradient
              id="paint1_linear_1_10"
              x1="124.786"
              y1="39.3258"
              x2="249.357"
              y2="39.3258"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#4E00FF" />
              <stop offset="1" stop-color="#EC00FF" />
            </linearGradient>
          </defs>
        </svg>
        <div class="chart-date">
          <span class="chart-date__start"> 11/23 </span>
          <span class="chart-date__middle"> 02/22/2022 </span>
          <span class="chart-date__end"> <span>BY</span>05/25/2022 </span>
        </div>
      </div>

      <div class="container">
        <div class="banner">
          <div class="banner-img">
            <img src="./assets/images/chart/ozempic.png" alt="" />
          </div>
          <span class="banner-text">
            You have a <span class="bold italic">very high</span> chance of
            success with GLP-1 medications
          </span>
          <div class="banner-percent">
            <span class="banner-percent__value"> 93.6% </span>
            <span class="banner-percent__text"> VERY HIGH </span>
          </div>
        </div>
      </div>
    </div>

    <div class="plan">
      <div class="container">
        <div class="plan-title">
          The goals
          <span class="italic"
            >you will <br />
            accomplish</span
          >
          with your plan
        </div>
        <div class="plan-info">
          <div class="plan-info__img">
            <img src="./assets/images/plan/cup.png" alt="" />
          </div>
          <div class="plan-info__list">
            <div class="plan-info__item">
              Lose <span class="number">35</span> lbs
            </div>
            <div class="plan-info__item">
              Reset your “set point” so your body wants to naturally stay at
              <span class="number">145</span>
              lbs
            </div>
            <div class="plan-info__item">Look and feel healthier</div>
          </div>
        </div>
        <div class="plan-arrow">
          <svg
            width="109"
            height="134"
            viewBox="0 0 109 134"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M29.2304 132.188C29.2134 133.016 29.8711 133.702 30.6993 133.719L44.1965 133.996C45.0247 134.013 45.7099 133.355 45.727 132.527C45.744 131.699 45.0863 131.014 44.2581 130.997L32.2606 130.75L32.5071 118.753C32.5242 117.924 31.8665 117.239 31.0383 117.222C30.21 117.205 29.5248 117.863 29.5078 118.691L29.2304 132.188ZM102.447 1.21899C101.025 1.69537 101.024 1.69513 101.024 1.69504C101.024 1.69521 101.025 1.69528 101.025 1.69562C101.025 1.69632 101.025 1.69762 101.026 1.69952C101.027 1.70333 101.029 1.70956 101.032 1.71817C101.038 1.73539 101.047 1.76215 101.058 1.79823C101.082 1.87037 101.117 1.97973 101.162 2.12441C101.253 2.41379 101.385 2.84435 101.547 3.40096C101.872 4.5144 102.316 6.13095 102.789 8.1297C103.738 12.131 104.802 17.6449 105.272 23.7096C106.22 35.9472 104.712 49.9328 95.5953 58.5547L97.6566 60.7343C107.821 51.1215 109.225 35.8944 108.263 23.4779C107.777 17.2155 106.681 11.5421 105.708 7.43776C105.222 5.3837 104.764 3.71788 104.428 2.56216C104.259 1.98418 104.121 1.53346 104.024 1.22521C103.976 1.07107 103.938 0.95252 103.912 0.871463C103.898 0.830933 103.888 0.799773 103.881 0.778221C103.877 0.767445 103.875 0.75907 103.873 0.753126C103.872 0.750155 103.871 0.74779 103.87 0.746038C103.87 0.745162 103.87 0.744306 103.87 0.743868C103.869 0.743167 103.869 0.742618 102.447 1.21899ZM95.5953 58.5547C90.9492 62.9485 83.4517 67.5143 74.6018 71.3766C65.7712 75.2304 55.6965 78.339 45.9613 79.8737C36.2032 81.4119 26.9132 81.3487 19.5807 78.9823C12.3166 76.638 7.02316 72.0642 4.93807 64.4707L2.04515 65.265C4.44905 74.0197 10.6317 79.2465 18.6593 81.8373C26.6184 84.406 36.4354 84.4124 46.4285 82.8371C56.4444 81.2582 66.7648 78.07 75.8018 74.1261C84.8194 70.1907 92.6619 65.4578 97.6566 60.7343L95.5953 58.5547ZM4.93807 64.4707C2.75946 56.5365 3.06464 49.9983 4.91468 44.8311C6.76352 39.6672 10.1904 35.7712 14.4347 33.164C22.9752 27.9176 34.7878 27.9174 43.4307 33.4356L45.0451 30.907C35.4254 24.7652 22.3759 24.765 12.8644 30.6077C8.08274 33.5451 4.18612 37.966 2.09025 43.8198C-0.00442827 49.6704 -0.265227 56.8509 2.04515 65.265L4.93807 64.4707ZM43.4307 33.4356C51.9026 38.8446 55.6901 50.3978 55.7711 63.8811C55.8516 77.2806 52.2514 92.0912 46.5386 103.338L49.2133 104.697C55.1423 93.0242 58.8544 77.7417 58.771 63.863C58.6882 50.068 54.8357 37.1579 45.0451 30.907L43.4307 33.4356ZM46.5386 103.338C40.7388 114.756 36.4833 121.75 33.6949 125.872C32.3012 127.933 31.2763 129.272 30.6109 130.086C30.2784 130.493 30.0361 130.767 29.8831 130.934C29.8066 131.018 29.7524 131.074 29.7205 131.107C29.7046 131.124 29.6942 131.134 29.6893 131.139C29.6869 131.141 29.6859 131.142 29.6863 131.142C29.6864 131.142 29.687 131.141 29.6878 131.14C29.6883 131.14 29.6888 131.139 29.6894 131.139C29.6897 131.138 29.6902 131.138 29.6904 131.138C29.6909 131.137 29.6915 131.137 30.7301 132.219C31.7688 133.301 31.7694 133.301 31.77 133.3C31.7703 133.3 31.7709 133.299 31.7714 133.299C31.7723 133.298 31.7733 133.297 31.7745 133.296C31.7767 133.294 31.7792 133.291 31.7821 133.288C31.7878 133.283 31.7949 133.276 31.8032 133.268C31.8199 133.251 31.8419 133.229 31.8691 133.201C31.9235 133.145 31.9989 133.066 32.0957 132.96C32.2891 132.749 32.5678 132.432 32.9332 131.985C33.6636 131.092 34.7423 129.678 36.1798 127.553C39.0539 123.304 43.3714 116.198 49.2133 104.697L46.5386 103.338Z"
              fill="#442E74"
            />
          </svg>
        </div>
        <div class="plan-description">
          <div class="plan-description__wrap">
            <span class="plan-description__title"> Jessica’s plan </span>
            <p class="plan-description__text">
              You’ll get
              <span class="italic bold">everything you need</span>
              to drop those <span class="number">35</span> lbs and keep them
              off.
            </p>
          </div>
          <div class="plan-description__img">
            <img src="./assets/images/plan/complex.png" alt="" />
          </div>
        </div>
        <div class="plan-include">
          <span class="plan-include__title"> What’s included? </span>
          <div class="plan-include__list">
            <div class="plan-include__item">
              <div class="plan-include__img">
                <img src="./assets/images/plan/include1.png" alt="" />
              </div>
              <span class="plan-include__text">
                Access to Wegovy® or Ozempic®*
              </span>
            </div>
            <div class="plan-include__item">
              <div class="plan-include__img align-items-center">
                <img src="./assets/images/plan/include2.png" alt="" />
              </div>
              <span class="plan-include__text">
                Telehealth doctor appt. & 1:1 dietician guidance
              </span>
            </div>
            <div class="plan-include__item">
              <div class="plan-include__img">
                <img src="./assets/images/plan/include3.png" alt="" />
              </div>
              <span class="plan-include__text">
                Weekly updated diet plan based on metabolism
              </span>
            </div>
            <div class="plan-include__item">
              <div class="plan-include__img">
                <img src="./assets/images/plan/include4.png" alt="" />
              </div>
              <span class="plan-include__text">
                Daily nutrition curriculum
              </span>
            </div>
            <div class="plan-include__item">
              <div class="plan-include__img">
                <img src="./assets/images/plan/include5.png" alt="" />
              </div>
              <span class="plan-include__text"> Metabolic test report </span>
            </div>
          </div>
          <a href="#" class="plan-include__link"> + community and more! </a>
        </div>
      </div>
    </div>

    <best-offers-component-vue></best-offers-component-vue>

    <div class="company">
      <div class="container">
        <div class="company-wrap">
          <span class="company-title"> Backed by research from </span>
          <div class="company-block">
            <div class="company-item">
              <img src="./assets/images/company/company1.png" alt="" />
            </div>
            <div class="company-item">
              <img src="./assets/images/company/company2.png" alt="" />
            </div>
            <div class="company-item">
              <img src="./assets/images/company/company3.png" alt="" />
            </div>
            <div class="company-item">
              <img src="./assets/images/company/company4.png" alt="" />
            </div>
            <div class="company-item">
              <img src="./assets/images/company/company5.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="advantages">
      <div class="container">
        <div class="advantages-wrap">
          <span class="advantages-title">
            What makes G-Plans
            <span class="italic">so much better</span> than anything else?
          </span>
          <div class="advantages-block">
            <div class="advantages-item">
              <div class="advantages-item__img">
                <img src="./assets/images/advantages/advantages1.svg" alt="" />
              </div>
              <span class="advantages-item__value"> 15% </span>
              <span class="advantages-item__text">
                Average reduction in <br />
                body weight
              </span>
            </div>
            <div class="advantages-item">
              <div class="advantages-item__img">
                <img src="./assets/images/advantages/advantages2.svg" alt="" />
              </div>
              <span class="advantages-item__value"> 8/10 </span>
              <span class="advantages-item__text">
                Users say this is more effective <br />
                than anything they’ve ever tried
              </span>
            </div>
            <div class="advantages-item">
              <div class="advantages-item__img">
                <img src="./assets/images/advantages/advantages3.svg" alt="" />
              </div>
              <span class="advantages-item__value"> 6” </span>
              <span class="advantages-item__text">
                Average reduction in <br />
                waist size
              </span>
            </div>
            <div class="advantages-item">
              <div class="advantages-item__img">
                <img src="./assets/images/advantages/advantages4.svg" alt="" />
              </div>
              <span class="advantages-item__value"> 92% </span>
              <span class="advantages-item__text">
                Users have achieved <br />
                lasting weight loss
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <video-component-vue></video-component-vue>

    <div class="reviews">
      <div class="container">
        <div class="reviews-item">
          <div class="reviews-item__head">
            <span class="reviews-item__title">
              “My weight loss journey with G-Plans”
            </span>
            <div class="reviews-item__img">
              <svg
                width="68"
                height="13"
                viewBox="0 0 68 13"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M7.40625 0.921875L8.95312 4.03906L12.375 4.53125C12.9844 4.625 13.2422 5.375 12.7969 5.82031L10.3125 8.21094L10.8984 11.6094C10.9922 12.2188 10.3594 12.6875 9.79688 12.4062L6.75 10.8125L3.67969 12.4297C3.11719 12.7109 2.48438 12.2422 2.57812 11.6328L3.16406 8.23438L0.679688 5.82031C0.234375 5.375 0.492188 4.625 1.10156 4.53125L4.52344 4.03906L6.07031 0.921875C6.35156 0.359375 7.14844 0.382812 7.40625 0.921875ZM20.9062 0.921875L22.4531 4.03906L25.875 4.53125C26.4844 4.625 26.7422 5.375 26.2969 5.82031L23.8125 8.21094L24.3984 11.6094C24.4922 12.2188 23.8594 12.6875 23.2969 12.4062L20.25 10.8125L17.1797 12.4297C16.6172 12.7109 15.9844 12.2422 16.0781 11.6328L16.6641 8.23438L14.1797 5.82031C13.7344 5.375 13.9922 4.625 14.6016 4.53125L18.0234 4.03906L19.5703 0.921875C19.8516 0.359375 20.6484 0.382812 20.9062 0.921875ZM34.4062 0.921875L35.9531 4.03906L39.375 4.53125C39.9844 4.625 40.2422 5.375 39.7969 5.82031L37.3125 8.21094L37.8984 11.6094C37.9922 12.2188 37.3594 12.6875 36.7969 12.4062L33.75 10.8125L30.6797 12.4297C30.1172 12.7109 29.4844 12.2422 29.5781 11.6328L30.1641 8.23438L27.6797 5.82031C27.2344 5.375 27.4922 4.625 28.1016 4.53125L31.5234 4.03906L33.0703 0.921875C33.3516 0.359375 34.1484 0.382812 34.4062 0.921875ZM47.9062 0.921875L49.4531 4.03906L52.875 4.53125C53.4844 4.625 53.7422 5.375 53.2969 5.82031L50.8125 8.21094L51.3984 11.6094C51.4922 12.2188 50.8594 12.6875 50.2969 12.4062L47.25 10.8125L44.1797 12.4297C43.6172 12.7109 42.9844 12.2422 43.0781 11.6328L43.6641 8.23438L41.1797 5.82031C40.7344 5.375 40.9922 4.625 41.6016 4.53125L45.0234 4.03906L46.5703 0.921875C46.8516 0.359375 47.6484 0.382812 47.9062 0.921875ZM61.4062 0.921875L62.9531 4.03906L66.375 4.53125C66.9844 4.625 67.2422 5.375 66.7969 5.82031L64.3125 8.21094L64.8984 11.6094C64.9922 12.2188 64.3594 12.6875 63.7969 12.4062L60.75 10.8125L57.6797 12.4297C57.1172 12.7109 56.4844 12.2422 56.5781 11.6328L57.1641 8.23438L54.6797 5.82031C54.2344 5.375 54.4922 4.625 55.1016 4.53125L58.5234 4.03906L60.0703 0.921875C60.3516 0.359375 61.1484 0.382812 61.4062 0.921875Z"
                  fill="#FFE786"
                />
              </svg>
            </div>
          </div>
          <p class="reviews-item__text">
            I have been happy with my G-Plans experience so far! It’s been the
            only real successful way I’ve been able to lose weight!”
          </p>
          <div class="reviews-item__footer">
            <span class="reviews-item__name"> Phyllis J. </span>
            <div class="reviews-item__verifed">
              <svg
                width="17"
                height="16"
                viewBox="0 0 17 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M16.9688 8C16.9688 9.15625 16.4062 10.1562 15.5 10.7188C15.7188 11.75 15.4375 12.875 14.625 13.6562C13.8438 14.4688 12.7188 14.7812 11.6875 14.5625C11.0938 15.4375 10.125 16 8.96875 16C7.84375 16 6.84375 15.4375 6.25 14.5625C5.21875 14.7812 4.125 14.4688 3.3125 13.6562C2.53125 12.875 2.21875 11.75 2.4375 10.7188C1.5625 10.1562 0.96875 9.15625 0.96875 8C0.96875 6.875 1.5625 5.875 2.4375 5.3125C2.21875 4.28125 2.53125 3.15625 3.3125 2.34375C4.125 1.5625 5.25 1.25 6.25 1.46875C6.84375 0.59375 7.84375 0 8.96875 0C10.125 0 11.0938 0.59375 11.6875 1.46875C12.7188 1.25 13.8438 1.5625 14.625 2.34375C15.4375 3.15625 15.7188 4.28125 15.5 5.3125C16.375 5.875 16.9688 6.875 16.9688 8ZM12 6.78125C12.3125 6.5 12.3125 6.03125 12 5.75C11.7188 5.4375 11.25 5.4375 10.9688 5.75L8 8.71875L7 7.75C6.71875 7.4375 6.25 7.4375 5.96875 7.75C5.65625 8.03125 5.65625 8.5 5.96875 8.78125L7.46875 10.2812C7.59375 10.4375 7.78125 10.5 8 10.5C8.1875 10.5 8.375 10.4375 8.5 10.2812L12 6.78125Z"
                  fill="#B18FFF"
                />
              </svg>
              <span class="reviews-item__customer"> Verified customer </span>
            </div>
          </div>
        </div>
        <div class="reviews-item">
          <div class="reviews-item__head">
            <span class="reviews-item__title">
              “This program has been life changing for me”
            </span>
            <div class="reviews-item__img">
              <svg
                width="68"
                height="13"
                viewBox="0 0 68 13"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M7.40625 0.921875L8.95312 4.03906L12.375 4.53125C12.9844 4.625 13.2422 5.375 12.7969 5.82031L10.3125 8.21094L10.8984 11.6094C10.9922 12.2188 10.3594 12.6875 9.79688 12.4062L6.75 10.8125L3.67969 12.4297C3.11719 12.7109 2.48438 12.2422 2.57812 11.6328L3.16406 8.23438L0.679688 5.82031C0.234375 5.375 0.492188 4.625 1.10156 4.53125L4.52344 4.03906L6.07031 0.921875C6.35156 0.359375 7.14844 0.382812 7.40625 0.921875ZM20.9062 0.921875L22.4531 4.03906L25.875 4.53125C26.4844 4.625 26.7422 5.375 26.2969 5.82031L23.8125 8.21094L24.3984 11.6094C24.4922 12.2188 23.8594 12.6875 23.2969 12.4062L20.25 10.8125L17.1797 12.4297C16.6172 12.7109 15.9844 12.2422 16.0781 11.6328L16.6641 8.23438L14.1797 5.82031C13.7344 5.375 13.9922 4.625 14.6016 4.53125L18.0234 4.03906L19.5703 0.921875C19.8516 0.359375 20.6484 0.382812 20.9062 0.921875ZM34.4062 0.921875L35.9531 4.03906L39.375 4.53125C39.9844 4.625 40.2422 5.375 39.7969 5.82031L37.3125 8.21094L37.8984 11.6094C37.9922 12.2188 37.3594 12.6875 36.7969 12.4062L33.75 10.8125L30.6797 12.4297C30.1172 12.7109 29.4844 12.2422 29.5781 11.6328L30.1641 8.23438L27.6797 5.82031C27.2344 5.375 27.4922 4.625 28.1016 4.53125L31.5234 4.03906L33.0703 0.921875C33.3516 0.359375 34.1484 0.382812 34.4062 0.921875ZM47.9062 0.921875L49.4531 4.03906L52.875 4.53125C53.4844 4.625 53.7422 5.375 53.2969 5.82031L50.8125 8.21094L51.3984 11.6094C51.4922 12.2188 50.8594 12.6875 50.2969 12.4062L47.25 10.8125L44.1797 12.4297C43.6172 12.7109 42.9844 12.2422 43.0781 11.6328L43.6641 8.23438L41.1797 5.82031C40.7344 5.375 40.9922 4.625 41.6016 4.53125L45.0234 4.03906L46.5703 0.921875C46.8516 0.359375 47.6484 0.382812 47.9062 0.921875ZM61.4062 0.921875L62.9531 4.03906L66.375 4.53125C66.9844 4.625 67.2422 5.375 66.7969 5.82031L64.3125 8.21094L64.8984 11.6094C64.9922 12.2188 64.3594 12.6875 63.7969 12.4062L60.75 10.8125L57.6797 12.4297C57.1172 12.7109 56.4844 12.2422 56.5781 11.6328L57.1641 8.23438L54.6797 5.82031C54.2344 5.375 54.4922 4.625 55.1016 4.53125L58.5234 4.03906L60.0703 0.921875C60.3516 0.359375 61.1484 0.382812 61.4062 0.921875Z"
                  fill="#FFE786"
                />
              </svg>
            </div>
          </div>
          <p class="reviews-item__text">
            This program has been amazing! so far I’ve lost a total of 26 lbs in
            4 mnths & I am very happy with the steady progress.
          </p>
          <div class="reviews-item__footer">
            <span class="reviews-item__name"> Tina G. </span>
            <div class="reviews-item__verifed">
              <svg
                width="17"
                height="16"
                viewBox="0 0 17 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M16.9688 8C16.9688 9.15625 16.4062 10.1562 15.5 10.7188C15.7188 11.75 15.4375 12.875 14.625 13.6562C13.8438 14.4688 12.7188 14.7812 11.6875 14.5625C11.0938 15.4375 10.125 16 8.96875 16C7.84375 16 6.84375 15.4375 6.25 14.5625C5.21875 14.7812 4.125 14.4688 3.3125 13.6562C2.53125 12.875 2.21875 11.75 2.4375 10.7188C1.5625 10.1562 0.96875 9.15625 0.96875 8C0.96875 6.875 1.5625 5.875 2.4375 5.3125C2.21875 4.28125 2.53125 3.15625 3.3125 2.34375C4.125 1.5625 5.25 1.25 6.25 1.46875C6.84375 0.59375 7.84375 0 8.96875 0C10.125 0 11.0938 0.59375 11.6875 1.46875C12.7188 1.25 13.8438 1.5625 14.625 2.34375C15.4375 3.15625 15.7188 4.28125 15.5 5.3125C16.375 5.875 16.9688 6.875 16.9688 8ZM12 6.78125C12.3125 6.5 12.3125 6.03125 12 5.75C11.7188 5.4375 11.25 5.4375 10.9688 5.75L8 8.71875L7 7.75C6.71875 7.4375 6.25 7.4375 5.96875 7.75C5.65625 8.03125 5.65625 8.5 5.96875 8.78125L7.46875 10.2812C7.59375 10.4375 7.78125 10.5 8 10.5C8.1875 10.5 8.375 10.4375 8.5 10.2812L12 6.78125Z"
                  fill="#B18FFF"
                />
              </svg>
              <span class="reviews-item__customer"> Verified customer </span>
            </div>
          </div>
        </div>
        <div class="reviews-item">
          <div class="reviews-item__head">
            <span class="reviews-item__title">
              “Back to feeling beautiful”
            </span>
            <div class="reviews-item__img">
              <svg
                width="68"
                height="13"
                viewBox="0 0 68 13"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M7.40625 0.921875L8.95312 4.03906L12.375 4.53125C12.9844 4.625 13.2422 5.375 12.7969 5.82031L10.3125 8.21094L10.8984 11.6094C10.9922 12.2188 10.3594 12.6875 9.79688 12.4062L6.75 10.8125L3.67969 12.4297C3.11719 12.7109 2.48438 12.2422 2.57812 11.6328L3.16406 8.23438L0.679688 5.82031C0.234375 5.375 0.492188 4.625 1.10156 4.53125L4.52344 4.03906L6.07031 0.921875C6.35156 0.359375 7.14844 0.382812 7.40625 0.921875ZM20.9062 0.921875L22.4531 4.03906L25.875 4.53125C26.4844 4.625 26.7422 5.375 26.2969 5.82031L23.8125 8.21094L24.3984 11.6094C24.4922 12.2188 23.8594 12.6875 23.2969 12.4062L20.25 10.8125L17.1797 12.4297C16.6172 12.7109 15.9844 12.2422 16.0781 11.6328L16.6641 8.23438L14.1797 5.82031C13.7344 5.375 13.9922 4.625 14.6016 4.53125L18.0234 4.03906L19.5703 0.921875C19.8516 0.359375 20.6484 0.382812 20.9062 0.921875ZM34.4062 0.921875L35.9531 4.03906L39.375 4.53125C39.9844 4.625 40.2422 5.375 39.7969 5.82031L37.3125 8.21094L37.8984 11.6094C37.9922 12.2188 37.3594 12.6875 36.7969 12.4062L33.75 10.8125L30.6797 12.4297C30.1172 12.7109 29.4844 12.2422 29.5781 11.6328L30.1641 8.23438L27.6797 5.82031C27.2344 5.375 27.4922 4.625 28.1016 4.53125L31.5234 4.03906L33.0703 0.921875C33.3516 0.359375 34.1484 0.382812 34.4062 0.921875ZM47.9062 0.921875L49.4531 4.03906L52.875 4.53125C53.4844 4.625 53.7422 5.375 53.2969 5.82031L50.8125 8.21094L51.3984 11.6094C51.4922 12.2188 50.8594 12.6875 50.2969 12.4062L47.25 10.8125L44.1797 12.4297C43.6172 12.7109 42.9844 12.2422 43.0781 11.6328L43.6641 8.23438L41.1797 5.82031C40.7344 5.375 40.9922 4.625 41.6016 4.53125L45.0234 4.03906L46.5703 0.921875C46.8516 0.359375 47.6484 0.382812 47.9062 0.921875ZM61.4062 0.921875L62.9531 4.03906L66.375 4.53125C66.9844 4.625 67.2422 5.375 66.7969 5.82031L64.3125 8.21094L64.8984 11.6094C64.9922 12.2188 64.3594 12.6875 63.7969 12.4062L60.75 10.8125L57.6797 12.4297C57.1172 12.7109 56.4844 12.2422 56.5781 11.6328L57.1641 8.23438L54.6797 5.82031C54.2344 5.375 54.4922 4.625 55.1016 4.53125L58.5234 4.03906L60.0703 0.921875C60.3516 0.359375 61.1484 0.382812 61.4062 0.921875Z"
                  fill="#FFE786"
                />
              </svg>
            </div>
          </div>
          <p class="reviews-item__text">
            G-Plans has helped me lose weight and gain my confidence back and I
            am feeling like my old self again. Cancer treatment made me gain 30
            lbs but now I am back!
          </p>
          <div class="reviews-item__footer">
            <span class="reviews-item__name"> Tabatha B. </span>
            <div class="reviews-item__verifed">
              <svg
                width="17"
                height="16"
                viewBox="0 0 17 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M16.9688 8C16.9688 9.15625 16.4062 10.1562 15.5 10.7188C15.7188 11.75 15.4375 12.875 14.625 13.6562C13.8438 14.4688 12.7188 14.7812 11.6875 14.5625C11.0938 15.4375 10.125 16 8.96875 16C7.84375 16 6.84375 15.4375 6.25 14.5625C5.21875 14.7812 4.125 14.4688 3.3125 13.6562C2.53125 12.875 2.21875 11.75 2.4375 10.7188C1.5625 10.1562 0.96875 9.15625 0.96875 8C0.96875 6.875 1.5625 5.875 2.4375 5.3125C2.21875 4.28125 2.53125 3.15625 3.3125 2.34375C4.125 1.5625 5.25 1.25 6.25 1.46875C6.84375 0.59375 7.84375 0 8.96875 0C10.125 0 11.0938 0.59375 11.6875 1.46875C12.7188 1.25 13.8438 1.5625 14.625 2.34375C15.4375 3.15625 15.7188 4.28125 15.5 5.3125C16.375 5.875 16.9688 6.875 16.9688 8ZM12 6.78125C12.3125 6.5 12.3125 6.03125 12 5.75C11.7188 5.4375 11.25 5.4375 10.9688 5.75L8 8.71875L7 7.75C6.71875 7.4375 6.25 7.4375 5.96875 7.75C5.65625 8.03125 5.65625 8.5 5.96875 8.78125L7.46875 10.2812C7.59375 10.4375 7.78125 10.5 8 10.5C8.1875 10.5 8.375 10.4375 8.5 10.2812L12 6.78125Z"
                  fill="#B18FFF"
                />
              </svg>
              <span class="reviews-item__customer"> Verified customer </span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="description">
      <div class="container">
        <div class="description-wrap">
          <div class="description-head">
            <div class="description-head__info">
              <button class="description-head__btn btn">We’re ready!</button>
              <span class="description-head__title">
                Let’s get <br />
                started now
              </span>
              <span class="description-head__timer">
                You’re approved for
                <counter-component-vue></counter-component-vue>
              </span>
            </div>
            <div class="description-head__img">
              <img src="./assets/images/description/img.png" alt="" />
            </div>
          </div>
          <div class="description-body">
            <span class="description-body__info">
              Start now for just $99/mo - no insurance needed
            </span>
            <div class="description-body__block">
              <span class="description-body__title">
                The most powerful weight loss program -
                <span class="italic">is yours</span>
              </span>
              <span class="description-body__include"> What’s included? </span>
              <div class="description-body__item">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description1.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text">
                  Access to Wegovy® or Ozempic®
                </span>
              </div>
              <div class="description-body__item">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description2.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text">
                  Insurance coverage support
                </span>
              </div>
              <div class="description-body__item">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description3.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text">
                  Telehealth doctor appt.
                </span>
              </div>
              <div class="description-body__item">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description4.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text"> Dietician guidance </span>
              </div>
              <div class="description-body__item start">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description5.svg"
                    alt=""
                  />
                </div>
                <div class="description-body__add">
                  <span class="description-body__text"> Metabolic test </span>
                  <span class="description-body__more">
                    Includes custom in-depth metabolic results and typing
                    booklet
                  </span>
                </div>
              </div>
              <div class="description-body__item start">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description6.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text">
                  Weekly updated meal plan based on metabolism
                </span>
              </div>
              <div class="description-body__item">
                <div class="description-body__icon">
                  <img
                    src="./assets/images/description/description7.svg"
                    alt=""
                  />
                </div>
                <span class="description-body__text">
                  Daily nutrition curriculum
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <best-offers-component-vue></best-offers-component-vue>

    <accordion-component-vue></accordion-component-vue>

    <div class="footer">
      <div class="container">
        <div class="footer-wrap">
          <p class="footer-desc">
            Medication is not included in the cost of the G-Plans Program. But
            don’t worry, our insurance concierge partners explore all options to
            help get you covered.
          </p>
          <p class="footer-text">
            Wegovy is FDA-approved for weight loss. Ozempic is FDA-approved for
            type 2 diabetes treatment, but may be prescribed for weight loss.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

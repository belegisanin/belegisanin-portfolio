<template>
  <div id="preload" :class="{ 'preload-hidden': state.loaded }">
    <svg
      id="preload-logo"
      viewBox="0 0 289 373"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M152.95 200.67V301.43C152.95 314.27 147.863 324.373 137.69 331.74C127.517 339.107 114.267 342.793 97.94 342.8H42.02V29.24H100.36C115.867 29.24 128.51 33.0033 138.29 40.53C148.07 48.0567 152.957 57.9167 152.95 70.11V155.17H194.95V67.27C194.95 47.6233 186.787 31.5 170.46 18.9C154.133 6.3 133.377 0 108.19 0H0V372H108.21C133.203 372 153.91 365.7 170.33 353.1C186.75 340.5 194.963 324.373 194.97 304.72V200.67H152.95Z"
        fill="currentColor"
      />
      <path
        d="M228.86 207.11C227.49 188.2 226.14 168.26 225.51 149.5L197.29 163.5H132.71C132.76 173.21 133.53 182.66 134 192.27H197.94L228.86 207.11Z"
        fill="currentColor"
      />
      <path
        d="M100.36 37.6H85.96V334.44H97.96C111.43 334.44 122.5 331.63 130.96 326.17V192.32H135.09C134.61 182.71 134.45 173.26 134.41 163.55H130.96V45.6C122.98 40.31 112.73 37.6 100.36 37.6Z"
        fill="currentColor"
      />
      <path
        d="M272.05 195.41L233.86 177.34L269.46 161.65C281.54 154.983 287.58 146.743 287.58 136.93V26.38C287.58 18.62 284.247 12.2866 277.58 7.37997C270.913 2.47331 262.283 0.0166459 251.69 0.00997925H154.21C161.854 3.12477 169.045 7.25162 175.59 12.28C181.874 17.0617 187.371 22.7979 191.88 29.28H242.27V141.28L224.59 149.98C225.22 168.73 226.59 187.79 227.92 206.7L243.59 214.19V342.8H191.82C187.273 349.287 181.739 355.023 175.42 359.8C168.854 364.819 161.651 368.945 154 372.07H252.95C263.523 372.07 272.153 369.613 278.84 364.7C285.527 359.787 288.86 353.453 288.84 345.7V219.18C288.86 208.4 283.263 200.477 272.05 195.41Z"
        fill="currentColor"
      />
    </svg>
  </div>
  <div id="container">
    <nav class="top-nav">
      <div class="logo-wrapper">
        <svg
          viewBox="0 0 289 373"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M152.95 200.67V301.43C152.95 314.27 147.863 324.373 137.69 331.74C127.517 339.107 114.267 342.793 97.94 342.8H42.02V29.24H100.36C115.867 29.24 128.51 33.0033 138.29 40.53C148.07 48.0567 152.957 57.9167 152.95 70.11V155.17H194.95V67.27C194.95 47.6233 186.787 31.5 170.46 18.9C154.133 6.3 133.377 0 108.19 0H0V372H108.21C133.203 372 153.91 365.7 170.33 353.1C186.75 340.5 194.963 324.373 194.97 304.72V200.67H152.95Z"
            fill="currentColor"
          />
          <path
            d="M228.86 207.11C227.49 188.2 226.14 168.26 225.51 149.5L197.29 163.5H132.71C132.76 173.21 133.53 182.66 134 192.27H197.94L228.86 207.11Z"
            fill="currentColor"
          />
          <path
            d="M100.36 37.6H85.96V334.44H97.96C111.43 334.44 122.5 331.63 130.96 326.17V192.32H135.09C134.61 182.71 134.45 173.26 134.41 163.55H130.96V45.6C122.98 40.31 112.73 37.6 100.36 37.6Z"
            fill="currentColor"
          />
          <path
            d="M272.05 195.41L233.86 177.34L269.46 161.65C281.54 154.983 287.58 146.743 287.58 136.93V26.38C287.58 18.62 284.247 12.2866 277.58 7.37997C270.913 2.47331 262.283 0.0166459 251.69 0.00997925H154.21C161.854 3.12477 169.045 7.25162 175.59 12.28C181.874 17.0617 187.371 22.7979 191.88 29.28H242.27V141.28L224.59 149.98C225.22 168.73 226.59 187.79 227.92 206.7L243.59 214.19V342.8H191.82C187.273 349.287 181.739 355.023 175.42 359.8C168.854 364.819 161.651 368.945 154 372.07H252.95C263.523 372.07 272.153 369.613 278.84 364.7C285.527 359.787 288.86 353.453 288.84 345.7V219.18C288.86 208.4 283.263 200.477 272.05 195.41Z"
            fill="currentColor"
          />
        </svg>
      </div>
      <ul>
        <li><a href="#">about me</a></li>
        <li><a href="#">my work</a></li>
        <li><a href="#">contact</a></li>
      </ul>
    </nav>
    <nav class="side-nav">
      <a
        href="https://github.com/belegisanin"
        class="side-nav-link"
        target="_blank"
        rel="nofollow noopener noreferrer"
      >
        <span class="visually-hidden">GitHub Page (Opens in new tab.)</span>
        <svg viewBox="0 0 40 39" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M17.8 0.2C8.6 1.2 1.2 8.6 0.200003 17.6C-0.799997 27 4.6 35.4 12.8 38.6C13.4 38.8 14 38.4 14 37.6V34.4C14 34.4 13.2 34.6 12.2 34.6C9.4 34.6 8.2 32.2 8 30.8C7.8 30 7.4 29.4 6.8 28.8C6.2 28.6 6 28.6 6 28.4C6 28 6.6 28 6.8 28C8 28 9 29.4 9.4 30C10.4 31.6 11.6 32 12.2 32C13 32 13.6 31.8 14 31.6C14.2 30.2 14.8 28.8 16 28C11.4 27 8 24.4 8 20C8 17.8 9 15.6 10.4 14C10.2 13.6 10 12.6 10 11.2C10 10.4 10 9.2 10.6 8C10.6 8 13.4 8 16.2 10.6C17.2 10.2 18.6 10 20 10C21.4 10 22.8 10.2 24 10.6C26.6 8 29.6 8 29.6 8C30 9.2 30 10.4 30 11.2C30 12.8 29.8 13.6 29.6 14C31 15.6 32 17.6 32 20C32 24.4 28.6 27 24 28C25.2 29 26 30.8 26 32.6V37.8C26 38.4 26.6 39 27.4 38.8C34.8 35.8 40 28.6 40 20.2C40 8.2 29.8 -1.2 17.8 0.2Z"
            fill="currentColor"
          />
        </svg>
      </a>
      <a
        href="https://twitter.com/belegisanind"
        class="side-nav-link"
        target="_blank"
        rel="nofollow noopener noreferrer"
      >
        <span class="visually-hidden">Twitter Page (Opens in new tab.)</span>
        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path
            d="M12 0C5.373 0 0 5.373 0 12C0 18.627 5.373 24 12 24C18.627 24 24 18.627 24 12C24 5.373 18.627 0 12 0ZM18.464 9.535C18.47 9.668 18.473 9.8 18.473 9.932C18.473 14 15.378 18.688 9.717 18.688C7.978 18.688 6.361 18.179 5 17.305C5.241 17.334 5.486 17.347 5.735 17.347C7.178 17.347 8.504 16.856 9.556 16.029C8.209 16.004 7.072 15.114 6.681 13.892C6.869 13.928 7.062 13.947 7.26 13.947C7.541 13.947 7.814 13.909 8.071 13.839C6.663 13.557 5.602 12.313 5.602 10.822C5.602 10.809 5.602 10.796 5.602 10.783C6.017 11.014 6.491 11.152 6.996 11.168C6.171 10.617 5.627 9.674 5.627 8.607C5.627 8.042 5.778 7.513 6.043 7.06C7.561 8.922 9.829 10.148 12.386 10.276C12.334 10.051 12.307 9.816 12.307 9.575C12.307 7.876 13.685 6.497 15.384 6.497C16.269 6.497 17.069 6.871 17.63 7.469C18.331 7.33 18.99 7.075 19.585 6.722C19.355 7.441 18.867 8.043 18.231 8.425C18.853 8.351 19.446 8.186 19.999 7.941C19.588 8.559 19.067 9.1 18.464 9.535Z"
            fill="currentColor"
          />
        </svg>
      </a>
      <a href="mailto:belegisanin@outlook.com" class="side-nav-link">
        <span class="visually-hidden">Send an email. (Opens mail client.)</span>
        <svg
          viewBox="0 0 300 300"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M149.996 0C67.157 0 0.00100708 67.158 0.00100708 149.997C0.00100708 232.834 67.157 299.997 149.996 299.997C232.835 299.997 299.996 232.834 299.996 149.997C299.996 67.158 232.835 0 149.996 0ZM149.999 52.686L238.762 108.036H61.236L149.999 52.686ZM239.868 196.423H239.859C239.859 205.301 232.664 212.495 223.787 212.495H76.211C67.333 212.495 60.139 205.3 60.139 196.423V111.558C60.139 110.619 60.235 109.706 60.391 108.809L145.199 161.692C145.303 161.757 145.414 161.801 145.521 161.861C145.633 161.923 145.747 161.983 145.861 162.04C146.46 162.349 147.077 162.598 147.708 162.761C147.773 162.779 147.838 162.787 147.903 162.802C148.595 162.965 149.296 163.067 149.996 163.067H150.001C150.006 163.067 150.011 163.067 150.011 163.067C150.711 163.067 151.412 162.968 152.104 162.802C152.169 162.786 152.234 162.779 152.299 162.761C152.929 162.598 153.544 162.349 154.146 162.04C154.26 161.983 154.374 161.923 154.486 161.861C154.592 161.801 154.704 161.757 154.808 161.692L239.616 108.809C239.772 109.706 239.868 110.617 239.868 111.558V196.423Z"
            fill="currentColor"
          />
        </svg>
      </a>
    </nav>
    <div class="landing">
      <video autoplay loop muted>
        <source :src="randomQuote.video" type="video/mp4" />
      </video>
      <div class="quote-wrapper">
        <q
          v-html="randomQuote.quote"
          data-aos="fade-up"
          data-aos-duration="3000"
        ></q>
        <p data-aos="fade-up" data-aos-duration="1000">
          - {{ randomQuote.author }}
        </p>
      </div>
    </div>
    <div class="content">
      <div class="about-wrapper">
        <video autoplay loop muted data-aos="fade-left">
          <source
            src="https://belegisanin.sirv.com/Portfolio_Videos/Timelapse-1.mp4"
            type="video/mp4"
          />
        </video>
        <div class="about">
          <h1 data-aos="fade-up">About Me</h1>
          <p data-aos="fade-up">
            I'm a full-stack web developer/UX & UI designer and mobile app
            developer from Serbia.
          </p>
        </div>
      </div>
      <div class="work-wrapper">
        <h1 data-aos="fade-up">My work</h1>
        <div class="grid-container">
          <div class="area1 work-tile" data-aos="fade-down-right">
            <div class="tile">agroasistent</div>
          </div>
          <div class="area2 work-tile" data-aos="fade-down">
            <div class="tile"></div>
          </div>
          <div class="area3 work-tile" data-aos="fade-down-left">
            <div class="tile"></div>
          </div>
          <div class="area4 work-tile" data-aos="fade-left">
            <div class="tile">more coming soon...</div>
          </div>
          <div class="area5 work-tile" data-aos="fade-up-right">
            <div class="tile"></div>
          </div>
          <div class="area6 work-tile" data-aos="fade-up-left">
            <div class="tile"></div>
          </div>
        </div>
      </div>
      <div class="contact-wrapper">
        <div class="contact">
          <h1 data-aos="fade-up">Contact me</h1>
          <p data-aos="fade-up">
            You can email me at
            <a href="mailto:belegisanin@outlook.com">belegisanin@outlook.com</a>
            or you can send me a message on
            <a href="https://twitter.com/belegisanind">twitter</a>. While you're
            at it, you can also visit my
            <a href="https://github.com/belegisanin">github</a> page. I hope I
            will hear from you soon.
          </p>
        </div>
      </div>
    </div>
    <footer>
      <p>Author: Dragan Belegišanin</p>
      <p>2020/2021 &copy; Copyright: belegisanin</p>
      <a href="#" class="back-to-top">Back To Top</a>
      <p>
        Stock Footage:
        <a href="https://www.youtube.com/channel/UC060L2YXizeMJwAVDoiVjhg"
          >Aleksandar Milutinović</a
        >;
        <a href="https://www.youtube.com/channel/UCfUCIeKeSko0fOnv2LtQkoA"
          >Pablo Camacho</a
        >
      </p>
    </footer>
  </div>
</template>

<script setup>
import { reactive, computed, onMounted } from "vue";
import { useMouse } from "@vueuse/core";
import AOS from "aos";
import "aos/dist/aos.css";

const { x, y } = useMouse({ touch: false });

const state = reactive({
  quotes: [
    {
      quote:
        "It has become appallingly obvious that our <u>technology</u> has exceeded our humanity.",
      author: "Albert Einstein, Scientist",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Galaxy%20-%20318%20Sparkvideo-1.mp4", //Done
    },
    {
      quote: "I do not fear <u>computers</u>. I fear lack of them.",
      author: "Isaac Asimov, Author & Professor of Biochemistry",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Dna%20-%206213%20-%201-1.mp4", //Done
    },
    {
      quote: "Never trust a <u>computer</u> you can’t throw out a window.",
      author: "Steve Wozniak, Electronics Engineer & Programmer",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/pexels-cottonbro-7858274_SparkVideo.mp4", //Done
    },
    {
      quote:
        "Everything is <u>designed</u>. Few things are <u>designed</u> well.",
      author: "Brian Reed, Podcaster",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Blue%20-%2022908%20Sparkvideo-1.mp4",
    },
    {
      quote:
        "<u>Simplicity</u> is about subtracting the obvious and adding the <u>meaningful</u>.",
      author: "John Maeda, Designer & Technologist",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Blue%20-%2022908%20Sparkvideo-1.mp4", //Done
    },
    {
      quote:
        "It is only when they go wrong that <u>machines</u> remind you how <u>powerful</u> they are.",
      author: "Clive James, Broadcaster & Journalist",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Network%20-%2014906%20Sparkvideo-1.mp4",
    },
    {
      quote:
        "The <u>Web</u> as I envisaged it, we have not seen it yet. The <u>future</u> is still so much bigger than the past.",
      author: "Tim Berners-Lee, Inventor of the World Wide Web",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Network%20-%2014906%20Sparkvideo-1.mp4", //Done
    },
    {
      quote: "<u>Technology</u> is best when it brings <u>people</u> together.",
      author: "Matt Mullenweg, Social Media Entrepreneur",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Blue%20-%2022908%20Sparkvideo-1.mp4",
    },
    {
      quote:
        "The <u>advance</u> of technology is based on making it <u>fit</u> in so that you don't really even notice it, so it's part of <u>everyday</u> life.",
      author: "Bill Gates, Co-founder of Microsoft",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Galaxy%20-%20318%20Sparkvideo-1.mp4",
    },
    {
      quote:
        "Let’s go <u>invent</u> tomorrow instead of worrying about what happened yesterday.",
      author: "Steve Jobs, Co-founder of Apple",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Galaxy%20-%20318%20Sparkvideo-1.mp4",
    },
    {
      quote: "It’s not that we use technology, we <u>live</u> technology.",
      author: "Godfrey Reggio, Film Director",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Camera%20-%2057257%20Sparkvideo-1.mp4", //Done
    },
    {
      quote:
        "I don't care that they stole my <u>idea</u>... I care that they don't have any of their own",
      author: "Nikola Tesla, Inventor, Electrical Engineer & Futurist",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Tesla%20Coil%20Demonstration%20Sparkvideo-1.mp4", //Done
    },
    {
      quote:
        "The present is theirs; the <u>future</u>, for which I really worked, is <u>mine</u>.",
      author: "Nikola Tesla, Inventor, Electrical Engineer & Futurist",
      video:
        "https://belegisanin.sirv.com/Portfolio_Videos/Tesla%20Coil%20Demonstration%20Sparkvideo-1.mp4", //Done
    },
  ],
  loaded: false,
});

function randomInt(max, min) {
  return Math.floor(Math.random() * (max - min + 1) + min);
}

const randomQuote = computed(
  () => state.quotes[randomInt(0, state.quotes.length)]
);

onMounted(() => {
  const preloader = document.getElementById("preload");

  document.onreadystatechange = function () {
    if (document.readyState == "complete") {
      state.loaded = true;
    }
  };

  preloader.addEventListener("animationend", () => {
    preloader.style.display = "none";
  });

  AOS.init();
});
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Source+Code+Pro:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400;1,500;1,600;1,700;1,900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Lora:wght@400;500&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background: black;
  font-family: "Source Code Pro", monospace;
  cursor: crosshair;
}
::selection {
  color: black;
  background: rgb(215, 215, 215);
}

/* Preloader */

#preload {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background: black;
  z-index: 9999;
  opacity: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}
#preload-logo {
  width: 3em;
  color: white;
  animation: preload-logo 0.5s infinite alternate ease-in-out;
}

/* Site */

.top-nav {
  width: 100%;
  height: 8em;
  position: fixed;
  display: flex;
  align-items: center;
  z-index: 50;
}
.top-nav svg {
  height: 8em;
  padding: 1.8em;
  cursor: pointer;
}
.top-nav svg path {
  color: rgb(250, 250, 250);
}
.top-nav ul {
  list-style: none;
  font-weight: 500;
  font-size: 1.3em;
}
.top-nav ul a {
  text-decoration: none;
  color: rgb(250, 250, 250);
  cursor: crosshair;
}
.top-nav ul a:hover {
  background: rgb(250, 250, 250);
  color: black;
}
.side-nav {
  position: fixed;
  height: 100vh;
  width: 6em;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.side-nav-link {
  width: 55%;
  margin: 0.3em 0;
  cursor: crosshair;
}
.side-nav-link svg {
  width: 100%;
  padding: 0.4em;
  color: rgb(250, 250, 250);
}
.side-nav-link svg:hover {
  color: black;
  background: rgb(215, 215, 215);
}
.landing {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.landing video {
  position: absolute;
  height: 70%;
  filter: grayscale(1);
}
.quote-wrapper {
  position: relative;
  width: 65%;
  max-height: 50%;
  font-family: "Lora", serif;
}
.quote-wrapper q {
  font-size: calc(5em - 50%);
  color: white;
}
.quote-wrapper p {
  width: 100%;
  text-align: right;
  font-style: italic;
  font-size: 2em;
  margin-top: 1.5em;
  color: white;
}
.content {
  width: 100%;
  min-height: 100vh;
}

/* About Me */

.about-wrapper {
  width: 100%;
  min-height: 100vh;
  padding: 8em 16em;
  font-family: "Lora", serif;
  color: white;
}
.about-wrapper video {
  position: absolute;
  right: 16em;
  height: 60%;
  filter: grayscale(1);
}
.about-wrapper h1 {
  font-weight: 300;
  font-size: 7em;
  width: 100%;
}
.about-wrapper p {
  font-size: 4em;
  margin-top: 1em;
}

/* Work */

.work-wrapper {
  width: 100%;
  min-height: 100vh;
  padding: 9em 15em;
  font-family: "Lora", serif;
  color: white;
}
.work-wrapper h1 {
  font-size: 7em;
  font-weight: 300;
  margin-bottom: 0.5em;
}
.grid-container {
  box-sizing: content-box;
  width: 100%;
  height: 750px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "area1 area1 area2 area3"
    "area1 area1 area4 area4"
    "area5 area6 area6 area6";
}
.work-tile {
  color: white;
  font-size: 2em;
}
.work-tile .tile {
  width: 100%;
  height: 100%;
  padding: 0.8em;
  transition: background 0.15s ease;
}
.work-tile .tile:hover {
  background: rgba(255, 255, 255, 0.2);
}
.area1 {
  width: 100%;
  height: 100%;
  grid-area: area1;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 2px 0px 2px 2px;
  font-size: 4em;
}
.area2 {
  width: 100%;
  height: 100%;
  grid-area: area2;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 2px 0px 2px 2px;
}
.area3 {
  width: 100%;
  height: 100%;
  grid-area: area3;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 2px 2px 2px 2px;
}
.area4 {
  width: 100%;
  height: 100%;
  grid-area: area4;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 0px 2px 2px 2px;
}
.area5 {
  width: 100%;
  height: 100%;
  grid-area: area5;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 0px 2px 2px 2px;
}
.area6 {
  width: 100%;
  height: 100%;
  grid-area: area6;
  border-style: solid;
  border-color: rgb(230, 230, 230);
  border-width: 0px 2px 2px 0px;
}

/* Contact */

.contact-wrapper {
  width: 100%;
  min-height: 100vh;
  padding: 8em 15em;
  font-family: "Lora", serif;
  color: white;
}
.contact {
  width: 100%;
  height: 100%;
}
.contact h1 {
  font-size: 7em;
  font-weight: 300;
  margin-bottom: 0.5em;
}
.contact p {
  font-size: 3em;
}
.contact p a {
  color: white;
}

/* Footer */
footer {
  width: 100%;
  padding: 5em;
  color: rgb(125, 125, 125);
  display: flex;
  flex-direction: column;
  justify-content: center;
  font-family: "Lora", serif;
}
footer p {
  text-align: center;
}
footer a {
  color: rgb(180, 180, 180);
  text-align: center;
}
footer .back-to-top {
  margin: 1em;
}

/* Animation */

.preload-hidden {
  animation: preload-hide 1s ease forwards;
}

@keyframes preload-hide {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}

@keyframes preload-logo {
  from {
    transform: scale(1);
  }
  to {
    transform: scale(1.2);
  }
}

/* Accessibility */

.visually-hidden {
  border: 0;
  padding: 0;
  margin: 0;
  position: absolute !important;
  height: 1px;
  width: 1px;
  overflow: hidden;
  clip: rect(
    1px 1px 1px 1px
  ); /* IE6, IE7 - a 0 height clip, off to the bottom right of the visible 1px box */
  clip: rect(
    1px,
    1px,
    1px,
    1px
  ); /*maybe deprecated but we need to support legacy browsers */
  clip-path: inset(
    50%
  ); /*modern browsers, clip-path works inwards from each corner*/
  white-space: nowrap; /* added line to stop words getting smushed together (as they go onto seperate lines and some screen readers do not understand line feeds as a space */
}
</style>

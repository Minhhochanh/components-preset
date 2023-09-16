<template>
  <body>
    <div class="head_container">
      <b class="protect-title">Term & conditions</b>
      <div class="term-container">
        <p class="script-blank">
          By clicking “PROTECT MY IDENTITY FOR FREE* NOW” you are agreeing to
          our terms and conditions. It’s important to us that you understand the
          full terms and conditions
        </p>
      </div>
      <div class="term-image-container">
        <div class="image-content1">
          <img class="term-image" src="./public/undefined8.png" />
          <u>T&C</u>
        </div>

        <div class="image-content2">
          <img class="term-image" src="./public/undefined7.png" />
          <u>Privacy Policy</u>
        </div>
      </div>
    </div>
  </body>
</template>

<script></script>
<style>
.head_container {
  display: flex;
  flex-direction: column;
  width: 400px;
  background-color: #18187c;
  align-items: center;
  margin: 0 auto; /* Thiết lập margin tự động */
  text-align: center;
  font-size: var(--font-size-xl);
  color: var(--color-white);
  font-family: var(--font-open-sans);
}
.term-container {
  margin-block-start: 1.5em;
}
.script-blank {
  margin: 0;
  margin-left: 40px;
  margin-right: 40px;
  width: 79.49%;
}
.term-image-container {
  display: flex;
  flex-direction: row;
  margin-block-start: 1.5em;
}
.image-content1,
.image-content2 {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.image-content2 {
  margin-inline-start: 2.5em;
}
.term-image {
  width: 85px;
  height: 85px;
}
body {
  margin: 0;
  line-height: normal;
}

:root {
  /* fonts */
  --font-open-sans: 'Open Sans';
  --font-inter: Inter;

  /* font sizes */
  --font-size-xl: 20px;
  --font-size-base: 16px;
  --font-size-xs: 12px;
  --font-size-3xs: 10px;

  /* Colors */
  --color-midnightblue: #18187c;
  --color-white: #fff;
  --color-red: #f30000;
  --color-black: #000;
  --color-gray: rgba(0, 0, 0, 0.8);
  --color-gainsboro: rgba(231, 231, 231, 0.5);

  /* Gaps */
  --gap-5xl: 24px;
}
</style>

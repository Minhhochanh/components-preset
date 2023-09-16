<template>
  <body>
    <div class="head_container">
      <b class="protect-title">ID Screen</b>

      <p class="script-blank">Just £9.95 per month</p>
      <p class="script-blank">(billed quarterly)</p>

      <div class="cross-line"></div>

      <span class="id-screen">
        <b>We Monitor</b> Account, data, dark web and social media to protect
        you from risk 24/7 <b> We Notify & Alert</b> We let you know if there is
        a problem <b>We Restore</b> We help get your accounts back online
      </span>

      <p class="script-blank">100% Automatic</p>
      <p class="script-blank">Nothing to download, nothing to install</p>

      <div class="cross-line"></div>

      <b class="protect-title">Identity protection</b>
      <div class="protect-container">
        <div class="protect-content">
          <img class="tick-image" src="./public/undefined9.png" />
          <p class="script-base-size">IBAN number</p>
        </div>

        <div class="protect-content">
          <img class="tick-image" src="./public/undefined9.png" />
          <p class="script-base-size">Telephone numbers</p>
        </div>
      </div>

      <b class="protect-title">Online protection</b>
      <div class="protect-container">
        <div class="protect-content">
          <img class="tick-image" src="./public/undefined9.png" />
          <p class="script-base-size">Credit & debit cards</p>
        </div>

        <div class="protect-content">
          <img class="tick-image" src="./public/undefined9.png" />
          <p class="script-base-size">Email addresses</p>
        </div>
      </div>

      <img class="logo-image" src="./public/undefined2.png" />
    </div>
  </body>
</template>

<script>
export default {
  name: 'headercomp',
};
</script>
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
.id-screen {
  margin-block-start: 1em;
  margin: 40px;
}
.script-blank {
  margin: 0;
  margin-left: 40px;
  margin-right: 40px;
}
.cross-line {
  margin-block-start: 1em;
  width: 90%;
  height: 2px;
  background-color: white;
}
.protect-container {
  display: flex;
  flex-direction: column;
}
.tick-image {
  margin-left: 20px;
  height: 8.7%;
  width: 8.42%;
  max-width: 100%;
  overflow: hidden;
  max-height: 100%;
  object-fit: cover;
  margin-right: 5px;
}
.protect-content {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 0;
}
.script-base-size {
  font-size: var(--font-size-base);
  margin: 3px;
}
.protect-title {
  margin-block-start: 1em;
  margin: 20px;
}
.logo-image {
  width: 70px;
  height: 70px;
  object-fit: cover;
  margin-block-start: 1em;
  margin-block-end: 1em;
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

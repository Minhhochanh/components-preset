<template>
  <body>
    <div class="footer_container">
      <div class="footer_script">
        ID Screen is provided by Northwest Innovations Ltd, which is a company
        registered in England and Wales at Companies House. Our registered
        office is Northwest Innovations Limited, Bentley Suite, The Motorworks,
        Chestergate, Macclesfield, Cheshire, United Kingdom, SK11 6DU and our
        registered number is 14425558. Northwest Innovations Ltd is registered
        for VAT under VAT Registration number GB428679449.
      </div>
      <div class="foot-images">
        <img class="image-2-icon" alt="" src="./public/undefined.png" />
        <img class="image-1-icon" alt="" src="./public/undefined1.png" />
      </div>
    </div>
  </body>
</template>

<script></script>
<style>
.footer_container {
  display: flex;
  flex-direction: column;
  width: 400px;
  background-color: white;
  align-items: center;
  margin: 0 auto; /* Thiết lập margin tự động */
  text-align: center;
  font-family: var(--font-inter);
  color: black;
  justify-content: flex-start;
  position: relative;
  flex-shrink: 0;
}
.footer_script {
  font-size: 10px;
  margin-block-end: 1em;
}
.foot-images {
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.image-1-icon,
.image-2-icon {
  position: relative;
  width: 89.54px;
  height: 35.4px;
  object-fit: cover;
}
.image-1-icon {
  width: 97.17px;
  height: 37.48px;
  margin-inline-start: 1.5em;
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

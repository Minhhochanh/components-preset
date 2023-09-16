<template>
  <body>
    <div class="head_container">
      <img class="head_logo" alt="" src="Files/public/header_logo.png" />
      <div class="head_script_container">
        <p class="head_script">Is your identity at risk?</p>
        <p class="head_script">
          25% of people in the UK will have their identity stolen. You have been
          breached and are in danger of being a victim of fraud.
        </p>
      </div>
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
  font-family: var(--font-open-sans);
}
.head_logo {
  width: 50%;
  margin-block-end: 1.5em;
}
.head_script_container {
  margin: 0;
}
.head_script {
  color: white;
  font-size: 11px;
  margin: 0;
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

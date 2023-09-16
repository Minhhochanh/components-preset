<template>
  <body>
    <div class="body-container">
      <div class="content-container">
        <img class="dots-image" alt="" src="./public/undefined3.png" />
        <img class="rectangle-image" alt="" src="./public/undefined5.png" />
        <img class="Exclamation" alt="" src="./public/undefined6.png" />

        <b class="script-header">
          <p class="script-blank">
            {First_Name} {Last_name} your identify has been breached!!
          </p>
        </b>
        <div class="email-container">
          <p class="script-blank">
            {email_address} has been compromised {eyeonid_api_response} times
          </p>
        </div>
        <div class="content-script">
          <span class="script1">
            <p class="header-details">
              Your personal details are at risk of fraud:
            </p>
            <p class="script-blank">Bank Account: {bank account}</p>
            <p class="script-blank">Sort Code: {sort code}</p>
            <p class="script-blank">Mobile Number: {mobile number}</p>
            <p class="script-blank">Address: {address}</p>
          </span>
        </div>
        <div class="protect-button">
          <b class="protect-script">PROTECT MY IDENTITY FOR FREE* NOW!</b>
        </div>
        <div class="note-script">
          *Membership cost £9.98 per month after 14 day FREE Trial
        </div>
        <div class="warning-container">
          <span class="script1">
            <p class="script-blank">
              <span class="red-word">You are at risk!!</span>
              <span>
                If your identity is stolen you are at risk of fraud, losing
                money and being declined for credit.
              </span>
            </p>
            <p class="script-blank">
              Your name, address and date of birth is enough for fraudsters to
              create another 'you' and steal your identity.
            </p>
          </span>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name: 'bodycomp',
};
</script>
<style>
.content-container {
  position: relative;
  background-color: var(--color-midnightblue);
  width: 400px;
  height: 2649px;
  overflow: hidden;
  flex-shrink: 0;
}
.body-container {
  position: relative;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-size: var(--font-size-xl);
  color: var(--color-white);
  font-family: var(--font-open-sans);
}
.dots-image {
  position: absolute;
  top: 162px;
  left: 17px;
  width: 264px;
  height: 318px;
  object-fit: cover;
}
.rectangle-image {
  position: absolute;
  top: 17px;
  left: 110px;
  width: 171px;
  height: 50px;
  object-fit: cover;
}
.rectangle-image {
  top: 182px;
  left: 25px;
  border-radius: 26px;
  width: 341px;
  height: 821px;
}
.Exclamation {
  position: absolute;
  height: 3.25%;
  width: 22.05%;
  top: 5.4%;
  right: 38.97%;
  bottom: 91.36%;
  left: 38.97%;
  max-width: 100%;
  overflow: hidden;
  max-height: 100%;
  object-fit: cover;
}
.script-header {
  position: absolute;
  top: 260px;
  left: 55px;
  font-size: 32px;
  display: inline-block;
  font-family: var(--font-inter);
  color: var(--color-black);
  width: 282px;
  height: 160px;
}
.script-blank {
  margin: 0;
}
.note-script,
.warning-container {
  position: absolute;
  top: 879px;
  left: 43px;
  font-size: var(--font-size-xs);
  display: flex;
  align-items: center;
  width: 304px;
  height: 91px;
  color: var(--color-gray);
}
.note-script {
  top: 841px;
  left: 97px;
  justify-content: center;
  width: 195px;
  height: 34px;
}
.email-container {
  position: absolute;
  top: 455px;
  left: 34px;
  font-weight: 600;
  color: var(--color-red);
  display: inline-block;
  width: 323px;
  height: 71px;
}
.content-script {
  position: absolute;
  top: 539px;
  left: 40px;
  color: var(--color-black);
  display: flex;
  align-items: center;
  width: 311px;
}
.script1 {
  line-break: anywhere;
  width: 100%;
}
.header-details {
  margin: 0;
  font-weight: 600;
}
.protect-button {
  position: absolute;
  height: 2.91%;
  width: 77.95%;
  top: 27.94%;
  right: 11.03%;
  bottom: 69.16%;
  left: 11.03%;
  border-radius: 5px;
  background-color: #45ba51;
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  padding: 0 6px;
  box-sizing: border-box;
  align-items: flex-start;
  justify-content: center;
  font-size: 24px;
}
.protect-script {
  position: relative;
  display: inline-block;
  width: 291px;
  height: 61px;
  flex-shrink: 0;
}
.red-word {
  color: var(--color-red);
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

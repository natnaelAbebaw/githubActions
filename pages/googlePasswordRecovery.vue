<template>
  <main>
    <div class="container">
      <div class="topBox">
        <div @click="back">
          <Icon class="fa-solid fa-arrow-left"></Icon>
        </div>
        <span>Password recovery</span>
      </div>

      <div class="google">
        <Image
          src="data:image/svg+xml,%3csvg%20width='50'%20height='50'%20viewBox='0%200%2050%2050'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cpath%20d='M45.4284%2020.9199H43.7503V20.8334H25.0003V29.1667H36.7743C35.0566%2034.0178%2030.441%2037.5001%2025.0003%2037.5001C18.0972%2037.5001%2012.5003%2031.9032%2012.5003%2025.0001C12.5003%2018.097%2018.0972%2012.5001%2025.0003%2012.5001C28.1868%2012.5001%2031.0857%2013.7022%2033.293%2015.6657L39.1857%209.773C35.4649%206.30529%2030.4878%204.16675%2025.0003%204.16675C13.4951%204.16675%204.16699%2013.4949%204.16699%2025.0001C4.16699%2036.5053%2013.4951%2045.8334%2025.0003%2045.8334C36.5055%2045.8334%2045.8337%2036.5053%2045.8337%2025.0001C45.8337%2023.6032%2045.6899%2022.2397%2045.4284%2020.9199Z'%20fill='%23FFC107'/%3e%3cpath%20d='M6.56836%2015.3032L13.4132%2020.323C15.2652%2015.7376%2019.7507%2012.5001%2024.9996%2012.5001C28.1861%2012.5001%2031.085%2013.7022%2033.2923%2015.6657L39.185%209.773C35.4642%206.30529%2030.4871%204.16675%2024.9996%204.16675C16.9975%204.16675%2010.0579%208.68446%206.56836%2015.3032Z'%20fill='%23FF3D00'/%3e%3cpath%20d='M25%2045.8333C30.3812%2045.8333%2035.2708%2043.7739%2038.9677%2040.425L32.5198%2034.9687C30.4281%2036.5531%2027.8281%2037.5%2025%2037.5C19.5812%2037.5%2014.9802%2034.0448%2013.2469%2029.2229L6.45312%2034.4573C9.90104%2041.2041%2016.9031%2045.8333%2025%2045.8333Z'%20fill='%234CAF50'/%3e%3cpath%20d='M45.4281%2020.9197H43.75V20.8333H25V29.1666H36.774C35.949%2031.4968%2034.45%2033.5062%2032.5167%2034.9697C32.5177%2034.9687%2032.5187%2034.9687%2032.5198%2034.9676L38.9677%2040.4239C38.5115%2040.8385%2045.8333%2035.4166%2045.8333%2024.9999C45.8333%2023.603%2045.6896%2022.2395%2045.4281%2020.9197Z'%20fill='%231976D2'/%3e%3c/svg%3e"
        />
        <div class="googleText">
          <Heading level="h2" text="Add a new password" />
          <Text text="Your account uses google Sign-in. Add a new password." />
        </div>
      </div>

      <div class="recoverLink">
        <Heading level="h2" text="Recovery link send to:" />
        <address>natnaell70a@gmail.com</address>
      </div>

      <div class="imageDig">
        <Image
          type="md"
          src="https://develop.aladia.io/_nuxt/image.ChQ3biW9.png"
        />
        <div>
          <Icon icon="fa-solid fa-arrow-right"></Icon>
          <Image
            src="data:image/svg+xml,%3csvg%20width='48'%20height='34'%20viewBox='0%200%2048%2034'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20id='Group%2022'%20opacity='0.6'%3e%3cpath%20id='Union'%20fill-rule='evenodd'%20clip-rule='evenodd'%20d='M37.309%203.885L23.7397%2018.8413L10.1704%203.885H37.309ZM41.3597%203.885C41.3286%203.91929%2041.2971%203.95399%2041.2652%203.98913L25.2209%2021.6734C24.5288%2022.4363%2024.1827%2022.8177%2023.7397%2022.8177C23.2967%2022.8177%2022.9507%2022.4363%2022.2585%2021.6734L6.21421%203.98913L6.21419%203.98911C6.18232%203.95398%206.15083%203.91928%206.11975%203.885H5.36023C4.25566%203.885%203.36023%204.78043%203.36023%205.885V28.6172C3.36023%2029.7218%204.25566%2030.6172%205.36022%2030.6172H42.1206C43.2251%2030.6172%2044.1206%2029.7218%2044.1206%2028.6172V5.885C44.1206%204.78043%2043.2251%203.885%2042.1206%203.885H41.3597ZM42.6518%200.912893C45.1635%201.17815%2047.1206%203.30302%2047.1206%205.885V28.6172C47.1206%2031.3787%2044.882%2033.6172%2042.1206%2033.6172H5.36022C2.5988%2033.6172%200.360229%2031.3787%200.360229%2028.6172V5.885C0.360229%203.3036%202.31645%201.1791%204.82731%200.913068C5.24797%200.671204%206.03628%200.64778%207.27962%200.645511L7.28514%200.645499C7.41677%200.645267%207.55351%200.645266%207.69543%200.645266L39.784%200.645264C39.9259%200.645264%2040.0626%200.645264%2040.1943%200.645496L40.1998%200.645508C41.4428%200.647776%2042.2311%200.67119%2042.6518%200.912893Z'%20fill='url(%23paint0_linear_318_751)'/%3e%3c/g%3e%3cdefs%3e%3clinearGradient%20id='paint0_linear_318_751'%20x1='23.9999'%20y1='0.999878'%20x2='23.9999'%20y2='39.4999'%20gradientUnits='userSpaceOnUse'%3e%3cstop%20stop-color='%23373333'/%3e%3cstop%20offset='1'%20stop-color='%237C7C7C'%20stop-opacity='0'/%3e%3c/linearGradient%3e%3c/defs%3e%3c/svg%3e"
          />
        </div>

        <Image
          src="data:image/svg+xml,%3csvg%20width='55'%20height='75'%20viewBox='0%200%2055%2075'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cpath%20id='Vector'%20opacity='0.6'%20d='M13.2501%2029.0097V29.1097H13.3501H48.2411C49.0523%2029.1097%2049.8557%2029.2719%2050.6053%2029.5869C51.3549%2029.902%2052.0361%2030.3639%2052.6099%2030.9463C53.1838%2031.5286%2053.6391%2032.2201%2053.9497%2032.9812C54.2604%2033.7423%2054.4203%2034.5581%2054.4203%2035.3819V67.7194C54.4203%2069.3834%2053.7689%2070.9789%2052.6099%2072.1551C51.4509%2073.3312%2049.8794%2073.9917%2048.241%2073.9917H6.27918C4.64083%2073.9917%203.06929%2073.3312%201.91035%2072.1551C0.751369%2070.9789%200.1%2069.3834%200.1%2067.7194V35.3822C0.1%2033.7181%200.751399%2032.1226%201.91044%2030.9463C3.06943%2029.7702%204.64104%2029.1097%206.27945%2029.1097H7.40356H7.50356V29.0097V20.5626C7.50356%209.75405%2015.764%200.581119%2026.3963%200.118872L26.3964%200.11887C29.8817%20-0.0347026%2033.345%200.751297%2036.4339%202.39701C39.5229%204.04273%2042.1274%206.48949%2043.9823%209.48854L43.9828%209.48932C44.1975%209.82945%2044.3362%2010.2133%2044.3889%2010.6138C44.4417%2011.0144%2044.4072%2011.4218%2044.2881%2011.8073C44.1689%2012.1928%2043.968%2012.5471%2043.6994%2012.8451C43.431%2013.143%2043.1015%2013.3774%2042.7343%2013.5321C42.7342%2013.5321%2042.7341%2013.5321%2042.734%2013.5322L42.4278%2013.6596C42.4276%2013.6597%2042.4274%2013.6598%2042.4273%2013.6598C41.8271%2013.9016%2041.1622%2013.9208%2040.5496%2013.7139C39.9367%2013.507%2039.4151%2013.0871%2039.077%2012.5277L39.0762%2012.5264C37.7554%2010.4162%2035.9093%208.69673%2033.724%207.54181C31.5388%206.3869%2029.0919%205.83744%2026.6303%205.949C19.0733%206.28687%2013.2501%2012.8729%2013.2501%2020.5387V29.0097ZM33.291%2062.4359H33.4268L33.3865%2062.3062L30.2816%2052.2987C31.4411%2051.6324%2032.3557%2050.6005%2032.8858%2049.3588C33.4267%2048.092%2033.5369%2046.6787%2033.199%2045.3415C32.8611%2044.0043%2032.0943%2042.8189%2031.0191%2041.9722C29.9438%2041.1256%2028.6214%2040.6659%2027.26%2040.6659C25.8987%2040.6659%2024.5762%2041.1256%2023.501%2041.9722C22.4257%2042.8189%2021.659%2044.0043%2021.3211%2045.3415C20.9832%2046.6787%2021.0933%2048.092%2021.6342%2049.3588C22.1643%2050.6005%2023.0789%2051.6324%2024.2385%2052.2987L21.1337%2062.3062L21.0935%2062.4359H21.2292H33.291Z'%20fill='url(%23paint0_linear_318_755)'%20stroke='%23383434'%20stroke-width='0.2'/%3e%3cdefs%3e%3clinearGradient%20id='paint0_linear_318_755'%20x1='27.2601'%20y1='0'%20x2='27.2601'%20y2='74.0917'%20gradientUnits='userSpaceOnUse'%3e%3cstop%20stop-color='%236F6363'/%3e%3cstop%20offset='1'%20stop-color='%238A8A8A'%20stop-opacity='0'/%3e%3c/linearGradient%3e%3c/defs%3e%3c/svg%3e"
        />
      </div>
      <Button class="btn">Send Link</Button>
    </div>
  </main>
</template>

<script>
import Button from "~/components/Button.vue";

export default {
  layout: "default",
  methods: {
    back() {
      this.$router.back();
    },
  },
};
</script>

<style scoped>
.bg {
  display: grid;
  place-items: center;
  height: 100vh;
}

h2 {
  color: white;
}

.container {
  border: 1px solid rgb(90, 90, 90);
  padding: 20px;
  max-width: 400px;
  border-radius: 6px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

p {
  color: white;
}

main {
  display: grid;
  place-items: center;
  height: 100vh;
}

.google {
  display: grid;
  grid-template-columns: 1fr 2fr;
  align-items: center;
  margin-bottom: 20px;
  border: 1px solid red;
  padding: 1rem 2rem;
  border-radius: 4px;
  gap: 30px;
}

.google img {
  width: 100px;
}

.google h2 {
  font-size: 16px;
  margin-bottom: 1rem;
}
.google p {
  font-size: 14px;
  color: rgb(190, 190, 190);
}

.topBox {
  color: white;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  margin-bottom: 20px;

  width: 100%;
}

.topBox span {
  transform: translateX(-50%);
}
.topBox i {
  justify-self: start;
  color: rgb(123, 123, 123);
}

.btn {
  padding: 12px 20px;
  background-color: none;
  border: none;
  width: 100%;
  color: rgb(190, 190, 190);
  opacity: 0.8;
  border-radius: 4px;
  background: linear-gradient(
    15deg,
    #fff0 9.55%,
    #fff0 30.28%,
    #fff6,
    #fff0 41.58%,
    #fff0 59.02%,
    #fff 67.97%,
    #fff0 74.56%,
    #fff
  );
  background-position: right bottom;
  margin-bottom: 20px;
}

.recoverLink {
  margin-bottom: 100px;
  align-self: self-start;
  padding: 10px 20px;
}

.recoverLink h2 {
  color: rgb(160, 160, 160);
  font-size: 14px;
}

.recoverLink address {
  color: rgb(160, 160, 160);
  font-size: 14px;
}

.imageDig {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  align-items: center;
  justify-content: center;
  justify-items: center;
  gap: 20px;
  margin-bottom: 100px;
}

.imageDig div {
  display: flex;
  color: white;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 20px;
}

.imageDig div i {
  transform: translateX(-10px);
}

.imageDig div img {
  width: 30px;
}

.imageDig img:last-child {
  width: 80px;
}
</style>

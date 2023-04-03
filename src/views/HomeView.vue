<template>
  <div class="bg-[#202020]">
    <div
      id="intro"
      class="container mx-auto sm:block  sm:pt-[100px] md:pt-0 md:min-h-screen md:flex md:justify-center items-center md:gap-[150px]"
    >
      <div class="md:w-[500px] w-[80%] mx-auto md:mx-0 md:pt-0 pt-[100px] "
      data-aos="zoom-in"
      data-aos-duration="3000">
        <h1 class="text-white text-[30px] xl:w-[500px] md:w-[300px] w-[300px] font-bold">
          Hello, I'm
          <span class="text-[#13FF00]">Ikromov Abdulaziz</span>
          Full Stack developer
        </h1>
        <div
          class="bg-blue-300 border-[#13FF00] w-[90%] md:w-[400px] border mt-[20px]"
        ></div>
        <h1 class="mt-[10px] text-gray-400 text-[20px]">As a Full Stack developer. I have
          proficiency in programming languages such as HTML, CSS, JavaScript,
          Typescript, and Node js. I have an experience with
          framework Vue, as well as my knowledge of
          databases like MySQL, MongoDB, and PostgreSQL. And I have  an experience
          with DevOps tools like Docker</h1>
        <div class="border-[#13FF00] w-[90%] md:w-[400px] border mt-[20px]"></div>
        <div class="gap-[20px] flex items-center w-[400px] mt-[20px]">
          <a
            href="https://instagram.com/1_ikramovv_"
            class="hover:shadow-md bg-[#353535] w-[40px] h-[40px] flex rounded-[50%] justify-center items-center"
            ><i
              class="bx bxl-instagram text-[30px] text-white hover:text-black w-[40px] h-[40px] rounded-[50%] justify-center items-center flex"
            ></i
          ></a>
          <a
            href="https://t.me/abdulazizikromovv"
            class="bg-[#353535] hover:text-black w-[40px] h-[40px] flex rounded-[50%] justify-center items-center"
            ><i
              class="bx bxl-telegram text-[30px] text-white hover:text-black w-[40px] h-[40px] rounded-[50%] justify-center items-center flex"
            ></i
          ></a>
          <a
            href="https://github.com/1kromov"
            class="bg-[#353535] w-[40px] h-[40px] flex rounded-[50%] justify-center items-center"
            ><i
              class="bx bxl-github text-[30px] hover:text-black text-white w-[40px] h-[40px] rounded-[50%] justify-center items-center flex"
            ></i
          ></a>
          <a
            href="https://www.linkedin.com/in/abdulaziz-ikromov-5a4652261/"
            class="bg-[#353535] w-[40px] h-[40px] flex rounded-[50%] justify-center items-center"
            ><i
              class="bx bxl-linkedin hover:text-black text-[30px] text-white w-[40px] h-[40px] rounded-[50%] justify-center items-center flex"
            ></i
          ></a>
          <a
            href="https://www.facebook.com/profile.php?id=100069323370597"
            class="bg-[#353535] w-[40px] h-[40px] flex rounded-[50%] justify-center items-center"
            ><i
              class="bx bxl-facebook-circle hover:text-black text-[30px] text-white w-[40px] h-[40px] rounded-[50%] justify-center items-center flex"
            ></i
          ></a>
        </div>

        <div class="mt-[80px]">
          <a
          href="https://drive.google.com/file/d/17bjJy0phuWDemKDKbFiiPQbPQgDwE4f5/view?usp=sharing"
            download=""
            class="w-[full] border border-[#13FF00] rounded-lg mt-[100px] hover:shadow p-[7px] bg-transparet hover:bg-[#13FF00] text-[#13FF00] hover:text-white font-bold text-[20px]"
          >
            Download CV
          </a>
        </div>
      </div>

      <div
        class="w-[80%] md:w-[500px] mx-auto md:mx-0 mt-[40px]"
        data-aos="zoom-in-left"
        data-aos-duration="3000"
      >
        <img
          class="border-[3px] border-[#13FF00] rounded-full w-[500px] h-[500px]"
          src="https://picsum.photos/200/300"
          alt=""
        />
      </div>
    </div>
  </div>
  <div></div>
  <AboutView />
  <ServiceView />
  <PortifolioView />
  <ContactView />
</template>
<script>
import AboutView from "./AboutView.vue";
import ContactView from "./ContactView.vue";
import PortifolioView from "./PortifolioView.vue";
import ServiceView from "./ServiceView.vue";

export default {
  name: "HomeView",
  components: {
    ContactView,
    AboutView,
    ServiceView,
    PortifolioView,
  },

  mounted(){
    AOS.init();
  }
};
</script>
<style>
p {
  animation-duration: 3s;
  animation-name: slidein;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}
</style>

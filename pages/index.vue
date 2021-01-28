<template>
  <div>
    <Navbar />
    <Testimonials />
    <Features />
    <Newsletter />
    <Footer year="2021" />
  </div>
</template>

<script>
import Navbar from "~/components/mainpage/Navbar";
import Testimonials from "~/components/mainpage/Testimonials";
import Features from "~/components/mainpage/Features";
import Newsletter from "~/components/mainpage/Newsletter";
import Footer from "~/components/mainpage/Footer";

export default {
  components: {
    Navbar,
    Testimonials,
    Features,
    Newsletter,
    Footer,
  },
  head: {
    script: [
      {
        src:
          "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/js/all.js",
      },
    ],
  },
  name: "HomePage",
};
</script>

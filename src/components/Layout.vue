<template>
  <div>
  <Header/>
  <main className="container flex-grow px-4 mx-auto my-12 px-10">
    <slot/>
  </main>
  <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";

export default {
  components: {
    Header,
    Footer,
  },
}
</script>
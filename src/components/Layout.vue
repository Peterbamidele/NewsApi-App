<template>
  <div>
  <Header/>
  <main className="container flex-grow px-4 mx-auto my-12">
    <slot/>
  </main>
  <Footer/>
  </div>
</template>

<script>
import Header from "./Header.vue"
import Footer from "./Footer.vue"

export default {
  components: {
    Header,
    Footer,
  },
}
</script>
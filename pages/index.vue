<template>
  <div class="w-full">
    <div>
      <NavBar />
      <Hero />
      <Highlights/>
      <Footer/>
      <HowWorks/>
      <Header />
      <h1 class="title">
        round-vue
      </h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="px-5 py-3 text-gray-200 bg-blue-500 rounded-md"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Interview Help | Master Interviews with Pragra Prep| Tech Interview Help'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'PragraPrep is unique platform to get all interview help, our mentors will provide your custom trailer made strategies to clear inteview'
        }
      ]
    }
  }
}
</script>

<style>
</style>

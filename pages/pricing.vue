<template>
  <div class="w-full">
    <div>
      <NavBar />
      <Pricetab/>
      <Footer/>
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

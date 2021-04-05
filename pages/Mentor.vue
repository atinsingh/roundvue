<template>
  <div class="w-full">
    <div>
      <NavBar />
      <div class="block lg:flex lg:space-x-2 px-10  mt-10 mb-10 p-10">
      <div class="w-full lg:w-2/3">

        <a class="block rounded w-full lg:flex mb-10"
          href="./blog-single-1.html"
        >
          <div 
            class="h-48 lg:w-48 flex-none bg-cover text-center overflow-hidden opacity-75"
            style="background-image: url('https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2100&q=80')" 
            title="deit is very important"
          >
          </div>
          <div class="bg-white rounded px-4 flex flex-col justify-between leading-normal">
            <div>
              <div class="mt-3 md:mt-0 text-gray-700 font-bold text-2xl mb-2">
                Aliquam venenatis nisl id purus rhoncus, in efficitur sem hendrerit.
              </div>
              <p class="text-gray-700 text-base">
                Duis euismod est quis lacus elementum, eu laoreet dolor consectetur. 
                Pellentesque sed neque vel tellus lacinia elementum. Proin consequat ullamcorper eleifend.
              </p>
            </div>
            <div class="flex mt-3">
              <img src="https://randomuser.me/api/portraits/men/86.jpg"
                class="h-10 w-10 rounded-full mr-2 object-cover" />
              <div>
                <p class="font-semibold text-gray-700 text-sm capitalize"> eduard franz </p>
                <p class="text-gray-600 text-xs"> 14 Aug </p>
              </div>
            </div>
          </div>
        </a>

        <div class="rounded w-full lg:flex mb-10">
          <div class="h-48 lg:w-48 flex-none bg-cover text-center overflow-hidden opacity-75"
            style="background-image: url('https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2100&q=80')" title="deit is very important">
          </div>
          <div class="bg-white rounded px-4 flex flex-col justify-between leading-normal">
            <div>
              <div class="mt-3 md:mt-0 text-gray-700 font-bold text-2xl mb-2">
                Integer commodo, sapien ut vulputate viverra
              </div>
              <p class="text-gray-700 text-base">
                Nam malesuada aliquet metus, ac commodo augue mollis sit amet. 
                Nam bibendum risus sit amet metus semper consectetur.
                Proin consequat ullamcorper eleifend.
                Nam bibendum risus sit amet metus semper consectetur.
              </p>
            </div>
            <div class="flex mt-3">
              <img src="https://randomuser.me/api/portraits/women/54.jpg"
                class="h-10 w-10 rounded-full mr-2 object-cover" />
              <div>
                <p class="font-semibold text-gray-700 text-sm capitalize"> Serenity Hughes </p>
                <p class="text-gray-600 text-xs"> 14 Aug </p>
              </div>
            </div>
          </div>
        </div>

        <div class="rounded w-full lg:flex mb-10">
          <div class="h-48 lg:w-48 flex-none bg-cover text-center overflow-hidden opacity-75"
            style="background-image: url('https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2100&q=80')" title="deit is very important">
          </div>
          <div class="bg-white rounded px-4 flex flex-col justify-between leading-normal">
            <div>
              <div class="mt-3 md:mt-0 text-gray-700 font-bold text-2xl mb-2">
                Suspendisse varius justo eu risus laoreet fermentum non aliquam dolor
              </div>
              <p class="text-gray-700 text-base">
                Mauris porttitor, velit at tempus vulputate, odio turpis facilisis dui, 
                vitae eleifend odio ipsum at odio. Phasellus luctus scelerisque felis eget suscipit. 
              </p>
            </div>
            <div class="flex mt-3">
              <img src="https://randomuser.me/api/portraits/men/86.jpg"
                class="h-10 w-10 rounded-full mr-2 object-cover" />
              <div>
                <p class="font-semibold text-gray-700 text-sm capitalize"> eduard franz </p>
                <p class="text-gray-600 text-xs"> 14 Aug </p>
              </div>
            </div>
          </div>
        </div>

      </div>   
      </div>  
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

<template>
  <div class="main bg-neutral-100">
    <headerComp />
    <div class="container max-w-7xl mx-auto px-6 py-20 2xl:p-28 rounded-xl bg-contain bg-no-repeat bg-white border border-gray-200" style="background-image:url('https://polaris.shopify.com/bundles/493efd38c8d3ec9de863ac327a04f49e6dfc069465e960dcd295d28ddadaae02.svg');">
      <h1 class="text-5xl font-medium">Polaris</h1>
      <p class="text-2xl w-full sm:max-w-sm mt-8">Our design system helps us work together to build a great experience for all of Shopify’s merchants.</p>
      <h3 class="text-3xl mt-24 font-medium">Guides</h3>
      <p class="text-2xl w-full sm:max-w-xl mt-8 text-stone-500">Check out these practical guides to help you understand how to design for the Shopify platform using Polaris.</p>
      <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-10 mt-10 pb-10 border-b-4 border-gray-100">
        <a href="#!" class="text-blue-500 underline">Shopify experience values</a>
        <a href="#!" class="text-blue-500 underline">Page layouts</a>
        <a href="#!" class="text-blue-500 underline">Designing apps for Shopify</a>
        <a href="#!" class="text-blue-500 underline">Internationalization</a>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-10 my-10">
        <div>
          <h4 class="text-2xl mb-4">Content</h4>
          <p class="mb-4">Learn how to use language to design a more thoughtful product experience.</p>
          <a href="#!" class="text-blue-500 underline">Read content guidelines</a>
        </div>
        <div>
          <h4 class="text-2xl mb-4">Design</h4>
          <p class="mb-4">Find out how we approach the visual elements of our interface with purpose.</p>
          <a href="#!" class="text-blue-500 underline">Read design guidelines</a>
        </div>
        <div>
          <h4 class="text-2xl mb-4">Components</h4>
          <p class="mb-4">Use components as building blocks as you develop new products and features.</p>
          <a href="#!" class="text-blue-500 underline">Browse components</a>
        </div>
        <div>
          <h4 class="text-2xl mb-4">Patterns</h4>
          <p class="mb-4">Read guidance for crafting patterns in the Shopify admin.</p>
          <a href="#!" class="text-blue-500 underline">Browse experiences</a>
        </div>
      </div>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10 mt-16 pb-16 border-b-4 border-gray-100">
        <div class="px-5 py-10 md:px-10 bg-stone-100 rounded-md">
          <h6 class="font-medium">What’s new</h6>
          <h4 class="text-2xl mb-4 font-medium">Polaris v9.0.0</h4>
          <p class="mb-4">A new approach to design tokens. Removes Sass functions, mixins, and more for new CSS custom properties and components to ensure you can ship design decisions with consistency and scale.</p>
          <a href="#!" class="text-blue-500 underline">Read all Polaris updates</a>
        </div>
        <div class="px-5 py-10 md:px-10 bg-stone-100 rounded-md">
          <h6 class="font-medium">Blog posts, talks, and events</h6>
          <div class="mt-4">
            <div class="flex mb-4">
              <img src="https://ritecaremedicalofficepc.com/wp-content/uploads/2019/09/img_avatar.png" class="w-16 h-16 rounded-2xl mr-4" />
              <div class="flex-col">
                <a href="#!" class="text-blue-500 underline flex-grow-3">Design systems are flawed</a>
                <div class="flex">
                  <p class="mr-2">Post by</p>
                  <a href="#!" class="text-gray-500 underline">José Torre</a>
                </div>
              </div>
            </div>
            <div class="flex mb-4">
              <img src="https://ritecaremedicalofficepc.com/wp-content/uploads/2019/09/img_avatar.png" class="w-16 h-16 rounded-2xl mr-4" />
              <div class="flex-col">
                <a href="#!" class="text-blue-500 underline flex-grow-3">How to create accessible and inclusive product content guidelines</a>
                <div class="flex">
                  <p class="mr-2">Post by</p>
                  <a href="#!" class="text-gray-500 underline">Shay Perez</a>
                </div>
              </div>
            </div>
            <div class="flex">
              <img src="https://ritecaremedicalofficepc.com/wp-content/uploads/2019/09/img_avatar.png" class="w-16 h-16 rounded-2xl mr-4" />
              <div class="flex-col">
                <a href="#!" class="text-blue-500 underline flex-grow-3">A map for uncovering your assumptions</a>
                <div class="flex">
                  <p class="mr-2">Post by</p>
                  <a href="#!" class="text-gray-500 underline">Sara Hill</a>
                </div>
              </div>
            </div>
          </div>       
        </div> 
      </div>
      <div class="mt-10">
        <h3 class="text-3xl font-medium mb-3">Resources</h3>
        <p class="w-full md:max-w-2xl">Downloads, links, and third-party tools to help you and your teams learn, draft, design, and build products for Shopify.</p>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10 mt-20">
          <div>
            <h5 class="text-2xl">React components</h5>
            <p>Browse the source code and latest release notes on GitHub.</p>
          </div>
          <div>
            <h5 class="text-2xl">Figma UI Kit</h5>
            <p>Access the Figma UI Kit via the Shopify Figma Community profile.</p>
          </div>
          <div>
            <h5 class="text-2xl">GraphQL API</h5>
            <p> Use the API to build Figma plugins, text editor extensions, or even a completely new site.</p>
          </div>
        </div>
        <a href="#!" class="block text-blue-500 underline flex-grow-3 mt-10 md:text-center">Browse more resources</a>
      </div>  
    </div>
    <footerComp />
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

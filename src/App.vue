<script setup>
import Header from './components/Header.vue'
import SliderFirst from './components/SliderSectionOne.vue'
import SelectingBrand from './components/SelectingBrand.vue'
import BlockSeeOffers from './components/BlockSeeOffers.vue'
import ShopSomeWear from './components/ShopSomeWear.vue'
import Bannershoping from './components/Bannershoping.vue'
import FeaturedItems from './components/FeaturedItems.vue'
import ExploreBlock from './components/ExploreBlock.vue'
import Blog from './components/Blog.vue'
import Footer from './components/Footer.vue'
import BlogCheckboxes from './components/BlogCheckboxes.vue'
</script>


<template> 
  <Header></Header>
  <SliderFirst></SliderFirst>
  <SelectingBrand></SelectingBrand>
  <BlockSeeOffers></BlockSeeOffers>
  <ShopSomeWear></ShopSomeWear>
  <Bannershoping></Bannershoping>
  <FeaturedItems></FeaturedItems>
  <ExploreBlock></ExploreBlock>
  <Blog></Blog>
  <BlogCheckboxes></BlogCheckboxes>
  <Footer></Footer>
</template>



<style>

@font-face {
  font-family: "Oswald";
  font-style: 'light';
  src: url('../public/fonts/oswald/Oswaldlight.woff2');
}

@font-face {
  font-family: "Oswald";
  font-style: 'medium';
  src: url('../public/fonts/oswald/Oswaldmedium.woff2');
}

@font-face {
  font-family: "Roboto Medium";
  font-style: 'Medium';
  src: url('../public/fonts/roboto/Robotomedium.woff2');
}
@font-face {
  font-family: "Roboto Light";
  font-style: 'light';
  src: url('../public/fonts/roboto/Robotolight.woff2');
}
@font-face {
  font-family: "Inter";
  font-style: 'Medium';
  src: url('../public/fonts/Inter/Inter-Regular.woff2');
}

:root {
	--main-color: #e6f1fa;
	--main-color-2: #eb5757;
	--advanced: #57a4eb;
	--black: #000;
	--black-2: #3f3f3f;
	--white: #fff;
	--gray-1: #828282;
	--light-blue-hover: #f0f2f2;
	--divider: #c4c4c4;
	--link: #0f6db1;
}

:root {
  --font-family: "Oswald", sans-serif;
  --font-family-medium: "Oswald", sans-serif;
  --second-family: "Roboto", sans-serif;
  --third-family: "Roboto Medium", sans-serif;
  --font3: "Roboto Light", sans-serif;
  --font4: "Inter", sans-serif;
}


a, button, input {
  cursor: pointer;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.content {
  padding: 0 20px;
}
</style>

<template>
<div class="slider-section-one__wrap">
<div class="slider-first">
<div class="slider-first__central-block">
<div class="slider-first__block-advertisements">

  <svg class="block-advertisements__frame" width="498" height="102" viewBox="0 0 498 102" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0.5 1L497 1V101.5" stroke="black" stroke-width="2" />
</svg> 
<p class="block-advertisements__text">
  SUMMER SALE
GEt <span class="persent-30">30% OFF</span>
On all dress.
</p>

<button class="shop-button" type="button">
  shop now
</button>
</div>

<div class="slider-first__block-photo-models">
<img class="model-1" src="../assets/img/image-slider-model.jpg" alt="photo">
<img class="model-2" src="../assets/img/image-slider-model-2.jpg" alt="photo">
</div>
</div>



<fieldset class="slider-dots"> 

  <div>
<input type="radio" name="rb" id="rb1" checked> <label for="rb1"></label>
</div>

<div>
<input type="radio" name="rb" id="rb2"> <label for="rb2"></label>
</div>

<div>
<input type="radio" name="rb" id="rb3"> <label for="rb3"></label>
</div>
 </fieldset>

<div class="slider-arrows-block">
<div class="arrow">
  <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect width="50" height="50" fill="black" fill-opacity="0.9" />
  <path d="M28.0703 18L20.9995 25.0708L28.0703 32.1417" stroke="white" stroke-width="2" />
</svg>
</div>
<div class="arrow">
  <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="50" y="50" width="50" height="50" transform="rotate(-180 50 50)" fill="black" fill-opacity="0.9" />
  <path d="M21.9297 32L29.0005 24.9292L21.9297 17.8583" stroke="white" stroke-width="2" />
</svg>
</div>
</div>


</div>
</div>
</template>
  
  <script>
  
  </script>
  
  <style scoped>

.slider-section-one__wrap {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px 20px;
}
.slider-first {
    width: 100%;
    height: 800px;

    background: linear-gradient(174deg, rgba(255, 255, 255, 0.6) 35.42%, rgba(255, 255, 255, 0.6) 100%), url('../assets/img/background.png');
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    position: relative;
}

.slider-first__central-block {
    display: flex;
    width: 1458px;
    justify-content: space-between;
    align-items: center;    
}

.slider-first__block-advertisements {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
    width: 545px;
    z-index: 2;
}

.block-advertisements__frame{
    position: absolute;
    top: -30px;
    right: 0;
}

.block-advertisements__text {
    font-family: var(--font-family);
    font-weight: 600;
    font-size: 86px;
    line-height: 112%;
    text-transform: uppercase;
    color: var(--black);    
    width: 100%;
}

.persent-30 {
  font-family: var(--font-family);
font-weight: 600;
font-size: 86px;
line-height: 112%;
text-transform: uppercase;
color: var(--black);
}

.slider-first__block-photo-models {
    display: flex;
    max-width: 804px;
    box-sizing: border-box;
    position: relative;
    align-items: center;
}

.shop-button {
    width: 175px;
    font-family: var(--font-family);
    font-weight: 500;
    font-size: 18px;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    text-align: center;
    color: var(--black);
    background: transparent;
    border: 2px solid var(--black);
    height: 56px;
    margin-top: 48px;
}

.model-1 {
    display: flex;
    align-items: center;
    width: 416px;
    height: 623px;
    margin-left: -290px;
    position: absolute;
    z-index: 1;
}

.model-2  {
  z-index: 2;
}

.slider-dots {
    max-width: 100px;
    display: flex;
    width: 100%;
    justify-content: space-between;
    margin-left: 28px;
    margin-right: auto;
    position: absolute;
    left: 0;
    bottom: 0;
    outline: none;
    border: none;
}

.radiobutton {
  border: 1px solid var(--gray-1);
width: 18px;
height: 18px;
}

label {
  position: relative;
}

.slider-first__control-block {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.slider-arrows-block {
    display: flex;
    width: 103px;
    justify-content: space-between;
    position: absolute;
    bottom: 0;
    right: 0;
}

input[type="checkbox"]:checked, 
input[type="checkbox"]:not(:checked), 
input[type="radio"]:checked, 
input[type="radio"]:not(:checked) 
{
    position: absolute;
    left: -9999px;
}

input[type="checkbox"]:checked + label, 
input[type="checkbox"]:not(:checked) + label, 
input[type="radio"]:checked + label, 
input[type="radio"]:not(:checked) + label {
    display: inline-block;
    position: relative;
    padding-left: 28px;
    line-height: 20px;
    cursor: pointer;
}

input[type="checkbox"]:checked + label:before, 
input[type="checkbox"]:not(:checked) + label:before,
input[type="radio"]:checked + label:before, 
input[type="radio"]:not(:checked) + label:before {
    content: "";
    position: absolute;
    left: 0px;
    top: 0px;
    width: 18px;
    height: 18px;
    border: 1px solid #dddddd;
    background-color: #ffffff;
}

input[type="checkbox"]:checked + label:before, 
input[type="checkbox"]:not(:checked) + label:before {
    border-radius: 2px;
}

input[type="radio"]:checked + label:before, 
input[type="radio"]:not(:checked) + label:before {
    border-radius: 100%;
}

input[type="checkbox"]:checked + label:after, 
input[type="checkbox"]:not(:checked) + label:after, 
input[type="radio"]:checked + label:after, 
input[type="radio"]:not(:checked) + label:after {
    content: "";
    position: absolute;
    -webkit-transition: all 0.2s ease;
    -moz-transition: all 0.2s ease;
    -o-transition: all 0.2s ease;
    transition: all 0.2s ease;
}

input[type="checkbox"]:checked + label:after, 
input[type="checkbox"]:not(:checked) + label:after {
    left: 3px;
    top: 4px;
    width: 10px;
    height: 5px;
    border-radius: 1px;
    border-left: 4px solid #e145a3;
    border-bottom: 4px solid #e145a3;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    transform: rotate(-45deg);
}

input[type="radio"]:checked + label:after, 
input[type="radio"]:not(:checked) + label:after {
    left: 5px;
    top: 5px;
    width: 10px;
    height: 10px;
    border-radius: 100%;
    background-color: #e145a3;
}

input[type="checkbox"]:not(:checked) + label:after, 
input[type="radio"]:not(:checked) + label:after {
    opacity: 0;
}

input[type="checkbox"]:checked + label:after, 
input[type="radio"]:checked + label:after {
    opacity: 1;
}

  </style>
  
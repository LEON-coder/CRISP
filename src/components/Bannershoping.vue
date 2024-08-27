<template>
  <div class="Bannershoping">
    <div class="content">
<section class="Bannershoping__wrap">
  <div class="slider-first__block-advertisements Bannershoping-modify">

<svg class="block-advertisements__frame Bannershoping-frame" width="498" height="102" viewBox="0 0 498 102" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M0.5 1L497 1V101.5" stroke="black" stroke-width="2" />
</svg> 
<p class="block-advertisements__text Bannershoping-text">
  shoping without limits.
</p>
<p class="block-advertisements__text Bannershoping-text-describe">
  You can choose the best option for you, and it does not matter whether you are in Prague or San Francisco.
   We will deliver your purchase anywhere!
</p>


<button class="shop-button" type="button">
shop now
</button>
</div>


</section>
    </div>
  </div>
</template>


<script>
    
</script>


<style scoped> 

.Bannershoping {
    background: url('../assets/img/Bannershoping/Bannershoping__background.png') no-repeat center center;
    display: flex;
    width: 100%;
    height: 467px;
    margin-top: 62px;
}
.Bannershoping__wrap {
    display: flex;
    width: 100%;
    justify-content: space-between;
    position: relative;    
    height: 100%;
    
}

.Bannershoping__img {
    z-index: 0;   
}
.slider-first__block-advertisements {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: relative;
    width: 545px;
    z-index: 2;
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

.Bannershoping-modify {
    z-index: 3;
    padding: 77px 0 78px 269px;
    height: 100%;
    max-width: 1357px;
    width: 100%;
}
.Bannershoping-text {
  font-family: var(--font-family);
font-weight: 500;
font-size: 56px;
line-height: 129%;
text-transform: uppercase;
color: var(--black);
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

.Bannershoping-text-describe {
    font-family: var(--font3);
    font-weight: 400;
    font-size: 25px;
    line-height: 148%;
    letter-spacing: 0.01em;
    color: var(--black);
    max-width: 639px;
    text-transform: none;
}

.Bannershoping-frame {
    position: absolute;
    top: 60px;
    right: 0;
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

</style>
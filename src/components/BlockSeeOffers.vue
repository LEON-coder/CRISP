<template>
<div class="BlockSeeOffers">
<div class="content">
<section class="BlockSeeOffers__wrap">

  <div class="BlockProposing__left-block">
<div class="BlockProposing your-look">
 <picture class="woman-1">
  <img src="../assets/img/BlockSeeOffers/woman-1.png" alt="woman-picture">
</picture>
  
<div class="your-look__block-info">
<div class="your-look__block-text">
<h3 class="BlockProposing__headline">
  choosе your look
</h3>

<p class="BlockProposing__describe">
  See our clothing collections
</p>
</div>
<button type="button" class="button-see-offers">
  see offers
</button>
</div>

</div>


<div class="BlockProposing brand-new-style"> 
  <div class="brand-new-style__block-info">
<div class="your-look__block-text new-style-width">
<h3 class="BlockProposing__headline ">
  brand new style
</h3>

<p class="BlockProposing__describe">
  Popular clothing brands
</p>
</div>
<button type="button" class="button-see-offers">
  see offers </button>
</div>
 
  <picture class="woman-2">
  <img src="../assets/img/BlockSeeOffers/woman-2.png" alt="woman-picture">
</picture>
  

</div>
  </div>

<div class="BlockProposing__right-block">
<picture class="woman-3">
 <img src="../assets/img/BlockSeeOffers/woman-3.png">
</picture>

<div class="your-look__block-info block-info-3">
<div class="your-look__block-text  block-text-3">
<h3 class="BlockProposing__headline BlockProposing__headline-3">
  Up to 40% off
</h3>

<p class="BlockProposing__describe describe-3">
  Special offers and great deals
</p>
</div>
<button type="button" class="button-see-offers">
  see offers
</button>
</div>
</div>


</section>
  </div>

</div>
</template>



<script>
</script>


<style scoped>
.BlockProposing {
  display: flex;
  max-width: 924px;
  height: 434px;
  position: relative;
}

.your-look {
    background: linear-gradient(270deg, rgba(241, 239, 240, 0) 0%, #f1f0f0 10.94%, #f3f0ef 100%);
    justify-content: end;
    align-items: center;
    display: flex;
}

.woman-1 {
  position: absolute;
  top: 0;
  left: 0;
}

.your-look__block-text {
    display: flex;
    flex-direction: column;   
}

.BlockSeeOffers__wrap {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    width: 100%;
}

.BlockProposing__headline {
  font-family: var(--font-family);
font-weight: 600;
font-size: 48px;
line-height: 129%;
text-transform: uppercase;
color: var(--black);
}

.BlockProposing__left-block {
    display: flex;
    flex-direction: column;
    max-width: 924px;
    width: 100%;
    justify-content: space-between;
    max-height: 898px;
    gap: 30px;
}

.BlockProposing__describe {
  font-family: var(--font3);
font-weight: 400;
font-size: 22px;
line-height: 168%;
letter-spacing: 0.01em;
color: var(--black);
}

.button-see-offers {
    font-family: var(--font-family);
    font-weight: 500;
    font-size: 18px;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    text-align: center;
    color: var(--black);
    max-width: 175px;
    min-height: 56px;
    border: 2px solid var(--black);
    margin-top: 51px;
}

.your-look__block-info {
    padding: 82px 64px 82px 112px;
    max-width: 450px;
    display: flex;
    flex-direction: column;
    z-index: 2;
}

.brand-new-style {
    background: linear-gradient(90deg, #f7e0d5 0%, #f3dcd2 83.85%, rgba(243, 220, 210, 0.14) 100%);
    display: flex;
}
.woman-2 {
    background: var(--divider);
    max-width: 557px;
    height: 434px;
    position: absolute;
    top: 0;
    right: 0;
}

.brand-new-style__block-info {
    padding: 115px 94px 0 115px;
    z-index: 2;
}

.new-style-width {
    max-width: 370px;
}

.BlockProposing__right-block {
    display: flex;
    max-width: 925px;
    width: 100%;
    position: relative;
    background: linear-gradient(90deg, #e0ded3 0%, #e0ddd5 86.82%, #e0ddd5 100%);
}

.woman-3 {
position: absolute;
top: 0;
right: 0;
padding: 0;
}

.block-info-3 {
    margin-top: 430px;
    margin-left: 86px;
    padding: 0;
}

.block-text-3 {
  font-family: var(--font-family);
font-weight: 600;
font-size: 96px;
line-height: 115%;
color: #131313;
}

.describe-3 {
    max-width: 320px;   
}

.BlockProposing__headline-3 {
    font-size: 96px;
    line-height: 115%;
    text-transform: uppercase;
    color: #131313;
}
</style>
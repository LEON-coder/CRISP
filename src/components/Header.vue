<template>
  <section class="header">
    <img class="Logo" src="../../public/img/Logo.svg" alt="logo">
  
    <nav class="navigation">
      <ul class="navigation__links">
        <li class="navigation__item">
          <a class="navigation__link" href="#">home</a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#">shop</a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#">blog</a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#">sale</a>
        </li>
        <li class="navigation__item">
          <a class="navigation__link" href="#">contact us</a>
        </li>
      </ul>
  
      <section class="search-block">
        <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="6.15385" cy="6.15385" r="4.95385" stroke="white" stroke-width="2.4" />
          <path d="M11.4872 11.4871L16 15.9999" stroke="white" stroke-width="2.4" />
        </svg>
  
        <span class="search-block__text">
          search
        </span>
  
        <section class="search-block-open">
  <input type="search" placeholder="Search">
  <svg class="search-open-icon" width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="6.15385" cy="6.15385" r="4.95385" stroke="white" stroke-width="2.4" />
          <path d="M11.4872 11.4871L16 15.9999" stroke="white" stroke-width="2.4" />
        </svg>
        </section>
  
        
      </section>
    </nav>
  
    <div class="header__block-autorization">
      <a class="header__sign-in" href="#">
        SIGN IN
      </a>
      <a class="header__create-account" href="#">
        CREATE AN ACCOUNT
      </a>
    </div>
  
    <div class="header__cart-block">
      <a href="#" class="icon-like">
        <svg width="23" height="22" viewBox="0 0 23 22" fill="" xmlns="http://www.w3.org/2000/svg">
          <path d="M10.7096 18.9029L11.5 19.5949L12.2904 18.9029L13.5212 17.8254L13.5229 17.8239L13.561 17.7907C15.7089 15.9176 17.5897 14.2775 18.9222 12.7097C20.2744 11.1187 21.2 9.44687 21.2 7.49591C21.2 4.26214 18.5597 1.8 15.325 1.8C13.9256 1.8 12.5737 2.2769 11.5 3.08132C10.4263 2.2769 9.07441 1.8 7.675 1.8C4.44032 1.8 1.8 4.26214 1.8 7.49591C1.8 9.44687 2.7256 11.1187 4.07783 12.7097C5.41031 14.2774 7.29114 15.9176 9.43903 17.7907L9.47705 17.8239L9.4788 17.8254L10.7096 18.9029Z" stroke="white" stroke-width="2.4" />
        </svg>
      </a>
  
      <div class="shopping-cart-total">
        <a href="#" class="icon-cart">
          <svg width="18" height="22" viewBox="0 0 18 22" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1.27266 20.8L2.13149 6.2H15.8685L16.7273 20.8H1.27266Z" stroke="white" stroke-width="2.4" />
            <path d="M5 5V3C5 2.44772 5.44772 2 6 2H12C12.5523 2 13 2.44772 13 3V5" stroke="white" stroke-width="2.4" />
          </svg>
        </a>
  
        <div class="header__shopping-cart-block">
          <p class="shopping-cart-text">
            Shopping Cart
          </p>
          <div class="shopping-cart-sum-block">
            <div class="shopping-cart-summ">
              0,00
            </div>
  
            <div class="shopping-cart-currency">
              EUR
            </div>
          </div>
        </div>
  
      </div>
    </div>
  
  </section>
  </template>
  
  <script>
  
  </script>
  
  <style scoped>
  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 100%;
    min-height: 115px;
    background-color: #000000;
    padding: 0 21px;
    box-sizing: border-box;
  }
  
  .navigation {
    display: flex;
    align-items: center;
    max-width: 415px;
    justify-content: space-between;
    width: 100%;
  }
  
  .navigation__item {
    display: flex;
    height: 28px;
    justify-content: center;
    align-items: center;
    padding: 10px 10px;
    border-bottom: 2px solid transparent;
    transition: 1s ease;
  }
  
  .navigation__item:hover {
    padding: 10px 10px;
    border-bottom: 2px solid var(--main-color-2);
  }
  
  .navigation__links {
    display: flex;
    justify-content: space-between;
    width: 100%;
    padding-left: 0;
  }
  
  .navigation__link {
    font-family: var(--font-family);
    font-weight: 600;
    font-size: 14px;
    text-transform: uppercase;
    color: var(--white);
    -webkit-text-decoration: transparent;
    text-decoration: transparent;
    transition: 1s all;
    width: fit-content;
  }
  
  .navigation__link:last-child {
    margin-right: 0;
  }
  
  .search-block__text {
    font-family: var(--font-family);
    font-weight: 600;
    font-size: 14px;
    text-transform: uppercase;
    color: var(--white);
  }
  
  .header__block-autorization {
    display: flex;
    align-items: center;
  }
  
  .header__sign-in,
  .header__create-account {
    font-family: var(--font-family);
    font-weight: 600;
    font-size: 14px;
    text-transform: uppercase;
    color: var(--white);
    text-decoration: none;
  }
  
  .header__create-account {
    margin-left: 12px;
  }
  
  .header__cart-block {
    display: flex;
    align-items: center;
  }
  
  .search-block {
    display: flex;
    margin-left: 29px;
    max-width: 69px;
    justify-content: space-around;
    width: 100%;
  }
  
  .shopping-cart-total {
    display: flex;
  }
  
  .icon-cart {
    display: flex;
    align-items: center;
    margin-right: 16px;
    height: 25px;
  }
  
  .icon-like {
    margin-right: 20px;
  }
  
  .shopping-cart-text {
    font-family: var(--third-family);
    font-weight: 400;
    font-size: 12px;
    letter-spacing: 0.01em;
    color: var(--white);
    margin: 0;
  }
  
  .shopping-cart-sum-block {
    display: flex;
    width: 100%;
    justify-content: space-between;
    max-width: 60px;
  }
  
  .shopping-cart-summ,
  .shopping-cart-currency {
    font-family: var(--second-family);
    font-weight: 700;
    font-size: 14px;
    letter-spacing: 0.01em;
    color: var(--white);
  }

  .search-block-open {
    display: none;
  }
  </style>
  
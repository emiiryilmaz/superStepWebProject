
import { RouterLink } from 'vue-router';

<template>
  <div>
    <header>
      <div class="global-notification">
        <p>
          Siparişin 2-4 iş günü içerisinde kargoya verilecektir.
        </p>
      </div>
      <div class="header-row">
        <div class="header-wrapper">
          <div class="header-left">
            <a href="#" class="logo"></a>
            <img loading="lazy" src="https://akn-ss.b-cdn.net/static_omnishop/super522/assets/img/logo-black.svg"
              alt="Super Step" width="200">
          </div>
          <div class="header-center-menu">
            <div class="header-center">
              <nav class="navigation">
                <ul class="menu-list">
                  <li class="menu-list-item">
                    <a href="#" class="menu-link">Markalar</a>
                  </li>
                  <li class="menu-list-item">
                    <a href="#" class="menu-link">Erkek</a>
                  </li>
                  <li class="menu-list-item">
                    <a href="#" class="menu-link">Kadın</a>
                  </li>
                  <li class="menu-list-item">
                    <a href="#" class="menu-link"> Çocuk </a>
                  </li>
                  <li class="menu-list-item">
                    <a href="#" class="menu-link">Giyim</a>
                  </li>
                  <li class="menu-list-item">
                    <a href="#" class="menu-link">İndirim</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
          <div class="header-right">
            <ul class="menu-list">
              <li class="menu-list-item">
                <a href="#" class="menu-link">
                  <img loading="lazy" class="icon-favorite-svg"
                    src="https://akn-ss.b-cdn.net/static_omnishop/super522/assets/img/header-icons/search.svg"
                    height="24px">
                </a>
              </li>
              <router-link to="LoginPage">
                <li class="menu-list-item">
                  <a href="#" class="menu-link">
                    <router-link to="LoginPage"></router-link>
                    <img loading="lazy" class="icon-favorite-svg"
                      src="https://akn-ss.b-cdn.net/static_omnishop/super522/assets/img/header-icons/user.svg"
                      height="24px">
                  </a>
                </li>
              </router-link>

              <li class="menu-list-item">
                <a href="#" class="menu-link">
                  <img loading="lazy" class="icon-favorite-svg"
                    src="https://akn-ss.b-cdn.net/static_omnishop/super522/assets/img/header-icons/heart.svg"
                    height="24px">

                </a>
              </li>
              <li class="menu-list-item">
                <a href="#" class="menu-link">
                  <img loading="lazy" class="icon-favorite-svg"
                    src="https://akn-ss.b-cdn.net/static_omnishop/super522/assets/img/header-icons/bag.svg"
                    height="24px">
                </a>
              </li>
            </ul>

          </div>
        </div>
      </div>
    </header>
  </div>
</template>

 

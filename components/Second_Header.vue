<script setup>

</script>

<template>
  <div class="header__bottom" style="padding: 0;">
    <div class="header__bottom-inner container">
      <button class="header__show-menu show-menu" type="button" data-modal-toggle="#modal-mobile-menu">
        <span></span>
      </button>

      <span class="header__logo logo" href="/">
                        <img src="/images/logo.png" style="width: 40px; height: 40px;" alt="UniTrade">
                    </span>

      <button class="header__catalog btn-toggle" data-modal-toggle="#modal-header-catalog">
        <span class="header__catalog-icon btn-toggle__icons" style="margin: 0px 5px 0px 0px;">📕</span>
        <span class="header__catalog-text">Каталог</span></button>
      <form class="header__search search" action="/search/?search=query&amp;json=true"
            data-action="/search/?search=query&amp;json=true" data-ignore-fields="">
        <button class="header__search-button search__button" type="button"
                data-modal-toggle="#modal-search">
          <svg class="icon icon_search">
            <use xlink:href="images/sprite.svg#search"></use>
          </svg>
        </button>
        <div class="header__search-inner search__inner">
          <label class="search__label">
            <input class="search__input main-search" type="text" placeholder="Найти товар" name="search"
                   autocomplete="off">
          </label>
          <!--noindex-->
          <ul class="search__result search__result_popular">
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Кабель+СИП" rel="nofollow">
                Кабель СИП
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Электрод+для+сварки+чугуна"
                 rel="nofollow">
                Электрод для сварки чугуна
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Обратный+клапан" rel="nofollow">
                Обратный клапан
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Задвижка+стальная+фланцевая+Ду-150"
                 rel="nofollow">
                Задвижка стальная фланцевая Ду-150
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=НКТ" rel="nofollow">
                Труба НКТ
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Перфорированный+лист">
                Перфорированный лист
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Кладочная+сварная+сетка"
                 rel="nofollow">
                Кладочная сварная сетка
              </a>
            </li>
            <li class="search__result-item">
              <a class="search__result-link" href="/search/?search=Труба+ГОСТ+632-80" rel="nofollow">
                Труба ГОСТ 632-80
              </a>
            </li>
          </ul>
          <!--/noindex-->
        </div>
      </form>
      <ul class="header__menu">
        <li class="header__menu-item">
          <a class="header__menu-link" href="/services/">
            Услуги</a>
        </li>
        <li class="header__menu-item drop-menu">
          <a class="header__menu-link" href="#">
            Покупателям
            <svg width="16" height="16" viewBox="0 0 16 16" fill="none"
                 xmlns="http://www.w3.org/2000/svg">
              <path d="M11.5515 5L4.44853 5C3.91399 5 3.64628 5.64628 4.02426 6.02426L7.29289 9.29289C7.68342 9.68342 8.31658 9.68342 8.70711 9.29289L11.9757 6.02426C12.3537 5.64629 12.086 5 11.5515 5Z"
                    fill="#383A44"></path>
            </svg>
          </a>
          <div class="drop-menu__content header__menu-sub">
            <a class="header__menu-link" href="/delivery">
              Доставка</a>
            <a class="header__menu-link" href="/payment">
              Оплата</a>
            <a class="header__menu-link" href="/refund">
              Возврат</a>
          </div>
        </li>
        <li class="header__menu-item">
          <a class="header__menu-link" href="/contacts/">Контакты</a>
        </li>
        <li class="header__menu-item">
          <a class="header__menu-link" href="/contacts/">О компании</a>
        </li>
      </ul>
      <div id="js-relocate-container"></div>
      <button class="header__callback" data-modal-show="#modal-callback">
        <svg class="icon icon_callback-header">
          <use xlink:href="images/sprite.svg#callback-header"></use>
        </svg>
      </button>
      <div class="header__basket">
        <button class="basket" data-call-modal="cart">
                        <span class="basket__img">
                            <svg class="icon icon_basket">
                                <use xlink:href="images/sprite.svg#basket"></use>
                            </svg>
                            <span class="basket__counter button_cart_counter" id="button_cart_counter">0</span>
                        </span>
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>

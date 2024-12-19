<script setup>

</script>

<template>
  <div>
    <header class="header">
      <div class="header__inner">
        <div class="header__middle-inner container">
          <div class="header__middle">

                <span class="header__logo logo" href="/">
                    <img src="/images/logo.png" alt="UniTrade" style="height: 50px; width: 50px;">
                </span>


            <div class="header__content-right flex-wrap">
              <!--                    <div class="drop-menu">-->
              <!--                        <a class="header__phone link mgo-number" href="tel:+77172640297">-->
              <!--                            <span class="link__icon">-->
              <!--                                <svg class="icon icon_phone">-->
              <!--                                  <use xlink:href="images/sprite.svg#phone"></use>-->
              <!--                                </svg>-->
              <!--                            </span>-->
              <!--                            <span class="mgo-number__target">+7 (717) 264 02 97</span>-->
              <!--                            <span class="header__phone-arrow-down">-->
              <!--                                <svg class="icon icon_arrow-down">-->
              <!--                                  <use xlink:href="images/sprite.svg#arrow-down"></use>-->
              <!--                                </svg>-->
              <!--                            </span>-->
              <!--                        </a>-->
              <!--                        <div class="drop-menu__content header__phone-menu">-->

              <!--                            <div class="header__phone-menu-block">-->
              <!--                                <div class="header__phone-main d-flex">-->
              <!--                                    <div>-->
              <!--                                        <svg class="icon icon_time">-->
              <!--                                            <use xlink:href="images/sprite.svg#time"></use>-->
              <!--                                        </svg>-->
              <!--                                    </div>-->
              <!--                                    <div class="header__phone-main_time">-->
              <!--                                        <p>Пн-Чт: с 9:00 до 18:00, Пт: с 9:00 до 17:00</p>-->
              <!--                                    </div>-->
              <!--                                </div>-->
              <!--                                <div class="header__phone-lable">Время работы</div>-->
              <!--                            </div>-->
              <!--                            <div class="d-flex header__phone-menu-block_social">-->

              <!--                                <a class="btn btn_light" href="https://t.me/isteelskz_bot" target="_blank">-->
              <!--                                    <span>Telegram</span>-->
              <!--                                    <img loading="lazy" src="images/telegram.png" alt="Telegram">-->
              <!--                                </a>-->

              <!--                                <a class="btn btn_light" href="https://wa.me/77005330150" target="_blank">-->
              <!--                                    <span>WhatsApp</span>-->
              <!--                                    <img loading="lazy" src="images/whatsapp.png" alt="WhatsApp">-->
              <!--                                </a>-->

              <!--                            </div>-->
              <!--                            <button class="btn btn_light-black header__phone-menu-block_btn"-->
              <!--                                    onclick="ym(window.isteels.ym_id, 'reachGoal', 'click_callback');"-->
              <!--                                    data-modal-toggle="#modal-call">-->
              <!--                                Перезвонить-->
              <!--                                <svg class="icon icon_callback">-->
              <!--                                    <use xlink:href="images/sprite.svg#callback"></use>-->
              <!--                                </svg>-->
              <!--                            </button>-->
              <!--                        </div>-->
              <!--                    </div>-->
              <!--                    <a class="header__email link mgo-email" href="mailto:zakaz@steelfed.kz">-->
              <!--                        <span class="link__icon">-->
              <!--                          <svg class="icon icon_email">-->
              <!--                            <use xlink:href="images/sprite.svg#email"></use>-->
              <!--                          </svg>-->
              <!--                        </span>-->
              <!--                        <span class="mgo-email">zakaz@steelfed.kz</span>-->
              <!--                    </a>-->
              <!--                    <span class="header__gray-lable"-->
              <!--                          onclick="ym(window.isteels.ym_id, 'reachGoal', 'click_fast_order');"-->
              <!--                          data-call-modal="order-click">-->
              <!--                        📞 Заказ в 1 клик-->
              <!--                    </span>-->

              <button class="header__expanding_list header__language link drop-menu">
                <span class="expanding-list__option js-language-title">🇷🇺 RU</span>
                <div class="drop-menu__content header__menu-sub">
                        <span class="header__menu-link" data-google-lang="ru"
                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_ru');">🇷🇺 Русский</span>
                  <span class="header__menu-link" data-google-lang="en"
                        onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_en');">🇺🇸 Английский</span>
                  <span class="header__menu-link" data-google-lang="kk"
                        onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_kz');">🇰🇿 Казахский</span>
                </div>
              </button>

              <button class="header__expanding_list header__city link drop-menu">
                        <span class="link__icon">
                            <p style="margin: 0;">📍</p>
                        </span>
                <span class="expanding-list__option js-city-title">Выберите город</span>
                <div class="drop-menu__content header__menu-sub">
                  <!-- Города на букву А -->
                  <div class="city-group">
                    <div class="city-group__letter">А</div>
                    <div class="city-group__cities">
                      <span class="header__menu-link" onclick="changeCity('Астана');">📍 Астана</span>
                      <span class="header__menu-link" onclick="changeCity('Алматы');">📍 Алматы</span>
                    </div>
                  </div>
                  <!-- Города на букву Б -->
                  <div class="city-group">
                    <div class="city-group__letter">Б</div>
                    <div class="city-group__cities">
                      <span class="header__menu-link" onclick="changeCity('Балхаш');">📍 Балхаш</span>
                    </div>
                  </div>
                  <!-- Города на букву Ш -->
                  <div class="city-group">
                    <div class="city-group__letter">Ш</div>
                    <div class="city-group__cities">
                      <span class="header__menu-link" onclick="changeCity('Шымкент');">📍 Шымкент</span>
                    </div>
                  </div>
                </div>
              </button>


            </div>
          </div>
        </div>
        <style>
          @media screen and (max-width: 768px) {
            .header__middle-inner.container {
              display: none;
            }
          }
        </style>
        <div class="header__bottom">
          <div class="header__bottom-inner container">
            <button class="header__show-menu show-menu" type="button" data-modal-toggle="#modal-mobile-menu">
              <span></span>
            </button>

            <span class="header__logo logo" href="/">
            <img style="height: 35px; width: 35px;" src="/images/logo.png" alt="Стальная федерация">
          </span>

            <button class="header__catalog btn-toggle" data-modal-toggle="#modal-header-catalog">
                    <span class="header__catalog-icon btn-toggle__icons">
                        <img src="/images/menu.webp" alt="Открыть меню" class="open-icon" style="margin-bottom: 9px;;">
                        <img src="/images/close.webp" alt="Закрыть меню" class="close-icon">
                      </span>
              <span class="header__catalog-text">Каталог 📕</span></button>
            <form class="header__search search" action="/search/?search=query&amp;json=true"
                  data-action="/search/?search=query&json=true" type="search" data-ignore-fields="">
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
            <ul class="header__menu" style="margin-left: 200px;">
              <li class="header__menu-item">
                <a class="header__menu-link actives" href="/">
                  Главная</a>
              </li>
              <li class="header__menu-item">
                <a class="header__menu-link" href="/articles.html">
                  Статьи</a>
              </li>
              <li class="header__menu-item drop-menu">
                <a class="header__menu-link" href="#">
                  Покупателям
                  <svg width="16" height="16" viewBox="0 0 16 16" fill="none"
                       xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M11.5515 5L4.44853 5C3.91399 5 3.64628 5.64628 4.02426 6.02426L7.29289 9.29289C7.68342 9.68342 8.31658 9.68342 8.70711 9.29289L11.9757 6.02426C12.3537 5.64629 12.086 5 11.5515 5Z"
                      fill="#383A44"></path>
                  </svg>
                </a>
                <div class="drop-menu__content header__menu-sub">
                  <a class="header__menu-link" href="/payment/">
                    Оплата</a>
                  <a class="header__menu-link" href="/delivery/">
                    Доставка</a>
                  <a class="header__menu-link" href="/refund/">
                    Возврат</a>
                </div>
              </li>
              <li class="header__menu-item">
                <a class="header__menu-link" href="/contacts.html">Контакты</a>
              </li>
              <li class="header__menu-item">
                <a class="header__menu-link" href="/contacts.html">О компании</a>
              </li>
              <!--                    <li class="header__menu-item drop-menu">-->
              <!--                        <a class="header__menu-link with-arrow" href="/about/">-->
              <!--                            О компании-->
              <!--                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none"-->
              <!--                                 xmlns="http://www.w3.org/2000/svg">-->
              <!--                                <path d="M11.5515 5L4.44853 5C3.91399 5 3.64628 5.64628 4.02426 6.02426L7.29289 9.29289C7.68342 9.68342 8.31658 9.68342 8.70711 9.29289L11.9757 6.02426C12.3537 5.64629 12.086 5 11.5515 5Z"-->
              <!--                                      fill="#383A44"></path>-->
              <!--                            </svg>-->
              <!--                        </a>-->
              <!--                        <div class="drop-menu__content header__menu-sub">-->
              <!--                            <a class="header__menu-link" href="/dealership/">-->
              <!--                                Дилерство</a>-->
              <!--                            <a class="header__menu-link" href="/charity/">-->
              <!--                                Благотворительность</a>-->
              <!--                            <a class="header__menu-link" href="/blog/">-->
              <!--                                Статьи</a>-->
              <!--                            <a class="header__menu-link" href="/news/">-->
              <!--                                Новости</a>-->
              <!--                            <a class="header__menu-link" href="/cases/">-->
              <!--                                Наши проекты</a>-->
              <!--                            <a class="header__menu-link" href="/thanks/">-->
              <!--                                Благодарности</a>-->

              <!--                            <a class="header__menu-link" href="/employee/">-->
              <!--                                Наши сотрудники</a>-->

              <!--                        </div>-->
              <!--                    </li>-->

            </ul>
            <div id="js-relocate-container"></div>
            <button class="header__callback" data-modal-show="#modal-callback">
              <svg class="icon icon_callback-header">
                <use xlink:href="images/sprite.svg#callback-header"></use>
              </svg>
            </button>
            <div class="header__basket">
              <button class="basket" data-call-modal="cart">
                <div class="basket__img">
                  <img src="images/card.webp" style="height: 17px; width: 17px;" alt="">
                  <span class="basket__counter button_cart_counter" id="button_cart_counter">0</span>
                </div>
              </button>
            </div>
          </div>
        </div>
        <!-- Город-->
        <div class="modal header-modal modal-geo" id="modal-geo">
          <div class="modal__dialog">
            <div class="modal__content">
              <div class="modal-geo__container container">
                <button class="modal__close header-modal-close" aria-label="Закрыть окно">
                  <svg class="icon icon_close">
                    <use xlink:href="images/sprite.svg#close"></use>
                  </svg>
                </button>
                <b class="header-modal__title">Ваш город – Астана?</b>
                <div class="header-modal__controls">
                  <button class="header-modal__yes btn btn_dark" data-modal-hide="#modal-geo">
                    Да, всё верно
                    <svg class="icon icon_check">
                      <use xlink:href="images/sprite.svg#check"></use>
                    </svg>
                  </button>
                  <button class="header-modal__no btn btn_outline" data-modal-show="#modal-choice-city">
                    Выбрать другой
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Поиск-->
        <div class="modal header-modal search-modal" id="modal-search">
          <div class="modal__dialog">
            <div class="modal__content">
              <div class="search-modal__search search" data-action="/search/">
                <div class="search__inner">
                  <div class="search-modal__search-header">
                    <div class="container">
                      <label class="search__label">
                        <input class="search-modal__search-input search__input" type="text"
                               placeholder="Найти товар">
                      </label>
                    </div>
                  </div>
                  <div class="container">
                    <!--noindex-->
                    <ul
                      class="search-modal__search-result search-modal__search-result_popular search__result search__result_popular">
                      <li class="search__result-item">
                        <div class="search__result-title">Часто ищут</div>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Кабель+СИП" rel="nofollow">
                          Кабель СИП
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Электрод+для+сварки+чугуна"
                           rel="nofollow">
                          Электрод для сварки чугуна
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Обратный+клапан"
                           rel="nofollow">
                          Обратный клапан
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link"
                           href="/search/?search=Задвижка+стальная+фланцевая+Ду-150" rel="nofollow">
                          Задвижка стальная фланцевая Ду-150
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=НКТ" rel="nofollow">
                          Труба НКТ
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Перфорированный+лист"
                           rel="nofollow">
                          Перфорированный лист
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Кладочная+сварная+сетка"
                           rel="nofollow">
                          Кладочная сварная сетка
                        </a>
                      </li>
                      <li class="search-modal__search-item search__result-item">
                        <a class="search__result-link" href="/search/?search=Труба+ГОСТ+632-80"
                           rel="nofollow">
                          Труба ГОСТ 632-80
                        </a>
                      </li>
                    </ul>
                    <ul
                      class="search-modal__search-result search-modal__search-result_product search__result search__result_product">
                      <li class="search__result-item">
                        <div class="search__result-title">Искать</div>
                      </li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">Трубы 09Г2С<span>Все размеры</span></a>
                      </li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ
                        8731-8<span>38 x 8</span></a></li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ 8730-12<span>45 x 10</span></a>
                      </li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ
                        8730-87<span>48 x 8</span></a></li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ 8732-78<span>43,5 x 7,5</span></a>
                      </li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ 8732-01<span>40,5 x 10,5</span></a>
                      </li>
                      <li class="search-modal__search-item search__result-item"><a
                        class="search__result-link" href="#">...трубы 09Г2С ГОСТ 8732-22<span>7,5 x 7,5</span></a>
                      </li>
                      <li class="search__result-more"><a class="search__result-more-link link-more"
                                                         href="#">Все результаты
                        <svg class="icon icon_arrow-right">
                          <use xlink:href="images/sprite.svg#arrow-right"></use>
                        </svg>
                      </a></li>
                    </ul>
                    <!--/noindex-->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Каталог-->
        <div class="modal header-modal header-catalog-modal" style="margin-top: 10px;" id="modal-header-catalog">
          <div class="modal__overlay">
            <div class="modal__content">
              <div class="header-catalog-modal__inner" data-toggle-to=" ">
                <div class="header-modal__back active" data-toggle-first-add=" ">
                  <div class="container d-flex">
                    <button class="header-modal__back-btn" id="menu-btn-catalog" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      каталог продукции
                    </button>
                  </div>
                </div>
                <div class="header-modal__back" data-toggle-second-add=" ">
                  <div class="container d-flex">
                    <button class="header-modal__back-btn" id="menu-btn-catalog" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      доп меню
                    </button>
                  </div>
                </div>
                <div class="container-xl header-catalog-menu-container">
                  <div class="header-catalog-menu-holder">
                    <!--                                <div class="toggle toggle_reverse d-lg-flex">-->
                    <!--                                    <label for="catalog-checkbox"></label>-->
                    <!--                                    <input type="checkbox" name="name-234" id="catalog-checkbox">-->
                    <!--                                    <label class="toggle_label" for="catalog-checkbox">По сфере деятельности</label>-->
                    <!--                                </div>-->
                    <ul class="header-catalog-menu active" id="mobile-catalog" data-toggle-first=" "></ul>
                    <ul class="header-catalog-menu" id="mobile-catalog" data-toggle-second=" "></ul>
                    <a class="header-catalog-menu__view-all" href="/catalog/">
                      data-href="Здесь ссылка на страницу каталог продукции"&gt;Посмотреть все</a>
                  </div>
                  <div class="header-catalog-menu__wrapper-fast-order">
                    <!--                                <span class="header-catalog-menu__fast-order" data-call-modal="order-click"-->
                    <!--                                      style="background-image: url(images/fast-order.webp);">-->
                    <!--                                <div class="header-catalog-menu__fast-order-top-text">Нет времени смотреть каталог?-->
                    <!--                                </div>-->
                    <!--                                <div class="header-catalog-menu__fast-order-title-text">Оформите быстрый заказ!</div>-->
                    <!--                                <div class="header-catalog-menu__fast-order-description-text">Займет всего 2 минуты,-->
                    <!--                                    после чего мы вышлем подготовленный список товаров с ценами-->
                    <!--                                </div>-->
                    </span></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Каталог-->
        <div class="modal header-modal header-catalog-modal" id="modal-company-catalog">
          <div class="modal__overlay">
            <div class="modal__content">
              <div class="header-catalog-modal__inner">
                <div class="header-modal__back">
                  <div class="container">
                    <button class="header-modal__back-btn" id="menu-btn-catalog" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      о компании
                    </button>
                  </div>
                </div>
                <div class="container-xl header-catalog-menu-container">
                  <ul class="header-catalog-menu active">
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/dealership/">
                        Дилерство
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/charity/">
                        Благотворительность
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/blog/">
                        Статьи
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/news/">
                        Новости
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/cases/">
                        Наши проекты
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/thanks/">
                        Благодарности
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>

                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/employee/">
                        Наши сотрудники
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>

                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="modal header-modal header-catalog-modal" id="modal-buyers-catalog">
          <div class="modal__overlay">
            <div class="modal__content">
              <div class="header-catalog-modal__inner">
                <div class="header-modal__back">
                  <div class="container">
                    <button class="header-modal__back-btn" id="menu-btn-catalog" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      покупателям
                    </button>
                  </div>
                </div>
                <div class="container-xl header-catalog-menu-container">
                  <ul class="header-catalog-menu active">
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/delivery/">
                        Доставка
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/payment/">
                        Оплата
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/refund/">
                        Возврат
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/stamps/">
                        Марочник
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                    <li class="header-catalog-menu__item">
                      <a class="header-catalog-menu__item-link mobile-category" href="/gosts/">
                        ГОСТы
                        <svg class="icon icon_arrow-right-min">
                          <use xlink:href="images/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>

  </div>

</template>

<style scoped>

</style>

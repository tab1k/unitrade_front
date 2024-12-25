<script setup>

</script>

<template>
  <div>
    <header class="header">
      <div class="header__inner">

        <First_Header />
        <Second_Header />

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
        <!-- Выбор города-->
        <div class="modal header-modal choice-city" id="modal-choice-city">
          <div class="modal__dialog">
            <div class="modal__content">
              <div class="header-modal__back">
                <div class="container">
                  <button class="header-modal__back-btn" type="button" data-modal-hide="#modal-choice-city">
                    <svg class="icon icon_prev">
                      <use xlink:href="images/sprite.svg#prev"></use>
                    </svg>
                    Астана
                  </button>
                </div>
              </div>
              <div class="choice-city__container container-lg">
                <button class="modal__close header-modal-close" data-modal-hide="#modal-choice-city">
                  <svg class="icon icon_close">
                    <use xlink:href="images/sprite.svg#close"></use>
                  </svg>
                </button>

                <div class="choice-city__city-list-container container">
                  <!--noindex-->
                  <div class="choice-city__city-list choice-city__section row">

                    <a class="choice-city__link" rel="nofollow" href="https://aktau.isteels.kz/">Актау</a>

                    <a class="choice-city__link" rel="nofollow" href="https://aktobe.isteels.kz/">Актобе</a>

                    <a class="choice-city__link" rel="nofollow" href="https://almaty.isteels.kz/">Алматы</a>

                    <a class="choice-city__link" rel="nofollow" href="https://isteels.kz/">Астана</a>

                    <a class="choice-city__link" rel="nofollow" href="https://atyrau.isteels.kz/">Атырау</a>

                    <a class="choice-city__link" rel="nofollow" href="https://zhezkazgan.isteels.kz/">Жезказган</a>

                    <a class="choice-city__link" rel="nofollow" href="https://karaganda.isteels.kz/">Караганда</a>

                    <a class="choice-city__link" rel="nofollow" href="https://kokshetau.isteels.kz/">Кокшетау</a>

                    <a class="choice-city__link" rel="nofollow"
                       href="https://kostanay.isteels.kz/">Костанай</a>

                    <a class="choice-city__link" rel="nofollow" href="https://kyzylorda.isteels.kz/">Кызылорда</a>

                    <a class="choice-city__link" rel="nofollow"
                       href="https://pavlodar.isteels.kz/">Павлодар</a>

                    <a class="choice-city__link" rel="nofollow" href="https://petropavlovsk.isteels.kz/">Петропавловск</a>

                    <a class="choice-city__link" rel="nofollow" href="https://semej.isteels.kz/">Семей</a>

                    <a class="choice-city__link" rel="nofollow" href="https://taldykorgan.isteels.kz/">Талдыкорган</a>

                    <a class="choice-city__link" rel="nofollow" href="https://taraz.isteels.kz/">Тараз</a>

                    <a class="choice-city__link" rel="nofollow" href="https://turkestan.isteels.kz/">Туркестан</a>

                    <a class="choice-city__link" rel="nofollow"
                       href="https://uralsk.isteels.kz/">Уральск</a>

                    <a class="choice-city__link" rel="nofollow" href="https://ust-kamenogorsk.isteels.kz/">Усть-Каменогорск</a>

                    <a class="choice-city__link" rel="nofollow"
                       href="https://shymkent.isteels.kz/">Шымкент</a>

                  </div>
                  <!--/noindex-->
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Обратный звонок-->
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
                    <ul class="search-modal__search-result search-modal__search-result_popular search__result search__result_popular">
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
                    <ul class="search-modal__search-result search-modal__search-result_product search__result search__result_product">
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
        <div class="modal header-modal header-catalog-modal" id="modal-header-catalog" style="margin-top: 29px;">
          <div class="modal__overlay">
            <div class="modal__content">
              <div class="header-catalog-modal__inner" data-toggle-to=" ">
                <div class="header-modal__back active" data-toggle-first-add=" ">
                  <div class="container d-flex">
                    <button class="header-modal__back-btn" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      каталог
                    </button>
                  </div>
                </div>
                <div class="header-modal__back" data-toggle-second-add=" ">
                  <div class="container d-flex">
                    <button class="header-modal__back-btn" type="button"
                            data-modal-toggle="#modal-mobile-menu">
                      <svg class="icon icon_prev">
                        <use xlink:href="images/sprite.svg#prev"></use>
                      </svg>
                      доп меню
                    </button>
                  </div>
                </div>
                <div class="container-xl header-catalog-menu-container">
                  <div class="header-catalog-menu-holder" style="max-width: 324px;">
                    <div class="toggle toggle_reverse d-lg-flex" style="padding-left: 40px;">
                      <label for="catalog-checkbox"></label>
                      <input type="checkbox" name="name-234" id="catalog-checkbox">
                      <label class="toggle_label" for="catalog-checkbox">По сфере деятельности</label>
                    </div>
                    <ul class="header-catalog-menu mobile-catalog active" data-toggle-first=" "><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1604">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/chernyj-metalloprokat/" data-id-category="1604">
                        Черный металлопрокат
                        <svg class="icon icon_arrow-right-min" data-id-category="1604">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="264" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubnyj-prokat/" data-id-category="264">
                            Трубный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="264">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1279" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-stali/" data-id-category="1279">
                                Стальной трубный прокат
                                <svg class="icon icon_arrow-right-min" data-id-category="1279">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1324" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-truby/" data-id-category="1324">
                                    Труба круглая стальная
                                    <svg class="icon icon_arrow-right-min" data-id-category="1324">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1496" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrosvarnye-stalnye-truby/" data-id-category="1496">Электросварные стальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1634" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/besshovnye-stalnye-truby/" data-id-category="1634">Бесшовные стальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1848" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tonkostennye-stalnye-truby/" data-id-category="1848">Тонкостенные стальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1762" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tolstostennye-stalnye-truby/" data-id-category="1762">Толстостенные стальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="2145" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-bolshogo-diametra/" data-id-category="2145">Трубы большого диаметра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="2031" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/celnotyanutye-stalnye-truby/" data-id-category="2031">Цельнотянутые трубы</a>
                                    </li></ul>
                                    <a href="/catalog/stalnye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1682" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-profilnye-truby/" data-id-category="1682">
                                    Профильные стальные трубы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1682">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1685" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-arochnye-truby/" data-id-category="1685">Арочные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1746" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kaplevidnye-truby/" data-id-category="1746">Каплевидные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1386" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kvadratnye-truby/" data-id-category="1386">Квадратные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1520" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-ovalnye-truby/" data-id-category="1520">Овальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1613" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-ploskoovalnye-truby/" data-id-category="1613">Плоскоовальные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1403" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-pryamougolnye-truby/" data-id-category="1403">Прямоугольные трубы</a>
                                    </li></ul>
                                    <a href="/catalog/stalnye-profilnye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/truby-iz-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1353" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-truby/" data-id-category="1353">Чугунные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1563" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-vgp/" data-id-category="1563">ВГП трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1340" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/obsadnye-truby/" data-id-category="1340">Обсадные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="549" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kotelnye-truby/" data-id-category="549">Котельные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1448" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-bu/" data-id-category="1448">Трубы Б/У</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2125" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kapillyarnye-trubki/" data-id-category="2125">Капиллярные трубки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="570" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-nkt/" data-id-category="570">НКТ трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1456" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/burilnye-truby/" data-id-category="1456">Бурильные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1532" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-v-izolyacii/" data-id-category="1532">Изолированные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1909" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/futerovannye-truby/" data-id-category="1909">Футерованные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1556" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magistralnye-truby/" data-id-category="1556">Магистральные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1308" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/orebrennye-truby/" data-id-category="1308">Оребренные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1711" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolonkovye-truby/" data-id-category="1711">Колонковые трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1378" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazliftnye-truby/" data-id-category="1378">Газлифтные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2048" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plakirovannye-truby/" data-id-category="2048">Плакированные трубы</a>
                            </li></ul>
                            <a href="/catalog/trubnyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2126" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ploskiy-stalnoy-prokat/" data-id-category="2126">
                            Плоский прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2126">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1477" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy/" data-id-category="1477">
                                Листы
                                <svg class="icon icon_arrow-right-min" data-id-category="1477">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1095" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prosechno-vytyazhnye-listy/" data-id-category="1095">Просечно-вытяжные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1099" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perforirovannye-listy/" data-id-category="1099">Перфорированные металлические листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1060" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronelisty/" data-id-category="1060">Бронелисты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1049" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zhestyanye-listy/" data-id-category="1049">
                                    Жестяные листы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1049">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="715" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovaya-zhest/" data-id-category="715">Листовая жесть</a>
                                    </li></ul>
                                    <a href="/catalog/zhestyanye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="828" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-listy/" data-id-category="828">
                                    Стальной листовой прокат
                                    <svg class="icon icon_arrow-right-min" data-id-category="828">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="144" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-riflenye-listy/" data-id-category="144">Стальные рифленые листы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="786" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-perforirovannye-listy/" data-id-category="786">Стальные перфорированные листы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="959" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/goryachekatanye-listy/" data-id-category="959">Горячекатаные листы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="433" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-stali/" data-id-category="433">Листы из стали</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="977" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-s-zadannymi-svojstvami-uprugosti/" data-id-category="977">Листы с заданными свойствами упругости</a>
                                    </li></ul>
                                    <a href="/catalog/stalnye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="228" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-listy/" data-id-category="228">Судовые листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="501" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-listy/" data-id-category="501">Низколегированные листы</a>
                                </li></ul>
                                <a href="/catalog/listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1705" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polosy/" data-id-category="1705">
                                Полосы
                                <svg class="icon icon_arrow-right-min" data-id-category="1705">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="597" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-polosy/" data-id-category="597">Стальные полосы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="791" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kovanye-polosy/" data-id-category="791">Кованые полосы</a>
                                </li></ul>
                                <a href="/catalog/polosy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1600" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty/" data-id-category="1600">
                                Ленты
                                <svg class="icon icon_arrow-right-min" data-id-category="1600">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="242" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-lenty/" data-id-category="242">Стальные ленты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2203" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnaya-upakovochnaya-lenta/" data-id-category="2203">Упаковочные стальные ленты</a>
                                </li></ul>
                                <a href="/catalog/lenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1832" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plity/" data-id-category="1832">
                                Плиты
                                <svg class="icon icon_arrow-right-min" data-id-category="1832">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="967" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-plity/" data-id-category="967">Стальные плиты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="963" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/legirovannye-plity/" data-id-category="963">Легированные плиты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="957" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nelegirovannye-plity/" data-id-category="957">Нелегированные плиты</a>
                                </li></ul>
                                <a href="/catalog/plity/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="3" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shiny/" data-id-category="3">Шины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2079" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rulony/" data-id-category="2079">
                                Рулоны
                                <svg class="icon icon_arrow-right-min" data-id-category="2079">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="525" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-rulony/" data-id-category="525">Стальные рулоны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="721" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rulonnaya-zhest/" data-id-category="721">Рулонная жесть</a>
                                </li></ul>
                                <a href="/catalog/rulony/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/ploskiy-stalnoy-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1741" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnyj-prokat/" data-id-category="1741">
                            Фасонный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1741">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="183" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvutavry/" data-id-category="183">
                                Двутавры
                                <svg class="icon icon_arrow-right-min" data-id-category="183">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="188" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-dvutavry/" data-id-category="188">Стальные двутавры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="208" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shirokopolochnye-dvutavry/" data-id-category="208">Широкополочные двутавры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="199" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolonnye-dvutavry/" data-id-category="199">Колонные двутавры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="194" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/normalnye-dvutavry/" data-id-category="194">Нормальные двутавры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="539" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-dvutavry/" data-id-category="539">Низколегированные двутавры</a>
                                </li></ul>
                                <a href="/catalog/dvutavry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="77" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ugolki/" data-id-category="77">
                                Уголки
                                <svg class="icon icon_arrow-right-min" data-id-category="77">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="148" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-ravnopolochnye-ugolki/" data-id-category="148">Равнополочные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="155" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-neravnopolochnye-ugolki/" data-id-category="155">Неравнополочные уголки</a>
                                </li></ul>
                                <a href="/catalog/ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="564" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shvellery/" data-id-category="564">
                                Швеллеры
                                <svg class="icon icon_arrow-right-min" data-id-category="564">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="569" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shvellery-goryachekatanye/" data-id-category="569">Горячекатаные швеллеры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="576" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shvellery-gnutye/" data-id-category="576">Гнутые швеллеры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="508" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-shvellery/" data-id-category="508">Низколегированные швеллеры</a>
                                </li></ul>
                                <a href="/catalog/stalnye-shvellery/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="214" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tavry/" data-id-category="214">
                                Тавры
                                <svg class="icon icon_arrow-right-min" data-id-category="214">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="990" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-tavry/" data-id-category="990">Стальные тавры</a>
                                </li></ul>
                                <a href="/catalog/tavry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="566" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-relsy/" data-id-category="566">
                                Рельсы
                                <svg class="icon icon_arrow-right-min" data-id-category="566">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1342" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kranovye-relsy/" data-id-category="1342">Крановые рельсы</a>
                                </li></ul>
                                <a href="/catalog/stalnye-relsy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/fasonnyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1678" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sortovoj-prokat/" data-id-category="1678">
                            Сортовой прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1678">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1993" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/armatura/" data-id-category="1993">
                                Арматура
                                <svg class="icon icon_arrow-right-min" data-id-category="1993">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1037" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnaya-armatura/" data-id-category="1037">Сварная арматура</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="640" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/armatura-goryachekatanaya/" data-id-category="640">Горячекатаная арматура</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="646" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/armatura-holodnokatanaya/" data-id-category="646">Холоднокатаная арматура</a>
                                </li></ul>
                                <a href="/catalog/armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2023" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kvadraty/" data-id-category="2023">
                                Квадраты
                                <svg class="icon icon_arrow-right-min" data-id-category="2023">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="562" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kvadraty/" data-id-category="562">Стальные квадраты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1223" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kalibrovannye-kvadraty/" data-id-category="1223">Калиброванные квадраты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1229" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kovanye-kvadraty/" data-id-category="1229">Кованые квадраты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="487" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokolegirovannye-kvadraty/" data-id-category="487">Высоколегированные квадраты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="522" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-kvadraty/" data-id-category="522">Низколегированные квадраты</a>
                                </li></ul>
                                <a href="/catalog/kvadraty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1925" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krugi/" data-id-category="1925">
                                Круги
                                <svg class="icon icon_arrow-right-min" data-id-category="1925">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="961" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-krugi/" data-id-category="961">Стальные круги</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="528" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-krugi/" data-id-category="528">Низколегированные круги</a>
                                </li></ul>
                                <a href="/catalog/krugi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1894" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prutki/" data-id-category="1894">
                                Прутки
                                <svg class="icon icon_arrow-right-min" data-id-category="1894">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="533" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-prutki/" data-id-category="533">Низколегированные прутки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1127" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-prutki/" data-id-category="1127">Стальные прутки</a>
                                </li></ul>
                                <a href="/catalog/prutki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="556" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-pokovki/" data-id-category="556">Поковки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1018" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shestigranniki/" data-id-category="1018">
                                Шестигранники
                                <svg class="icon icon_arrow-right-min" data-id-category="1018">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="403" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-goryachekatanye-shestigranniki/" data-id-category="403">Горячекатаные шестигранники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="494" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkolegirovannye-shestigranniki/" data-id-category="494">Низколегированные шестигранники</a>
                                </li></ul>
                                <a href="/catalog/stalnye-shestigranniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/sortovoj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="254" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnyj-prokat/" data-id-category="254">
                            Чугунный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="254">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2460" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-krany/" data-id-category="2460">Чугунные краны</a>
                            </li></ul>
                            <a href="/catalog/chugunnyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/chernyj-metalloprokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="260">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/specialnye-stali/" data-id-category="260">
                        Специальные стали
                        <svg class="icon icon_arrow-right-min" data-id-category="260">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2116" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-stali/" data-id-category="2116">
                            Прецизионные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="2116">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1872" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-truby/" data-id-category="1872">Трубы прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="865" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-lenty/" data-id-category="865">Ленты прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="880" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-provoloki/" data-id-category="880">Проволоки прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="870" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-listy/" data-id-category="870">Листы прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="887" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-prutki/" data-id-category="887">Прутки прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="891" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-krugi/" data-id-category="891">Круги прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="120" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnaya-folga/" data-id-category="120">Фольга прецизионная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="10" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-shiny/" data-id-category="10">Шины прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="874" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/precizionnye-polosy/" data-id-category="874">Полосы прецизионные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="972" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-tklr/" data-id-category="972">Проволоки ТКЛР</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="979" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-s-zadannymi-svojstvami-uprugosti/" data-id-category="979">Проволоки с заданными свойствами упругости</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="998" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prutki-s-zadannymi-svojstvami-uprugosti/" data-id-category="998">Прутки с заданными свойствами упругости</a>
                            </li></ul>
                            <a href="/catalog/precizionnye-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="379" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnaya-stal/" data-id-category="379">
                            Инструментальные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="379">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="559" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-polosy/" data-id-category="559">
                                Полосы инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="559">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="711" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-polosy/" data-id-category="711">Инструментальные легированные полосы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="717" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-polosy/" data-id-category="717">Инструментальные углеродистые полосы</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-polosy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="778" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-listy/" data-id-category="778">Листы инструментальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1989" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-truby/" data-id-category="1989">Трубы инструментальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="771" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-krugi/" data-id-category="771">
                                Круги инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="771">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="734" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-krugi/" data-id-category="734">Инструментальные легированные круги</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="758" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-krugi/" data-id-category="758">Инструментальные углеродистые круги</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-krugi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="470" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-lenty/" data-id-category="470">Ленты инструментальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="785" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-prutki/" data-id-category="785">
                                Прутки инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="785">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="740" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-prutki/" data-id-category="740">Инструментальные легированные прутки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="764" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-prutki/" data-id-category="764">Инструментальные углеродистые прутки</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-prutki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="766" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-kvadraty/" data-id-category="766">
                                Квадраты инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="766">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="728" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-kvadraty/" data-id-category="728">Инструментальные легированные квадраты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="752" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-kvadraty/" data-id-category="752">Инструментальные углеродистые квадраты</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-kvadraty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="449" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-plity/" data-id-category="449">
                                Плиты инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="449">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="481" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-provoloki/" data-id-category="481">
                                    Инструментальные проволоки
                                    <svg class="icon icon_arrow-right-min" data-id-category="481">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="723" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-provoloki/" data-id-category="723">Инструментальные углеродистые проволоки</a>
                                    </li></ul>
                                    <a href="/catalog/instrumentalnye-provoloki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-plity/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="677" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-pokovki/" data-id-category="677">
                                Поковки инструментальные
                                <svg class="icon icon_arrow-right-min" data-id-category="677">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="700" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-pokovki/" data-id-category="700">Инструментальные легированные поковки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="694" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-pokovki/" data-id-category="694">Инструментальные углеродистые поковки</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-pokovki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1242" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-shiny/" data-id-category="1242">Шины инструментальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2114" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-shestigranniki/" data-id-category="2114">
                                Инструментальные шестигранники
                                <svg class="icon icon_arrow-right-min" data-id-category="2114">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="745" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-legirovannye-shestigranniki/" data-id-category="745">Инструментальные легированные шестигранники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="769" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/instrumentalnye-uglerodistye-shestigranniki/" data-id-category="769">Инструментальные углеродистые шестигранники</a>
                                </li></ul>
                                <a href="/catalog/instrumentalnye-shestigranniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/instrumentalnaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="354" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnaya-stal/" data-id-category="354">
                            Конструкционные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="354">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="707" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-pokovki/" data-id-category="707">Поковки конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2008" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-truby/" data-id-category="2008">Трубы конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="837" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-listy/" data-id-category="837">Листы конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="813" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-krugi/" data-id-category="813">Круги конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="795" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-provoloki/" data-id-category="795">Проволоки конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="454" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-lenty/" data-id-category="454">Ленты конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="952" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-plity/" data-id-category="952">Плиты конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2115" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-ugolki/" data-id-category="2115">
                                Уголки конструкционные
                                <svg class="icon icon_arrow-right-min" data-id-category="2115">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1142" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-ugolki-neravnopolochnye-legirovannye/" data-id-category="1142">Легированные неравнополочные конструкционные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1151" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-ugolki-neravnopolochnye-uglerodistye/" data-id-category="1151">Углеродистые неравнополочные конструкционные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1146" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-ugolki-neravnopolochnye-nizkolegirovannye/" data-id-category="1146">Низколегированные неравнополочные конструкционные уголки</a>
                                </li></ul>
                                <a href="/catalog/konstrukcionnye-ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="847" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-shestigranniki/" data-id-category="847">
                                Шестигранники конструкционные
                                <svg class="icon icon_arrow-right-min" data-id-category="847">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="801" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-legirovannye-shestigranniki/" data-id-category="801">Конструкционные легированные шестигранники</a>
                                </li></ul>
                                <a href="/catalog/konstrukcionnye-shestigranniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="563" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-polosy/" data-id-category="563">Полосы конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="804" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-kvadraty/" data-id-category="804">Квадраты конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="638" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-vtulki/" data-id-category="638">Втулки конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="714" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-legirovannye-pokovki/" data-id-category="714">Поковки легированные конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="821" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-prutki/" data-id-category="821">Прутки конструкционные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1248" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-shiny/" data-id-category="1248">Шины конструкционные</a>
                            </li></ul>
                            <a href="/catalog/konstrukcionnaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="344" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bystrorezhushaya-stal/" data-id-category="344">
                            Быстрорежущие стали
                            <svg class="icon icon_arrow-right-min" data-id-category="344">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="683" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bystrorezhushie-pokovki/" data-id-category="683">Поковки быстрорежущие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="931" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kvadraty-stalnye-bystrorezhushie/" data-id-category="931">Квадраты стальные быстрорежущие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="925" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krugi-stalnye-bystrorezhushie/" data-id-category="925">Круги стальные быстрорежущие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="936" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-stalnye-bystrorezhushie/" data-id-category="936">Листы стальные быстрорежущие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="917" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polosy-stalnye-bystrorezhushie/" data-id-category="917">Полосы стальные быстрорежущие</a>
                            </li></ul>
                            <a href="/catalog/bystrorezhushaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="366" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevaya-stal/" data-id-category="366">
                            Пищевые стали
                            <svg class="icon icon_arrow-right-min" data-id-category="366">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1505" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-truby/" data-id-category="1505">Пищевые трубы</a>
                            </li></ul>
                            <a href="/catalog/pishevaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="375" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskaya-stal/" data-id-category="375">
                            Электротехнические стали
                            <svg class="icon icon_arrow-right-min" data-id-category="375">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="426" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-listy/" data-id-category="426">Листы электротехнические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1231" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-shiny/" data-id-category="1231">Шины электротехнические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="548" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-polosy/" data-id-category="548">Полосы электротехнические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="900" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-krugi/" data-id-category="900">Круги электротехнические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="895" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-kvadraty/" data-id-category="895">Квадраты электротехнические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="518" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrotehnicheskie-rulony/" data-id-category="518">Рулоны электротехнические</a>
                            </li></ul>
                            <a href="/catalog/elektrotehnicheskaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="350" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-stali/" data-id-category="350">
                            Жаропрочные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="350">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="947" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-plity/" data-id-category="947">Плиты жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1691" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-truby/" data-id-category="1691">Трубы жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="754" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-listy/" data-id-category="754">Листы жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="726" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-krugi/" data-id-category="726">Круги жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="571" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-lenty/" data-id-category="571">Ленты жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="665" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-provoloki/" data-id-category="665">Проволоки жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="760" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-prutki/" data-id-category="760">Прутки жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="172" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-pokovki/" data-id-category="172">Поковки жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="555" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-polosy/" data-id-category="555">Полосы жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="565" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-kvadraty/" data-id-category="565">Квадраты жаропрочные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1237" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zharoprochnye-shiny/" data-id-category="1237">Шины жаропрочные</a>
                            </li></ul>
                            <a href="/catalog/zharoprochnye-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="370" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-stali/" data-id-category="370">
                            Рессорно-пружинные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="370">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="849" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-polosy/" data-id-category="849">Полосы рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="859" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-krugi/" data-id-category="859">Круги рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="720" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-pokovki/" data-id-category="720">Поковки рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="854" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-kvadraty/" data-id-category="854">Квадраты рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="863" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-prutki/" data-id-category="863">Прутки рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="868" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-shestigranniki/" data-id-category="868">Шестигранники рессорно-пружинные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="937" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ressorno-pruzhinnye-plity/" data-id-category="937">Плиты рессорно-пружинные</a>
                            </li></ul>
                            <a href="/catalog/ressorno-pruzhinnye-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="359" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kriogennyj-prokat/" data-id-category="359">
                            Криогенный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="359">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="544" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kriogennye-truby/" data-id-category="544">Криогенные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1136" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-ugolki-neravnopolochnye-kriogennye/" data-id-category="1136">Криогенные неравнополочные конструкционные уголки</a>
                            </li></ul>
                            <a href="/catalog/kriogennyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="346" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-stali/" data-id-category="346">
                            Автоматные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="346">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="642" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-krugi/" data-id-category="642">Круги автоматные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="656" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-prutki/" data-id-category="656">Прутки автоматные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="661" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-shestigranniki/" data-id-category="661">Шестигранники автоматные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="635" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-kvadraty/" data-id-category="635">Квадраты автоматные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="648" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-listy/" data-id-category="648">Листы автоматные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="942" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/avtomatnye-plity/" data-id-category="942">Плиты автоматные</a>
                            </li></ul>
                            <a href="/catalog/avtomatnye-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1509" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskij-prokat/" data-id-category="1509">
                            Биметаллический прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1509">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1808" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskie-truby/" data-id-category="1808">
                                Биметаллические трубы
                                <svg class="icon icon_arrow-right-min" data-id-category="1808">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1433" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-bimetallicheskie-truby/" data-id-category="1433">Круглые биметаллические трубы</a>
                                </li></ul>
                                <a href="/catalog/bimetallicheskie-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="926" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskie-provoloki/" data-id-category="926">Проволоки биметаллические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="918" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskie-listy/" data-id-category="918">Листы биметаллические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="573" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskie-lenty/" data-id-category="573">Ленты биметаллические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="903" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bimetallicheskie-plity/" data-id-category="903">Плиты биметаллические</a>
                            </li></ul>
                            <a href="/catalog/bimetallicheskij-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1332" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislotostojkie-stali/" data-id-category="1332">
                            Кислотостойкие стали
                            <svg class="icon icon_arrow-right-min" data-id-category="1332">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="551" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislotostojkie-truby/" data-id-category="551">Трубы кислотостойкие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="775" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislotostojkie-listy/" data-id-category="775">Листы кислотостойкие</a>
                            </li></ul>
                            <a href="/catalog/kislotostojkie-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2113" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovaya-stal/" data-id-category="2113">
                            Штамповые стали
                            <svg class="icon icon_arrow-right-min" data-id-category="2113">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="687" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovye-pokovki/" data-id-category="687">Поковки штампованные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="884" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovye-krugi/" data-id-category="884">Круги штамповые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="872" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovye-polosy/" data-id-category="872">Полосы штамповые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1269" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovye-prutki/" data-id-category="1269">Прутки штамповые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="878" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtampovye-kvadraty/" data-id-category="878">Квадраты штамповые</a>
                            </li></ul>
                            <a href="/catalog/shtampovaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="341" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudostroitelnaya-stal/" data-id-category="341">
                            Судостроительные стали
                            <svg class="icon icon_arrow-right-min" data-id-category="341">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1595" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudostroitelnye-truby/" data-id-category="1595">Судостроительные трубы</a>
                            </li></ul>
                            <a href="/catalog/sudostroitelnaya-stal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2073" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nihromovyj-prokat/" data-id-category="2073">
                            Нихром
                            <svg class="icon icon_arrow-right-min" data-id-category="2073">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="761" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nihromovye-provoloki/" data-id-category="761">Проволоки нихромовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="506" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nihromovye-lenty/" data-id-category="506">Ленты нихромовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="127" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-krugi/" data-id-category="127">Круги хромоникелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="133" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-listy/" data-id-category="133">Листы хромоникелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2064" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-truby/" data-id-category="2064">Трубы хромоникелевые</a>
                            </li></ul>
                            <a href="/catalog/nihromovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2112" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fehral/" data-id-category="2112">
                            Фехраль
                            <svg class="icon icon_arrow-right-min" data-id-category="2112">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="514" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fehralevye-lenty/" data-id-category="514">Ленты фехралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="372" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fehralevye-prutki/" data-id-category="372">Прутки фехралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="125" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fehralevye-krugi/" data-id-category="125">Круги фехралевые</a>
                            </li></ul>
                            <a href="/catalog/fehral/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2276" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/list-hardox/" data-id-category="2276">Листы Hardox</a>
                        </li></ul>
                        <a href="/catalog/specialnye-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="176">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/nerzhaveyushij-prokat/" data-id-category="176">
                        Нержавеющий прокат
                        <svg class="icon icon_arrow-right-min" data-id-category="176">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1526" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-nerzhaveyushej-stali/" data-id-category="1526">
                            Нержавеющий трубопрокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1526">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1291" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby/" data-id-category="1291">
                                Трубы нержавеющие
                                <svg class="icon icon_arrow-right-min" data-id-category="1291">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2148" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-besshovnye/" data-id-category="2148">Нержавеющие трубы бесшовные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1766" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrosvarnye-nerzhaveyushie-truby/" data-id-category="1766">Электросварные нержавеющие трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2150" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-polirovannye/" data-id-category="2150">Нержавеющие трубы полированные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2149" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-zerkalnye/" data-id-category="2149">Нержавеющие трубы зеркальные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2151" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-shlifovannye/" data-id-category="2151">Нержавеющие трубы шлифованные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2152" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-holodnodeformirovannye/" data-id-category="2152">Нержавеющие трубы холоднодеформированные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2154" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-nerzhaveyushie-matovye/" data-id-category="2154">Трубы нержавеющие матовые</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1417" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-gofrirovannye-truby/" data-id-category="1417">Гофрированные нержавеющие трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1593" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-profilnye-truby/" data-id-category="1593">Профильные нержавеющие трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1607" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/korrozionnostojkie-truby/" data-id-category="1607">Коррозионностойкие трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2551" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kotelnaya-nerzhaveyushaya-truba/" data-id-category="2551">Котельные нержавеющие трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1296" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kapillyarnye-trubki/" data-id-category="1296">Капиллярные трубки нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1802" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-s-rezboj/" data-id-category="1802">Трубы с резьбой нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1851" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-truby-bolshogo-diametra/" data-id-category="1851">Трубы большого диаметра нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1896" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-dupleksnoj-stali/" data-id-category="1896">Трубы из дуплексной стали</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1932" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-superdupleksnoj-stali/" data-id-category="1932">Трубы из супердуплексной стали</a>
                            </li></ul>
                            <a href="/catalog/truby-iz-nerzhaveyushej-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2121" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ploskiy-nerzhaveyushij-prokat/" data-id-category="2121">
                            Плоский нержавеющий прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2121">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="239" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-listy/" data-id-category="239">
                                Листы нержавеющие
                                <svg class="icon icon_arrow-right-min" data-id-category="239">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1102" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-perforirovannye-listy/" data-id-category="1102">Нержавеющие перфорированные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="845" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-riflenye-listy/" data-id-category="845">Нержавеющие рифленые листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="924" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-dekorativnye-listy/" data-id-category="924">Нержавеющие декоративные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="235" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-listy-hk-ns/" data-id-category="235">Листы нержавеющие никельсодержащие</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="246" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-plity/" data-id-category="246">Плиты нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="26" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-lenty/" data-id-category="26">
                                Нержавеющие ленты
                                <svg class="icon icon_arrow-right-min" data-id-category="26">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="232" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-lenty-shtrips/" data-id-category="232">Штрипс нержавеющий</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-lenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="542" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-polosy/" data-id-category="542">Полосы нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="49" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-rulony/" data-id-category="49">Рулоны нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="609" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-shiny/" data-id-category="609">Шины нержавеющие</a>
                            </li></ul>
                            <a href="/catalog/ploskiy-nerzhaveyushij-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2123" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnyi-nerzhaveyushij-prokat/" data-id-category="2123">
                            Фасонный нержавеющий прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2123">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="122" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-ugolki/" data-id-category="122">
                                Уголки нержавеющие
                                <svg class="icon icon_arrow-right-min" data-id-category="122">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="128" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-ravnopolochnye-ugolki/" data-id-category="128">Нержавеющие равнополочные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="135" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-neravnopolochnye-ugolki/" data-id-category="135">Нержавеющие неравнополочные уголки</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="170" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-shvellery/" data-id-category="170">Швеллеры нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="203" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-dvutavry/" data-id-category="203">Двутавры нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="224" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-tavry/" data-id-category="224">Тавры нержавеющие</a>
                            </li></ul>
                            <a href="/catalog/fasonnyi-nerzhaveyushij-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2124" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sortovoj-nerzhaveyushij-prokat/" data-id-category="2124">
                            Сортовой нержавеющий прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2124">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="973" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-krugi/" data-id-category="973">
                                Круги нержавеющие
                                <svg class="icon icon_arrow-right-min" data-id-category="973">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="833" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kalibrovannye-krugi/" data-id-category="833">Круги нержавеющие калиброванные</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-krugi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1154" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-prutki/" data-id-category="1154">Прутки нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1246" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-shestigranniki/" data-id-category="1246">Шестигранники нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1197" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kvadraty/" data-id-category="1197">Квадраты нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1178" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pokovki/" data-id-category="1178">Поковки нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="732" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-polukrugi/" data-id-category="732">Полукруги нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="738" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-poluovaly/" data-id-category="738">Полуовалы нержавеющие</a>
                            </li></ul>
                            <a href="/catalog/sortovoj-nerzhaveyushij-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2709" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushij-krepezh/" data-id-category="2709">Нержавеющий крепеж</a>
                        </li></ul>
                        <a href="/catalog/nerzhaveyushij-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1507">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/cvetnoj-metalloprokat/" data-id-category="1507">
                        Цветной металлопрокат
                        <svg class="icon icon_arrow-right-min" data-id-category="1507">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1275" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievyj-prokat/" data-id-category="1275">
                            Алюминиевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1275">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="319" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievyj-profil/" data-id-category="319">Профиль алюминиевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="102" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-ugolki/" data-id-category="102">
                                Уголки алюминиевые
                                <svg class="icon icon_arrow-right-min" data-id-category="102">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="116" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-neravnopolochnye-ugolki/" data-id-category="116">Алюминиевые неравнополочные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="108" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-ravnopolochnye-ugolki/" data-id-category="108">Алюминиевые равнополочные уголки</a>
                                </li></ul>
                                <a href="/catalog/alyuminievye-ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1440" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-truby/" data-id-category="1440">
                                Трубы алюминиевые
                                <svg class="icon icon_arrow-right-min" data-id-category="1440">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1323" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-profilnye-truby/" data-id-category="1323">Алюминиевые профильные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1441" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-alyuminievye-truby/" data-id-category="1441">Алюминиевые круглые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1701" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-gofrirovannye-truby/" data-id-category="1701">Алюминиевые гофрированные трубы</a>
                                </li></ul>
                                <a href="/catalog/alyuminievye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="980" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-listy/" data-id-category="980">
                                Листы алюминиевые
                                <svg class="icon icon_arrow-right-min" data-id-category="980">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="796" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-perforirovannye-listy/" data-id-category="796">Алюминиевые перфорированные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1093" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-anodirovannye-listy/" data-id-category="1093">Алюминиевые анодированные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="985" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-gladkie-listy/" data-id-category="985">Алюминиевые гладкие листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="992" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-riflenye-listy/" data-id-category="992">Алюминиевые рифленые листы</a>
                                </li></ul>
                                <a href="/catalog/alyuminievye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="310" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievaya-folga/" data-id-category="310">Фольга алюминиевая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="20" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-lenty/" data-id-category="20">Ленты алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="262" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-provoloki/" data-id-category="262">Проволоки алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1265" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-shiny/" data-id-category="1265">Шины алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="244" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-plity/" data-id-category="244">
                                Плиты алюминиевые
                                <svg class="icon icon_arrow-right-min" data-id-category="244">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="782" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kovanye-alyuminievye-plity/" data-id-category="782">Кованые алюминиевые плиты</a>
                                </li></ul>
                                <a href="/catalog/alyuminievye-plity/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="580" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-polosy/" data-id-category="580">Полосы алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1193" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-kvadraty/" data-id-category="1193">Квадраты алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1123" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-prutki/" data-id-category="1123">Прутки алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="178" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-shvellery/" data-id-category="178">Швеллеры алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1467" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-chushki/" data-id-category="1467">Чушки алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="910" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-krugi/" data-id-category="910">Круги алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="512" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-rulony/" data-id-category="512">Рулоны алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="237" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-boksy/" data-id-category="237">Боксы алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="747" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-pokovki/" data-id-category="747">Поковки алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1240" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-shestigranniki/" data-id-category="1240">Шестигранники алюминиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="219" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-tavry/" data-id-category="219">Тавры алюминиевые</a>
                            </li></ul>
                            <a href="/catalog/alyuminievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2122" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/berillij/" data-id-category="2122">
                            Бериллиевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2122">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="185" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/berillievye-polosy/" data-id-category="185">Полосы бериллиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="175" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/berillievye-prutki/" data-id-category="175">Прутки бериллиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="181" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/berillievye-shtabiki/" data-id-category="181">Штабики бериллиевые</a>
                            </li></ul>
                            <a href="/catalog/berillij/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1603" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovyj-prokat/" data-id-category="1603">
                            Бронзовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1603">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="789" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-vtulki/" data-id-category="789">Втулки бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="345" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-prutki/" data-id-category="345">Прутки бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="342" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-krugi/" data-id-category="342">Круги бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1763" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-truby/" data-id-category="1763">
                                Трубы бронзовые
                                <svg class="icon icon_arrow-right-min" data-id-category="1763">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1325" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-profilnye-truby/" data-id-category="1325">Бронзовые профильные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1444" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-kruglye-truby/" data-id-category="1444">Бронзовые круглые трубы</a>
                                </li></ul>
                                <a href="/catalog/bronzovye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1110" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-listy/" data-id-category="1110">Листы бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="52" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-lenty/" data-id-category="52">Ленты бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="266" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-provoloki/" data-id-category="266">Проволоки бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="590" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-polosy/" data-id-category="590">Полосы бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-shestigranniki/" data-id-category="1">Шестигранники бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="999" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovaya-folga/" data-id-category="999">Фольга бронзовая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1771" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-chushki/" data-id-category="1771">Чушки бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="616" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-shiny/" data-id-category="616">Шины бронзовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="196" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-kvadraty/" data-id-category="196">Квадраты бронзовые</a>
                            </li></ul>
                            <a href="/catalog/bronzovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1676" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanadievyj-prokat/" data-id-category="1676">
                            Ванадиевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1676">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="216" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanadievye-shestigranniki/" data-id-category="216">Шестигранники ванадиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="520" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanadievye-lenty/" data-id-category="520">Ленты ванадиевые</a>
                            </li></ul>
                            <a href="/catalog/vanadievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1742" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovyj-prokat/" data-id-category="1742">
                            Вольфрамовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1742">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="970" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-provoloki/" data-id-category="970">Проволоки вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="111" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-prutki/" data-id-category="111">Прутки вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="12" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-listy/" data-id-category="12">Листы вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="131" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-krugi/" data-id-category="131">Круги вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="526" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-lenty/" data-id-category="526">Ленты вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1991" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-truby/" data-id-category="1991">Трубы вольфрамовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="5" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovaya-folga/" data-id-category="5">Фольга вольфрамовая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1064" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volfram-renievye-listy/" data-id-category="1064">Листы вольфрам-рениевые</a>
                            </li></ul>
                            <a href="/catalog/volframovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1791" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievyj-prokat/" data-id-category="1791">
                            Гафниевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1791">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1015" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievye-provoloki/" data-id-category="1015">Проволоки гафниевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="401" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievye-listy/" data-id-category="401">Листы гафниевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="395" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievye-polosy/" data-id-category="395">Полосы гафниевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="389" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievye-prutki/" data-id-category="389">Прутки гафния</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="391" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnievye-shtabiki/" data-id-category="391">Штабики гафниевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2117" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnij/" data-id-category="2117">Соли гафния</a>
                            </li></ul>
                            <a href="/catalog/gafnievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1830" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevyj-prokat/" data-id-category="1830">
                            Дюралевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1830">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1699" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralyuminievye-truby/" data-id-category="1699">
                                Трубы дюралевые
                                <svg class="icon icon_arrow-right-min" data-id-category="1699">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1317" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/profilnye-dyuralyuminievye-truby/" data-id-category="1317">Дюралевые профильные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1437" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-dyuralyuminievye-truby/" data-id-category="1437">Дюралевые круглые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1573" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-pressovannye-truby/" data-id-category="1573">Дюралевые прессованные трубы</a>
                                </li></ul>
                                <a href="/catalog/dyuralyuminievye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1033" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-listy/" data-id-category="1033">
                                Листы дюралевые
                                <svg class="icon icon_arrow-right-min" data-id-category="1033">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="163" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-perforirovannye-listy/" data-id-category="163">Дюралевые перфорированные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="552" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-gladkie-listy/" data-id-category="552">Дюралевые гладкие листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="157" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-riflenye-listy/" data-id-category="157">Дюралевые рифленые листы</a>
                                </li></ul>
                                <a href="/catalog/dyuralevye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="82" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-ugolki/" data-id-category="82">
                                Уголки дюралевые
                                <svg class="icon icon_arrow-right-min" data-id-category="82">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="96" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-neravnopolochnye-ugolki/" data-id-category="96">Дюралевые неравнополочные уголки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="89" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-ravnopolochnye-ugolki/" data-id-category="89">Дюралевые равнополочные уголки</a>
                                </li></ul>
                                <a href="/catalog/dyuralevye-ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="330" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-krugi/" data-id-category="330">Круги дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1218" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-polosy/" data-id-category="1218">Полосы дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="333" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-prutki/" data-id-category="333">Прутки дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="248" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-plity/" data-id-category="248">Плиты дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1652" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-shvellery/" data-id-category="1652">Швеллеры дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1210" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-kvadraty/" data-id-category="1210">Квадраты дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1258" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-shestigranniki/" data-id-category="1258">Шестигранники дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="274" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-provoloki/" data-id-category="274">Проволоки дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="38" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-lenty/" data-id-category="38">Ленты дюралевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="16" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuralevye-shiny/" data-id-category="16">Шины дюралевые</a>
                            </li></ul>
                            <a href="/catalog/dyuralevyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1959" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovyj-prokat/" data-id-category="1959">
                            Кобальтовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1959">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1818" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-slitki/" data-id-category="1818">Слитки кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2017" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovyj-poroshok/" data-id-category="2017">Порошок кобальтовый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="168" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-polosy/" data-id-category="168">Полосы кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="799" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-provoloki/" data-id-category="799">Проволоки кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="159" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-prutki/" data-id-category="159">Прутки кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="831" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-listy/" data-id-category="831">Листы кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="816" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-niti/" data-id-category="816">Нити кобальтовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="164" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-shtabiki/" data-id-category="164">Штабики кобальтовые</a>
                            </li></ul>
                            <a href="/catalog/kobaltovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1985" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnyj-prokat/" data-id-category="1985">
                            Латунный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="1985">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1548" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-truby/" data-id-category="1548">
                                Трубы латунные
                                <svg class="icon icon_arrow-right-min" data-id-category="1548">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1327" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-profilnye-truby/" data-id-category="1327">Латунные профильные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1446" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-kruglye-truby/" data-id-category="1446">Латунные круглые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1694" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-kapillyarnye-trubki/" data-id-category="1694">Латунные капиллярные трубки</a>
                                </li></ul>
                                <a href="/catalog/latunnye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="614" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-vtulki/" data-id-category="614">Втулки латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="270" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-provoloki/" data-id-category="270">Проволоки латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="353" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-prutki/" data-id-category="353">Прутки латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1069" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-listy/" data-id-category="1069">Листы латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="575" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-polosy/" data-id-category="575">Полосы латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1260" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-shiny/" data-id-category="1260">Шины латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="331" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-plastiny/" data-id-category="331">Пластины латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="8" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-shestigranniki/" data-id-category="8">Шестигранники латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="349" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-krugi/" data-id-category="349">Круги латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="57" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-lenty/" data-id-category="57">Ленты латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="313" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnaya-folga/" data-id-category="313">Фольга латунная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="252" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-plity/" data-id-category="252">Плиты латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="190" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-kvadraty/" data-id-category="190">Квадраты латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1714" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-chushki/" data-id-category="1714">Чушки латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="334" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tkanye-setki-latunnye/" data-id-category="334">Сетки латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1206" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-rulony/" data-id-category="1206">Рулоны латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="272" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-anody/" data-id-category="272">Аноды латунные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="328" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-katanki/" data-id-category="328">Катанки латунные</a>
                            </li></ul>
                            <a href="/catalog/latunnyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2006" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnievyj-prokat/" data-id-category="2006">
                            Магниевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2006">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1819" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnievyj-poroshok/" data-id-category="1819">Порошок магниевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="861" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnievye-tavry/" data-id-category="861">Тавры магниевые</a>
                            </li></ul>
                            <a href="/catalog/magnievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2025" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednyj-prokat/" data-id-category="2025">
                            Медный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2025">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1328" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-truby/" data-id-category="1328">
                                Трубы медные
                                <svg class="icon icon_arrow-right-min" data-id-category="1328">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1297" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-kapillyarnye-trubki/" data-id-category="1297">Медные капиллярные трубки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1447" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-kruglye-truby/" data-id-category="1447">Медные круглые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1424" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-truby-dlya-kondicionerov/" data-id-category="1424">Трубы медные дюймовые для кондиционеров</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1549" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-profilnye-truby/" data-id-category="1549">Медные профильные трубы</a>
                                </li></ul>
                                <a href="/catalog/mednye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="946" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-provoloki/" data-id-category="946">
                                Проволоки медные
                                <svg class="icon icon_arrow-right-min" data-id-category="946">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="951" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-provoloki-kruglye/" data-id-category="951">Медные круглые проволоки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="956" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-provoloki-pryamougolnye/" data-id-category="956">Медные прямоугольные проволоки</a>
                                </li></ul>
                                <a href="/catalog/mednye-provoloki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="624" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-shiny/" data-id-category="624">Шины медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1204" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-kvadraty/" data-id-category="1204">Квадраты медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="63" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-plastiny/" data-id-category="63">Пластины медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="33" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-lenty/" data-id-category="33">Ленты медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1299" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-slitki/" data-id-category="1299">Слитки медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1076" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-listy/" data-id-category="1076">Листы медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="318" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednaya-folga/" data-id-category="318">Фольга медная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1140" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-prutki/" data-id-category="1140">Прутки медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="981" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-polosy/" data-id-category="981">Полосы медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="256" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-plity/" data-id-category="256">Плиты медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="902" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-krugi/" data-id-category="902">
                                Круги медные
                                <svg class="icon icon_arrow-right-min" data-id-category="902">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="93" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-molibdenovye-krugi/" data-id-category="93">Медно-молибденовые круги</a>
                                </li></ul>
                                <a href="/catalog/mednye-krugi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1508" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-chushki/" data-id-category="1508">Чушки медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1199" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-rulony/" data-id-category="1199">Рулоны медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="70" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-pokovki/" data-id-category="70">Поковки медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1252" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-shestigranniki/" data-id-category="1252">Шестигранники медные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="323" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tkanye-setki-mednye/" data-id-category="323">Сетки медные</a>
                            </li></ul>
                            <a href="/catalog/mednyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2119" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevyj-prokat/" data-id-category="2119">
                            Медно-никелевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2119">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="387" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-prutki/" data-id-category="387">Прутки медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1917" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-truby/" data-id-category="1917">Трубы медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="383" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-krugi/" data-id-category="383">Круги медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="492" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-lenty/" data-id-category="492">Ленты медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1073" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-listy/" data-id-category="1073">
                                Листы медно-никелевые
                                <svg class="icon icon_arrow-right-min" data-id-category="1073">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="805" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-perforirovannye-listy/" data-id-category="805">Медно-никелевые перфорированные листы</a>
                                </li></ul>
                                <a href="/catalog/medno-nikelevye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1996" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-slitki/" data-id-category="1996">Слитки медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="773" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-polosy/" data-id-category="773">Полосы медно-никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="744" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-plity/" data-id-category="744">Плиты медно-никелевые</a>
                            </li></ul>
                            <a href="/catalog/medno-nikelevyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2038" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovyj-prokat/" data-id-category="2038">
                            Молибденовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2038">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="974" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-provoloki/" data-id-category="974">
                                Проволоки молибденовые
                                <svg class="icon icon_arrow-right-min" data-id-category="974">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="113" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdeno-mednye-provoloki/" data-id-category="113">Молибдено-медные проволоки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="48" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-renievye-provoloki/" data-id-category="48">Молибден-рениевые проволоки</a>
                                </li></ul>
                                <a href="/catalog/molibdenovye-provoloki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1950" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovyj-poroshok/" data-id-category="1950">Порошок молибденовый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="119" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-prutki/" data-id-category="119">Прутки молибденовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1965" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-truby/" data-id-category="1965">
                                Трубы молибденовые
                                <svg class="icon icon_arrow-right-min" data-id-category="1965">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2024" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdeno-mednye-truby/" data-id-category="2024">Молибдено-медные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1934" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-renievye-truby/" data-id-category="1934">Молибден-рениевые трубы</a>
                                </li></ul>
                                <a href="/catalog/molibdenovye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1010" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovaya-folga/" data-id-category="1010">
                                Фольга молибденовая
                                <svg class="icon icon_arrow-right-min" data-id-category="1010">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="106" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdeno-mednaya-folga/" data-id-category="106">Молибдено-медная фольга</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="42" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-renievaya-folga/" data-id-category="42">Молибден-рениевая фольга</a>
                                </li></ul>
                                <a href="/catalog/molibdenovaya-folga/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1087" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-listy/" data-id-category="1087">
                                Листы молибденовые
                                <svg class="icon icon_arrow-right-min" data-id-category="1087">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="100" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdeno-mednye-listy/" data-id-category="100">Молибдено-медные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="35" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-renievye-listy/" data-id-category="35">Молибден-рениевые листы</a>
                                </li></ul>
                                <a href="/catalog/molibdenovye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="532" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-lenty/" data-id-category="532">Ленты молибденовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="138" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovye-krugi/" data-id-category="138">
                                Круги молибденовые
                                <svg class="icon icon_arrow-right-min" data-id-category="138">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="30" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-renievye-krugi/" data-id-category="30">Молибден-рениевые круги</a>
                                </li></ul>
                                <a href="/catalog/molibdenovye-krugi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2089" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdeno-mednyj-poroshok/" data-id-category="2089">Порошок молибдено-медный</a>
                            </li></ul>
                            <a href="/catalog/molibdenovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2052" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevyj-prokat/" data-id-category="2052">
                            Никелевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2052">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="755" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-provoloki/" data-id-category="755">Проволоки никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="485" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-lenty/" data-id-category="485">Ленты никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1854" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevyj-poroshok/" data-id-category="1854">Порошок никелевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1091" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-listy/" data-id-category="1091">Листы никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1845" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-truby/" data-id-category="1845">Трубы никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1004" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevaya-folga/" data-id-category="1004">Фольга никелевая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="381" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-prutki/" data-id-category="381">Прутки никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="377" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-krugi/" data-id-category="377">Круги никелевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="87" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-pokovki/" data-id-category="87">Поковки никелевые</a>
                            </li></ul>
                            <a href="/catalog/nikelevyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2065" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievyj-prokat/" data-id-category="2065">
                            Ниобиевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2065">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="114" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-provoloki/" data-id-category="114">Проволоки ниобиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="69" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-prutki/" data-id-category="69">Прутки ниобиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="75" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-listy/" data-id-category="75">Листы ниобиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2014" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-truby/" data-id-category="2014">Трубы ниобиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="537" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-lenty/" data-id-category="537">Ленты ниобиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="80" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievaya-folga/" data-id-category="80">Фольга ниобиевая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2071" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievyj-poroshok/" data-id-category="2071">Порошок ниобиевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="62" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievye-krugi/" data-id-category="62">Круги ниобиевые</a>
                            </li></ul>
                            <a href="/catalog/niobievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2078" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyannyj-prokat/" data-id-category="2078">
                            Оловянный прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2078">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="993" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyannaya-folga/" data-id-category="993">Фольга оловянная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1886" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyannye-chushki/" data-id-category="1886">Чушки оловянные</a>
                            </li></ul>
                            <a href="/catalog/olovyannyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2096" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/renievyj-prokat/" data-id-category="2096">
                            Рениевый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2096">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="152" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/renievye-shtabiki/" data-id-category="152">Штабики рениевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2086" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/renievyj-poroshok/" data-id-category="2086">Порошок рениевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="140" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/renievye-polosy/" data-id-category="140">Полосы рениевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="132" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/renievye-prutki/" data-id-category="132">Прутки рениевые</a>
                            </li></ul>
                            <a href="/catalog/renievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2099" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovyj-prokat/" data-id-category="2099">
                            Свинцовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2099">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="50" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-plity/" data-id-category="50">Плиты свинцовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="962" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-provoloki/" data-id-category="962">Проволоки свинцовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="43" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-listy/" data-id-category="43">Листы свинцовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1810" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-truby/" data-id-category="1810">Трубы свинцовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1645" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-chushki/" data-id-category="1645">Чушки свинцовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="546" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovye-holodnokatanye-listy/" data-id-category="546">Листы холоднокатаные свинцовые</a>
                            </li></ul>
                            <a href="/catalog/svincovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2103" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovyj-prokat/" data-id-category="2103">
                            Танталовый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2103">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="279" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-provoloki/" data-id-category="279">Проволоки танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1953" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovyj-poroshok/" data-id-category="1953">Порошок танталовый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="316" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovaya-folga/" data-id-category="316">Фольга танталовая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="65" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-lenty/" data-id-category="65">Ленты танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="469" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-prutki/" data-id-category="469">Прутки танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2041" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-truby/" data-id-category="2041">Трубы танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="150" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-listy/" data-id-category="150">Листы танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="356" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-krugi/" data-id-category="356">Круги танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="568" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-polosy/" data-id-category="568">Полосы танталовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1254" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovye-shiny/" data-id-category="1254">Шины танталовые</a>
                            </li></ul>
                            <a href="/catalog/tantalovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2105" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovyj-prokat/" data-id-category="2105">
                            Титановый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2105">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1637" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-truby/" data-id-category="1637">Титановые трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1028" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-listy/" data-id-category="1028">Листы титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="276" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-provoloki/" data-id-category="276">Проволоки титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="340" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-prutki/" data-id-category="340">Прутки титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1719" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovyj-poroshok/" data-id-category="1719">Порошок титановый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="618" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-plity/" data-id-category="618">Плиты титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="336" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-krugi/" data-id-category="336">Круги титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="986" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovaya-folga/" data-id-category="986">Фольга титановая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="210" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-shestigranniki/" data-id-category="210">Шестигранники титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1225" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-polosy/" data-id-category="1225">Полосы титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="499" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-lenty/" data-id-category="499">Ленты титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="742" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-pokovki/" data-id-category="742">Поковки титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="201" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-kvadraty/" data-id-category="201">Квадраты титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1948" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-chushki/" data-id-category="1948">Чушки титановые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="22" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-shiny/" data-id-category="22">Шины титановые</a>
                            </li></ul>
                            <a href="/catalog/titanovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2107" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovyj-prokat/" data-id-category="2107">
                            Цинковый прокат
                            <svg class="icon icon_arrow-right-min" data-id-category="2107">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="966" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovye-provoloki/" data-id-category="966">Проволоки цинковые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1853" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovye-chushki/" data-id-category="1853">Чушки цинковые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="543" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovye-lenty/" data-id-category="543">Ленты цинковые</a>
                            </li></ul>
                            <a href="/catalog/cinkovyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/cvetnoj-metalloprokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2118">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/blagorodnye-metally/" data-id-category="2118">
                        Благородные металлы
                        <svg class="icon icon_arrow-right-min" data-id-category="2118">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1867" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zolotoj-prokat/" data-id-category="1867">
                            Золото
                            <svg class="icon icon_arrow-right-min" data-id-category="1867">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1278" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zolotye-diski/" data-id-category="1278">Диски золотые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1744" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-iz-zolota/" data-id-category="1744">Порошок золотой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1869" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zoloto-v-granulah/" data-id-category="1869">Гранулы золотые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1609" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty-iz-zolota/" data-id-category="1609">Ленты из золота</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1511" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zolotye-truby/" data-id-category="1511">Трубы золотые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1399" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/folga-iz-zolota/" data-id-category="1399">Фольга из золота</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1680" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polosy-iz-zolota/" data-id-category="1680">Полосы из золота</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1796" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-iz-zolota/" data-id-category="1796">Проволоки из золота</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1833" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pripoi-dlya-zolota/" data-id-category="1833">Припои для золота</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1905" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zolotye-anody/" data-id-category="1905">Аноды золотые</a>
                            </li></ul>
                            <a href="/catalog/zolotoj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1407" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izdeliya-iz-serebra/" data-id-category="1407">
                            Серебро
                            <svg class="icon icon_arrow-right-min" data-id-category="1407">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1287" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanye-pripoi/" data-id-category="1287">Припои серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1412" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanye-provoloki/" data-id-category="1412">Проволоки серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1618" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanye-lenty/" data-id-category="1618">Ленты серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1523" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanaya-folga/" data-id-category="1523">Фольга серебряная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1749" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanye-polosy/" data-id-category="1749">Полосы серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1871" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-serebra/" data-id-category="1871">Трубы серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1799" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanyj-poroshok/" data-id-category="1799">Порошок серебряный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1835" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanye-anody/" data-id-category="1835">Аноды серебряные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1690" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebro-v-granulah/" data-id-category="1690">Гранулы серебряные</a>
                            </li></ul>
                            <a href="/catalog/izdeliya-iz-serebra/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1515" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izdeliya-iz-platiny/" data-id-category="1515">
                            Платина
                            <svg class="icon icon_arrow-right-min" data-id-category="1515">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1282" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovye-provoloki/" data-id-category="1282">Проволоки платиновые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1405" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovye-anody/" data-id-category="1405">Аноды платиновые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1683" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovaya-folga/" data-id-category="1683">Фольга платиновая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1518" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-iz-platiny/" data-id-category="1518">Порошок из платины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1615" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovye-lenty/" data-id-category="1615">Ленты платиновые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1834" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovye-truby/" data-id-category="1834">Трубы платиновые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1745" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polosy-iz-platiny/" data-id-category="1745">Полосы из платины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1877" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/platinovye-katalizatornye-setki/" data-id-category="1877">Сетки катализаторные платиновые</a>
                            </li></ul>
                            <a href="/catalog/izdeliya-iz-platiny/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1621" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izdeliya-iz-palladiya/" data-id-category="1621">
                            Палладий
                            <svg class="icon icon_arrow-right-min" data-id-category="1621">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1295" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-iz-palladiya/" data-id-category="1295">Проволоки из палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1420" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-palladiya/" data-id-category="1420">Порошок палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1527" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/palladievye-pripoi/" data-id-category="1527">Припои палладиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1623" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/palladievaya-folga/" data-id-category="1623">Фольга палладиевая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1695" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/anody-iz-palladiya/" data-id-category="1695">Аноды из палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1875" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty-iz-palladiya/" data-id-category="1875">Ленты из палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1838" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polosy-iz-palladiya/" data-id-category="1838">Полосы из палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1755" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ulavlivayushaya-setka-iz-palladiya/" data-id-category="1755">Сетки улавливающие из палладия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1801" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-palladiya/" data-id-category="1801">Трубы из палладия</a>
                            </li></ul>
                            <a href="/catalog/izdeliya-iz-palladiya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1564" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/osmij/" data-id-category="1564">Осмий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1357" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rodij/" data-id-category="1357">Родий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1903" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/iridievyj-prokat/" data-id-category="1903">
                            Иридий
                            <svg class="icon icon_arrow-right-min" data-id-category="1903">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1464" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/iridij/" data-id-category="1464">Иридий металл</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2510" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/diski-iz-iridiya/" data-id-category="2510">Диски из иридия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2506" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/igly-iz-iridiya/" data-id-category="2506">Иглы из иридия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2508" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/iridievye-misheni/" data-id-category="2508">Мишени иридиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2504" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/iridievye-polosy/" data-id-category="2504">Полосы иридиевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2507" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-iz-iridiya/" data-id-category="2507">Проволоки из иридия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2505" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubki-iz-iridiya/" data-id-category="2505">Трубки из иридия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2509" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/iridievaya-folga/" data-id-category="2509">Фольга иридиевая</a>
                            </li></ul>
                            <a href="/catalog/iridievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1650" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rutenij/" data-id-category="1650">Рутений</a>
                        </li></ul>
                        <a href="/catalog/blagorodnye-metally/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1425">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/redkozemelnye-metally/" data-id-category="1425">
                        Редкоземельные металлы
                        <svg class="icon icon_arrow-right-min" data-id-category="1425">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2109" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievyj-prokat/" data-id-category="2109">
                            Цирконий
                            <svg class="icon icon_arrow-right-min" data-id-category="2109">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="361" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-krugi/" data-id-category="361">Круги циркониевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1990" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-truby/" data-id-category="1990">Трубы циркониевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2018" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievyj-poroshok/" data-id-category="2018">Порошок циркониевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="550" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-lenty/" data-id-category="550">Ленты циркониевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="17" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-provoloki/" data-id-category="17">Проволоки циркониевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="23" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievaya-folga/" data-id-category="23">Фольга циркониевая</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1016" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-listy/" data-id-category="1016">Листы циркониевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="364" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievye-prutki/" data-id-category="364">Прутки циркониевые</a>
                            </li></ul>
                            <a href="/catalog/cirkonievyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1436" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/skandij/" data-id-category="1436">Скандий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1309" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lantan/" data-id-category="1309">Лантан</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1438" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cerij/" data-id-category="1438">Церий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1539" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samarij/" data-id-category="1539">Самарий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1846" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tulij/" data-id-category="1846">Тулий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1537" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ittrij/" data-id-category="1537">Иттрий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1756" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gadolinij/" data-id-category="1756">Гадолиний</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1629" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neodim/" data-id-category="1629">Неодим</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1809" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lyutecij/" data-id-category="1809">Лютеций</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1302" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/germanij/" data-id-category="1302">Германий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1878" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/evropij/" data-id-category="1878">Европий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1700" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/erbij/" data-id-category="1700">Эрбий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1941" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/itterbij/" data-id-category="1941">Иттербий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1915" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/terbij/" data-id-category="1915">Тербий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1988" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/disprozij/" data-id-category="1988">Диспрозий</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1966" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prazeodim/" data-id-category="1966">Празеодим</a>
                        </li></ul>
                        <a href="/catalog/redkozemelnye-metally/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1443">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/kabelnaya-produkciya/" data-id-category="1443">
                        Кабельная продукция
                        <svg class="icon icon_arrow-right-min" data-id-category="1443">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1098" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-svyazi/" data-id-category="1098">
                            Связь
                            <svg class="icon icon_arrow-right-min" data-id-category="1098">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1101" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-gorodskie-telefonnye/" data-id-category="1101">Городские телефонные кабели</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1106" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-svyazi-stancionnye/" data-id-category="1106">Станционные кабели связи</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1109" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-mestnoj-svyazi-vysokochastotnye/" data-id-category="1109">Высокочастотные кабели местной связи</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1114" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-radiochastotnye/" data-id-category="1114">Радиочастотные кабели</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1119" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-svyazi/" data-id-category="1119">Кабели связи</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1122" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-svyazi-telefonnye-shahtnye/" data-id-category="1122">Шахтные телефонные кабели связи</a>
                            </li></ul>
                            <a href="/catalog/kabeli-i-provoda-svyazi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1063" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoda/" data-id-category="1063">
                            Провода
                            <svg class="icon icon_arrow-right-min" data-id-category="1063">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1068" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoda-obmotochnye/" data-id-category="1068">Провода обмоточные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1072" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoda-bortovye/" data-id-category="1072">Провода бортовые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1075" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-vozdushnyh-linij-elektroperedach/" data-id-category="1075">Кабели для воздушных линий электропередач</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1080" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoda-silovye/" data-id-category="1080">Провода силовые</a>
                            </li></ul>
                            <a href="/catalog/provoda/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2028" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sip-samonesushij-izolirovannyj-provod/" data-id-category="2028">СИП</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2040" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vitaya-para-informacionnyj-kabel/" data-id-category="2040">Витая пара</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1283" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-silovoj/" data-id-category="1283">
                            Силовые кабели
                            <svg class="icon icon_arrow-right-min" data-id-category="1283">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1284" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-silovoj-mednyj/" data-id-category="1284">Медные силовые кабели</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1408" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-silovoj-alyuminievyj/" data-id-category="1408">Алюминиевые силовые кабели</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1022" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-silovoj-s-bumazhnoj-izolyaciej/" data-id-category="1022">Силовые кабели с бумажной изоляцией</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1027" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-silovye-s-plastmassovoj-izolyaciej/" data-id-category="1027">Силовые кабели с пластмассовой изоляцией</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1032" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-silovoj-s-rezinovoj-izolyaciej/" data-id-category="1032">Силовые кабели с резиновой изоляцией</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1038" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-silovye-s-izolyaciej-iz-sshitogo-polietilena/" data-id-category="1038">Силовые кабели с изоляцией из сшитого полиэтилена</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1043" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-ustanovochnye/" data-id-category="1043">Установочные кабели и провода</a>
                            </li></ul>
                            <a href="/catalog/kabel-silovoj/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1177" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-opticheskie/" data-id-category="1177">Оптические кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1413" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/koaksialnyj-kabel/" data-id-category="1413">Коаксиальные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1874" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samoreguliruyushiesya-greyushie-kabeli/" data-id-category="1874">Греющие саморегулирующиеся кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1624" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/akusticheskij-kabel/" data-id-category="1624">Акустические кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1521" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-gibkij/" data-id-category="1521">Гибкие кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1754" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/soedinitelnye-provoda/" data-id-category="1754">Соединительные провода</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1800" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/telefonnyj-kabel/" data-id-category="1800">Телефонные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1707" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronirovannyj-kabel/" data-id-category="1707">Бронированные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1174" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shnury/" data-id-category="1174">Шнуры электрические</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1836" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-kontrolnyj/" data-id-category="1836">Контрольные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1054" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-montazhnye/" data-id-category="1054">Провод монтажный</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1911" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-dlya-videonablyudeniya/" data-id-category="1911">Кабели для видеонаблюдения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1962" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/montazhnyj-kabel/" data-id-category="1962">Монтажные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1939" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-vysokovoltnyj/" data-id-category="1939">Высоковольтные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1059" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-universalnye/" data-id-category="1059">Универсальные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2009" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provod-ustanovochnyj/" data-id-category="2009">Установочные провода</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1209" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-magistralnye/" data-id-category="1209">Магистральные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1987" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neizolirovannye-provoda/" data-id-category="1987">Неизолированные провода</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1144" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-kompyuternyh-setej/" data-id-category="1144">Кабели для компьютерных сетей</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1048" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-sudovye/" data-id-category="1048">Судовые кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1222" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-vysokochastotnye/" data-id-category="1222">Высокочастотные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1083" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-upravleniya/" data-id-category="1083">
                            Кабели систем управления
                            <svg class="icon icon_arrow-right-min" data-id-category="1083">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1086" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-promyshlennoj-avtomatizacii-i-sistem-upravleniya/" data-id-category="1086">Кабели для промышленной автоматизации и систем управления</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1090" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-signalizacii-i-blokirovki/" data-id-category="1090">Кабели сигнализаций и блокировок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1094" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-sistem-pozharnoj-i-ohrannoj-signalizacii/" data-id-category="1094">Кабели пожарной и охранной сигнализации</a>
                            </li></ul>
                            <a href="/catalog/kabeli-upravleniya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1157" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-neftepogruzhnye/" data-id-category="1157">Нефтепогружные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1009" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodopogruzhnoj-kabel/" data-id-category="1009">Водопогружные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2054" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabel-ohranno-pozharnoj-signalizacii/" data-id-category="2054">Охранно-пожарные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1203" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-stancionnye/" data-id-category="1203">Станционные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1196" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-antivibracionnye/" data-id-category="1196">Антивибрационные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1235" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-triaksialnye/" data-id-category="1235">Триаксиальные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1164" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-termoelektrodnye/" data-id-category="1164">Термоэлектродные кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1161" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-dlya-podvizhnogo-sostava/" data-id-category="1161">Кабели и провода для подвижного состава</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1188" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-termostojkie/" data-id-category="1188">Термостойкие провода и кабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1215" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-provodnogo-veshaniya/" data-id-category="1215">Кабели проводного вещания</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1171" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-geofizicheskie/" data-id-category="1171">Геофизические кабели и провода</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1184" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-aerodromnyh-ognej/" data-id-category="1184">Кабели для аэродромных огней</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1228" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-i-provoda-dlya-medicinskih-priborov/" data-id-category="1228">Кабели и провода для медицинских приборов</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1192" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pnevmokabeli/" data-id-category="1192">Пневмокабели</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1956" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-vysokovoltnye-maloj-moshnosti/" data-id-category="1956">Высоковольтные кабели малой мощности</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1149" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-dlya-gornorudnoj-promyshlennosti/" data-id-category="1149">
                            Кабели для горнорудной промышленности
                            <svg class="icon icon_arrow-right-min" data-id-category="1149">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1153" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-shahtnye-i-ekskavatornyj/" data-id-category="1153">Шахтные и экскаваторные кабели</a>
                            </li></ul>
                            <a href="/catalog/kabeli-dlya-gornorudnoj-promyshlennosti/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1126" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-nagrevatelnye-i-provoda-termoparnye/" data-id-category="1126">
                            Нагревательные, термопарные кабели и провода
                            <svg class="icon icon_arrow-right-min" data-id-category="1126">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1129" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-termoparnye/" data-id-category="1129">Кабели термопарные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1139" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kabeli-nagrevatelnye/" data-id-category="1139">Кабели нагревательные</a>
                            </li></ul>
                            <a href="/catalog/kabeli-nagrevatelnye-i-provoda-termoparnye/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/kabelnaya-produkciya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1397">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/svarochnye-materialy/" data-id-category="1397">
                        Сварочные материалы
                        <svg class="icon icon_arrow-right-min" data-id-category="1397">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1277" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarochnaya-provoloka/" data-id-category="1277">
                            Проволоки сварочные
                            <svg class="icon icon_arrow-right-min" data-id-category="1277">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1281" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/omednennaya-svarochnaya-provoloka/" data-id-category="1281">Омедненные сварочные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1404" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshkovaya-svarochnaya-provoloka/" data-id-category="1404">Порошковые сварочные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1517" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushaya-svarochnaya-provoloka/" data-id-category="1517">Нержавеющие сварочные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1614" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-svarochnye-provoloki/" data-id-category="1614">Алюминиевые сварочные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1747" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polirovannaya-svarochnaya-provoloka/" data-id-category="1747">Полированные сварочные проволоки</a>
                            </li></ul>
                            <a href="/catalog/svarochnaya-provoloka/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1398" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarochnye-elektrody/" data-id-category="1398">
                            Электроды сварочные
                            <svg class="icon icon_arrow-right-min" data-id-category="1398">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1510" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovye-elektrody/" data-id-category="1510">Вольфрамовые электроды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1286" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-svarki-stali/" data-id-category="1286">Электроды для сварки стали</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1406" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-naplavki/" data-id-category="1406">Электроды для наплавки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1619" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-svarki-alyuminiya/" data-id-category="1619">Электроды для сварки алюминия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1524" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-svarki-chuguna/" data-id-category="1524">Электроды для сварки чугуна</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1687" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-rezki/" data-id-category="1687">Электроды для резки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1748" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-svarki-nerzhaveyushej-stali/" data-id-category="1748">Электроды для сварки нержавеющей стали</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="147" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrody-dlya-svarki-i-naplavki-medi-i-splavov/" data-id-category="147">Электроды для сварки и наплавки меди и сплавов</a>
                            </li></ul>
                            <a href="/catalog/svarochnye-elektrody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1608" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarochnyj-flyus/" data-id-category="1608">Флюс сварочный</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1679" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prisadochnye-prutki/" data-id-category="1679">
                            Присадочные прутки
                            <svg class="icon icon_arrow-right-min" data-id-category="1679">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1280" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-prisadochnye-prutki/" data-id-category="1280">Алюминиевые присадочные прутки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1514" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-prisadochnye-prutki/" data-id-category="1514">Медные присадочные прутки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1402" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-prisadochnye-prutki/" data-id-category="1402">Нержавеющие присадочные прутки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1612" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/omednyonnye-prisadochnyj-prutki/" data-id-category="1612">Омеднённые присадочные прутки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="141" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kobaltovye-prisadochnye-prutki/" data-id-category="141">Кобальтовые присадочные прутки</a>
                            </li></ul>
                            <a href="/catalog/prisadochnye-prutki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="311" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pripoi/" data-id-category="311">
                            Припои для пайки
                            <svg class="icon icon_arrow-right-min" data-id-category="311">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="423" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-cinkovye-pripoi/" data-id-category="423">Медно-цинковые припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="326" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyanno-mednye-pripoi/" data-id-category="326">Оловянно-медные припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="324" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyanno-cinkovye-pripoi/" data-id-category="324">Оловянно-цинковые припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1797" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pripoi-dlya-platiny/" data-id-category="1797">Припои для платины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="558" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/specialnye-splavy/" data-id-category="558">Специальные припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="320" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/indievye-pripoi/" data-id-category="320">Индиевые припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="410" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-fosfornye-pripoi/" data-id-category="410">Медно-фосфорные припои ПМФ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="321" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vismutovye-pripoi/" data-id-category="321">Висмутовые припои</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="312" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bessurmyanistye-pripoi/" data-id-category="312">Бессурьмянистые припои ПОС</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="317" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/malosurmyanistye-pripoi/" data-id-category="317">Малосурьмянистые припои ПОССу</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="315" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/surmyanistye-pripoi/" data-id-category="315">Сурьмянистые припои ПОССу</a>
                            </li></ul>
                            <a href="/catalog/pripoi/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="154" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/naplavochnye-poroshki/" data-id-category="154">Наплавочные порошки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2251" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshkovaya-naplavochnaya-lenta/" data-id-category="2251">Порошковые наплавочные ленты</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2711" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vannochka-dlya-svarki/" data-id-category="2711">Ванночка для сварки</a>
                        </li></ul>
                        <a href="/catalog/svarochnye-materialy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1792">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/truboprovodnaya-armatura/" data-id-category="1792">
                        Трубопроводная арматура
                        <svg class="icon icon_arrow-right-min" data-id-category="1792">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1395" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapornaya-truboprovodnaya-armatura/" data-id-category="1395">
                            Запорная арматура
                            <svg class="icon icon_arrow-right-min" data-id-category="1395">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1750" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/filtry/" data-id-category="1750">
                                Фильтры
                                <svg class="icon icon_arrow-right-min" data-id-category="1750">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1352" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/setchatye-filtry/" data-id-category="1352">Сетчатые фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1419" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-filtry/" data-id-category="1419">Газовые фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1561" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gryazeviki/" data-id-category="1561">Грязевики</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1643" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mehanicheskie-filtry/" data-id-category="1643">
                                    Механические фильтры
                                    <svg class="icon icon_arrow-right-min" data-id-category="1643">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="690" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-mehanicheskie-filtry/" data-id-category="690">Фланцевые механические фильтры</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="696" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-mehanicheskie-filtry/" data-id-category="696">Муфтовые механические фильтры</a>
                                    </li></ul>
                                    <a href="/catalog/mehanicheskie-filtry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1689" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-filtry/" data-id-category="1689">Фланцевые фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1770" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnitnye-filtry/" data-id-category="1770">
                                    Магнитные фильтры
                                    <svg class="icon icon_arrow-right-min" data-id-category="1770">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="709" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-magnitnye-filtry/" data-id-category="709">Муфтовые магнитные фильтры</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="716" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-magnitnye-filtry/" data-id-category="716">Фланцевые магнитные фильтры</a>
                                    </li></ul>
                                    <a href="/catalog/magnitnye-filtry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1805" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-filtry/" data-id-category="1805">Угловые фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1837" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molochnye-filtry/" data-id-category="1837">Молочные фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1873" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-filtry/" data-id-category="1873">Проходные фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1910" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perenosnye-filtry/" data-id-category="1910">Переносные фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1940" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neftyanye-filtry/" data-id-category="1940">Нефтяные фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1964" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtucernye-filtry/" data-id-category="1964">Штуцерные фильтры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1995" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-trubchatye-filtry/" data-id-category="1995">Угловые трубчатые фильтры</a>
                                </li></ul>
                                <a href="/catalog/filtry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1795" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany/" data-id-category="1795">
                                Клапаны
                                <svg class="icon icon_arrow-right-min" data-id-category="1795">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="602" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-klapany/" data-id-category="602">Хромоникелевые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1333" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/obratnye-klapany/" data-id-category="1333">Обратные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1449" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/predohranitelnye-klapany/" data-id-category="1449">Предохранительные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1550" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reguliruyushie-klapany/" data-id-category="1550">Регулирующие клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1638" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapornye-klapany/" data-id-category="1638">Запорные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1733" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/balansirovochnye-klapany/" data-id-category="1733">Балансировочные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1751" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-klapany/" data-id-category="1751">Фланцевые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1816" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pruzhinnye-klapany/" data-id-category="1816">Пружинные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1850" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-klapany/" data-id-category="1850">Латунные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1889" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-klapany/" data-id-category="1889">Муфтовые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1906" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otsechnye-klapany/" data-id-category="1906">Отсечные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1947" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/igolchatye-klapany/" data-id-category="1947">Игольчатые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1971" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-klapany/" data-id-category="1971">Чугунные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1992" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-klapany/" data-id-category="1992">Стальные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2010" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtucernye-klapany/" data-id-category="2010">Штуцерные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2027" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/privarnye-klapany/" data-id-category="2027">Приварные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2039" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samozapornye-klapany/" data-id-category="2039">Самозапорные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2053" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-pod-dyurit/" data-id-category="2053">Клапаны под дюрит</a>
                                </li></ul>
                                <a href="/catalog/klapany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1396" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany/" data-id-category="1396">
                                Краны
                                <svg class="icon icon_arrow-right-min" data-id-category="1396">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="416" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-sharovye-ksh/" data-id-category="416">Краны шаровые КШ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1486" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-krany/" data-id-category="1486">
                                    Газовые краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1486">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="866" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-muftovye-krany/" data-id-category="866">Газовые муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1085" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-probkovye-krany/" data-id-category="1085">Газовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1078" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-flancevye-krany/" data-id-category="1078">Газовые фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1082" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany-dlya-gaza/" data-id-category="1082">Шаровые краны для газа</a>
                                    </li></ul>
                                    <a href="/catalog/gazovye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1571" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-krany/" data-id-category="1571">
                                    Фланцевые краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1571">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="938" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-flancevye-krany/" data-id-category="938">Латунные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="920" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nepolnoprohodnye-flancevye-krany/" data-id-category="920">Неполнопроходные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="905" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-flancevye-krany/" data-id-category="905">Нержавеющие фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="888" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polnoprohodnye-flancevye-krany/" data-id-category="888">Полнопроходные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1042" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnikovye-flancevye-krany/" data-id-category="1042">Сальниковые фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="912" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-flancevye-krany/" data-id-category="912">Стальные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="928" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/standartnoprohodnye-flancevye-krany/" data-id-category="928">Стандартнопроходные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="897" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/celnosvarnye-flancevye-krany/" data-id-category="897">Цельносварные фланцевые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="892" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-flancevye-krany/" data-id-category="892">Чугунные фланцевые краны</a>
                                    </li></ul>
                                    <a href="/catalog/flancevye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1648" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-krany/" data-id-category="1648">
                                    Муфтовые краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1648">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="852" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-muftovye-krany/" data-id-category="852">Латунные муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="944" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-probkovye-krany/" data-id-category="944">Муфтовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="857" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-muftovye-krany/" data-id-category="857">Нержавеющие муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1053" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnikovye-muftovye-krany/" data-id-category="1053">Сальниковые муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1014" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/spusknye-muftovye-krany/" data-id-category="1014">Спускные муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="997" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-muftovye-krany/" data-id-category="997">Стальные муфтовые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="883" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-muftovye-krany/" data-id-category="883">Угловые муфтовые краны</a>
                                    </li></ul>
                                    <a href="/catalog/muftovye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1709" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-dlya-manometra/" data-id-category="1709">
                                    Краны для манометра
                                    <svg class="icon icon_arrow-right-min" data-id-category="1709">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="613" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-krany-dlya-manometra/" data-id-category="613">Латунные краны для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="940" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-krany-dlya-manometra/" data-id-category="940">Муфтовые краны для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1256" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-krany-dlya-manometra/" data-id-category="1256">Стальные краны для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="923" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trehhodovye-krany-dlya-manometra/" data-id-category="923">Трехходовые краны для манометра</a>
                                    </li></ul>
                                    <a href="/catalog/krany-dlya-manometra/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1760" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodorazbornye-krany/" data-id-category="1760">
                                    Водоразборные краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1760">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="427" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodorazbornye-krany-so-shtucerom/" data-id-category="427">Водоразборные краны со штуцером</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="421" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodorazbornye-sharovye-krany/" data-id-category="421">Водоразборные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1138" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-vodorazbornye-krany/" data-id-category="1138">Латунные водоразборные краны</a>
                                    </li></ul>
                                    <a href="/catalog/vodorazbornye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1811" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/probkovye-krany/" data-id-category="1811">
                                    Пробковые краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1811">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1326" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kran-probno-spusknoj/" data-id-category="1326">Кран пробно-спускной</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="382" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovyj-probkovyj-kran/" data-id-category="382">Бронзовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="509" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvuhhodovye-probkovye-krany/" data-id-category="509">Двухходовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="534" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyujmovye-probkovye-krany/" data-id-category="534">Дюймовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="472" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kran-probkovyj-so-smazkoj/" data-id-category="472">Кран пробковый со смазкой</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="511" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kran-reguliruyushij/" data-id-category="511">Кран регулирующий</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="467" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kran-s-parovym-obogrevom/" data-id-category="467">Кран с паровым обогревом</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="622" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-probkovye-krany/" data-id-category="622">Латунные пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1170" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-probkovye-krany/" data-id-category="1170">Нержавеющие пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1071" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/probkovye-krany-dlya-manometra/" data-id-category="1071">Пробковые краны для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1067" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-probkovye-krany/" data-id-category="1067">Проходные пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1047" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnikovye-probkovye-krany/" data-id-category="1047">Сальниковые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1234" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-probkovye-krany/" data-id-category="1234">Стальные пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1208" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tryohhodovye-probkovye-krany/" data-id-category="1208">Трёхходовые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1191" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-probkovye-krany/" data-id-category="1191">Фланцевые пробковые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1133" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-probkovye-krany/" data-id-category="1133">Чугунные пробковые краны</a>
                                    </li></ul>
                                    <a href="/catalog/probkovye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1852" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/protivopozharnye-krany/" data-id-category="1852">
                                    Противопожарные краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1852">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="662" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pozharnye-krany/" data-id-category="662">Пожарные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="158" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/protivopozharnye-sharovye-krany/" data-id-category="158">Противопожарные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="666" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-pozharnye-krany/" data-id-category="666">Угловые пожарные краны</a>
                                    </li></ul>
                                    <a href="/catalog/protivopozharnye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1879" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konusnye-krany/" data-id-category="1879">
                                    Конусные краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1879">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="374" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-konusnye-krany/" data-id-category="374">Бронзовые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="502" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvuhhodovye-konusnye-krany/" data-id-category="502">Двухходовые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="529" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyujmovye-konusnye-krany/" data-id-category="529">Дюймовые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1125" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konusnye-krany-dlya-manometra/" data-id-category="1125">Конусные краны для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="601" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-konusnye-krany/" data-id-category="601">Латунные конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1160" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-konusnye-krany/" data-id-category="1160">Муфтовые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1167" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-konusnye-krany/" data-id-category="1167">Нержавеющие конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1239" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-konusnye-krany/" data-id-category="1239">Проходные конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1245" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnikovye-konusnye-krany/" data-id-category="1245">Сальниковые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1250" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-konusnye-krany/" data-id-category="1250">Стальные конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1214" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tryohhodovye-konusnye-krany/" data-id-category="1214">Трёхходовые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1202" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-konusnye-krany/" data-id-category="1202">Фланцевые конусные краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1152" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-konusnye-krany/" data-id-category="1152">Чугунные конусные краны</a>
                                    </li></ul>
                                    <a href="/catalog/konusnye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1919" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-krany/" data-id-category="1919">Хромоникелевые краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="180" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kombinirovannye-krany/" data-id-category="180">Комбинированные краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="191" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/capkovye-krany/" data-id-category="191">Цапковые краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="197" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtucernye-krany/" data-id-category="197">Штуцерные краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="205" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-pod-dyurit/" data-id-category="205">Краны под дюрит</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="869" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-sharovye-pnd/" data-id-category="869">Краны шаровые ПНД</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1349" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany/" data-id-category="1349">
                                    Шаровые краны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1349">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="822" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-sharovye-krany/" data-id-category="822">Алюминиевые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="787" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvuhhodovye-sharovye-krany/" data-id-category="787">Двухходовые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="767" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyujmovye-sharovye-krany/" data-id-category="767">Дюймовые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="829" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapornye-sharovye-krany/" data-id-category="829">Запорные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="731" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-sharovye-krany/" data-id-category="731">Латунные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="814" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-sharovye-krany-so-spusknym-ustrojstvom/" data-id-category="814">Латунные шаровые краны со спускным устройством</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="695" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-sharovye-krany/" data-id-category="695">Муфтовые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="743" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-sharovye-krany/" data-id-category="743">Нержавеющие шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="708" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polnoprohodnye-sharovye-krany/" data-id-category="708">Полнопроходные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="727" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnye-sharovye-krany/" data-id-category="727">Сварные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="737" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-sharovye-krany/" data-id-category="737">Стальные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="748" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/standartnoprohodnye-sharovye-krany/" data-id-category="748">Стандартнопроходные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="779" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trehhodovye-sharovye-krany/" data-id-category="779">Трехходовые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="877" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-sharovye-krany/" data-id-category="877">Угловые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="702" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-sharovye-krany/" data-id-category="702">Фланцевые шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="839" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-sharovye-krany/" data-id-category="839">Чугунные шаровые краны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="797" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany-babochki/" data-id-category="797">Шаровые краны-бабочки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="806" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany-dlya-vody/" data-id-category="806">Шаровые краны для воды</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="689" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtucernye-sharovye-krany/" data-id-category="689">Штуцерные шаровые краны</a>
                                    </li></ul>
                                    <a href="/catalog/sharovye-krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/krany/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2011" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaslonki/" data-id-category="2011">
                                Заслонки
                                <svg class="icon icon_arrow-right-min" data-id-category="2011">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1314" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-zaslonki/" data-id-category="1314">Фланцевые заслонки</a>
                                </li></ul>
                                <a href="/catalog/zaslonki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1881" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lyuki/" data-id-category="1881">
                                Люки
                                <svg class="icon icon_arrow-right-min" data-id-category="1881">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1369" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lyuki-lazy/" data-id-category="1369">Люки-лазы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1487" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zamernye-lyuki/" data-id-category="1487">Замерные люки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1585" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svetovye-lyuki/" data-id-category="1585">Световые люки</a>
                                </li></ul>
                                <a href="/catalog/lyuki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1300" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/manometry/" data-id-category="1300">Манометры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1533" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektroprivody/" data-id-category="1533">Электроприводы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1697" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventili/" data-id-category="1697">
                                Вентили
                                <svg class="icon icon_arrow-right-min" data-id-category="1697">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1937" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-ventili/" data-id-category="1937">Бронзовые вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1868" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodoprovodnye-ventili/" data-id-category="1868">Водопроводные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1504" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-ventili/" data-id-category="1504">
                                    Газовые вентили
                                    <svg class="icon icon_arrow-right-min" data-id-category="1504">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="4" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-ventili-vysokogo-davleniya/" data-id-category="4">Газовые вентили высокого давления</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="11" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/igolchatye-gazovye-ventili/" data-id-category="11">Игольчатые газовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1266" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-zapornye-ventili/" data-id-category="1266">Запорные газовые вентили</a>
                                    </li></ul>
                                    <a href="/catalog/gazovye-ventili/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2050" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaporno-balansirovochnye-ventili/" data-id-category="2050">Запорно-балансировочные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2004" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaporno-regulirovochnye-ventili/" data-id-category="2004">Запорно-регулировочные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1382" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapornye-ventili/" data-id-category="1382">
                                    Запорные вентили
                                    <svg class="icon icon_arrow-right-min" data-id-category="1382">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="595" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-ventili/" data-id-category="595">Хромоникелевые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1166" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-zapornye-ventili/" data-id-category="1166">Угловые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1169" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-zapornye-ventili/" data-id-category="1169">Фланцевые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1176" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-zapornye-ventili/" data-id-category="1176">Муфтовые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1180" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-zapornye-ventili/" data-id-category="1180">Латунные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1183" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-zapornye-ventili/" data-id-category="1183">Стальные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1186" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silfonnye-zapornye-ventili/" data-id-category="1186">Сильфонные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1190" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovoj-zapornyj-ventil/" data-id-category="1190">Шаровые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1195" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-zapornye-ventili/" data-id-category="1195">Чугунные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1200" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodoprovodnye-zapornye-ventili/" data-id-category="1200">Водопроводные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1207" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-zapornye-ventili/" data-id-category="1207">Бронзовые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1213" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/capkovye-zapornye-ventili/" data-id-category="1213">Цапковые запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1220" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/radiatornye-zapornye-ventili/" data-id-category="1220">Радиаторные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1227" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislorodnye-zapornye-ventili/" data-id-category="1227">Кислородные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1233" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/holodilnye-zapornye-ventili/" data-id-category="1233">Холодильные запорные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1238" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapornye-ventili-dlya-manometra/" data-id-category="1238">Запорные вентили для манометра</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1244" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/privarnye-zapornye-ventili/" data-id-category="1244">Приварные запорные вентили</a>
                                    </li></ul>
                                    <a href="/catalog/zapornye-ventili/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1737" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislorodnye-ventili/" data-id-category="1737">Кислородные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="29" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglekislotnye-ventili/" data-id-category="29">Углекислотные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1831" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-ventili/" data-id-category="1831">Латунные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2070" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventili-pod-muftu/" data-id-category="2070">
                                    Вентили под муфту
                                    <svg class="icon icon_arrow-right-min" data-id-category="2070">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="86" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-muftovye-ventili/" data-id-category="86">Стальные муфтовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="112" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-muftovye-ventili/" data-id-category="112">Латунные муфтовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="126" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-muftovye-ventili/" data-id-category="126">Чугунные муфтовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="139" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/igolchatye-muftovye-ventili/" data-id-category="139">Игольчатые муфтовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="145" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-muftovye-ventili/" data-id-category="145">Проходные муфтовые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="151" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-ventili/" data-id-category="151">Муфтовые вентили</a>
                                    </li></ul>
                                    <a href="/catalog/ventili-pod-muftu/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2051" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventili-pod-flanec/" data-id-category="2051">
                                    Вентили под фланец
                                    <svg class="icon icon_arrow-right-min" data-id-category="2051">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="41" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-flancevye-ventili/" data-id-category="41">Стальные фланцевые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="47" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-flancevye-ventili/" data-id-category="47">Чугунные фланцевые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="55" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-flancevye-ventili/" data-id-category="55">Проходные фланцевые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="61" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silfonnye-flancevye-ventili/" data-id-category="61">Сильфонные фланцевые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="68" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/parovye-flancevye-ventili/" data-id-category="68">Паровые фланцевые вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="74" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-ventili/" data-id-category="74">Фланцевые вентили</a>
                                    </li></ul>
                                    <a href="/catalog/ventili-pod-flanec/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1960" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/predohranitelnye-ventili/" data-id-category="1960">Предохранительные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2007" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/protivopozharnye-ventili/" data-id-category="2007">
                                    Противопожарные вентили
                                    <svg class="icon icon_arrow-right-min" data-id-category="2007">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="206" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pozharnye-zapornye-ventili/" data-id-category="206">Запорные пожарные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="222" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-pozharnye-ventili/" data-id-category="222">Латунные пожарные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="227" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-pozharnye-ventili/" data-id-category="227">Чугунные пожарные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="231" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pozharnye-ventili/" data-id-category="231">Пожарные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="212" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/muftovye-pozharnye-ventili/" data-id-category="212">Муфтовые пожарные вентили</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="217" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglovye-pozharnye-ventili/" data-id-category="217">Угловые пожарные вентили</a>
                                    </li></ul>
                                    <a href="/catalog/protivopozharnye-ventili/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1605" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamye-ventili/" data-id-category="1605">Прямые вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1677" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reguliruyushie-ventili/" data-id-category="1677">Регулирующие вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1904" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-ventili/" data-id-category="1904">Стальные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1794" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-ventili/" data-id-category="1794">Чугунные вентили</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1525" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-ventili/" data-id-category="1525">
                                    Шаровые вентили
                                    <svg class="icon icon_arrow-right-min" data-id-category="1525">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="2062" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-ventili-dyujmovye/" data-id-category="2062">Шаровые дюймовые вентили</a>
                                    </li></ul>
                                    <a href="/catalog/sharovye-ventili/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2026" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtucernye-ventili/" data-id-category="2026">Штуцерные вентили</a>
                                </li></ul>
                                <a href="/catalog/ventili/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1616" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki/" data-id-category="1616">
                                Задвижки
                                <svg class="icon icon_arrow-right-min" data-id-category="1616">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2432" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki-s-elektroprivodom/" data-id-category="2432">Задвижки с электроприводом</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1968" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievye-zadvizhki/" data-id-category="1968">Алюминиевые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1882" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-zadvizhki/" data-id-category="1882">Бронзовые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1986" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-klinovye-zadvizhki/" data-id-category="1986">Газовые клиновые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1319" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klinovye-zadvizhki/" data-id-category="1319">
                                    Клиновые задвижки
                                    <svg class="icon icon_arrow-right-min" data-id-category="1319">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1916" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klinovye-zadvizhki-s-ruchnym-upravleniem/" data-id-category="1916">Клиновые задвижки с ручным управлением</a>
                                    </li></ul>
                                    <a href="/catalog/klinovye-zadvizhki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1759" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-zadvizhki/" data-id-category="1759">Латунные задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1703" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mezhflancevye-zadvizhki/" data-id-category="1703">Межфланцевые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1847" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mehanicheskie-zadvizhki/" data-id-category="1847">Механические задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1813" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-zadvizhki/" data-id-category="1813">Нержавеющие задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1636" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nozhevye-zadvizhki/" data-id-category="1636">Ножевые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2012" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki-pod-muftu/" data-id-category="2012">
                                    Задвижки под муфту
                                    <svg class="icon icon_arrow-right-min" data-id-category="2012">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="384" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klinovye-muftovye-zadvizhki/" data-id-category="384">Клиновые муфтовые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="388" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-muftovye-zadvizhki/" data-id-category="388">Латунные муфтовые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="453" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-muftovye-zadvizhki/" data-id-category="453">Стальные муфтовые задвижки</a>
                                    </li></ul>
                                    <a href="/catalog/zadvizhki-pod-muftu/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1942" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki-pod-flanec/" data-id-category="1942">
                                    Задвижки под фланец
                                    <svg class="icon icon_arrow-right-min" data-id-category="1942">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="357" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-flancevye-zadvizhki/" data-id-category="357">Чугунные фланцевые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="362" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-flancevye-zadvizhki/" data-id-category="362">Стальные фланцевые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="365" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klinovye-flancevye-zadvizhki/" data-id-category="365">Клиновые фланцевые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="369" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ruchnye-flancevye-zadvizhki/" data-id-category="369">Ручные фланцевые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="373" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shibernye-flancevye-zadvizhki/" data-id-category="373">Шиберные фланцевые задвижки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="378" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-zadvizhki/" data-id-category="378">Фланцевые задвижки</a>
                                    </li></ul>
                                    <a href="/catalog/zadvizhki-pod-flanec/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1544" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki-s-obrezinennym-klinom/" data-id-category="1544">Задвижки с обрезиненным клином</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="607" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-zadvizhki/" data-id-category="607">Хромоникелевые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1445" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shibernye-zadvizhki/" data-id-category="1445">Шиберные задвижки</a>
                                </li></ul>
                                <a href="/catalog/zadvizhki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1908" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zatvory/" data-id-category="1908">
                                Затворы
                                <svg class="icon icon_arrow-right-min" data-id-category="1908">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1339" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/diskovye-zatvory/" data-id-category="1339">
                                    Дисковые затворы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1339">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="292" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/diskovye-zatvory-pod-rezbu/" data-id-category="292">Дисковые затворы под резьбу</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="296" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/diskovye-trehhodovye-zatvory/" data-id-category="296">Дисковые трехходовые затворы</a>
                                    </li></ul>
                                    <a href="/catalog/diskovye-zatvory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1338" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mezhflancevye-zatvory/" data-id-category="1338">Межфланцевые затворы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1642" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-zatvory/" data-id-category="1642">Нержавеющие затворы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1708" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-zatvory/" data-id-category="1708">Стальные затворы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1783" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-zatvory/" data-id-category="1783">Титановые затворы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1411" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-zatvory/" data-id-category="1411">Фланцевые затворы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1554" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-zatvory/" data-id-category="1554">Чугунные затворы</a>
                                </li></ul>
                                <a href="/catalog/zatvory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1839" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kompensatory/" data-id-category="1839">
                                Компенсаторы
                                <svg class="icon icon_arrow-right-min" data-id-category="1839">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1373" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silfonnye-kompensatory/" data-id-category="1373">Сильфонные компенсаторы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1423" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezinovye-kompensatory/" data-id-category="1423">Резиновые компенсаторы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1531" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/osevye-kompensatory/" data-id-category="1531">Осевые компенсаторы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1662" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnikovye-kompensatory/" data-id-category="1662">Сальниковые компенсаторы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1729" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/linzovye-kompensatory/" data-id-category="1729">
                                    Линзовые компенсаторы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1729">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1104" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-linzovye-kompensatory/" data-id-category="1104">Круглые линзовые компенсаторы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1108" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-linzovye-kompensatory/" data-id-category="1108">Прямоугольные линзовые компенсаторы</a>
                                    </li></ul>
                                    <a href="/catalog/linzovye-kompensatory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1780" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-vibrovstavki/" data-id-category="1780">Фланцевые вибровставки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1825" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tkanevye-kompensatory/" data-id-category="1825">
                                    Тканевые компенсаторы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1825">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1132" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-tkanevye-kompensatory/" data-id-category="1132">Круглые тканевые компенсаторы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1137" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-tkanevye-kompensatory/" data-id-category="1137">Прямоугольные тканевые компенсаторы</a>
                                    </li></ul>
                                    <a href="/catalog/tkanevye-kompensatory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1861" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-vibrokompensatory/" data-id-category="1861">Фланцевые виброкомпенсаторы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1912" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kompensatory-dlya-sistem-otopleniya/" data-id-category="1912">Компенсаторы для систем отопления</a>
                                </li></ul>
                                <a href="/catalog/kompensatory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/zapornaya-truboprovodnaya-armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1321" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubnye-soedineniya/" data-id-category="1321">
                            Соединительная арматура
                            <svg class="icon icon_arrow-right-min" data-id-category="1321">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1858" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/probki/" data-id-category="1858">Пробки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1782" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty/" data-id-category="1782">
                                Муфты
                                <svg class="icon icon_arrow-right-min" data-id-category="1782">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2127" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-elektrosvarnye/" data-id-category="2127">
                                    Муфты электросварные
                                    <svg class="icon icon_arrow-right-min" data-id-category="2127">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="850" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-elektrosvarnye-pe-100/" data-id-category="850">Муфты электросварные ПЭ 100</a>
                                    </li></ul>
                                    <a href="/catalog/mufty-elektrosvarnye/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="776" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-pnd-kompressionnye/" data-id-category="776">Муфты ПНД компрессионные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="639" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-mufty/" data-id-category="639">Хромоникелевые муфты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1366" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-mufty/" data-id-category="1366">Стальные муфты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1498" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-mufty/" data-id-category="1498">Медные муфты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1580" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-mufty/" data-id-category="1580">Нержавеющие муфты</a>
                                </li></ul>
                                <a href="/catalog/mufty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1826" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki/" data-id-category="1826">
                                Заглушки
                                <svg class="icon icon_arrow-right-min" data-id-category="1826">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="645" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-zaglushki/" data-id-category="645">Хромоникелевые заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="792" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-pnd-kompressionnye/" data-id-category="792">Заглушки ПНД компрессионные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1383" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-zaglushki/" data-id-category="1383">Стальные заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1493" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-zaglushki/" data-id-category="1493">Фланцевые заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1592" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ellipticheskie-zaglushki/" data-id-category="1592">Эллиптические заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1664" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/povorotnye-zaglushki/" data-id-category="1664">Поворотные заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1734" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-zaglushki/" data-id-category="1734">Нержавеющие заглушки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1786" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-zaglushki/" data-id-category="1786">Медные заглушки</a>
                                </li></ul>
                                <a href="/catalog/zaglushki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2068" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vorotniki/" data-id-category="2068">
                                Воротники
                                <svg class="icon icon_arrow-right-min" data-id-category="2068">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1368" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-vorotniki/" data-id-category="1368">Стальные воротники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1484" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-vorotniki/" data-id-category="1484">Нержавеющие воротники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1560" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-vorotniki/" data-id-category="1560">Хромоникелевые воротники</a>
                                </li></ul>
                                <a href="/catalog/vorotniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1730" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki/" data-id-category="1730">
                                Тройники
                                <svg class="icon icon_arrow-right-min" data-id-category="1730">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="629" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-trojniki/" data-id-category="629">Хромоникелевые тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1381" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-trojniki/" data-id-category="1381">Стальные тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1495" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-trojniki/" data-id-category="1495">Оцинкованные тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1588" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-trojniki/" data-id-category="1588">Нержавеющие тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1666" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-trojniki/" data-id-category="1666">Медные тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1717" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-trojniki/" data-id-category="1717">Медно-никелевые тройники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="834" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-pnd-kompressionnye/" data-id-category="834">Тройники ПНД компрессионные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="855" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-elektrosvarnye-pe-100/" data-id-category="855">Тройники электросварные ПЭ 100</a>
                                </li></ul>
                                <a href="/catalog/trojniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1371" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody/" data-id-category="1371">
                                Отводы
                                <svg class="icon icon_arrow-right-min" data-id-category="1371">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="623" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-otvody/" data-id-category="623">Хромоникелевые отводы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1372" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-otvody/" data-id-category="1372">
                                    Стальные отводы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1372">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="2160" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salnoj-otvod-oss/" data-id-category="2160">ОСС стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="398" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krutoizognutye-otvody/" data-id-category="398">Крутоизогнутые стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="404" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-oksh/" data-id-category="404">ОКШ стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="411" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnye-sektornye-otvody/" data-id-category="411">Секторные сварные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="417" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-gnutye-otvody/" data-id-category="417">Гнутые стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="983" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglerodistye-otvody/" data-id-category="983">Углеродистые стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="989" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnye-otvody/" data-id-category="989">Сварные стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="996" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezbovye-otvody/" data-id-category="996">Резьбовые стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1002" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/naruzhnye-otvody/" data-id-category="1002">Наружные стальные отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1007" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/besshovnye-otvody/" data-id-category="1007">Бесшовные стальные отводы</a>
                                    </li></ul>
                                    <a href="/catalog/stalnye-otvody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1488" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-otvody/" data-id-category="1488">
                                    Нержавеющие отводы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1488">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="430" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-gnutye-otvody/" data-id-category="430">Гнутые нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="436" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-krutoizognutye-otvody/" data-id-category="436">Крутоизогнутые нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="441" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-otvody-oksh/" data-id-category="441">ОКШ нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="447" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-svarnye-otvody/" data-id-category="447">Сварные нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1013" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-besshovnye-otvody/" data-id-category="1013">Бесшовные нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1021" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-rezbovye-otvody/" data-id-category="1021">Резьбовые нержавеющие отводы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1026" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-naruzhnye-otvody/" data-id-category="1026">Наружные нержавеющие отводы</a>
                                    </li></ul>
                                    <a href="/catalog/nerzhaveyushie-otvody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1596" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-otvody/" data-id-category="1596">Медные отводы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1656" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-otvody/" data-id-category="1656">Никелевые отводы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1715" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-otvody/" data-id-category="1715">Медно-никелевые отводы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="842" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-pnd-kompressionnye/" data-id-category="842">Отводы ПНД компрессионные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="864" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-elektrosvarnye-pe-100/" data-id-category="864">Отводы электросварные ПЭ 100</a>
                                </li></ul>
                                <a href="/catalog/otvody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1481" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancy/" data-id-category="1481">
                                Фланцы
                                <svg class="icon icon_arrow-right-min" data-id-category="1481">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="588" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-flancy/" data-id-category="588">Хромоникелевые фланцы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1384" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-flancy/" data-id-category="1384">Стальные фланцы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1474" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-flancy/" data-id-category="1474">Нержавеющие фланцы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1578" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevye-flancy/" data-id-category="1578">Никелевые фланцы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="819" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancy-dlya-pnd-trub/" data-id-category="819">Фланцы для ПНД труб</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="879" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancy-pod-vtulki-pe-100/" data-id-category="879">Фланцы под втулки ПЭ 100</a>
                                </li></ul>
                                <a href="/catalog/flancy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1897" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krestoviny/" data-id-category="1897">Крестовины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1599" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uplotnitelnye-kolca/" data-id-category="1599">Уплотнительные кольца</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1974" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dnisha/" data-id-category="1974">
                                Днища
                                <svg class="icon icon_arrow-right-min" data-id-category="1974">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2567" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievoe-dnishe/" data-id-category="2567">Алюминиевые днища</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="670" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-dnisha/" data-id-category="670">Нержавеющие днища</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1970" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-dnisha/" data-id-category="1970">Стальные днища</a>
                                </li></ul>
                                <a href="/catalog/dnisha/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1955" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nippeli/" data-id-category="1955">
                                Ниппели
                                <svg class="icon icon_arrow-right-min" data-id-category="1955">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="658" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-nippeli/" data-id-category="658">Хромоникелевые ниппели</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1385" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-nippeli/" data-id-category="1385">Нержавеющие ниппели</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="873" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nippeli-pnd/" data-id-category="873">Ниппели ПНД</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1494" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-nippeli/" data-id-category="1494">Стальные ниппели</a>
                                </li></ul>
                                <a href="/catalog/nippeli/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2058" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/futorki/" data-id-category="2058">Футорки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1975" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bobyshki/" data-id-category="1975">
                                Бобышки
                                <svg class="icon icon_arrow-right-min" data-id-category="1975">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1388" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-bobyshki/" data-id-category="1388">Стальные бобышки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1497" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-bobyshki/" data-id-category="1497">Нержавеющие бобышки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1559" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-bobyshki/" data-id-category="1559">Хромоникелевые бобышки</a>
                                </li></ul>
                                <a href="/catalog/bobyshki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1663" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody/" data-id-category="1663">
                                Переходы для труб
                                <svg class="icon icon_arrow-right-min" data-id-category="1663">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="633" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-perehody/" data-id-category="633">Хромоникелевые переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1375" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-perehody/" data-id-category="1375">Стальные переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1490" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-perehody/" data-id-category="1490">Оцинкованные переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1590" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-perehody/" data-id-category="1590">Нержавеющие переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1667" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-perehody/" data-id-category="1667">Медные переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1716" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-perehody/" data-id-category="1716">Медно-никелевые переходы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="860" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-elektrosvarnye-pe-100/" data-id-category="860">Переходы электросварные ПЭ 100</a>
                                </li></ul>
                                <a href="/catalog/perehody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1591" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polumufty/" data-id-category="1591">
                                Полумуфты
                                <svg class="icon icon_arrow-right-min" data-id-category="1591">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1379" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-polumufty/" data-id-category="1379">Стальные полумуфты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1491" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-polumufty/" data-id-category="1491">Нержавеющие полумуфты</a>
                                </li></ul>
                                <a href="/catalog/polumufty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1927" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/privarnye-kolca/" data-id-category="1927">
                                Приварные кольца
                                <svg class="icon icon_arrow-right-min" data-id-category="1927">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="653" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromonikelevye-privarnye-kolca/" data-id-category="653">Хромоникелевые приварные кольца</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1367" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-privarnye-kolca/" data-id-category="1367">Стальные приварные кольца</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1483" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-privarnye-kolca/" data-id-category="1483">Нержавеющие приварные кольца</a>
                                </li></ul>
                                <a href="/catalog/privarnye-kolca/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2037" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konicheskie-patrubki/" data-id-category="2037">Конические патрубки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="846" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sedlovye-vrezki-pnd-kompressionnye/" data-id-category="846">Седловые врезки ПНД компрессионные</a>
                            </li></ul>
                            <a href="/catalog/trubnye-soedineniya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="554" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truboprovodnaya-armatura-v-vus-izolyacii/" data-id-category="554">
                            Трубопроводная арматура в ВУС изоляции
                            <svg class="icon icon_arrow-right-min" data-id-category="554">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="579" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-v-vus-izolyacii/" data-id-category="579">Тройники в ВУС изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="567" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-sektornye-svarnye-v-vus-izolyacii/" data-id-category="567">Отводы секторные сварные в ВУС изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="574" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-svarnye-v-vus-izolyacii/" data-id-category="574">Переходы сварные в ВУС изоляции</a>
                            </li></ul>
                            <a href="/catalog/truboprovodnaya-armatura-v-vus-izolyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="397" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truboprovodnaya-armatura-v-ppm-izolyacii/" data-id-category="397">
                            Трубопроводная арматура в ППМ изоляции
                            <svg class="icon icon_arrow-right-min" data-id-category="397">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="429" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-v-ppm-izolyacii/" data-id-category="429">Отводы в ППМ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="461" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/opory-v-ppm-izolyacii/" data-id-category="461">Опоры в ППМ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="446" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany-v-ppm-izolyacii/" data-id-category="446">Шаровые краны в ППМ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="440" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-v-ppm-izolyacii/" data-id-category="440">Тройники в ППМ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="435" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-v-ppm-izolyacii/" data-id-category="435">Переходы в ППМ изоляции</a>
                            </li></ul>
                            <a href="/catalog/truboprovodnaya-armatura-v-ppm-izolyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="169" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truboprovodnaya-armatura-v-ppu-izolyacii/" data-id-category="169">
                            Трубопроводная арматура в ППУ изоляции
                            <svg class="icon icon_arrow-right-min" data-id-category="169">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="309" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/opory-v-ppu-izolyacii/" data-id-category="309">Опоры ППУ в изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="306" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-v-ppu-izolyacii/" data-id-category="306">Отвод в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="308" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-v-ppu-izolyacii/" data-id-category="308">Заглушки в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1117" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silfonnye-kompensatory-v-ppu-izolyacii/" data-id-category="1117">Сильфонные компенсаторы в изоляции ППУ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="325" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-sharovye-v-ppu-izolyacii/" data-id-category="325">
                                Краны шаровые в ППУ изоляции
                                <svg class="icon icon_arrow-right-min" data-id-category="325">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2158" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharovye-krany-s-vozdushnikom/" data-id-category="2158">Шаровые краны с воздушником</a>
                                </li></ul>
                                <a href="/catalog/krany-sharovye-v-ppu-izolyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="298" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-v-ppu-izolyacii/" data-id-category="298">Тройники в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="177" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-v-ppu-izolyacii/" data-id-category="177">Переход в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="293" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojnikovoe-otvetvlenie-v-ppu-izolyacii/" data-id-category="293">Тройниковое ответвление в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="304" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/parallelnyj-trojniki-v-ppu-izolyacii/" data-id-category="304">Параллельный тройник в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="301" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-s-sharovym-kranom-vozdushnika-v-ppu-izolyacii/" data-id-category="301">Тройник с шаровым краном воздушника в ППУ изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2157" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/z-obraznye-elementy/" data-id-category="2157">Z-образные элементы в ППУ изоляции</a>
                            </li></ul>
                            <a href="/catalog/truboprovodnaya-armatura-v-ppu-izolyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="531" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truboprovodnaya-armatura-v-cpp-izolyacii/" data-id-category="531">
                            Трубопроводная арматура в ЦПП изоляции
                            <svg class="icon icon_arrow-right-min" data-id-category="531">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="536" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-v-cpp-izolyacii/" data-id-category="536">Отводы в ЦПП изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="541" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-v-cpp-izolyacii/" data-id-category="541">Тройники в ЦПП изоляции</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="547" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-v-cpp-izolyacii/" data-id-category="547">Переходы в ЦПП изоляции</a>
                            </li></ul>
                            <a href="/catalog/truboprovodnaya-armatura-v-cpp-izolyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="584" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truboprovodnaya-armatura-s-epoksidnym-pokrytiem/" data-id-category="584">
                            Трубопроводная арматура с эпоксидным покрытием
                            <svg class="icon icon_arrow-right-min" data-id-category="584">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="596" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-s-epoksidnym-pokrytiem/" data-id-category="596">Отводы с эпоксидным покрытием</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="589" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-s-epoksidnym-pokrytiem/" data-id-category="589">Тройники с эпоксидным покрытием</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="603" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-s-epoksidnym-pokrytiem/" data-id-category="603">Переходы с эпоксидным покрытием</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="615" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-s-epoksidnym-pokrytiem/" data-id-category="615">Заглушки с эпоксидным покрытием</a>
                            </li></ul>
                            <a href="/catalog/truboprovodnaya-armatura-s-epoksidnym-pokrytiem/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2627" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnaya-armatura/" data-id-category="2627">
                            Чугунная арматура
                            <svg class="icon icon_arrow-right-min" data-id-category="2627">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2173" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-k-trubam-sml/" data-id-category="2173">
                                Фасонные части к трубам SML
                                <svg class="icon icon_arrow-right-min" data-id-category="2173">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2183" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-trojniki-sml/" data-id-category="2183">Тройники чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2174" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-otvody-sml/" data-id-category="2174">Отводы чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2190" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-perehody-sml/" data-id-category="2190">Переходы чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2184" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-zaglushki-sml/" data-id-category="2184">Заглушки чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2187" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-krestoviny-sml/" data-id-category="2187">Крестовины чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2181" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-revizii-s-krugloj-kryshkoj-sml/" data-id-category="2181">Ревизии с круглой крышкой чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2180" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-opornye-truby-sml/" data-id-category="2180">Трубы опорные чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2188" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-krestoviny-dvuhloskostnye-sml/" data-id-category="2188">Крестовины двухплоскостные чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2178" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-dvojnye-kolena-sml/" data-id-category="2178">Колена двойные чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2179" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-opornye-kolca-sml/" data-id-category="2179">Кольца опорные чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2185" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-flancevye-perehodniki-sml/" data-id-category="2185">Переходники фланцевые чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2175" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-otvody-s-udlinennoj-storonoj-sml/" data-id-category="2175">Отводы с удлиненной стороной чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2176" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-s-otvody-sml/" data-id-category="2176">S-отводы чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2177" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-otvody-s-uspokoitelnym-uchastkom-sml/" data-id-category="2177">Отводы с успокоительным участком чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2182" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-revizii-s-kvadratnoj-kryshkoj-sml/" data-id-category="2182">Ревизии с квадратной крышкой чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2186" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-germetichnye-zaglushki-sml/" data-id-category="2186">Заглушки герметичные чугунные SML</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2189" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-kanalizacionnye-sifonnye-zatvory-sml/" data-id-category="2189">Затворы сифонные канализационные чугунные SML</a>
                                </li></ul>
                                <a href="/catalog/fasonnye-chasti-k-trubam-sml/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2164" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-k-trubam-vchgsh/" data-id-category="2164">
                                Фасонные части к трубам ВЧШГ
                                <svg class="icon icon_arrow-right-min" data-id-category="2164">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2165" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-vchshg/" data-id-category="2165">Тройники ВЧШГ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2172" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvojnye-rastruby/" data-id-category="2172">Двойные раструбы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2167" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-vchshg/" data-id-category="2167">Переходы ВЧШГ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2171" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-vchshg/" data-id-category="2171">Отводы ВЧШГ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2169" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pozharnye-podstavki-vchshg/" data-id-category="2169">Пожарные подставки ВЧШГ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2170" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/koleno-vchshg/" data-id-category="2170">Колено ВЧШГ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2166" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krestoviny-vchshg/" data-id-category="2166">Крестовины ВЧШГ</a>
                                </li></ul>
                                <a href="/catalog/fasonnye-chasti-k-trubam-vchgsh/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2191" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-k-trubam-chk/" data-id-category="2191">
                                Фасонные части к трубам ЧК
                                <svg class="icon icon_arrow-right-min" data-id-category="2191">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2192" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-krestoviny-chk/" data-id-category="2192">Чугунные крестовины ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2194" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-revizii-chk/" data-id-category="2194">Ревизии чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2197" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-otvody-chk/" data-id-category="2197">Отводы чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2195" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-trapy-chk/" data-id-category="2195">Трапы чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2200" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-trojniki-chk/" data-id-category="2200">Тройники чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2193" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-mufty-chk/" data-id-category="2193">Муфты чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2196" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-kolena-chk/" data-id-category="2196">Колена чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2198" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-otstupy-chk/" data-id-category="2198">Отступы чугунные ЧК</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2199" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-patrubki-chk/" data-id-category="2199">Патрубки чугунные ЧК</a>
                                </li></ul>
                                <a href="/catalog/fasonnye-chasti-k-trubam-chk/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/chugunnaya-armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/truboprovodnaya-armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1610">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/teploizolyacii-dlya-trub/" data-id-category="1610">
                        Теплоизоляция для труб
                        <svg class="icon icon_arrow-right-min" data-id-category="1610">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1512" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mineralovatnye-cilindry/" data-id-category="1512">
                            Минераловатные цилиндры
                            <svg class="icon icon_arrow-right-min" data-id-category="1512">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1285" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-truboprovoda-negoryuchie-kashirovannye/" data-id-category="1285">
                                Фасонные части трубопровода негорючие кашированные
                                <svg class="icon icon_arrow-right-min" data-id-category="1285">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="286" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/negoryuchie-kashirovannye-cilindry/" data-id-category="286">Негорючие кашированные цилиндры</a>
                                </li></ul>
                                <a href="/catalog/fasonnye-chasti-truboprovoda-negoryuchie-kashirovannye/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1401" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-truboprovoda-bez-pokrytiya/" data-id-category="1401">
                                Фасонные части трубопровода без покрытия
                                <svg class="icon icon_arrow-right-min" data-id-category="1401">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="249" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-bez-pokrytiya/" data-id-category="249">Отводы без покрытия</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="253" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-bez-pokrytiya/" data-id-category="253">Тройники без покрытия</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="257" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cilindry-bez-pokrytiya/" data-id-category="257">Цилиндры без покрытия</a>
                                </li></ul>
                                <a href="/catalog/fasonnye-chasti-truboprovoda-bez-pokrytiya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/mineralovatnye-cilindry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1631" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/okozhushka/" data-id-category="1631">
                            Окожушка
                            <svg class="icon icon_arrow-right-min" data-id-category="1631">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1450" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kozhuhi-iz-nerzhaveyushej-stali/" data-id-category="1450">
                                Кожухи из нержавеющей стали
                                <svg class="icon icon_arrow-right-min" data-id-category="1450">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="561" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vrezki-kozhuha-iz-nerzhaveyushej-stali/" data-id-category="561">Врезки кожуха из нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="581" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-kozhuha-iz-nerzhaveyushej-stali/" data-id-category="581">Заглушки кожуха из нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="585" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-kozhuha-iz-nerzhaveyushej-stali/" data-id-category="585">Отводы кожуха из нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="592" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-kozhuha-iz-nerzhaveyushej-stali/" data-id-category="592">Переходы кожуха из нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="605" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-kozhuha-iz-nerzhaveyushej-stali/" data-id-category="605">Тройники кожуха из нержавеющей стали</a>
                                </li></ul>
                                <a href="/catalog/kozhuhi-iz-nerzhaveyushej-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1545" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kozhuhi-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="1545">
                                Кожухи из зеркальной нержавеющей стали
                                <svg class="icon icon_arrow-right-min" data-id-category="1545">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="443" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vrezki-kozhuha-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="443">Врезки кожуха из зеркальной нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="452" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-kozhuha-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="452">Заглушки кожуха из зеркальной нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="459" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otvody-kozhuha-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="459">Отводы кожуха из зеркальной нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="463" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehody-kozhuha-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="463">Переходы кожуха из зеркальной нержавеющей стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="479" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-kozhuha-iz-zerkalnoj-nerzhaveyushej-stali/" data-id-category="479">Тройники кожуха из зеркальной нержавеющей стали</a>
                                </li></ul>
                                <a href="/catalog/kozhuhi-iz-zerkalnoj-nerzhaveyushej-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/okozhushka/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/teploizolyacii-dlya-trub/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2045">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/metizy-i-krepezh/" data-id-category="2045">
                        Метизы и крепеж
                        <svg class="icon icon_arrow-right-min" data-id-category="2045">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="932" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolty/" data-id-category="932">
                            Болты
                            <svg class="icon icon_arrow-right-min" data-id-category="932">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1017" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-bolty/" data-id-category="1017">Шестигранные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1044" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mebelnye-bolty/" data-id-category="1044">Мебельные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1039" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokoprochnye-bolty/" data-id-category="1039">Высокопрочные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1029" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otkidnye-bolty/" data-id-category="1029">Откидные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1055" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-bolty/" data-id-category="1055">Стальные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1065" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-bolty/" data-id-category="1065">Медные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1023" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/usilennye-bolty/" data-id-category="1023">Усиленные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1061" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-bolty/" data-id-category="1061">Латунные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1050" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lemeshnye-bolty/" data-id-category="1050">Лемешные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1034" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-shestigrannye-bolty/" data-id-category="1034">Нержавеющие шестигранные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1221" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolty-skoby-u-obraznye/" data-id-category="1221">Болты-скобы U-образные</a>
                            </li></ul>
                            <a href="/catalog/bolty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1205" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki/" data-id-category="1205">
                            Гайки
                            <svg class="icon icon_arrow-right-min" data-id-category="1205">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="15" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki/" data-id-category="15">Шестигранные гайки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="9" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-barashki/" data-id-category="9">Гайки-барашки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1217" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolpachkovye-gajki/" data-id-category="1217">Колпачковые гайки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1259" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokoprochnye-gajki/" data-id-category="1259">Высокопрочные гайки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1224" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-gajki-shlicevye/" data-id-category="1224">Круглые гайки шлицевые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1163" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-normalnye/" data-id-category="1163">Шестигранные гайки нормальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="39" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-dlya-flancevyh-soedinenij/" data-id-category="39">Гайки для фланцевых соединений</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="21" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-nizkie/" data-id-category="21">Шестигранные гайки низкие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1147" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-vysokie/" data-id-category="1147">Шестигранные гайки высокие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="34" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-koronchatye/" data-id-category="34">Шестигранные гайки корончатые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1211" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-bolshogo-razmera/" data-id-category="1211">Гайки большого размера</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="27" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-proreznye/" data-id-category="27">Шестигранные гайки прорезные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1230" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-s-kontryashim-vintom/" data-id-category="1230">Гайки с контрящим винтом</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shestigrannye-gajki-s-umenshennym-razmerom-pod-klyuch/" data-id-category="2">Шестигранные гайки с уменьшенным размером "под ключ"</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1247" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-s-rukoyatkoj-dlya-stanochnyh-prisposoblenij/" data-id-category="1247">Гайки с рукояткой для станочных приспособлений</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="6" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shlicevye-nakidnye-gajki/" data-id-category="6">Шлицевые накидные гайки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1241" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-s-trapeceidalnoj-rezboj-s-burtikom/" data-id-category="1241">Гайки с трапецеидальной резьбой с буртиком</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1236" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokie-gajki-s-trapeceidalnoj-rezboj/" data-id-category="1236">Высокие гайки с трапецеидальной резьбой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1253" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajki-s-otverstiem-pod-rukoyatku-dlya-stanochnyh-prisposoblenij/" data-id-category="1253">Гайки с отверстием под рукоятку для станочных приспособлений</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1264" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokoprochnye-shestigrannye-gajki-s-uvelichennym-razmerom/" data-id-category="1264">Высокопрочные шестигранные гайки с увеличенным размером</a>
                            </li></ul>
                            <a href="/catalog/gajki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1516" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki/" data-id-category="1516">
                            Проволоки
                            <svg class="icon icon_arrow-right-min" data-id-category="1516">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="302" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-provoloki/" data-id-category="302">Стальные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="288" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vyazalnye-provoloki/" data-id-category="288">Вязальные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="284" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-provoloki/" data-id-category="284">
                                Проволоки нержавеющие
                                <svg class="icon icon_arrow-right-min" data-id-category="284">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="949" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pruzhinnye-provoloki/" data-id-category="949">Нержавеющие пружинные проволоки</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-provoloki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1003" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnitnye-provoloki/" data-id-category="1003">Магнитные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="299" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nizkouglerodistye-provoloki/" data-id-category="299">Низкоуглеродистые проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="307" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uglerodistye-provoloki/" data-id-category="307">Углеродистые проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="954" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-pruzhinnye-provoloki/" data-id-category="954">Пружинные стальные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="305" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provoloki-s-polimernym-pokrytiem/" data-id-category="305">Проволоки с полимерным покрытием</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="294" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kalibrovannye-provoloki/" data-id-category="294">Калиброванные проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="750" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevye-provoloki/" data-id-category="750">Медно-никелевые проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="290" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/igolnye-provoloki/" data-id-category="290">Игольные проволоки</a>
                            </li></ul>
                            <a href="/catalog/provoloki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1084" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shajby/" data-id-category="1084">
                            Шайбы
                            <svg class="icon icon_arrow-right-min" data-id-category="1084">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1128" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pruzhinnye-shajby/" data-id-category="1128">Пружинные шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1103" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ploskie-shajby/" data-id-category="1103">Плоские шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1130" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/uvelichennye-shajby/" data-id-category="1130">Увеличенные шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1100" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kosye-shajby/" data-id-category="1100">Косые шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1092" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-mnogolapchatye-shajby/" data-id-category="1092">Стопорные многолапчатые шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1124" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vysokoprochnye-shajby/" data-id-category="1124">Высокопрочные шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1111" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konicheskie-shajby/" data-id-category="1111">Конические шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1088" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/umenshennye-shajby/" data-id-category="1088">Уменьшенные шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1135" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shajby-dlya-flancevyh-soedinenij/" data-id-category="1135">Шайбы для фланцевых соединений</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1096" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-shajby-s-vnutrennimi-zubyami/" data-id-category="1096">Стопорные шайбы с внутренними зубьями</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1107" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/upornye-bystrosemnye-shajby/" data-id-category="1107">Упорные быстросъемные шайбы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1116" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-shajby-s-lapkoj-i-nosikom/" data-id-category="1116">Стопорные шайбы с лапкой и носиком</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1120" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-shajby-s-lapkoj-umenshennye/" data-id-category="1120">Стопорные шайбы с лапкой уменьшенные</a>
                            </li></ul>
                            <a href="/catalog/shajby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1141" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty/" data-id-category="1141">
                            Винты
                            <svg class="icon icon_arrow-right-min" data-id-category="1141">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1198" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-potajnoj-golovkoj/" data-id-category="1198">Винты с потайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1189" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-polukrugloj-golovkoj/" data-id-category="1189">Винты с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1185" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-cilindricheskoj-golovkoj/" data-id-category="1185">Винты с цилиндрической головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1165" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-cilindricheskoj-golovkoj-i-shestigrannym-uglubleniem/" data-id-category="1165">Винты с цилиндрической головкой и шестигранным углублением</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1194" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-polupotajnoj-golovkoj/" data-id-category="1194">Винты с полупотайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1155" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samonarezayushie-vinty-s-polukrugloj-golovkoj/" data-id-category="1155">Самонарезающие винты с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1179" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ustanovochnye-vinty-s-ploskim-koncom/" data-id-category="1179">Установочные винты с плоским концом</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1168" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vinty-s-burtikom/" data-id-category="1168">Винты с буртиком</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1182" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ustanovochnye-vinty-s-konicheskim-koncom/" data-id-category="1182">Установочные винты с коническим концом</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1145" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nevypadayushie-vinty-s-cilindricheskoj-golovkoj/" data-id-category="1145">Невыпадающие винты с цилиндрической головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1159" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ustanovochnye-vinty-s-ploskim-koncom-i-shestigrannym-uglubleniem/" data-id-category="1159">Установочные винты с плоским концом и шестигранным углублением</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1162" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ustanovochnye-vinty-s-cilindricheskim-koncom-i-shestigrannym-uglubleniem/" data-id-category="1162">Установочные винты с цилиндрическим концом и шестигранным углублением</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1175" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nazhimnye-vinty-s-cilindricheskim-koncom/" data-id-category="1175">Нажимные винты с цилиндрическим концом</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1150" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nevypadayushie-vinty-s-polukrugloj-golovkoj/" data-id-category="1150">Невыпадающие винты с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1172" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nazhimnye-vinty-s-zvezdoobraznoj-rukoyatkoj/" data-id-category="1172">Нажимные винты с звездообразной рукояткой</a>
                            </li></ul>
                            <a href="/catalog/vinty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2029" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vtulki/" data-id-category="2029">
                            Втулки
                            <svg class="icon icon_arrow-right-min" data-id-category="2029">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1008" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-vtulki/" data-id-category="1008">Стальные втулки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1079" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-vtulki/" data-id-category="1079">Нержавеющие втулки</a>
                            </li></ul>
                            <a href="/catalog/vtulki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1261" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/homuty/" data-id-category="1261">Хомуты</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1070" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpilki/" data-id-category="1070">
                            Шпильки
                            <svg class="icon icon_arrow-right-min" data-id-category="1070">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1081" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpilki-dlya-detalej-s-gladkimi-otverstiyami/" data-id-category="1081">Шпильки для деталей с гладкими отверстиями</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1074" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpilki-s-linzovym-uplotneniem/" data-id-category="1074">Шпильки с линзовым уплотнением</a>
                            </li></ul>
                            <a href="/catalog/shpilki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="73" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy/" data-id-category="73">
                            Саморезы
                            <svg class="icon icon_arrow-right-min" data-id-category="73">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="104" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-press-shajboj/" data-id-category="104">Саморезы с пресс-шайбой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="84" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-potajnoj-golovkoj/" data-id-category="84">Саморезы с потайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="98" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-shestigrannoj-golovkoj/" data-id-category="98">Саморезы с шестигранной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="91" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-polukrugloj-golovkoj/" data-id-category="91">Саморезы с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="79" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-polupotajnoj-golovkoj/" data-id-category="79">Саморезы с полупотайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="124" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-potajnoj-golovkoj-i-burom/" data-id-category="124">Саморезы с потайной головкой и буром</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="130" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-pryamym-shlicem/" data-id-category="130">Саморезы с прямым шлицем</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="110" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-shestigrannoj-golovkoj-i-burom/" data-id-category="110">Саморезы с шестигранной головкой и буром</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="118" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-polukrugloj-golovkoj-i-burom/" data-id-category="118">Саморезы с полукруглой головкой и буром</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="137" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-potajnoj-golovkoj-i-pryamym-shlicem/" data-id-category="137">Саморезы с потайной головкой и прямым шлицем</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="143" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samorezy-s-polupotajnoj-golovkoj-i-pryamym-shlicem/" data-id-category="143">Саморезы с полупотайной головкой и прямым шлицем</a>
                            </li></ul>
                            <a href="/catalog/samorezy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2128" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ankery/" data-id-category="2128">
                            Анкеры
                            <svg class="icon icon_arrow-right-min" data-id-category="2128">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2134" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ankernyj-bolt-s-kolcom/" data-id-category="2134">Анкерные болты с кольцом</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2132" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ankernyj-bolt-s-kryukom/" data-id-category="2132">Анкерные болты с крюком</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2130" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/raspornyj-ankernyj-bolt/" data-id-category="2130">Распорные анкерные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2131" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dvuhraspornyj-ankernyj-bolt/" data-id-category="2131">Двухраспорные анкерные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2129" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/anker-t-obraznyj/" data-id-category="2129">Анкеры т-образные</a>
                            </li></ul>
                            <a href="/catalog/ankery/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1584" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stropy/" data-id-category="1584">
                            Стропы
                            <svg class="icon icon_arrow-right-min" data-id-category="1584">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1370" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-petlevye-stropy/" data-id-category="1370">Канатные петлевые стропы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1485" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnaya-vetv/" data-id-category="1485">Канатная ветвь</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1587" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-chetyrehvetvevye-stropy/" data-id-category="1587">Канатные четырехветвевые стропы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1659" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zamki-smalya/" data-id-category="1659">Замок смаля</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1779" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-kolcevye-stropy/" data-id-category="1779">Канатные кольцевые стропы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1823" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-odnovetvevye-stropy/" data-id-category="1823">Канатные одноветвевые стропы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1727" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-dvuhvetvevye-stropy/" data-id-category="1727">Канатные двухветвевые стропы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1860" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanatnye-trehvetvevye-stropy/" data-id-category="1860">Канатные трехветвевые стропы</a>
                            </li></ul>
                            <a href="/catalog/stropy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1725" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kanaty/" data-id-category="1725">
                            Стальные канаты
                            <svg class="icon icon_arrow-right-min" data-id-category="1725">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2661" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanat-ocinkovannyj/" data-id-category="2661">Канаты оцинкованные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2694" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tros-ocinkovannyj/" data-id-category="2694">Трос оцинкованный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="841" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kanaty/" data-id-category="841">Нержавеющие канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1726" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-grozozashitnye-trosy/" data-id-category="1726">Стальные грозозащитные тросы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1821" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-zakrytye-kanaty/" data-id-category="1821">Стальные закрытые канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1776" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-talevye-kanaty/" data-id-category="1776">Стальные талевые канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1954" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kanaty-dlya-ekskavatorov/" data-id-category="1954">Стальные канаты для экскаваторов</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1658" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanaty-trojnoj-svivki/" data-id-category="1658">Канаты тройной свивки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1480" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanaty-odinarnoj-svivki/" data-id-category="1480">Канаты одинарной свивки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1857" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-shahtnye-kanaty/" data-id-category="1857">Стальные шахтные канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1928" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kranovye-kanaty/" data-id-category="1928">Стальные крановые канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1892" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-liftovye-kanaty/" data-id-category="1892">Стальные лифтовые канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1583" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-ploskie-kanaty/" data-id-category="1583">Стальные плоские канаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1980" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kanaty-dlya-dorozhnyh-mashin/" data-id-category="1980">Стальные канаты для дорожных машин</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2001" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kanaty-tyagovye-dlya-podvesnyh-dorog/" data-id-category="2001">Стальные канаты тяговые для подвесных дорог</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1365" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanaty-dvojnoj-svivki/" data-id-category="1365">Канаты двойной свивки</a>
                            </li></ul>
                            <a href="/catalog/stalnye-kanaty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="45" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaklepki/" data-id-category="45">
                            Заклепки
                            <svg class="icon icon_arrow-right-min" data-id-category="45">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="53" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaklepki-s-polukrugloj-golovkoj/" data-id-category="53">Заклепки с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="59" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaklepki-s-potajnoj-golovkoj/" data-id-category="59">Заклепки с потайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="67" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaklepki-s-ploskoj-golovkoj/" data-id-category="67">Заклепки с плоской головкой</a>
                            </li></ul>
                            <a href="/catalog/zaklepki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="189" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shurupy/" data-id-category="189">
                            Шурупы
                            <svg class="icon icon_arrow-right-min" data-id-category="189">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="209" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shurupy-s-shestigrannoj-golovkoj/" data-id-category="209">Шурупы с шестигранной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="200" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shurupy-s-potajnoj-golovkoj/" data-id-category="200">Шурупы с потайной головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="195" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shurupy-s-polukrugloj-golovkoj/" data-id-category="195">Шурупы с полукруглой головкой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="204" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shurupy-s-polupotajnoj-golovkoj/" data-id-category="204">Шурупы с полупотайной головкой</a>
                            </li></ul>
                            <a href="/catalog/shurupy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="171" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtifty/" data-id-category="171">
                            Штифты
                            <svg class="icon icon_arrow-right-min" data-id-category="171">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="184" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cilindricheskie-shtifty/" data-id-category="184">Цилиндрические штифты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="174" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pruzhinnye-shtifty/" data-id-category="174">Пружинные штифты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="179" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konicheskie-shtifty/" data-id-category="179">Конические штифты</a>
                            </li></ul>
                            <a href="/catalog/shtifty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="220" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolca-stopornye/" data-id-category="220">
                            Кольца стопорные
                            <svg class="icon icon_arrow-right-min" data-id-category="220">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="225" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-pruzhinnye-kolca-naruzhnye-koncentricheskie/" data-id-category="225">Стопорные пружинные кольца наружные концентрические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="230" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-pruzhinnye-kolca-vnutrennie-koncentricheskie/" data-id-category="230">Стопорные пружинные кольца внутренние концентрические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="234" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-pruzhinnye-kolca-naruzhnye-ekscentricheskie/" data-id-category="234">Стопорные пружинные кольца наружные эксцентрические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="238" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stopornye-pruzhinnye-kolca-vnutrennie-ekscentricheskie/" data-id-category="238">Стопорные пружинные кольца внутренние эксцентрические</a>
                            </li></ul>
                            <a href="/catalog/kolca-stopornye/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1973" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/setki/" data-id-category="1973">
                            Сетки металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="1973">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="40" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rabica/" data-id-category="40">Рабица</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="699" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gabiony/" data-id-category="699">
                                Габионы
                                <svg class="icon icon_arrow-right-min" data-id-category="699">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="934" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dinamicheskie-kamneulavlivayushie-barery/" data-id-category="934">Камнеулавливающие динамические барьеры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="907" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gabiony-dzhambo/" data-id-category="907">Габионы Джамбо</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="713" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/korobchatye-gabiony/" data-id-category="713">Коробчатые габионы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="719" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/matrasno-tyufyachnye-gabiony/" data-id-category="719">Матрасно-тюфячные габионы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="706" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gabiony-s-armiruyushej-panelyu/" data-id-category="706">Габионы с армирующей панелью</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="725" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cilindricheskie-gabiony/" data-id-category="725">Цилиндрические габионы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="914" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/matracy-reno/" data-id-category="914">Матрацы Рено</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="922" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/provolochnye-setki/" data-id-category="922">Проволочные сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="930" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sistema-terramesh/" data-id-category="930">Система Террамеш</a>
                                </li></ul>
                                <a href="/catalog/gabiony/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="28" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-setki/" data-id-category="28">
                                Нержавеющие сетки
                                <svg class="icon icon_arrow-right-min" data-id-category="28">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="810" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-riflyonye-setki/" data-id-category="810">Рифлёные нержавеющие сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="818" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-svarnye-setki/" data-id-category="818">Сварные нержавеющие сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="909" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-tkannye-setki/" data-id-category="909">Тканые нержавеющие сетки</a>
                                </li></ul>
                                <a href="/catalog/nerzhaveyushie-setki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="60" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-setki/" data-id-category="60">
                                Стальные сетки
                                <svg class="icon icon_arrow-right-min" data-id-category="60">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="660" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/armaturnye-setki/" data-id-category="660">Арматурные сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="664" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dorozhnye-setki/" data-id-category="664">Дорожные сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="672" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kladochnye-svarnye-setki/" data-id-category="672">Кладочные сварные сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="693" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shtukaturnye-setki/" data-id-category="693">Штукатурные сетки</a>
                                </li></ul>
                                <a href="/catalog/stalnye-setki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="685" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tkanaya-setka/" data-id-category="685">Тканые сетки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="167" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prosechno-vytyazhnye-setki/" data-id-category="167">Просечно-вытяжные сетки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="85" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/filtrovye-setki/" data-id-category="85">
                                Фильтровые сетки
                                <svg class="icon icon_arrow-right-min" data-id-category="85">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="92" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-filtrovye-setki/" data-id-category="92">Нержавеющие фильтровые сетки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="105" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/galunnye-filtrovannye-setki/" data-id-category="105">Галунные сетки фильтровальные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="99" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sarzhevye-filtrovye-setki/" data-id-category="99">Саржевые фильтровые сетки</a>
                                </li></ul>
                                <a href="/catalog/filtrovye-setki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/setki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="215" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shplinty/" data-id-category="215">Шплинты</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="901" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reshetchatye-nastily/" data-id-category="901">
                            Решетчатые настилы
                            <svg class="icon icon_arrow-right-min" data-id-category="901">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="896" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pressovannye-reshetchatye-nastily/" data-id-category="896">Прессованные решетчатые настилы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="885" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnye-nastily/" data-id-category="885">Сварные решетчатые настилы</a>
                            </li></ul>
                            <a href="/catalog/reshetchatye-nastily/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1671" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krepezhnye-skoby/" data-id-category="1671">Крепежные скобы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="630" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/melyushie-shary/" data-id-category="630">Мелющие шары</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1201" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubnye-zazhimy/" data-id-category="1201">Трубные зажимы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="149" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shponki/" data-id-category="149">
                            Шпонки металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="149">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="156" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prizmaticheskie-shponki/" data-id-category="156">Призматические шпонки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="166" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/segmentnye-shponki/" data-id-category="166">Сегментные шпонки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="162" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klinovye-shponki/" data-id-category="162">Клиновые шпонки</a>
                            </li></ul>
                            <a href="/catalog/shponki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/metizy-i-krepezh/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="160">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/ocinkovannyj-prokat/" data-id-category="160">
                        Оцинкованный прокат
                        <svg class="icon icon_arrow-right-min" data-id-category="160">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="226" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-listy/" data-id-category="226">
                            Листы оцинкованные
                            <svg class="icon icon_arrow-right-min" data-id-category="226">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1115" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-perforirovannye-listy/" data-id-category="1115">Перфорированные оцинкованные листы</a>
                            </li></ul>
                            <a href="/catalog/ocinkovannye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="221" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-setki/" data-id-category="221">Сетки оцинкованные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="438" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-ugolki/" data-id-category="438">
                            Уголки оцинкованные
                            <svg class="icon icon_arrow-right-min" data-id-category="438">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="414" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-ravnopolochnye-ugolki/" data-id-category="414">Равнополочные оцинкованные  уголки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="444" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-neravnopolochnye-ugolki/" data-id-category="444">Неравнополочные оцинкованные уголки</a>
                            </li></ul>
                            <a href="/catalog/ocinkovannye-ugolki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="407" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-provoloki/" data-id-category="407">Проволоки оцинкованные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="420" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-polosy/" data-id-category="420">Полосы оцинкованные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1212" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-rulony/" data-id-category="1212">Рулоны оцинкованные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1798" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-ocinkovannoj-stali/" data-id-category="1798">
                            Трубы из оцинкованной стали
                            <svg class="icon icon_arrow-right-min" data-id-category="1798">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1274" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-truby/" data-id-category="1274">Оцинкованные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1409" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/profilnye-ocinkovannye-truby/" data-id-category="1409">Профильные оцинкованные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1522" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kvadratnye-ocinkovannye-truby/" data-id-category="1522">Квадратные оцинкованные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1617" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-ocinkovannye-truby/" data-id-category="1617">Прямоугольные оцинкованные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1633" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-gidravlicheskie-trubki/" data-id-category="1633">Гидравлические трубки оцинкованные</a>
                            </li></ul>
                            <a href="/catalog/truby-iz-ocinkovannoj-stali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2202" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannyj-krug/" data-id-category="2202">Оцинкованные круги</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="876" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-shvellery/" data-id-category="876">Швеллеры оцинкованные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2201" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-upakovochnye-lenty/" data-id-category="2201">Оцинкованные упаковочные ленты</a>
                        </li></ul>
                        <a href="/catalog/ocinkovannyj-prokat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2111">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/oborudovanie/" data-id-category="2111">
                        Промышленное оборудование
                        <svg class="icon icon_arrow-right-min" data-id-category="2111">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2404" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyacionnoe-oborudovanie/" data-id-category="2404">
                            Вентиляционное оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="2404">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2433" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dymouloviteli/" data-id-category="2433">Дымоуловители</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2419" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kryshnye-ventilyatory/" data-id-category="2419">Крышные вентиляторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2420" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/osevye-ventilyatory/" data-id-category="2420">Осевые вентиляторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2431" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pylevye-ventilyatory/" data-id-category="2431">Пылевые вентиляторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2408" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/radialnye-ventilyatory/" data-id-category="2408">Радиальные вентиляторы</a>
                            </li></ul>
                            <a href="/catalog/ventilyacionnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2475" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konvejernye-lenty/" data-id-category="2475">
                            Конвейерные ленты
                            <svg class="icon icon_arrow-right-min" data-id-category="2475">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2477" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konvejernye-metallokordnye-lenty/" data-id-category="2477">Конвейерные металлокордные ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2512" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konvejernye-rezinotkanevye-lenty/" data-id-category="2512">Конвейерные резинотканевые ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2482" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konvejernye-shevronnye-lenty/" data-id-category="2482">Конвейерные шевронные ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2481" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konvejernye-elevatornye-lenty/" data-id-category="2481">Конвейерные элеваторные ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2480" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezinotkanevye-udaroprochnye-lenty-s-utkom/" data-id-category="2480">Резинотканевые ударопрочные ленты со стальным утком</a>
                            </li></ul>
                            <a href="/catalog/konvejernye-lenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2447" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motopompy/" data-id-category="2447">
                            Мотопомпы
                            <svg class="icon icon_arrow-right-min" data-id-category="2447">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2448" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motopompy-benzinovye/" data-id-category="2448">Мотопомпы бензиновые</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2449" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motopompy-dizelnye/" data-id-category="2449">Мотопомпы дизельные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2450" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motopompy-dlya-gryaznoj-vody/" data-id-category="2450">Мотопомпы для грязной воды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2451" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motopompy-pozharnye/" data-id-category="2451">Мотопомпы пожарные</a>
                            </li></ul>
                            <a href="/catalog/motopompy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2434" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podshipnikovye-uzly/" data-id-category="2434">
                            Подшипниковые узлы
                            <svg class="icon icon_arrow-right-min" data-id-category="2434">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2439" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/manzhety-gidravlicheskie/" data-id-category="2439">Манжеты гидравлические</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2441" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/remen-zubchatyj/" data-id-category="2441">Ремень зубчатый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2436" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/salniki/" data-id-category="2436">Сальники</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2435" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podshipniki/" data-id-category="2435">Подшипники</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2467" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podshipniki-rolikovye-radialno-upornye-konicheskie-odnoryadnye/" data-id-category="2467">Подшипники роликовые радиально-упорные конические однорядные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2473" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podshipniki-rolikovye-uporno-radialnye-sfericheskie-odinarnye/" data-id-category="2473">Подшипники роликовые упорно-радиальные сферические одинарные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2437" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shariki-dlya-podshipnikov/" data-id-category="2437">Шарики для подшипников</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2438" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/roliki-dlya-podshipnikov/" data-id-category="2438">Ролики для подшипников</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2440" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/korpusa-podshipnikov/" data-id-category="2440">Корпуса подшипников</a>
                            </li></ul>
                            <a href="/catalog/podshipnikovye-uzly/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2384" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reduktory/" data-id-category="2384">
                            Редукторы
                            <svg class="icon icon_arrow-right-min" data-id-category="2384">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2387" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konichesko-cilindricheskie-reduktory/" data-id-category="2387">Коническо-цилиндрические редукторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2388" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/motor-variatory/" data-id-category="2388">Моторы-вариаторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2385" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reduktory-chervyachnye/" data-id-category="2385">Редукторы червячные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2386" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cilindricheskij-reduktor/" data-id-category="2386">Цилиндрические редукторы</a>
                            </li></ul>
                            <a href="/catalog/reduktory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2391" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teplovoe-oborudovanie/" data-id-category="2391">
                            Тепловое оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="2391">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2426" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhonagrevateli/" data-id-category="2426">Воздухонагреватели</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2425" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kalorifer/" data-id-category="2425">Калорифер</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2399" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalnye-ventilyatory/" data-id-category="2399">Канальные вентиляторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2392" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teplovaya-zavesa/" data-id-category="2392">Тепловая завеса</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2422" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teplovye-pushki/" data-id-category="2422">Тепловые пушки</a>
                            </li></ul>
                            <a href="/catalog/teplovoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2389" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrogeneratory/" data-id-category="2389">
                            Электрогенераторы
                            <svg class="icon icon_arrow-right-min" data-id-category="2389">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2390" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/benzinovye-generatory/" data-id-category="2390">Бензиновые генераторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2395" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dizelnye-generatory/" data-id-category="2395">Дизельные генераторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2394" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mini-generatory/" data-id-category="2394">Мини-генераторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2397" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trehfaznye-generatory/" data-id-category="2397">Трехфазные генераторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2400" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrostancii-v-shumozashitnom-kozhuhe/" data-id-category="2400">Электростанции в шумозащитном кожухе</a>
                            </li></ul>
                            <a href="/catalog/elektrogeneratory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2442" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrodvigateli/" data-id-category="2442">
                            Электродвигатели
                            <svg class="icon icon_arrow-right-min" data-id-category="2442">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2443" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/servodvigateli/" data-id-category="2443">Серводвигатели</a>
                            </li></ul>
                            <a href="/catalog/elektrodvigateli/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="182" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/burovoe-oborudovanie/" data-id-category="182">
                            Буровое оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="182">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="229" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury/" data-id-category="229">
                                Буры для скважин
                                <svg class="icon icon_arrow-right-min" data-id-category="229">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="245" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-dlya-bureniya-kolodcev/" data-id-category="245">Буры для колодцев</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="247" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-kolonkovye/" data-id-category="247">Буры колонковые</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="251" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kovshebury/" data-id-category="251">Ковшебуры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="233" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konusnye-bury/" data-id-category="233">
                                    Конусные буры
                                    <svg class="icon icon_arrow-right-min" data-id-category="233">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="241" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bks/" data-id-category="241">Буры БКС</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="236" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bsu/" data-id-category="236">Буры БСУ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="243" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bts/" data-id-category="243">Буры БТС</a>
                                    </li></ul>
                                    <a href="/catalog/konusnye-bury/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="187" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lopastnye-bury/" data-id-category="187">
                                    Лопастные буры
                                    <svg class="icon icon_arrow-right-min" data-id-category="187">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="223" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-ba/" data-id-category="223">Буры БА</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="218" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bkm/" data-id-category="218">Буры БКМ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="193" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bl-300a/" data-id-category="193">Буры БЛ 300А</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="198" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bl-s5s6/" data-id-category="198">Буры БЛ S5/S6</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="202" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bl-a/" data-id-category="202">Буры БЛ-А</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="213" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-bsl/" data-id-category="213">Буры БСЛ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="207" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bury-btu-l/" data-id-category="207">Буры БТУ-Л</a>
                                    </li></ul>
                                    <a href="/catalog/lopastnye-bury/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="275" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehodniki-dlya-montazha-vintovyh-svaj/" data-id-category="275">Переходники для монтажа винтовых свай</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="287" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shnekovye-bury/" data-id-category="287">
                                    Шнековые буры
                                    <svg class="icon icon_arrow-right-min" data-id-category="287">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="285" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shnekovye-bury-bks/" data-id-category="285">Шнековые буры БКС</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="283" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shnekovye-bury-bl/" data-id-category="283">Шнековые буры БЛ</a>
                                    </li></ul>
                                    <a href="/catalog/shnekovye-bury/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/bury/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="261" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezhushie-instrumenty/" data-id-category="261">
                                Режущие буровые инструменты
                                <svg class="icon icon_arrow-right-min" data-id-category="261">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="273" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaburniki/" data-id-category="273">Забурники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="278" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izmelchiteli-pnej/" data-id-category="278">Измельчители пней</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="265" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-rezcy/" data-id-category="265">Круглые резцы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="269" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ploskie-rezcy/" data-id-category="269">Плоские резцы</a>
                                </li></ul>
                                <a href="/catalog/rezhushie-instrumenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="255" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shneki/" data-id-category="255">
                                Шнеки буровые
                                <svg class="icon icon_arrow-right-min" data-id-category="255">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="259" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shneki-vstavki/" data-id-category="259">Шнеки-вставки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="281" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shneki-teleskopicheskie/" data-id-category="281">Шнеки телескопические</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="289" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/udliniteli-shnekov/" data-id-category="289">Удлинители шнеков</a>
                                </li></ul>
                                <a href="/catalog/shneki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/burovoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="329" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy/" data-id-category="329">
                            Насосы
                            <svg class="icon icon_arrow-right-min" data-id-category="329">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2413" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gidravlicheskie-shesterennye-nasosy/" data-id-category="2413">Гидравлические шестеренные насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2414" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalizacionnye-nasosy/" data-id-category="2414">Канализационные насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2412" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/maslyanye-shesterennye-nasosy/" data-id-category="2412">Масляные шестеренные насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2445" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-dlya-gryaznoj-vody/" data-id-category="2445">Насосы для грязной воды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2444" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pogruzhnye-nasosy-bcp/" data-id-category="2444">Погружные насосы БЦП</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2411" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stancii-upravleniya-nasosami/" data-id-category="2411">Станции управления насосами</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2410" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/centrobezhnye-konsolno-monoblochnye-nasosy/" data-id-category="2410">Центробежные (консольно-моноблочные) насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2409" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/centrobezhnye-konsolnye-nasosy/" data-id-category="2409">Центробежные (консольные) насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2415" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkulyacionnye-nasosy/" data-id-category="2415">Циркуляционные насосы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="332" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-skvazhinnye-ecv/" data-id-category="332">Насосы скважинные ЭЦВ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="335" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-skvazhinnye-2ecv/" data-id-category="335">Насосы скважинные 2ЭЦВ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="339" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-skvazhinnye-3ecv/" data-id-category="339">Насосы скважинные 3ЭЦВ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="347" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-bytovye-pogruzhnye-bcp/" data-id-category="347">Насосы бытовые погружные БЦП</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="351" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-dlya-skvazhin-crs/" data-id-category="351">Насосы для скважин CRS</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="367" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosy-dlya-skvazhin-spa/" data-id-category="367">Насосы для скважин СПА</a>
                            </li></ul>
                            <a href="/catalog/nasosy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1251" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molochnoe-oborudovanie/" data-id-category="1251">
                            Молочное оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="1251">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="95" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/separatory/" data-id-category="95">
                                Сепараторы
                                <svg class="icon icon_arrow-right-min" data-id-category="95">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="121" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/separatory-dlya-vysokozhirnyh-slivok/" data-id-category="121">Сепараторы для высокожирных сливок</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="101" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/separatory-molokoochistiteli/" data-id-category="101">Сепараторы-молокоочистители</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="107" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/separatory-slivkootdeliteli/" data-id-category="107">Сепараторы-сливкоотделители</a>
                                </li></ul>
                                <a href="/catalog/separatory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="37" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sip-stancii-poluavtomat/" data-id-category="37">СИП станции полуавтомат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="7" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanny-dlitelnoj-pasterizacii/" data-id-category="7">Ванны длительной пастеризации</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="51" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-nasosy/" data-id-category="51">
                                Пищевые насосы
                                <svg class="icon icon_arrow-right-min" data-id-category="51">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="56" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/centrobezhnye-nasosy/" data-id-category="56">Центробежные насосы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="64" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/centrobezhnye-samovsasyvayushie-nasosy/" data-id-category="64">Центробежные самовсасывающие насосы</a>
                                </li></ul>
                                <a href="/catalog/pishevye-nasosy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="19" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/emkosti-proizvodstvennye-po-tipu-ya1-osv/" data-id-category="19">Резервуар&nbsp;Я1-ОСВ</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="76" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastinchatye-teploobmenniki/" data-id-category="76">
                                Пластинчатые теплообменники
                                <svg class="icon icon_arrow-right-min" data-id-category="76">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="88" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nagrevateli-plastinchatyi/" data-id-category="88">Нагреватели пластинчатые</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="81" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ohladiteli-plastinchatye/" data-id-category="81">Охладители пластинчатые</a>
                                </li></ul>
                                <a href="/catalog/plastinchatye-teploobmenniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="32" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pasterizacionno-ohladitelnye-ustanovki/" data-id-category="32">Пастеризационно-охладительные установки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1263" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ohladiteli-moloka/" data-id-category="1263">
                                Охладители молока
                                <svg class="icon icon_arrow-right-min" data-id-category="1263">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="134" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ohladiteli-moloka-vertikalnogo-tipa/" data-id-category="134">Охладители молока вертикального типа</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1268" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ohladiteli-moloka-zakrytogo-tipa/" data-id-category="1268">Охладители молока закрытого типа</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1257" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ohladiteli-moloka-otkrytogo-tipa/" data-id-category="1257">Охладители молока открытого типа</a>
                                </li></ul>
                                <a href="/catalog/ohladiteli-moloka/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="115" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rotorno-pulsacionnye-apparaty/" data-id-category="115">Роторно-пульсационные аппараты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="44" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/generatory-ledyanoj-vody-led/" data-id-category="44">Генераторы ледяной воды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="14" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/syrovarni-vdps/" data-id-category="14">Сыроварни ВДПС</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="71" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gomogenizatory/" data-id-category="71">Гомогенизаторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="25" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanny-tvorozhnye/" data-id-category="25">Ванны творожные</a>
                            </li></ul>
                            <a href="/catalog/molochnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2365" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary/" data-id-category="2365">
                            Резервуары
                            <svg class="icon icon_arrow-right-min" data-id-category="2365">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2458" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary-pozharnye/" data-id-category="2458">Резервуары пожарные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2361" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/oborudovanie-dlya-rezervuarov/" data-id-category="2361">
                                Оборудование для резервуаров
                                <svg class="icon icon_arrow-right-min" data-id-category="2361">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2370" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyhatelnye-klapany/" data-id-category="2370">Дыхательные клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2402" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lyuki-rezvevuarov/" data-id-category="2402">Люки резвевуаров</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2405" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mehanizmy-upravleniya-hlopushkami/" data-id-category="2405">Механизмы управления хлопушками</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2403" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/patrubki-rezervuarov/" data-id-category="2403">Патрубки резервуаров</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2407" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/predohraniteli-ognevye/" data-id-category="2407">Предохранители огневые</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2393" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/probootborniki/" data-id-category="2393">Пробоотборники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2406" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hlopushki-rezervuarov/" data-id-category="2406">Хлопушки резервуаров</a>
                                </li></ul>
                                <a href="/catalog/oborudovanie-dlya-rezervuarov/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2351" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/emkosti-drenazhnye/" data-id-category="2351">Емкости дренажные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2350" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neftegazovye-separatory/" data-id-category="2350">Нефтегазовые сепараторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2355" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/baki-akkumulyatory-goryachej-vody/" data-id-category="2355">Баки-аккумуляторы горячей воды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2354" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/apparaty-s-peremeshivayushimi-ustrojstvami/" data-id-category="2354">Аппараты с перемешивающими устройствами</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2346" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary-rvs/" data-id-category="2346">Резервуары вертикальные РВС</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2360" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary-gorizontalnye/" data-id-category="2360">Резервуары горизонтальные РГС</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2352" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sosudy-dlya-hraneniya-szhizhennogo-gaza/" data-id-category="2352">Сосуды для хранения сжиженного газа</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2349" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/otstojniki-vody-i-nefti/" data-id-category="2349">Отстойники воды и нефти</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2353" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary-dvustennye-rgsd/" data-id-category="2353">Резервуары двустенные РГСД</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2459" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezervuary-nerzhaveyushie-gorizontalnye/" data-id-category="2459">Резервуары нержавеющие горизонтальные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2356" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhosborniki-i-resivery-gaza/" data-id-category="2356">Воздухосборники и ресиверы газа</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2358" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silosy-i-baki/" data-id-category="2358">Силосы и баки</a>
                            </li></ul>
                            <a href="/catalog/rezervuary/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2381" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chastotnye-preobrazovateli/" data-id-category="2381">
                            Частотные преобразователи
                            <svg class="icon icon_arrow-right-min" data-id-category="2381">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2383" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tormoznye-rezistory/" data-id-category="2383">Тормозные резисторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2446" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tormoznye-bloki/" data-id-category="2446">Тормозные блоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2382" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chastotnye-preobrazovateli-dlya-paneli-upravleniya/" data-id-category="2382">Частотные преобразователи для панели управления</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2401" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pulty-distancionnogo-upravleniya/" data-id-category="2401">Пульты дистанционного управления ПУ ЗЦ</a>
                            </li></ul>
                            <a href="/catalog/chastotnye-preobrazovateli/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1451" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/oborudovanie-dlya-dobychi-nefti-i-gaza/" data-id-category="1451">
                            Оборудование для добычи нефти и газа
                            <svg class="icon icon_arrow-right-min" data-id-category="1451">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1639" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/manifoldy/" data-id-category="1639">
                                Манифольды
                                <svg class="icon icon_arrow-right-min" data-id-category="1639">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="608" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bloki-manifolda/" data-id-category="608">Блоки манифольда</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1758" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/manifoldy-burovye/" data-id-category="1758">Буровые манифольды</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1880" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/manifoldy-protivovybrosovye/" data-id-category="1880">Противовыбросовые манифольды</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1914" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-manifolda/" data-id-category="1914">Трубы манифольда</a>
                                </li></ul>
                                <a href="/catalog/manifoldy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1336" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-dlya-dobychi-nefti-i-gaza/" data-id-category="1336">
                                Нефтегазовые трубы
                                <svg class="icon icon_arrow-right-min" data-id-category="1336">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1640" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nasosno-kompressornye-truby/" data-id-category="1640">
                                    Насосно-компрессорные трубы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1640">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="593" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-nasosno-kompressornyh-trub/" data-id-category="593">
                                        Муфты насосно-компрессорных труб
                                        <svg class="icon icon_arrow-right-min" data-id-category="593">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="611" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-nkb/" data-id-category="611">Муфты НКБ</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="619" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-nkv/" data-id-category="619">Муфты НКВ</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="606" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-nkm/" data-id-category="606">Муфты НКМ</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="600" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mufty-nkt/" data-id-category="600">Муфты НКТ</a>
                                        </li></ul>
                                        <a href="/catalog/mufty-nasosno-kompressornyh-trub/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="644" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubnye-zagotovki-dlya-nkt/" data-id-category="644">Трубные заготовки для НКТ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="582" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-nkb/" data-id-category="582">Трубы НКБ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="586" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-nkv/" data-id-category="586">Трубы НКВ</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="577" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-nkm/" data-id-category="577">Трубы НКМ</a>
                                    </li></ul>
                                    <a href="/catalog/nasosno-kompressornye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/truby-dlya-dobychi-nefti-i-gaza/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1536" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neftegazovaya-armatura/" data-id-category="1536">
                                Нефтегазовая арматура
                                <svg class="icon icon_arrow-right-min" data-id-category="1536">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1543" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drosseli/" data-id-category="1543">Дроссели</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1628" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zadvizhki-burovye/" data-id-category="1628">Задвижки буровые</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1698" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-obratnye-s-brs/" data-id-category="1698">Клапаны обратные с БРС</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1757" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolena-sharnirnye/" data-id-category="1757">Колена шарнирные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1812" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krestoviny-tochenye/" data-id-category="1812">Крестовины точеные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1943" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ugolniki-tochenye/" data-id-category="1943">Угольники точеные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2043" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-tochenye/" data-id-category="2043">Тройники точеные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="393" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bystrorazemnye-soedineniya/" data-id-category="393">Быстроразъемные соединения</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="457" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/obvyazki-kolonnye/" data-id-category="457">Обвязки колонные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="483" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fontannaya-armatura/" data-id-category="483">Фонтанная арматура</a>
                                </li></ul>
                                <a href="/catalog/neftegazovaya-armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="477" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/burovye-dolota/" data-id-category="477">
                                Буровые долота
                                <svg class="icon icon_arrow-right-min" data-id-category="477">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="517" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dolota-fdc/" data-id-category="517">Долота FDC</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="497" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dolota-pdc/" data-id-category="497">Долота PDC</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="504" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pilotnye-dolota/" data-id-category="504">Пилотные долота</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="490" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharoshechnye-dolota/" data-id-category="490">Шарошечные долота</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="524" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sharoshechnye-dolota-s-produvkoj-vozduhom/" data-id-category="524">Шарошечные долота с продувкой воздухом</a>
                                </li></ul>
                                <a href="/catalog/burovye-dolota/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/oborudovanie-dlya-dobychi-nefti-i-gaza/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2000" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podemnoe-oborudovanie/" data-id-category="2000">
                            Подъемное оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="2000">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1390" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lebedki/" data-id-category="1390">
                                Лебедки
                                <svg class="icon icon_arrow-right-min" data-id-category="1390">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1272" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektricheskie-lebedki/" data-id-category="1272">Электрические лебедки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1391" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/barabannye-ruchnye-lebedki/" data-id-category="1391">Барабанные ручные лебедки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1506" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rychazhnye-ruchnye-trosovye-lebedki/" data-id-category="1506">Рычажные ручные тросовые лебедки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1602" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rychazhnye-ruchnye-kanatnye-lebedki/" data-id-category="1602">Рычажные ручные канатные лебедки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1674" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/promyshlennye-lebedki-mtm/" data-id-category="1674">Промышленные лебедки МТМ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1738" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shesterennye-kanatnye-lebedki/" data-id-category="1738">Шестеренные канатные лебедки</a>
                                </li></ul>
                                <a href="/catalog/lebedki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1672" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tali/" data-id-category="1672">
                                Тали
                                <svg class="icon icon_arrow-right-min" data-id-category="1672">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1270" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ruchnye-tali/" data-id-category="1270">Ручные тали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1482" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektricheskie-tali/" data-id-category="1482">Электрические тали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1582" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pnevmaticheskie-tali/" data-id-category="1582">Пневматические тали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1673" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/koshki-s-ruchnym-privodom/" data-id-category="1673">Кошки с ручным приводом</a>
                                </li></ul>
                                <a href="/catalog/tali/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1374" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty/" data-id-category="1374">
                                Захваты грузоподъемные
                                <svg class="icon icon_arrow-right-min" data-id-category="1374">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1389" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-sendvich-panelej/" data-id-category="1389">Захваты для сэндвич-панелей</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1499" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-trub/" data-id-category="1499">Захваты для труб</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1598" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-strubciny/" data-id-category="1598">Захваты струбцины</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1665" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-kolonn/" data-id-category="1665">Захваты для колонн</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1732" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-lestnichnyh-marshej/" data-id-category="1732">Захваты для лестничных маршей</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1785" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-rels/" data-id-category="1785">Захваты для рельс</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1824" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dvutavrovyh-balok/" data-id-category="1824">Захваты двутавровых балок</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1864" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-rulonov-stali/" data-id-category="1864">Захваты для рулонов стали</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1895" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-gorizontalnogo-podema-lista/" data-id-category="1895">Захваты для горизонтального подъема листа</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1930" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-gorizontalnogo-podema-barabana/" data-id-category="1930">Захваты для горизонтального подъема барабана</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1957" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-poddonov-s-kirpichom/" data-id-category="1957">Захваты для поддонов с кирпичом</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1982" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-vertikalnogo-podema-lista/" data-id-category="1982">Захваты для вертикального подъема листа</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2003" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-podema-bochek-v-vertikalnom-polozhenii/" data-id-category="2003">Захваты для подъема бочек в вертикальном положении</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2021" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-vertikalnogo-podema-barabana/" data-id-category="2021">Захваты для вертикального подъема барабана</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2036" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-rels-kleshevye/" data-id-category="2036">Захваты для рельс клещевые</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2047" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-gruzov-na-poddone/" data-id-category="2047">Захваты для грузов на поддоне</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2060" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-metalla-v-pachkah/" data-id-category="2060">Захваты для металла в пачках</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2069" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-importnye/" data-id-category="2069">Захваты импортные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2076" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-buht-provoloki-i-polyh-materialov/" data-id-category="2076">Захваты для бухт проволоки и полых материалов</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2082" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-shvellerov-i-ugolkov/" data-id-category="2082">Захваты швеллеров и уголков</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2088" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-betonnyh-trub/" data-id-category="2088">Захваты для бетонных труб</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2093" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-tyukov-s-myagkim-materialom/" data-id-category="2093">Захваты для тюков с мягким материалом</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2095" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnitnye-zahvaty-s-otklyucheniem-magnitnogo-polya/" data-id-category="2095">Магнитные захваты с отключением магнитного поля</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2098" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-balansiry-dlya-gruzov-so-smeshennym-centrom-tyazhesti/" data-id-category="2098">Захваты-балансиры для грузов со смещенным центром тяжести</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2100" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-blokov-pryamougolnoj-formy/" data-id-category="2100">Захваты для блоков прямоугольной формы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2102" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-yashikov-za-naruzhnye-kanty/" data-id-category="2102">Захваты для ящиков за наружные канты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2104" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kryukovye-zahvaty-nasadki-dlya-vilochnogo-pogruzchika-teleskopicheskie/" data-id-category="2104">Крюковые захваты-насадки для вилочного погрузчика телескопические</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2106" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-relsosvarochnyh-poezdov/" data-id-category="2106">Захваты для рельсосварочных поездов</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2108" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-yashikov-za-vnutrennie-kanty/" data-id-category="2108">Захваты для ящиков за внутренние канты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="2110" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zahvaty-dlya-podema-bochek-v-gorizontalnom-polozhenii/" data-id-category="2110">Захваты для подъема бочек в горизонтальном положении</a>
                                </li></ul>
                                <a href="/catalog/zahvaty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/podemnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2063" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teploobmennoe-oborudovanie/" data-id-category="2063">
                            Теплообменное оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="2063">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="647" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/radiatory/" data-id-category="647">
                                Радиаторы
                                <svg class="icon icon_arrow-right-min" data-id-category="647">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="655" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/orebrennye-trubchatye-radiatory/" data-id-category="655">Оребренные трубчатые радиаторы</a>
                                </li></ul>
                                <a href="/catalog/radiatory/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="117" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teploobmenniki/" data-id-category="117">
                                Теплообменники
                                <svg class="icon icon_arrow-right-min" data-id-category="117">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="136" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kozhuhotrubchatye-teploobmenniki/" data-id-category="136">Кожухотрубчатые теплообменники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="129" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/razbornye-plastinchatye-teploobmenniki/" data-id-category="129">Разборные пластинчатые теплообменники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="123" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svarnye-plastinchatye-teploobmenniki/" data-id-category="123">Сварные пластинчатые теплообменники</a>
                                </li></ul>
                                <a href="/catalog/teploobmenniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="58" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podogrevateli/" data-id-category="58">
                                Подогреватели
                                <svg class="icon icon_arrow-right-min" data-id-category="58">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="66" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodovodyanye-podogrevateli/" data-id-category="66">Водоводяные подогреватели</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="78" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podogrevateli-kozhuhotrubnye-vodo-vodyanye/" data-id-category="78">Подогреватели кожухотрубные водо-водяные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="72" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podogrevateli-setevoj-vody/" data-id-category="72">Подогреватели сетевой воды</a>
                                </li></ul>
                                <a href="/catalog/podogrevateli/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="604" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kalorifery/" data-id-category="604">
                                Калориферы
                                <svg class="icon icon_arrow-right-min" data-id-category="604">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="625" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodyanye-kalorifery/" data-id-category="625">Водяные калориферы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="617" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/parovye-kalorifery/" data-id-category="617">Паровые калориферы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="610" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kalorifery/" data-id-category="610">Стальные калориферы</a>
                                </li></ul>
                                <a href="/catalog/kalorifery/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="83" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodogrejnye-kotly/" data-id-category="83">
                                Водогрейные котлы
                                <svg class="icon icon_arrow-right-min" data-id-category="83">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="109" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodogrejnye-kotly-naruzhnogo-razmesheniya/" data-id-category="109">Водогрейные котлы наружного размещения</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="90" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-vodogrejnye-kotly/" data-id-category="90">Газовые водогрейные котлы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="97" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/parovye-vodogrejnye-kotly/" data-id-category="97">Паровые водогрейные котлы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="103" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tverdotoplivnye-vodogrejnye-kotly/" data-id-category="103">Твердотопливные водогрейные котлы</a>
                                </li></ul>
                                <a href="/catalog/vodogrejnye-kotly/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="631" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/registry-otopleniya/" data-id-category="631">
                                Регистры отопления
                                <svg class="icon icon_arrow-right-min" data-id-category="631">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="634" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/registry-otopleniya-ploskie/" data-id-category="634">Регистры отопления плоские</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="641" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/registry-otopleniya-ellipticheskie/" data-id-category="641">Регистры отопления эллиптические</a>
                                </li></ul>
                                <a href="/catalog/registry-otopleniya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="598" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/resivery/" data-id-category="598">Воздушные ресиверы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="591" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/emkostnye-apparaty/" data-id-category="591">Емкостные аппараты</a>
                            </li></ul>
                            <a href="/catalog/teploobmennoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1978" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnoe-oborudovanie/" data-id-category="1978">
                            Рентгенозащитное оборудование
                            <svg class="icon icon_arrow-right-min" data-id-category="1978">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="950" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-dveri/" data-id-category="950">Двери рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2696" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-paneli/" data-id-category="2696">Панели рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="991" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-shirmy/" data-id-category="991">Ширмы рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="955" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-okna/" data-id-category="955">Окна рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="960" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-stavni/" data-id-category="960">Ставни рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="935" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-stekla/" data-id-category="935">
                                Стекла рентгенозащитные
                                <svg class="icon icon_arrow-right-min" data-id-category="935">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="941" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-rentgenozashitnye-stekla/" data-id-category="941">Круглые рентгенозащитные стекла</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="945" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-rentgenozashitnye-stekla/" data-id-category="945">Прямоугольные рентгенозащитные стекла</a>
                                </li></ul>
                                <a href="/catalog/rentgenozashitnye-stekla/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="984" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovyj-listy-dlya-rentgenkabineta/" data-id-category="984">Свинцовые листы для рентгенкабинета</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="965" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenozashitnye-zhalyuzi/" data-id-category="965">Жалюзи рентгенозащитные</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2695" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rentgenovskaya-trubka/" data-id-category="2695">Рентгеновская трубка</a>
                            </li></ul>
                            <a href="/catalog/rentgenozashitnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2521">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/dorozhnoe-oborudovanie/" data-id-category="2521">
                        Дорожное оборудование
                        <svg class="icon icon_arrow-right-min" data-id-category="2521">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2570" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kronshtejn-opor-osvesheniya/" data-id-category="2570">Кронштейны опор освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1841" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dorozhnye-ograzhdeniya/" data-id-category="1841">
                            Дорожные ограждения
                            <svg class="icon icon_arrow-right-min" data-id-category="1841">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2523" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dorozhnoe-ograzhdenie-11do/" data-id-category="2523">Дорожные ограждения 11ДО</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2522" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dorozhnoe-ograzhdenie-21do/" data-id-category="2522">Дорожные ограждения 21ДО</a>
                            </li></ul>
                            <a href="/catalog/dorozhnye-ograzhdeniya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2525" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/opora-osvesheniya/" data-id-category="2525">Опоры освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2524" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stolbik-signalnyj/" data-id-category="2524">Столбики сигнальные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2569" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/machta-osvesheniya/" data-id-category="2569">Мачты освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2538" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shumozashitnye-ekrany/" data-id-category="2538">Шумозащитные экраны</a>
                        </li></ul>
                        <a href="/catalog/dorozhnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2558">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/zheleznodorozhnoe-oborudovanie/" data-id-category="2558">
                        Железнодорожное оборудование
                        <svg class="icon icon_arrow-right-min" data-id-category="2558">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2562" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bashmak-zheleznodorozhnyj/" data-id-category="2562">Башмаки железнодорожные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2553" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-zakladnoj/" data-id-category="2553">Болты закладные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2554" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-klemmnyj/" data-id-category="2554">Болты клеммные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2552" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-stykovoj/" data-id-category="2552">Болты стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2563" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajka-klemmnaya-i-stykovaya/" data-id-category="2563">Гайки клеммные и стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2561" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izolyaciya-dlya-relsov/" data-id-category="2561">Изоляция для рельсов</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2565" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klemma-pk/" data-id-category="2565">Клеммы ПК</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2560" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolodka-tormoznaya/" data-id-category="2560">Колодки тормозные железнодорожные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2556" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kostyl-putevoy/" data-id-category="2556">Костыли путевые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2555" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nakladka-relsovaya/" data-id-category="2555">Накладки рельсовые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2557" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podkladka-pod-rels/" data-id-category="2557">Подкладки под рельс</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2566" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/strelochnyj-perevod/" data-id-category="2566">Стрелочные переводы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2564" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shajba-klemmnaya-i-stykovaya/" data-id-category="2564">Шайбы клеммные и стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2559" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpala/" data-id-category="2559">Шпалы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="886" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-relsy/" data-id-category="886">Железнодорожные рельсы</a>
                        </li></ul>
                        <a href="/catalog/zheleznodorozhnoe-oborudovanie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1855">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/syryo/" data-id-category="1855">
                        Металлургическое сырьё
                        <svg class="icon icon_arrow-right-min" data-id-category="1855">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1358" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chushki/" data-id-category="1358">
                            Чушки
                            <svg class="icon icon_arrow-right-min" data-id-category="1358">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1920" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chushki-iz-surmy/" data-id-category="1920">Чушки из сурьмы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1976" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/babbitovye-chushki/" data-id-category="1976">Баббитовые чушки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2016" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vismutovye-chushki/" data-id-category="2016">Висмутовые чушки</a>
                            </li></ul>
                            <a href="/catalog/chushki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1768" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatura/" data-id-category="1768">
                            Лигатуры
                            <svg class="icon icon_arrow-right-min" data-id-category="1768">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="698" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-alyuminievye/" data-id-category="698">Алюминиевые лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="802" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-molibdenovye/" data-id-category="802">Молибденовые лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="712" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-mednye/" data-id-category="712">Медные лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="724" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-vanadievye/" data-id-category="724">Ванадиевые лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="811" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-niobievye/" data-id-category="811">Ниобиевые лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="705" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-nikelevye/" data-id-category="705">Никелевые лигатуры</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="783" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-na-osnove-redkozemelnyh-metallov/" data-id-category="783">Лигатуры на основе редкоземельных металлов</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="826" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ligatury-na-osnove-prochih-metallov/" data-id-category="826">Лигатуры на основе прочих металлов</a>
                            </li></ul>
                            <a href="/catalog/ligatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1710" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrosplavy/" data-id-category="1710">
                            Ферросплавы
                            <svg class="icon icon_arrow-right-min" data-id-category="1710">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="675" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hrom-metallicheskij/" data-id-category="675">Хром металлический</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="659" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrosilicij/" data-id-category="659">Ферросилиций</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="735" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrohrom/" data-id-category="735">Феррохром</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="692" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kremnij-metallicheskij/" data-id-category="692">Кремний металлический</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="671" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferromarganec/" data-id-category="671">Ферромарганец</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="746" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferromolibden/" data-id-category="746">Ферромолибден</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="765" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrotitan/" data-id-category="765">Ферротитан</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="759" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrovanadij/" data-id-category="759">Феррованадий</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="663" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/marganec-metallicheskij/" data-id-category="663">Марганец металлический</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="753" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferroniobij/" data-id-category="753">Феррониобий</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="718" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silikokalcij/" data-id-category="718">Силикокальций</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="680" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrosilikomarganec/" data-id-category="680">Ферросиликомарганец</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="741" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrovolfram/" data-id-category="741">Ферровольфрам</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="729" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrobor/" data-id-category="729">Ферробор</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="770" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrofosfor/" data-id-category="770">Феррофосфор</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2138" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferroalyuminij/" data-id-category="2138">Ферроалюминий</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="654" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrosilikohrom/" data-id-category="654">Ферросиликохром</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="684" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ferrosilikobarij/" data-id-category="684">Ферросиликобарий</a>
                            </li></ul>
                            <a href="/catalog/ferrosplavy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2301" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-struzhki/" data-id-category="2301">
                            Стружки металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="2301">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2305" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznaya-okalina/" data-id-category="2305">Железная окалина</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2309" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednaya-struzhka/" data-id-category="2309">Медная стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2306" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznaya-struzhka/" data-id-category="2306">Железная стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2302" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievaya-struzhka/" data-id-category="2302">Алюминиевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2308" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnievaya-struzhka/" data-id-category="2308">Магниевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2307" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnaya-struzhka/" data-id-category="2307">Латунная стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2316" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/struzhka-zolotaya/" data-id-category="2316">Золотая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2318" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovaya-struzhka/" data-id-category="2318">Титановая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2315" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/serebryanaya-struzhka/" data-id-category="2315">Серебряная стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2338" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievaya-struzhka/" data-id-category="2338">Циркониевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2313" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikelevaya-struzhka/" data-id-category="2313">Никелевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2312" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibdenovaya-struzhka/" data-id-category="2312">Молибденовая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2304" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovaya-struzhka/" data-id-category="2304">Вольфрамовая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2314" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/niobievaya-struzhka/" data-id-category="2314">Ниобиевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2310" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/medno-nikelevaya-struzhka/" data-id-category="2310">Медно-никелевая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2317" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tantalovaya-struzhka/" data-id-category="2317">Танталовая стружка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2303" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanadievaya-struzhka-briketirovannaya/" data-id-category="2303">Ванадиевая стружка брикетированная</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2311" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molibden-volframovaya-struzhka/" data-id-category="2311">Молибден-вольфрамовая стружка</a>
                            </li></ul>
                            <a href="/catalog/metallicheskie-struzhki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1568" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-poroshki/" data-id-category="1568">
                            Порошки металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="1568">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2245" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/borid/" data-id-category="2245">Бориды</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2229" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kuporos/" data-id-category="2229">Купорос</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2222" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/grafit/" data-id-category="2222">Графитовый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2274" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/oksalat/" data-id-category="2274">Оксалаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2214" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/karbonilnoe-zhelezo/" data-id-category="2214">Карбонильное железо</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2250" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ftorid/" data-id-category="2250">Фторид</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2235" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframat/" data-id-category="2235">Вольфрамат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2256" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/modifikator/" data-id-category="2256">Модификаторы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2224" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/karbid-kremniya/" data-id-category="2224">Карбид кремния</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2240" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svincovyj-poroshok/" data-id-category="2240">Свинцовые порошки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1765" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovyj-poroshok/" data-id-category="1765">Бронзовый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2259" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shihta/" data-id-category="2259">Шихта</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2218" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovyannyj-poroshok/" data-id-category="2218">Оловянный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2272" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/smes-poroshkov/" data-id-category="2272">Смесь порошков</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2263" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kriolit/" data-id-category="2263">Криолит</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2238" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-pripoya/" data-id-category="2238">Порошки припоя</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2225" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminaty/" data-id-category="2225">Алюминаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1888" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframovyj-poroshok/" data-id-category="1888">Вольфрамовый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1355" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznyj-poroshok/" data-id-category="1355">Железный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2511" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-rodiya/" data-id-category="2511">Порошок родия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2215" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrokorund/" data-id-category="2215">Электрокорунд</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2253" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/surik-svincovyj/" data-id-category="2253">Сурик свинцовый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1463" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednyj-poroshok/" data-id-category="1463">Медный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2266" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nitrid-alyuminiya/" data-id-category="2266">Нитрид алюминия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2241" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/okis-cinka/" data-id-category="2241">Окись цинка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1569" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievyj-poroshok/" data-id-category="1569">Алюминиевый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2213" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/okis-alyuminiya/" data-id-category="2213">Окись алюминия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1647" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovyj-poroshok/" data-id-category="1647">Цинковый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2265" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminij-sernokislyj/" data-id-category="2265">Алюминий сернокислый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2254" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnitnyj-poroshok/" data-id-category="2254">Магнитный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2227" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/natrij-malonat/" data-id-category="2227">Натрий малонат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1922" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushij-poroshok/" data-id-category="1922">Нержавеющий порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2281" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/litij-ftoristyj/" data-id-category="2281">Литий фтористый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1979" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rezistivnye-splavy/" data-id-category="1979">Резистивные сплавы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2034" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnyj-poroshok/" data-id-category="2034">Латунный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2226" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnitnyj-lyuminescentnyj-poroshok/" data-id-category="2226">Магнитный люминесцентный порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2044" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hromovyj-poroshok/" data-id-category="2044">Хромовый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2228" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metacirkonat/" data-id-category="2228">Метацирконат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2279" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievo-magnievyj-poroshok/" data-id-category="2279">Алюминиево-магниевый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1999" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kremnievyj-poroshok/" data-id-category="1999">Кремниевый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2261" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cirkonievyj-koncentrat/" data-id-category="2261">Циркониевый концентрат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2280" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/koncentrat-magnitnoj-suspenzii/" data-id-category="2280">Концентрат магнитной суспензии</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2283" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-gafnievyj/" data-id-category="2283">Порошок гафния</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2234" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-iz-iridiya/" data-id-category="2234">Порошок из иридия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2282" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrosiliciya/" data-id-category="2282">Порошок ферросилиция</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2221" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/samoflyusuyushijsya-poroshok/" data-id-category="2221">Самофлюсующийся порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2275" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gafnat/" data-id-category="2275">Гафнаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2321" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/koncentrat-vanadiya/" data-id-category="2321">Концентрат ванадия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2268" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-gadoliniya/" data-id-category="2268">Порошок гадолиния</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2278" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrohroma/" data-id-category="2278">Порошок феррохрома</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2264" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/litievyj-poroshok/" data-id-category="2264">Литиевый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2231" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-babbita/" data-id-category="2231">Порошок баббита</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2244" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-karbita/" data-id-category="2244">Порошок карбида</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2249" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fosfat-ceriya/" data-id-category="2249">Фосфат церия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2252" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/termoreagiruyushij-poroshok/" data-id-category="2252">Термореагирующий порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2285" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pironiobat/" data-id-category="2285">Пирониобаты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2273" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-zheleznyj-instrumentalnyj/" data-id-category="2273">Порошок железный инструментальный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2258" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferromarganca/" data-id-category="2258">Порошок ферромарганца</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2239" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vanadievyj-poroshok/" data-id-category="2239">Ванадиевый порошок</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2284" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-silikokalciya/" data-id-category="2284">Порошок силикокальция</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2286" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferroniobiya/" data-id-category="2286">Порошок феррониобия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2219" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tverdosplavnaya-smes-poroshka/" data-id-category="2219">Твердосплавная смесь порошка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2257" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-permalloj/" data-id-category="2257">Порошок пермаллой</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2230" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-evropiya/" data-id-category="2230">Порошок европия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2246" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/volframosilikat-natriya/" data-id-category="2246">Вольфрамосиликат натрия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2232" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ceriya-oktoat/" data-id-category="2232">Церия октоат</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2237" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-metallidov/" data-id-category="2237">Порошок металлидов</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2247" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kompaktirovannyj-poroshkovyj-material/" data-id-category="2247">Компактированный порошковый материал</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2260" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-zheleznyj-vysokouglerodistyj/" data-id-category="2260">Порошок железный высокоуглеродистый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2267" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminij-ftoristyj-kislyj/" data-id-category="2267">Алюминий фтористый кислый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2270" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metagafnat-litiya/" data-id-category="2270">Метагафнат лития</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2271" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-gallievyj/" data-id-category="2271">Порошок галлиевый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2277" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshkovaya-smes-tedicin/" data-id-category="2277">Порошковая смесь тедицин</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2287" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrovanadi/" data-id-category="2287">Порошок феррованадия</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2288" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrosilikomarganca/" data-id-category="2288">Порошок ферросиликомарганца</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2289" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrofosfora/" data-id-category="2289">Порошок феррофосфора</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2290" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferrobora/" data-id-category="2290">Порошок ферробора</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2291" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-tellurovyj/" data-id-category="2291">Порошок теллуровый</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2292" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poroshok-ferromolibdena/" data-id-category="2292">Порошок ферромолибдена</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2077" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/berillievyj-poroshok/" data-id-category="2077">Бериллиевый порошок</a>
                            </li></ul>
                            <a href="/catalog/metallicheskie-poroshki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2293" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-pudry/" data-id-category="2293">
                            Пудры металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="2293">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2294" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievaya-pudra/" data-id-category="2294">Алюминиевая пудра</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2295" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovaya-pudra/" data-id-category="2295">Бронзовая пудра</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2296" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnaya-pudra/" data-id-category="2296">Латунная пудра</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2297" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednaya-pudra/" data-id-category="2297">Медная пудра</a>
                            </li></ul>
                            <a href="/catalog/metallicheskie-pudry/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2319" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-granuly/" data-id-category="2319">
                            Гранулы металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="2319">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2331" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednye-granuly/" data-id-category="2331">Медные гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2320" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cink-granulirovannyj/" data-id-category="2320">Цинк гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2323" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminij-granulirovannyj/" data-id-category="2323">Алюминий гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2330" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mednaya-sechka/" data-id-category="2330">Медная сечка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2329" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/magnievye-granuly/" data-id-category="2329">Магниевые гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2333" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/olovo-granulirovannoe/" data-id-category="2333">Олово гранулированное</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2336" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svinec-granulirovannyj/" data-id-category="2336">Свинец гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2326" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/granulirovannaya-shihta/" data-id-category="2326">Гранулированная шихта</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2332" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nikel-granulirovannyj/" data-id-category="2332">Никель гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2341" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/titanovye-granuly/" data-id-category="2341">Титановые гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2325" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vismut-granulirovannyj/" data-id-category="2325">Висмут гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2337" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/selen-granulirovannyj/" data-id-category="2337">Селен гранулированный</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2324" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bronzovye-granuly/" data-id-category="2324">Бронзовые гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2342" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/silumin-granuly/" data-id-category="2342">Силумин гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2328" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/latunnye-granuly/" data-id-category="2328">Латунные гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2340" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cheshujki-hroma/" data-id-category="2340">Чешуйки хрома</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2339" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tellur-granuly/" data-id-category="2339">Теллур гранулы</a>
                            </li></ul>
                            <a href="/catalog/metallicheskie-granuly/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2298" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-krupki/" data-id-category="2298">
                            Крупки металлические
                            <svg class="icon icon_arrow-right-min" data-id-category="2298">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2299" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievaya-krupka/" data-id-category="2299">Алюминиевая крупка</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2300" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/cinkovaya-krupka/" data-id-category="2300">Цинковая крупка</a>
                            </li></ul>
                            <a href="/catalog/metallicheskie-krupki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/syryo/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1787">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/polimery/" data-id-category="1787">
                        Полимеры
                        <svg class="icon icon_arrow-right-min" data-id-category="1787">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1273" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kompozitnye-materialy-kompozity/" data-id-category="1273">
                            Композитные материалы (композиты)
                            <svg class="icon icon_arrow-right-min" data-id-category="1273">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1350" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stekloplastik/" data-id-category="1350">
                                Стеклопластик
                                <svg class="icon icon_arrow-right-min" data-id-category="1350">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="722" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-stekloplastika/" data-id-category="722">Листы из стеклопластика</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1058" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rulony-iz-stekloplastika/" data-id-category="1058">Рулоны из стеклопластика</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="13" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-stekloplastika/" data-id-category="13">Стержни из стеклопластика</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="899" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-stekloplastika/" data-id-category="899">Трубы из стеклопластика</a>
                                </li></ul>
                                <a href="/catalog/stekloplastik/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1457" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/paronit/" data-id-category="1457">
                                Паронит
                                <svg class="icon icon_arrow-right-min" data-id-category="1457">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="669" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-paronita/" data-id-category="669">Листы из паронита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1113" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prokladki-iz-paronita/" data-id-category="1113">Прокладки из паронита</a>
                                </li></ul>
                                <a href="/catalog/paronit/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1551" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyuroston/" data-id-category="1551">Дюростон</a>
                            </li></ul>
                            <a href="/catalog/kompozitnye-materialy-kompozity/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1500" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektroizolyacionnye-materialy/" data-id-category="1500">
                            Электроизоляционные материалы
                            <svg class="icon icon_arrow-right-min" data-id-category="1500">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1341" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polipropilen/" data-id-category="1341">
                                Полипропилен
                                <svg class="icon icon_arrow-right-min" data-id-category="1341">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="636" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polipropilenovye-listy/" data-id-category="636">Полипропиленовые листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1118" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polipropilenovye-truby/" data-id-category="1118">Полипропиленовые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1121" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polipropilenovye-rulony/" data-id-category="1121">Полипропиленовые рулоны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="649" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polipropilenovye-sterzhni/" data-id-category="649">Полипропиленовые стержни</a>
                                </li></ul>
                                <a href="/catalog/polipropilen/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1466" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fibra/" data-id-category="1466">Фибра</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1576" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/steklotkan/" data-id-category="1576">Стеклоткань</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1669" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tekstolit/" data-id-category="1669">
                                Текстолит
                                <svg class="icon icon_arrow-right-min" data-id-category="1669">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1232" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vtulki-iz-tekstolita/" data-id-category="1232">Втулки из текстолита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1219" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-tekstolita/" data-id-category="1219">Листы текстолита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1226" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-tekstolita/" data-id-category="1226">Стержни из текстолита</a>
                                </li></ul>
                                <a href="/catalog/tekstolit/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1713" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ebonit/" data-id-category="1713">
                                Эбонит
                                <svg class="icon icon_arrow-right-min" data-id-category="1713">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="739" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-ebonita/" data-id-category="739">Листы из эбонита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="809" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubki-iz-ebonita/" data-id-category="809">Трубки из эбонита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="817" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastiny-iz-ebonita/" data-id-category="817">Пластины из эбонита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="824" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-ebonita/" data-id-category="824">Стержни из эбонита</a>
                                </li></ul>
                                <a href="/catalog/ebonit/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1788" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/steklotekstolit/" data-id-category="1788">
                                Стеклотекстолит
                                <svg class="icon icon_arrow-right-min" data-id-category="1788">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1243" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-steklotekstolita/" data-id-category="1243">Трубы из стеклотекстолита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1249" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-steklotekstolita/" data-id-category="1249">Листы из стеклотекстолита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1255" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-steklotekstolita/" data-id-category="1255">Стержни из стеклотекстолита</a>
                                </li></ul>
                                <a href="/catalog/steklotekstolit/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1815" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kipernye-lenty/" data-id-category="1815">Киперные ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1849" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/getinaks/" data-id-category="1849">Гетинакс</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1884" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izofleks/" data-id-category="1884">Изофлекс</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1918" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lakotkani/" data-id-category="1918">Лакоткани</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1952" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektrokarton/" data-id-category="1952">Электрокартон</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1969" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/mikanit/" data-id-category="1969">
                                Миканит
                                <svg class="icon icon_arrow-right-min" data-id-category="1969">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="455" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gibkij-mikanit/" data-id-category="455">Гибкий миканит</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1097" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prokladochnyj-mikanit/" data-id-category="1097">Прокладочный миканит</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1143" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-mikanita/" data-id-category="1143">Листы из миканита</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1173" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/formovochnyj-mikanit/" data-id-category="1173">Формовочный миканит</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1187" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastiny-iz-mikanita/" data-id-category="1187">Пластины из миканита</a>
                                </li></ul>
                                <a href="/catalog/mikanit/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1998" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektroizolyacionnye-lenty/" data-id-category="1998">Электроизоляционные ленты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2019" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektroizolyacionnye-trubki/" data-id-category="2019">Электроизоляционные трубки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2035" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/slyudoplast/" data-id-category="2035">Слюдопласты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2046" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/steklomikanit/" data-id-category="2046">Стекломиканиты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2059" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ftorlakotkan/" data-id-category="2059">Фторлакоткань</a>
                            </li></ul>
                            <a href="/catalog/elektroizolyacionnye-materialy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1557" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/konstrukcionnye-polimery/" data-id-category="1557">
                            Конструкционные полимеры
                            <svg class="icon icon_arrow-right-min" data-id-category="1557">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="2161" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/npvh-truby/" data-id-category="2161">НПВХ трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2335" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilentereftalat-granuly/" data-id-category="2335">Полиэтилентерефталат гранулы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1348" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polikarbonat/" data-id-category="1348">
                                Поликарбонат
                                <svg class="icon icon_arrow-right-min" data-id-category="1348">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="710" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-polikarbonata/" data-id-category="710">Листы из поликарбоната</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="679" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-polikarbonata/" data-id-category="679">Стержни из поликарбоната</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="908" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-polikarbonata/" data-id-category="908">Трубы из поликарбоната</a>
                                </li></ul>
                                <a href="/catalog/polikarbonat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1410" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/akril/" data-id-category="1410">
                                Акрил
                                <svg class="icon icon_arrow-right-min" data-id-category="1410">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="303" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/akrilovye-stekla/" data-id-category="303">Акриловые стекла</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="297" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/akrilovye-truby/" data-id-category="297">Акриловые трубы</a>
                                </li></ul>
                                <a href="/catalog/akril/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1649" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilen/" data-id-category="1649">
                                Полиэтилен
                                <svg class="icon icon_arrow-right-min" data-id-category="1649">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="838" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-polietilen/" data-id-category="838">Листовой полиэтилен</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="851" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilenovaya-plenka/" data-id-category="851">Полиэтиленовая пленка</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="651" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilenovye-sterzhni/" data-id-category="651">Полиэтиленовые стержни</a>
                                </li></ul>
                                <a href="/catalog/polietilen/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1688" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/orgsteklo/" data-id-category="1688">
                                Оргстекло
                                <svg class="icon icon_arrow-right-min" data-id-category="1688">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="343" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bloki-iz-orgstekla/" data-id-category="343">Блоки из оргстекла</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="757" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoe-orgsteklo/" data-id-category="757">Листовое оргстекло</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="652" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-orgstekla/" data-id-category="652">Стержни из оргстекла</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="915" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-orgstekla/" data-id-category="915">Трубы из оргстекла</a>
                                </li></ul>
                                <a href="/catalog/orgsteklo/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1769" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poliuretan/" data-id-category="1769">
                                Полиуретан
                                <svg class="icon icon_arrow-right-min" data-id-category="1769">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="686" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-poliuretan/" data-id-category="686">Листовой полиуретан</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="682" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastiny-iz-poliuretana/" data-id-category="682">Пластины из полиуретана</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="676" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-poliuretana/" data-id-category="676">Стержни из полиуретана</a>
                                </li></ul>
                                <a href="/catalog/poliuretan/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1817" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polistirol/" data-id-category="1817">
                                Полистирол
                                <svg class="icon icon_arrow-right-min" data-id-category="1817">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="763" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-polistirol/" data-id-category="763">Листовой полистирол</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="751" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polistirol-v-granulah/" data-id-category="751">Полистирол в гранулах</a>
                                </li></ul>
                                <a href="/catalog/polistirol/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1843" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poliamid/" data-id-category="1843">
                                Полиамид
                                <svg class="icon icon_arrow-right-min" data-id-category="1843">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="358" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/blochnyj-poliamid/" data-id-category="358">Блочный полиамид</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="31" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-poliamid/" data-id-category="31">Листовой полиамид</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="832" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/litevoj-poliamid/" data-id-category="832">Литьевой полиамид</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1105" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poliamid-v-granulah/" data-id-category="1105">Полиамид в гранулах</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="24" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-poliamida/" data-id-category="24">Стержни из полиамида</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="894" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubki-iz-poliamida/" data-id-category="894">Трубки из полиамида</a>
                                </li></ul>
                                <a href="/catalog/poliamid/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1890" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ftorplast/" data-id-category="1890">
                                Фторопласт
                                <svg class="icon icon_arrow-right-min" data-id-category="1890">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1040" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vtulki-iz-ftoroplasta/" data-id-category="1040">Втулки из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1030" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty-iz-ftoroplasta/" data-id-category="1030">Ленты из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1035" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-ftoroplasta/" data-id-category="1035">Листы из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1019" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastiny-iz-ftoroplasta/" data-id-category="1019">Пластины из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1024" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plenka-iz-ftoroplasta/" data-id-category="1024">Пленка из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1045" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-ftoroplasta/" data-id-category="1045">Стержни из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1051" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubki-iz-ftoroplasta/" data-id-category="1051">Трубки из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1056" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-ftoroplasta/" data-id-category="1056">Трубы из фторопласта</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="987" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fum/" data-id-category="987">
                                    ФУМ
                                    <svg class="icon icon_arrow-right-min" data-id-category="987">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1000" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zhguty-fum-kvadratnogo-secheniya/" data-id-category="1000">Жгуты ФУМ квадратного сечения</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="994" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zhguty-fum-krugloe-sechenie/" data-id-category="994">Жгуты ФУМ круглого сечения</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1005" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zhguty-fum-pryamougolnogo-secheniya/" data-id-category="1005">Жгуты ФУМ прямоугольного сечения</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1011" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty-fum/" data-id-category="1011">Ленты ФУМ</a>
                                    </li></ul>
                                    <a href="/catalog/fum/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/ftorplast/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1921" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kaprolon/" data-id-category="1921">
                                Капролон
                                <svg class="icon icon_arrow-right-min" data-id-category="1921">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="794" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/blochnyj-kaprolon/" data-id-category="794">Блочный капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="820" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vtulochnyj-kaprolon/" data-id-category="820">Втулки из капролона</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="777" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/grafitonapolnennyj-listovoj-kaprolon/" data-id-category="777">Графитонаполненный листовой капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="843" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/grafitonapolnennyj-sterzhnevoj-kaprolon/" data-id-category="843">Графитонаполненный стержневой капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="620" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kaprolonovye-plastiny/" data-id-category="620">Капролоновые пластины</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="626" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kaprolonovye-krugi/" data-id-category="626">Капролоновые круги</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="827" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kaprolonovye-truby/" data-id-category="827">Капролоновые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="803" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-kaprolon/" data-id-category="803">Листовой капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="784" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/maslonapolnennyj-listovoj-kaprolon/" data-id-category="784">Маслонаполненный листовой капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="836" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/maslonapolnennyj-sterzhnevoj-kaprolon/" data-id-category="836">Маслонаполненный стержневой капролон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="812" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhnevoj-kaprolon/" data-id-category="812">Стержневой капролон</a>
                                </li></ul>
                                <a href="/catalog/kaprolon/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1944" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/abs-plastik/" data-id-category="1944">
                                АБС-пластик
                                <svg class="icon icon_arrow-right-min" data-id-category="1944">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="465" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/granulirovannyj-plastik/" data-id-category="465">Гранулированный пластик ABS</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="790" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-plastik/" data-id-category="790">Листовой пластик АБС</a>
                                </li></ul>
                                <a href="/catalog/abs-plastik/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1981" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polimernye-truby/" data-id-category="1981">Полимерные трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1994" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-iz-plastika/" data-id-category="1994">Листы пластика</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2013" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilentereftalat/" data-id-category="2013">
                                Полиэтилентерефталат
                                <svg class="icon icon_arrow-right-min" data-id-category="2013">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="495" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/granuly-polietilentereftalat/" data-id-category="495">Гранулы ПЭТ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1156" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-polietilentereftalat/" data-id-category="1156">Листы ПЭТ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="976" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plenka-polietilentereftalat/" data-id-category="976">Пленка ПЭТ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="36" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prutki-polietilentereftalat/" data-id-category="36">Прутки ПЭТ</a>
                                </li></ul>
                                <a href="/catalog/polietilentereftalat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2032" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poliacetal/" data-id-category="2032">
                                Полиацеталь
                                <svg class="icon icon_arrow-right-min" data-id-category="2032">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="668" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vtulki-iz-poliacetalya/" data-id-category="668">Втулки из полиацеталя</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="904" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-poliacetal/" data-id-category="904">Листовой полиацеталь</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="927" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastiny-iz-poliacetalya/" data-id-category="927">Пластины ПОМ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="919" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/poliacetal-v-granulah/" data-id-category="919">Полиацеталь в гранулах</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="911" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-iz-poliacetalya/" data-id-category="911">Стержни из полиацеталя</a>
                                </li></ul>
                                <a href="/catalog/poliacetal/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2042" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/viniplast/" data-id-category="2042">
                                Винипласт
                                <svg class="icon icon_arrow-right-min" data-id-category="2042">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="402" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/viniplastovye-plenki/" data-id-category="402">Винипластовые пленки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="408" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/viniplastovye-truby/" data-id-category="408">Винипластовые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="774" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-viniplast/" data-id-category="774">Листовой винипласт</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="18" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhnevoj-viniplast/" data-id-category="18">Стержневой винипласт</a>
                                </li></ul>
                                <a href="/catalog/viniplast/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2057" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sloplast/" data-id-category="2057">Слопласт</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2066" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polivinilhlorid-pvh/" data-id-category="2066">
                                Поливинилхлорид
                                <svg class="icon icon_arrow-right-min" data-id-category="2066">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="488" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/granuly-pvh/" data-id-category="488">Гранулы ПВХ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="691" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-pvh/" data-id-category="691">Лист ПВХ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="733" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plastikat/" data-id-category="733">
                                    Пластикат ПВХ
                                    <svg class="icon icon_arrow-right-min" data-id-category="733">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="475" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/granuly-pvh-plastikat/" data-id-category="475">Гранулы ПВХ пластикат</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="628" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lenty-pvh-plastikat/" data-id-category="628">Ленты ПВХ пластикат</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1148" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listy-pvh-plastikat/" data-id-category="1148">Листы ПВХ пластикат</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1262" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rulony-pvh-plastikat/" data-id-category="1262">Рулоны ПВХ пластикат</a>
                                    </li></ul>
                                    <a href="/catalog/plastikat/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="697" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sterzhni-pvh/" data-id-category="697">Стержни ПВХ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="890" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trubki-pvh/" data-id-category="890">Трубки ПВХ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="703" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-iz-pvh/" data-id-category="703">Трубы ПВХ</a>
                                </li></ul>
                                <a href="/catalog/polivinilhlorid-pvh/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2075" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/steklolakotkan/" data-id-category="2075">Стеклолакоткань</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2080" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polivinilidenftorid/" data-id-category="2080">
                                Поливинилиденфторид
                                <svg class="icon icon_arrow-right-min" data-id-category="2080">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="781" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/listovoj-polivinilidenftorid/" data-id-category="781">Листовой поливинилиденфторид</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="800" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polivinilidenftoridnye-truby/" data-id-category="800">Поливинилиденфторидные трубы</a>
                                </li></ul>
                                <a href="/catalog/polivinilidenftorid/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2091" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bumazhnosloistyj-dekorativnyj-plastik-hpl/" data-id-category="2091">Бумажнослоистый декоративный пластик ДБСП</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2092" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plenkoelektrokarton/" data-id-category="2092">Пленкоэлектрокартон</a>
                            </li></ul>
                            <a href="/catalog/konstrukcionnye-polimery/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/polimery/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2697">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/prochee/" data-id-category="2697">
                        Прочее
                        <svg class="icon icon_arrow-right-min" data-id-category="2697">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1923" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stroitelstvo/" data-id-category="1923">
                            Строительство
                            <svg class="icon icon_arrow-right-min" data-id-category="1923">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1575" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kommunikacii/" data-id-category="1575">
                                Коммуникации жби
                                <svg class="icon icon_arrow-right-min" data-id-category="1575">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1476" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/teplotrassy/" data-id-category="1476">
                                    Элементы теплотрасс
                                    <svg class="icon icon_arrow-right-min" data-id-category="1476">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1364" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lotki-teplotrass/" data-id-category="1364">Лотки теплотрасс</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1479" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/plity-teplotrass/" data-id-category="1479">Плиты теплотрасс</a>
                                    </li></ul>
                                    <a href="/catalog/teplotrassy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1646" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/betonnye-truby/" data-id-category="1646">Бетонные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1718" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbocementnye-truby/" data-id-category="1718">Асбоцементные трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1772" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hrizotilcementnye-truby/" data-id-category="1772">Хризотилцементные трубы</a>
                                </li></ul>
                                <a href="/catalog/kommunikacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1304" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyaciya/" data-id-category="1304">
                                Вентиляция
                                <svg class="icon icon_arrow-right-min" data-id-category="1304">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1305" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhootvody/" data-id-category="1305">
                                    Воздуховоды
                                    <svg class="icon icon_arrow-right-min" data-id-category="1305">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1316" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gibkie-vozduhovody/" data-id-category="1316">
                                        Гибкие воздуховоды
                                        <svg class="icon icon_arrow-right-min" data-id-category="1316">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="386" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gibkie-alyuminievye-vozduhovody/" data-id-category="386">Гибкие алюминиевые воздуховоды</a>
                                        </li></ul>
                                        <a href="/catalog/gibkie-vozduhovody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1427" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-vozduhovody/" data-id-category="1427">
                                        Круглые воздуховоды
                                        <svg class="icon icon_arrow-right-min" data-id-category="1427">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="355" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhovody-kruglye-dlya-dymoudaleniya/" data-id-category="355">Воздуховоды круглые для дымоудаления</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="360" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhovody-kruglye-dlya-sistem-aspiracii/" data-id-category="360">Воздуховоды круглые для систем аспирации</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="352" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-vozduhovody/" data-id-category="352">Нержавеющие круглые воздуховоды</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="348" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-vozduhovody/" data-id-category="348">Оцинкованные круглые воздуховоды</a>
                                        </li></ul>
                                        <a href="/catalog/kruglye-vozduhovody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1538" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-vozduhovody/" data-id-category="1538">
                                        Прямоугольные воздуховоды
                                        <svg class="icon icon_arrow-right-min" data-id-category="1538">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="368" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhovody-pryamougolnye-dlya-dymoudaleniya/" data-id-category="368">Воздуховоды прямоугольные для дымоудаления</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="371" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vozduhovody-pryamougolnye-dlya-sistem-aspiracii/" data-id-category="371">Воздуховоды прямоугольные для систем аспирации</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="376" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pryamougolnye-vozduhovody/" data-id-category="376">Нержавеющие прямоугольные воздуховоды</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="380" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-pryamougolnye-vozduhovody/" data-id-category="380">Оцинкованные прямоугольные воздуховоды</a>
                                        </li></ul>
                                        <a href="/catalog/pryamougolnye-vozduhovody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li></ul>
                                    <a href="/catalog/vozduhootvody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1540" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fasonnye-chasti-ventilyacii/" data-id-category="1540">
                                    Фасонные части вентиляции
                                    <svg class="icon icon_arrow-right-min" data-id-category="1540">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="462" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyacionnye-vrezki/" data-id-category="462">
                                        Вентиляционные врезки
                                        <svg class="icon icon_arrow-right-min" data-id-category="462">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="468" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kruglye-ventilyacionnye-vyrezki/" data-id-category="468">Нержавеющие круглые вентиляционные врезки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="478" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pryamougolnye-ventilyacionnye-vyrezki/" data-id-category="478">Нержавеющие прямоугольные вентиляционные врезки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="473" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-kruglye-ventilyacionnye-vyrezki/" data-id-category="473">Оцинкованные круглые вентиляционные врезки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="484" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-pryamougolnye-ventilyacionnye-vyrezki/" data-id-category="484">Оцинкованные прямоугольные вентиляционные врезки</a>
                                        </li></ul>
                                        <a href="/catalog/ventilyacionnye-vrezki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="491" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyacionnye-zaglushki/" data-id-category="491">
                                        Вентиляционные заглушки
                                        <svg class="icon icon_arrow-right-min" data-id-category="491">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="498" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kruglye-ventilyacionnye-zaglushki/" data-id-category="498">Нержавеющие круглые вентиляционные заглушки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="513" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pryamougolnye-ventilyacionnye-zaglushki/" data-id-category="513">Нержавеющие прямоугольные вентиляционные заглушки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="505" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-kruglye-ventilyacionnye-zaglushki/" data-id-category="505">Оцинкованные круглые вентиляционные заглушки</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="519" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-pryamougolnye-ventilyacionnye-zaglushki/" data-id-category="519">Оцинкованные прямоугольные вентиляционные заглушки</a>
                                        </li></ul>
                                        <a href="/catalog/ventilyacionnye-zaglushki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="394" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyacionnye-otvody/" data-id-category="394">
                                        Вентиляционные отводы
                                        <svg class="icon icon_arrow-right-min" data-id-category="394">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="399" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kruglye-ventilyacionnye-otvody/" data-id-category="399">Круглые вентиляционные отводы</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="418" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pryamougolnye-ventilyacionnye-otvody/" data-id-category="418">Прямоугольные вентиляционные отводы</a>
                                        </li></ul>
                                        <a href="/catalog/ventilyacionnye-otvody/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="437" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyacionnye-trojniki/" data-id-category="437">
                                        Вентиляционные тройники
                                        <svg class="icon icon_arrow-right-min" data-id-category="437">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="442" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-kruglye-ventilyacionnye-trojniki/" data-id-category="442">Нержавеющие круглые вентиляционные тройники</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="451" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nerzhaveyushie-pryamougolnye-ventilyacionnye-trojniki/" data-id-category="451">Нержавеющие прямоугольные вентиляционные тройники</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="448" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-kruglye-ventilyacionnye-trojniki/" data-id-category="448">Оцинкованные круглые вентиляционные тройники</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="458" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ocinkovannye-pryamougolnye-ventilyacionnye-trojniki/" data-id-category="458">Оцинкованные прямоугольные вентиляционные тройники</a>
                                        </li></ul>
                                        <a href="/catalog/ventilyacionnye-trojniki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li></ul>
                                    <a href="/catalog/fasonnye-chasti-ventilyacii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/ventilyaciya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1460" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalizaciya/" data-id-category="1460">
                                Канализация
                                <svg class="icon icon_arrow-right-min" data-id-category="1460">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1461" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazh/" data-id-category="1461">
                                    Дренажные элементы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1461">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1377" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazhnye-truby/" data-id-category="1377">Дренажные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1462" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazhnye-gofrirovannye-truby/" data-id-category="1462">Дренажные гофрированные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1562" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazhnye-perforirovannye-truby/" data-id-category="1562">Дренажные перфорированные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1644" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazhnye-keramicheskie-truby/" data-id-category="1644">Дренажные керамические трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1712" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drenazhnye-polimernye-truby/" data-id-category="1712">Дренажные полимерные трубы</a>
                                    </li></ul>
                                    <a href="/catalog/drenazh/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1586" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dozhdepriemniki/" data-id-category="1586">Дождеприемники</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1660" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-kanalizacionnye-lyuki/" data-id-category="1660">Чугунные канализационные люки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1351" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalizacionnye-truby/" data-id-category="1351">
                                    Канализационные трубы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1351">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="701" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalizacionnye-plastikovye-truby/" data-id-category="701">Канализационные пластиковые трубы</a>
                                    </li></ul>
                                    <a href="/catalog/kanalizacionnye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/kanalizaciya/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1706" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/profnastil/" data-id-category="1706">
                                Профнастил
                                <svg class="icon icon_arrow-right-min" data-id-category="1706">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1337" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krovelnye-proflisty/" data-id-category="1337">Кровельные профлисты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1453" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stenovye-proflisty/" data-id-category="1453">Стеновые профлисты</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1552" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/universalnye-proflisty/" data-id-category="1552">Универсальные профлисты</a>
                                </li></ul>
                                <a href="/catalog/profnastil/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2081" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallocherepica-mp/" data-id-category="2081">Металлочерепица</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1885" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-balki/" data-id-category="1885">
                                Кран-балка
                                <svg class="icon icon_arrow-right-min" data-id-category="1885">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1455" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektricheskie-podvesnye-krany/" data-id-category="1455">Электрические подвесные краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1555" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/elektricheskie-opornye-krany/" data-id-category="1555">Электрические опорные краны</a>
                                </li></ul>
                                <a href="/catalog/krany-balki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1924" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-konstrukcii/" data-id-category="1924">
                                Металлические конструкции
                                <svg class="icon icon_arrow-right-min" data-id-category="1924">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1361" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ploshadki/" data-id-category="1361">
                                    Площадки металлические
                                    <svg class="icon icon_arrow-right-min" data-id-category="1361">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1362" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/promyshlennye-ploshadki/" data-id-category="1362">Промышленные металлические площадки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1472" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/perehodnye-ploshadki/" data-id-category="1472">Переходные металлические площадки</a>
                                    </li></ul>
                                    <a href="/catalog/ploshadki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1468" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/lestnicy/" data-id-category="1468">
                                    Лестницы металлические
                                    <svg class="icon icon_arrow-right-min" data-id-category="1468">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1360" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/promyshlennye-lestnicy/" data-id-category="1360">Промышленные лестницы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1471" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/marshevye-pozharnye-lestnicy/" data-id-category="1471">Маршевые пожарные лестницы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1572" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vertikalnye-pozharnye-lestnicy-s-ograzhdeniem/" data-id-category="1572">Вертикальные пожарные лестницы с ограждением</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1653" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vertikalnye-pozharnye-lestnicy-bez-ograzhdeniya/" data-id-category="1653">Вертикальные пожарные лестницы без ограждения</a>
                                    </li></ul>
                                    <a href="/catalog/lestnicy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1574" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prozhektornye-machty-pms/" data-id-category="1574">Прожекторные мачты ПМС</a>
                                </li></ul>
                                <a href="/catalog/metallicheskie-konstrukcii/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1946" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolyuchaya-provoloka/" data-id-category="1946">Колючие проволоки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1862" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodostochnye-sistemy/" data-id-category="1862">
                                Водосточные системы
                                <svg class="icon icon_arrow-right-min" data-id-category="1862">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1503" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zapchasti-vodostoka/" data-id-category="1503">
                                    Запчасти водостока
                                    <svg class="icon icon_arrow-right-min" data-id-category="1503">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1387" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodostochnye-zheloba/" data-id-category="1387">Водосточные желоба</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1501" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krepleniya-zheloba/" data-id-category="1501">Крепления желоба</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1597" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ugol-zheloba/" data-id-category="1597">Угол желоба</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1670" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zaglushki-zheloba/" data-id-category="1670">Заглушки желоба</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1736" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/voronki-zheloba/" data-id-category="1736">Воронки желоба</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1789" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolena-vodostochnoj-truby/" data-id-category="1789">Колена водосточной трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1827" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krepleniya-vodostochnyh-trub/" data-id-category="1827">Крепления водосточных труб</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1865" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/slivnye-kolena/" data-id-category="1865">Сливные колена</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1900" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodostochnye-soedinitelnye-truby/" data-id-category="1900">Водосточные соединительные трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1931" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodosbornye-kruglye-voronki/" data-id-category="1931">Водосборные круглые воронки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1958" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/trojniki-dlya-truby-vodostoka/" data-id-category="1958">Тройники для труб водостока</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1984" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheloba-s-vyhodnoj-voronkoj/" data-id-category="1984">Желоба с выходной воронкой</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="2005" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/soediniteli-vodostochnoj-truby-s-drenazhnoj-sistemoj/" data-id-category="2005">Соединители водосточной трубы с дренажной системой</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="2022" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodosbornye-konusnye-voronki/" data-id-category="2022">Водосборные конусные воронки</a>
                                    </li></ul>
                                    <a href="/catalog/zapchasti-vodostoka/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1356" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodostochnye-truby/" data-id-category="1356">Водосточные трубы</a>
                                </li></ul>
                                <a href="/catalog/vodostochnye-sistemy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1704" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyujmovye-truby/" data-id-category="1704">Дюймовые трубы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1983" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpunty-larsena/" data-id-category="1983">Шпунты Ларсена</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2015" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/fundamentnye-bolty/" data-id-category="2015">Фундаментные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2030" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stroitelnye-truby/" data-id-category="2030">
                                Строительные трубы
                                <svg class="icon icon_arrow-right-min" data-id-category="2030">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="2163" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-mnogoslojnye/" data-id-category="2163">Труба многослойная</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="560" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/polietilenovye-truby/" data-id-category="560">Пластиковые трубы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="173" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-pnd/" data-id-category="173">Полиэтиленовые трубы ПНД</a>
                                </li></ul>
                                <a href="/catalog/stroitelnye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2074" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-fundamenty/" data-id-category="2074">
                                Стальные фундаменты
                                <svg class="icon icon_arrow-right-min" data-id-category="2074">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1380" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vintovye-svai/" data-id-category="1380">Винтовые сваи</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="594" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/balki-rostverka/" data-id-category="594">Балки ростверка</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="612" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zabivnye-metallicheskie-svai/" data-id-category="612">Забивные металлические сваи</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="587" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nagolovniki-molota/" data-id-category="587">Наголовники молота</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="583" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nagolovnik-svaj/" data-id-category="583">Наголовник свай</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="578" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/rostverk/" data-id-category="578">Ростверк</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="572" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/svajnye-fundamenty/" data-id-category="572">Свайные фундаменты</a>
                                </li></ul>
                                <a href="/catalog/stalnye-fundamenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2085" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ankernye-gruppy/" data-id-category="2085">Анкерные группы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="2056" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zakladnye-konstrukcii/" data-id-category="2056">Закладные детали (конструкции)</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1720" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbest/" data-id-category="1720">
                                Асбестовые изделия
                                <svg class="icon icon_arrow-right-min" data-id-category="1720">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1290" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-listy/" data-id-category="1290">
                                    Асбестовые листы
                                    <svg class="icon icon_arrow-right-min" data-id-category="1290">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1292" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbocementnye-ploskie-listy/" data-id-category="1292">Асбоцементные плоские листы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1415" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbocementnye-volnistye-listy/" data-id-category="1415">Асбоцементные волнистые листы</a>
                                    </li></ul>
                                    <a href="/catalog/asbestovye-listy/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1478" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-shnury/" data-id-category="1478">Асбестовые шнуры</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1566" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/hrizotilcementnye-listy/" data-id-category="1566">Хризотилцементные листы</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1657" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovyj-karton/" data-id-category="1657">Асбестовый картон</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1722" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-lenty/" data-id-category="1722">
                                    Асбестовые ленты
                                    <svg class="icon icon_arrow-right-min" data-id-category="1722">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1363" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-lenty-tormoznye/" data-id-category="1363">Асбестовые ленты тормозные</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1475" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-lenty-teploizolyacionnye/" data-id-category="1475">Асбестовые ленты теплоизоляционные</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1579" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbolavsanovye-lenty/" data-id-category="1579">Асболавсановые ленты</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1655" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-lenty-elektroizolyacionnye/" data-id-category="1655">Асбестовые ленты электроизоляционные</a>
                                    </li></ul>
                                    <a href="/catalog/asbestovye-lenty/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1775" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbotkan/" data-id-category="1775">Асботкань</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1820" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbotekstolit/" data-id-category="1820">Асботекстолит</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1856" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-nakladki-dlya-tormoznyh-kolodok/" data-id-category="1856">Асбестовые накладки для тормозных колодок</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1891" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-trubki-pletenye/" data-id-category="1891">Асбестовые трубки плетеные</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1926" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbestovye-chehly-pletenye/" data-id-category="1926">Асбестовые чехлы плетеные</a>
                                </li></ul>
                                <a href="/catalog/asbest/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/stroitelstvo/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1977" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/himicheskaya-promyshlennost/" data-id-category="1977">Химическая промышленность</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1997" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudostroenie/" data-id-category="1997">
                            Судостроение
                            <svg class="icon icon_arrow-right-min" data-id-category="1997">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1347" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovaya-armatura/" data-id-category="1347">
                                Судовая арматура
                                <svg class="icon icon_arrow-right-min" data-id-category="1347">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1311" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kingstony/" data-id-category="1311">
                                    Кингстоны
                                    <svg class="icon icon_arrow-right-min" data-id-category="1311">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1312" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-kingstony/" data-id-category="1312">Судовые кингстоны</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1434" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/flancevye-kingstony/" data-id-category="1434">Фланцевые кингстоны</a>
                                    </li></ul>
                                    <a href="/catalog/kingstony/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1400" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bortovye-klapany/" data-id-category="1400">Бортовые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1513" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-ks/" data-id-category="1513">Клапаны КС</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1611" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-kot/" data-id-category="1611">Клапаны КОТ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1681" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-kosh/" data-id-category="1681">Клапаны КОШ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1743" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-latunnye-krany/" data-id-category="1743">Судовые латунные краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1793" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dyurito-capkovye-krany/" data-id-category="1793">Дюрито-цапковые краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1842" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-planki/" data-id-category="1842">
                                    Судовые планки
                                    <svg class="icon icon_arrow-right-min" data-id-category="1842">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1307" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/chugunnye-kipovye-planki/" data-id-category="1307">Чугунные киповые планки</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1429" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-kipovye-planki/" data-id-category="1429">Стальные киповые планки</a>
                                    </li></ul>
                                    <a href="/catalog/sudovye-planki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1870" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-bronzovye-krany/" data-id-category="1870">Судовые бронзовые краны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1907" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-uglovye-klapany/" data-id-category="1907">Судовые угловые клапаны</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1938" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klapany-kobsh/" data-id-category="1938">Клапаны КОБШ</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1961" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudovye-klinovye-zadvizhki/" data-id-category="1961">Судовые клиновые задвижки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="211" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prohodnye-krany/" data-id-category="211">Судовые проходные краны</a>
                                </li></ul>
                                <a href="/catalog/sudovaya-armatura/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1454" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievyj-polosobulb/" data-id-category="1454">Алюминиевый полособульб</a>
                            </li></ul>
                            <a href="/catalog/sudostroenie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2020" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnyj-transport/" data-id-category="2020">
                            Материалы ВСП
                            <svg class="icon icon_arrow-right-min" data-id-category="2020">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1589" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-prokladki/" data-id-category="1589">
                                Железнодорожные прокладки
                                <svg class="icon icon_arrow-right-min" data-id-category="1589">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1376" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-zheleznodorozhnye-prokladki/" data-id-category="1376">Стальные железнодорожные прокладки</a>
                                </li></ul>
                                <a href="/catalog/zheleznodorozhnye-prokladki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1728" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-planki/" data-id-category="1728">
                                Железнодорожные планки
                                <svg class="icon icon_arrow-right-min" data-id-category="1728">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1310" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/prizhimnye-planki/" data-id-category="1310">Прижимные планки</a>
                                </li><li class="header-catalog-menu__submenu-item" data-id-category="1431" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/upornye-planki/" data-id-category="1431">Упорные планки</a>
                                </li></ul>
                                <a href="/catalog/zheleznodorozhnye-planki/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/zheleznodorozhnyj-transport/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2033" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gornodobyvayushaya-promyshlennost/" data-id-category="2033">
                            Горнодобывающая промышленность
                            <svg class="icon icon_arrow-right-min" data-id-category="2033">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1731" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/melnicy/" data-id-category="1731">Мельницы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1492" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/drobilki/" data-id-category="1492">Дробилки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1594" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/futerovochnye-bolty/" data-id-category="1594">Футеровочные болты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1784" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/tyubingovye-kolca/" data-id-category="1784">Тюбинговые кольца</a>
                            </li></ul>
                            <a href="/catalog/gornodobyvayushaya-promyshlennost/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1887" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neftegazovaya-promyshlennost/" data-id-category="1887">
                            Нефтегазовая промышленность
                            <svg class="icon icon_arrow-right-min" data-id-category="1887">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1343" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazonefteprovod/" data-id-category="1343">
                                Газонефтепроводы
                                <svg class="icon icon_arrow-right-min" data-id-category="1343">
                                  <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                </svg>
                              </a>
                              <div class="lvl-holder-3">
                                <ul class="header-catalog-menu__submenu lvl-3"><li class="header-catalog-menu__submenu-item" data-id-category="1344" style="padding-left: 40px;">
                                  <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/truby-dlya-transportirovki-nefti-i-gaza/" data-id-category="1344">
                                    Трубы для транспортировки нефти и газа
                                    <svg class="icon icon_arrow-right-min" data-id-category="1344">
                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                    </svg>
                                  </a>
                                  <div class="lvl-holder-4">
                                    <ul class="header-catalog-menu__submenu lvl-4"><li class="header-catalog-menu__submenu-item" data-id-category="1346" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-truby/" data-id-category="1346">
                                        Газовые трубы
                                        <svg class="icon icon_arrow-right-min" data-id-category="1346">
                                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                                        </svg>
                                      </a>
                                      <div class="lvl-holder-5">
                                        <ul class="header-catalog-menu__submenu lvl-5"><li class="header-catalog-menu__submenu-item" data-id-category="1459" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-metallicheskie-truby/" data-id-category="1459">Газовые металлические трубы</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1547" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-polietilenovye-truby/" data-id-category="1547">Газовые полиэтиленовые трубы</a>
                                        </li><li class="header-catalog-menu__submenu-item" data-id-category="688" style="padding-left: 40px;">
                                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gazovye-gofrirovannye-truby/" data-id-category="688">Газовые гофрированные трубы</a>
                                        </li></ul>
                                        <a href="/catalog/gazovye-truby/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                      </div>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1558" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krekingovye-truby/" data-id-category="1558">Крекинговые трубы</a>
                                    </li><li class="header-catalog-menu__submenu-item" data-id-category="1458" style="padding-left: 40px;">
                                      <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/neftyanye-truby/" data-id-category="1458">Нефтяные трубы</a>
                                    </li></ul>
                                    <a href="/catalog/truby-dlya-transportirovki-nefti-i-gaza/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                                  </div>
                                </li></ul>
                                <a href="/catalog/gazonefteprovod/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                              </div>
                            </li></ul>
                            <a href="/catalog/neftegazovaya-promyshlennost/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1951" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevaya-promyshlennost/" data-id-category="1951">
                            Пищевая промышленность
                            <svg class="icon icon_arrow-right-min" data-id-category="1951">
                              <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                            </svg>
                          </a>
                          <div class="lvl-holder-2">
                            <ul class="header-catalog-menu__submenu lvl-2"><li class="header-catalog-menu__submenu-item" data-id-category="1601" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molochnye-mufty/" data-id-category="1601">Молочные муфты</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1393" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-perehody/" data-id-category="1393">Переходы нержавеющие</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1675" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-otvody/" data-id-category="1675">Пищевые отводы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1790" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-sharovye-kran/" data-id-category="1790">Пищевые шаровые краны</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1866" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-zaglushki/" data-id-category="1866">Пищевые заглушки</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1829" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-flancy/" data-id-category="1829">Пищевые фланцы</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1740" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-obratnye-klapany/" data-id-category="1740">Пищевые обратные клапаны</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1902" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-trojniki/" data-id-category="1902">Пищевые тройники</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1933" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-krestoviny/" data-id-category="1933">Пищевые крестовины</a>
                            </li><li class="header-catalog-menu__submenu-item" data-id-category="1967" style="padding-left: 40px;">
                              <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolcevye-pishevye-lyuki/" data-id-category="1967">Кольцевые пищевые люки</a>
                            </li></ul>
                            <a href="/catalog/pishevaya-promyshlennost/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                          </div>
                        </li></ul>
                        <a href="/catalog/prochee/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li></ul>
                    <ul class="header-catalog-menu mobile-catalog" data-toggle-second=" "><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="4">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/stroitelstvo/" data-id-category="4">
                        Строительство
                        <svg class="icon icon_arrow-right-min" data-id-category="4">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2570" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kronshtejn-opor-osvesheniya/" data-id-category="2570">Кронштейны опор освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1575" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kommunikacii/" data-id-category="1575">Коммуникации жби</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1841" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/dorozhnye-ograzhdeniya/" data-id-category="1841">Дорожные ограждения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1304" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ventilyaciya/" data-id-category="1304">Вентиляция</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1460" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kanalizaciya/" data-id-category="1460">Канализация</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2525" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/opora-osvesheniya/" data-id-category="2525">Опоры освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2569" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/machta-osvesheniya/" data-id-category="2569">Мачты освещения</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1706" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/profnastil/" data-id-category="1706">Профнастил</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2538" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shumozashitnye-ekrany/" data-id-category="2538">Шумозащитные экраны</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2081" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallocherepica-mp/" data-id-category="2081">Металлочерепица</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1885" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/krany-balki/" data-id-category="1885">Кран-балка</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1924" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/metallicheskie-konstrukcii/" data-id-category="1924">Металлические конструкции</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1946" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolyuchaya-provoloka/" data-id-category="1946">Колючие проволоки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1862" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/vodostochnye-sistemy/" data-id-category="1862">Водосточные системы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1983" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpunty-larsena/" data-id-category="1983">Шпунты Ларсена</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2030" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stroitelnye-truby/" data-id-category="2030">Строительные трубы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2074" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/stalnye-fundamenty/" data-id-category="2074">Стальные фундаменты</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2085" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/ankernye-gruppy/" data-id-category="2085">Анкерные группы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1720" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/asbest/" data-id-category="1720">Асбестовые изделия</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="901" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/reshetchatye-nastily/" data-id-category="901">Решетчатые настилы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1342" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kranovye-relsy/" data-id-category="1342">Крановые рельсы</a>
                        </li></ul>
                        <a href="/catalog/stroitelstvo/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="6">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/zheleznodorozhnyj-transport/" data-id-category="6">
                        Материалы ВСП
                        <svg class="icon icon_arrow-right-min" data-id-category="6">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="2566" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/strelochnyj-perevod/" data-id-category="2566">Стрелочные переводы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2562" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bashmak-zheleznodorozhnyj/" data-id-category="2562">Башмаки железнодорожные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2563" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/gajka-klemmnaya-i-stykovaya/" data-id-category="2563">Гайки клеммные и стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2565" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/klemma-pk/" data-id-category="2565">Клеммы ПК</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2564" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shajba-klemmnaya-i-stykovaya/" data-id-category="2564">Шайбы клеммные и стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2552" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-stykovoj/" data-id-category="2552">Болты стыковые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2553" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-zakladnoj/" data-id-category="2553">Болты закладные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2554" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/bolt-klemmnyj/" data-id-category="2554">Болты клеммные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2555" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/nakladka-relsovaya/" data-id-category="2555">Накладки рельсовые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2556" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kostyl-putevoy/" data-id-category="2556">Костыли путевые</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2557" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/podkladka-pod-rels/" data-id-category="2557">Подкладки под рельс</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2559" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/shpala/" data-id-category="2559">Шпалы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2560" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolodka-tormoznaya/" data-id-category="2560">Колодки тормозные железнодорожные</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="2561" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/izolyaciya-dlya-relsov/" data-id-category="2561">Изоляция для рельсов</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="886" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-relsy/" data-id-category="886">Железнодорожные рельсы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1589" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-prokladki/" data-id-category="1589">Железнодорожные прокладки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1728" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/zheleznodorozhnye-planki/" data-id-category="1728">Железнодорожные планки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1342" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kranovye-relsy/" data-id-category="1342">Крановые рельсы</a>
                        </li></ul>
                        <a href="/catalog/zheleznodorozhnyj-transport/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="7">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/pishevaya-promyshlennost/" data-id-category="7">
                        Пищевая промышленность
                        <svg class="icon icon_arrow-right-min" data-id-category="7">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1601" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/molochnye-mufty/" data-id-category="1601">Молочные муфты</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1393" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-perehody/" data-id-category="1393">Переходы нержавеющие</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1675" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-otvody/" data-id-category="1675">Пищевые отводы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1790" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-sharovye-kran/" data-id-category="1790">Пищевые шаровые краны</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1866" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-zaglushki/" data-id-category="1866">Пищевые заглушки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="51" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-nasosy/" data-id-category="51">Пищевые насосы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1829" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-flancy/" data-id-category="1829">Пищевые фланцы</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1740" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-obratnye-klapany/" data-id-category="1740">Пищевые обратные клапаны</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1902" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-trojniki/" data-id-category="1902">Пищевые тройники</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1933" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-krestoviny/" data-id-category="1933">Пищевые крестовины</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1967" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kolcevye-pishevye-lyuki/" data-id-category="1967">Кольцевые пищевые люки</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="1505" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/pishevye-truby/" data-id-category="1505">Пищевые трубы</a>
                        </li></ul>
                        <a href="/catalog/pishevaya-promyshlennost/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="3">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/himicheskaya-promyshlennost/" data-id-category="3">
                        Химическая промышленность
                        <svg class="icon icon_arrow-right-min" data-id-category="3">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1332" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/kislotostojkie-stali/" data-id-category="1332">Кислотостойкие стали</a>
                        </li></ul>
                        <a href="/catalog/himicheskaya-promyshlennost/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="2">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/sudostroenie/" data-id-category="2">
                        Судостроение
                        <svg class="icon icon_arrow-right-min" data-id-category="2">
                          <use xlink:href="/static/img/svg/symbol/sprite.svg#arrow-right-min"></use>
                        </svg>
                      </a>
                      <div class="lvl-holder-1">
                        <ul class="header-catalog-menu__submenu lvl-1"><li class="header-catalog-menu__submenu-item" data-id-category="1454" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/alyuminievyj-polosobulb/" data-id-category="1454">Алюминиевый полособульб</a>
                        </li><li class="header-catalog-menu__submenu-item" data-id-category="341" style="padding-left: 40px;">
                          <a class="header-catalog-menu__submenu-link mobile-category" href="/catalog/sudostroitelnaya-stal/" data-id-category="341">Судостроительные стали</a>
                        </li></ul>
                        <a href="/catalog/sudostroenie/" class="header-catalog-menu__view-all">Посмотреть всё</a>
                      </div>
                    </li><li class="header-catalog-menu__item" style="padding-left: 40px;" data-id-category="1">
                      <a class="header-catalog-menu__item-link mobile-category" href="/catalog/neftegazovaya-promyshlennost/" data-id-category="1">Нефтегазовая промышленность</a>
                    </li></ul>
                    <a class="header-catalog-menu__view-all" href="/catalog/">
                      data-href="Здесь ссылка на страницу каталог продукции"&gt;Посмотреть все</a>
                  </div>
                  <div class="header-catalog-menu__wrapper-fast-order">
                    <div class="header-catalog-menu__fast-order" data-call-modal="order-click" style="background-image: url(&quot;/static/img/content/fast-order.webp&quot;); right: 16px;">
                      <div class="header-catalog-menu__fast-order-top-text">Нет времени смотреть каталог?
                      </div>
                      <div class="header-catalog-menu__fast-order-title-text">Оформите быстрый заказ!
                      </div>
                      <div class="header-catalog-menu__fast-order-description-text">Займет всего 2 минуты,
                        после чего мы вышлем подготовленный список товаров с ценами
                      </div>
                    </div>
                  </div>
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
                    <button class="header-modal__back-btn" type="button"
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
                    <button class="header-modal__back-btn" type="button"
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

<script>
import First_Header from '@/components/First_Header.vue';
import Second_Header from '@/components/Second_Header.vue';

export default {
  components: {
    First_Header,
    Second_Header,
  },
};
</script>

<script setup>

</script>

<template>
  <main class="page-index">

    <section class="hero">
      <div class="hero__video">
        <video class="lazy" autoplay="" loop="" muted="" poster="images/get-img.jpg">
          <source data-src="video.mp4" type="video/mp4">
        </video>
      </div>
      <button class="hero__video-control" aria-label="video control"></button>
      <div class="hero__box">
        <div class="container">
          <div class="hero__wrapper-title">
            <h1 class="hero__title">Металлопродукция</h1>
            <div class="hero__slider swiper-container">
              <div class="swiper-wrapper">
                <div class="swiper-slide"><p class="hero__title">в Астане</p></div>
                <div class="swiper-slide"><p class="hero__title">в Алматы</p></div>
                <div class="swiper-slide"><p class="hero__title">в Павлодаре</p></div>
                <div class="swiper-slide"><p class="hero__title">по Казахстану и СНГ</p></div>
              </div>
            </div>
          </div>
          <div class="hero__bottom mt-4">
            <div class="mt-3">
              <div class="promo-help-white__desc">
                <p style="color: white;">Обсудить все вопросы, рассчитать стоимость доставки и договориться
                  о способе оплаты вы можете с
                  нашими специалистами.</p>
              </div>
              <div class="promo-help-white__controls">
                <button class="promo-help-white__consultant btn btn_outline" style="color: white;"
                        data-modal-toggle="#modal-request">
                  Оставить заявку 📩
                </button>
                <a class="promo-help-white__consultant btn btn_outline" style="color: white;">
                  Связаться ☎️
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section-container mt-4 mt-lg-5">
      <div class="container" data-toggle-to="">
<!--        <div class="mb-3">-->
<!--          <div class="toggle toggle_reverse">-->
<!--            <label for="id-318"></label>-->
<!--            <input type="checkbox" data-toggle-event="" data-onload-unchecked="" name="name-608" id="id-318">-->
<!--            <label for="id-318">По сфере деятельности</label>-->
<!--          </div>-->
<!--        </div>-->


        <div class="row row-cols-1 row-cols-md-2 row-cols-xl-4 pt-2 pt-lg-3 catalog__container active" data-toggle-first=" ">

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>

          <div class="catalog">
            <div class="col catalog__item">
              <div class="catalog__item-head">
                <div class="catalog__item-img">
                  <img loading="lazy"
                       src="/images/black-metall.jpg"
                       alt="Черный металлопрокат">
                </div>
                <a class="catalog__item-link stretched-link" href="/catalog/chernyj-metalloprokat/">
                  Черный металлопрокат
                </a>
              </div>
              <ul class="catalog__list" aria-expanded="false">
                <li class="catalog__list-item">
                  <a href="/catalog/trubnyj-prokat/">Трубный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/ploskiy-stalnoy-prokat/">Плоский прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/fasonnyj-prokat/">Фасонный прокат</a>
                </li>
                <li class="catalog__list-item">
                  <a href="/catalog/sortovoj-prokat/">Сортовой прокат</a>
                </li>
                <li class="catalog__list-item hidden">
                  <a href="/catalog/chugunnyj-prokat/">Чугунный прокат</a>
                </li>
                <li class="show-more-wrapper">
                  <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">
                    Показать все
                  </button>
                </li>
              </ul>
            </div>
            <!-- Повторите карточки тут -->
          </div>


          <style>
            .catalog {
              display: flex; /* Используем Flexbox */
              flex-wrap: wrap; /* Позволяем карточкам переноситься на следующую строку */
              gap: 20px; /* Задаем отступы между карточками */
            }

            .catalog__item {
              flex: 1 1 calc(25% - 20px); /* Каждая карточка занимает 25% ширины, учитывая отступы */
              box-sizing: border-box; /* Учитываем padding и border в ширину элемента */
            }

            @media (max-width: 768px) {
              .catalog__item {
                flex: 1 1 calc(50% - 10px); /* 2 карточки в ряд на планшетах */
              }
            }

            @media (max-width: 480px) {
              .catalog__item {
                flex: 1 1 100%; /* 1 карточка в ряд на мобильных */
              }
            }

          </style>
        </div>




<!--        <div class="row row-cols-1 row-cols-md-2 row-cols-xl-4 pt-2 pt-lg-3 catalog__container"-->
<!--             data-toggle-second=" ">-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/stroitelstvo_sFpGLPz.webp"-->
<!--                     alt="Строительство">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/stroitelstvo/">-->
<!--                Строительство-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/kronshtejn-opor-osvesheniya/">Кронштейны опор освещения</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/kommunikacii/">Коммуникации жби</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/dorozhnye-ograzhdeniya/">Дорожные ограждения</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/ventilyaciya/">Вентиляция</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kanalizaciya/">Канализация</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/opora-osvesheniya/">Опоры освещения</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/machta-osvesheniya/">Мачты освещения</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/shumozashitnye-ekrany/">Шумозащитные экраны</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/profnastil/">Профнастил</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/metallocherepica-mp/">Металлочерепица</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/krany-balki/">Кран-балка</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/metallicheskie-konstrukcii/">Металлические конструкции</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kolyuchaya-provoloka/">Колючие проволоки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/vodostochnye-sistemy/">Водосточные системы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/shpunty-larsena/">Шпунты Ларсена</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/stroitelnye-truby/">Строительные трубы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/stalnye-fundamenty/">Стальные фундаменты</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/ankernye-gruppy/">Анкерные группы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/asbest/">Асбестовые изделия</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/reshetchatye-nastily/">Решетчатые настилы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kranovye-relsy/">Крановые рельсы</a>-->
<!--              </li>-->

<!--              <li class="show-more-wrapper">-->
<!--                <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">-->
<!--                  Показать все-->
<!--                </button>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </div>-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/photo_2022-03-02_16-18-40.webp"-->
<!--                     alt="Железнодорожный транспорт">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/zheleznodorozhnyj-transport/">-->
<!--                Материалы ВСП-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/nakladka-relsovaya/">Накладки рельсовые</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/bolt-zakladnoj/">Болты закладные</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/kostyl-putevoy/">Костыли путевые</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/bolt-stykovoj/">Болты стыковые</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/bolt-klemmnyj/">Болты клеммные</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/strelochnyj-perevod/">Стрелочные переводы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/shajba-klemmnaya-i-stykovaya/">Шайбы клеммные и стыковые</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/klemma-pk/">Клеммы ПК</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/gajka-klemmnaya-i-stykovaya/">Гайки клеммные и стыковые</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/bashmak-zheleznodorozhnyj/">Башмаки железнодорожные</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/izolyaciya-dlya-relsov/">Изоляция для рельсов</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kolodka-tormoznaya/">Колодки тормозные железнодорожные</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/shpala/">Шпалы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/podkladka-pod-rels/">Подкладки под рельс</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/zheleznodorozhnye-relsy/">Железнодорожные рельсы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/zheleznodorozhnye-shpaly/">Железнодорожные шпалы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/zheleznodorozhnye-prokladki/">Железнодорожные прокладки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/zheleznodorozhnye-kolodki/">Железнодорожные колодки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/zheleznodorozhnye-planki/">Железнодорожные планки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kranovye-relsy/">Крановые рельсы</a>-->
<!--              </li>-->

<!--              <li class="show-more-wrapper">-->
<!--                <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">-->
<!--                  Показать все-->
<!--                </button>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </div>-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/pishevaya-promyshlennost.webp"-->
<!--                     alt="Пищевая промышленность">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/pishevaya-promyshlennost/">-->
<!--                Пищевая промышленность-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/molochnye-mufty/">Молочные муфты</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/pishevye-perehody/">Переходы нержавеющие</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/pishevye-otvody/">Пищевые отводы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/pishevye-sharovye-kran/">Пищевые шаровые краны</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-zaglushki/">Пищевые заглушки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-nasosy/">Пищевые насосы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-flancy/">Пищевые фланцы</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-obratnye-klapany/">Пищевые обратные клапаны</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-trojniki/">Пищевые тройники</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-krestoviny/">Пищевые крестовины</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/kolcevye-pishevye-lyuki/">Кольцевые пищевые люки</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item hidden">-->
<!--                <a href="/catalog/pishevye-truby/">Пищевые трубы</a>-->
<!--              </li>-->

<!--              <li class="show-more-wrapper">-->
<!--                <button class="show-more-btn" aria-expanded="false" aria-label="expand" tabindex="0" style="color: #c30a08;">-->
<!--                  Показать все-->
<!--                </button>-->
<!--              </li>-->
<!--            </ul>-->
<!--          </div>-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/himicheskaya-promyshlennost_2aCgZqH.webp"-->
<!--                     alt="Химическая промышленность">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/himicheskaya-promyshlennost/">-->
<!--                Химическая промышленность-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/kislotostojkie-stali/">Кислотостойкие стали</a>-->
<!--              </li>-->

<!--            </ul>-->
<!--          </div>-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/sudostroenie_B6ZPeRV.webp"-->
<!--                     alt="Судостроение">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/sudostroenie/">-->
<!--                Судостроение-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/alyuminievyj-polosobulb/">Алюминиевый полособульб</a>-->
<!--              </li>-->

<!--              <li class="catalog__list-item">-->
<!--                <a href="/catalog/sudostroitelnaya-stal/">Судостроительные стали</a>-->
<!--              </li>-->

<!--            </ul>-->
<!--          </div>-->

<!--          <div class="col catalog__item">-->
<!--            <div class="catalog__item-head">-->
<!--              <div class="catalog__item-img">-->
<!--                <img loading="lazy"-->
<!--                     src="/resize/200/media/uploads/catalog/category_extra/neftegazovaya-promyshlennost_r9WhXnu.webp"-->
<!--                     alt="Нефтегазовая промышленность">-->
<!--              </div>-->
<!--              <a class="catalog__item-link stretched-link" href="/catalog/neftegazovaya-promyshlennost/">-->
<!--                Нефтегазовая промышленность-->
<!--              </a>-->
<!--            </div>-->
<!--            <ul class="catalog__list" aria-expanded="false">-->

<!--            </ul>-->
<!--          </div>-->

<!--        </div>-->
      </div>
    </section>


    <section class="about">
      <div class="about__top" style="border-radius: 15px 15px 0px 0px;">
        <div class="container about__top-content">
          <p class="about__suptitle aos-init aos-animate" data-aos="fade-up" data-aos-delay="100">
            О компании
          </p>
          <div class="row align-items-center">
            <!-- Заменяем видео изображением с текстом -->
            <div class="col-lg-6 col-xl-6 about__image">
              <div class="image-box aos-init aos-animate" data-aos="fade-up" data-aos-delay="50">
                <img style="border-radius: 10px;" src="/images/black-metall.jpg" alt="О компании" class="img-fluid rounded">
              </div>
            </div>
            <!-- Описание компании -->
            <div class="col-lg-6 col-xl-6">
              <h2 class="about__title title aos-init aos-animate" data-aos="fade-up" data-aos-delay="50">
                Группа Компаний «Интерстилс»
              </h2>
              <div class="about__desc aos-init aos-animate" data-aos="fade-up" data-aos-delay="100">
                <p>Группа компаний «Интерстилс» - надёжный поставщик металлопроката и сопутствующих товаров: оборудования для пищевой, горнодобывающей, автомобильной, химической и нефтегазовой промышленности, сферы строительства, авиа- и судостроения, а также кабельной продукции, сварочных материалов, метизов, металлургического сырья, бурового и рентгенозащитного оборудования.</p>
                <p>Мы работаем только с оптовыми покупателями – коммерческими и государственными организациями. Высококвалифицированные эксперты коммерческого отдела помогают клиентам собрать заказ любой сложности.</p>
              </div>
            </div>
          </div>
          <div class="row mt-4">
            <!-- Информация о сотрудничестве -->
            <div class="col-lg-6 col-xl-6">
              <div class="about__box">
                <h3 class="about__box-title aos-init aos-animate" data-aos="fade-up" data-aos-delay="50">
                  Сотрудничество с командой ГК «Интерстилс»
                </h3>
                <div class="about__box-desc aos-init aos-animate" data-aos="fade-up" data-aos-delay="100">
                  <p>Благодаря широкой сети филиалов в крупнейших городах Казахстана мы доставляем заказы до любого производственного или складского объекта точно в срок и с соблюдением всех условий перевозки данного вида груза.</p>
                  <p>У нас в наличии всегда имеется широкий ассортимент готовой продукции – всего более 6 млн наименований. Весь товар произведен в строгом соответствии с отраслевыми стандартами и имеет сертификаты качества.</p>
                </div>
              </div>
            </div>
            <!-- Изображение, заменяющее видео -->
            <div class="col-lg-6 col-xl-6 about__image">
              <div class="image-box aos-init aos-animate" data-aos="fade-up" data-aos-delay="50">
                <img style="border-radius: 10px;" src="/images/nerzhaveyuschiy.jpg" alt="Склад" class="img-fluid rounded">
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>



    <!--    <section class="about">-->
    <!--        <div class="about__top">-->
    <!--            <div class="about__video">-->
    <!--                <video class="lazy" autoplay="" loop="" muted="" poster="/static/video/about-poster.webp">-->
    <!--                    <source data-src="" type="video/mp4">-->
    <!--                </video>-->
    <!--            </div>-->
    <!--            <div class="container about__top-content">-->
    <!--                <p class="about__suptitle" data-aos="fade-up" data-aos-delay="100">О компании</p>-->
    <!--                <div class="row">-->
    <!--                    <div class="col-lg-6 col-xl-6">-->
    <!--                        <h2 class="about__title title" data-aos="fade-up" data-aos-delay="50">-->
    <!--                            Вам требуется надежный поставщик металлопроката?-->
    <!--                        </h2>-->
    <!--                        <div class="about__desc" data-aos="fade-up" data-aos-delay="100">-->
    <!--                            <p></p>-->
    <!--                            <p>Мы - ваше идеальное решение! Мы предлагаем широкий ассортимент металлопроката высокого-->
    <!--                                качества по конкурентным ценам. Наша компания специализируется на поставке черного и-->
    <!--                                цветного металлопроката, а также изделий из нержавеющей стали. Мы гордимся нашим-->
    <!--                                обширным выбором и возможностью доставки продукции в удобное для вас время. Мы понимаем,-->
    <!--                                что каждый клиент имеет свои уникальные потребности. Поэтому мы предлагаем редкие марки-->
    <!--                                стали и специальные стали, чтобы удовлетворить даже самые требовательные проекты. Наша-->
    <!--                                команда профессионалов также предоставляет услуги металлообработки. Мы осуществляем-->
    <!--                                резку металла, гибку, обработку отверстий и нанесение защитных покрытий. Наш опыт и-->
    <!--                                навыки позволяют нам выполнить любые задачи с высокой точностью и качеством.<br><br>-->
    <!--                                Мы работаем только с оптовыми покупателями – коммерческими и государственными-->
    <!--                                организациями. Высококвалифицированные эксперты коммерческого отдела помогают клиентам-->
    <!--                                собрать заказ любой сложности.</p>-->
    <!--                        </div>-->
    <!--                    </div>-->
    <!--                    <div class="col-lg-6 col-xl-6">-->
    <!--                        <div class="about__box">-->
    <!--                            <h3 class="about__box-title" data-aos="fade-up" data-aos-delay="50">-->
    <!--                                сотрудничество с командой «Стальная федерация»-->
    <!--                            </h3>-->
    <!--                            <div class="about__box-desc" data-aos="fade-up" data-aos-delay="100">-->
    <!--                                <p></p>-->
    <!--                                <p>Мы гордимся тем, что являемся надежным партнером для многих компаний в Алматы. Наша-->
    <!--                                    репутация основана на высоком уровне обслуживания и доверии наших клиентов. Если вам-->
    <!--                                    требуется металлопрокат в Алматы, обратитесь к нам для получения четкого решения. Мы-->
    <!--                                    поможем вам выбрать оптимальные материалы, рассчитаем стоимость заказа и гарантируем-->
    <!--                                    своевременную отгрузку. С нами вы можете быть уверены в качестве, надежности и-->
    <!--                                    профессионализме.-->
    <!--                                    <br><br><br><br><br>-->
    <!--                                    У нас в наличии всегда имеется широкий ассортимент готовой продукции – всего более 6-->
    <!--                                    млн наименований. Весь товар произведен в строгом соответствии с отраслевыми-->
    <!--                                    стандартами и имеет сертификаты качества.</p>-->
    <!--                            </div>-->
    <!--                        </div>-->
    <!--                    </div>-->
    <!--                </div>-->
    <!--            </div>-->
    <!--        </div>-->
    <!--    </section>-->


<!--    <div class="container section-container">-->
<!--      <div class="slider">-->
<!--        <div class="slider__head">-->
<!--          <div class="slider__head-row">-->
<!--            <div class="slider__title">Специальные предложения</div>-->
<!--            <div class="slider__controls">-->
<!--              <button class="btn-control slider-prev">-->
<!--                <svg class="icon icon_prev">-->
<!--                  <use xlink:href="images/sprite.svg#prev"></use>-->
<!--                </svg>-->
<!--              </button>-->
<!--              <button class="btn-control slider-next">-->
<!--                <svg class="icon icon_next">-->
<!--                  <use xlink:href="images/sprite.svg#next"></use>-->
<!--                </svg>-->
<!--              </button>-->
<!--            </div>-->
<!--          </div>-->
<!--          <div>-->
<!--            <a class="link-more" href="/spec/">Посмотреть все-->
<!--              <i class="fi fi-rr-arrow-small-right"></i>-->
<!--            </a>-->
<!--          </div>-->
<!--        </div>-->
<!--        <div class="swiper">-->
<!--          <div class="swiper-wrapper">-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img"-->
<!--                     href="/product/pretsizionnyj-krug-s-vysokim-elektricheskim-soprotivleniem-10-mm-h27ju5t-gost-12766-4-90/">-->
<!--                    <img src="images/precizionnye-krugi_zpnZSaU.webp"-->
<!--                         alt="Прецизионный круг с высоким электрическим сопротивлением 10 мм Х27Ю5Т ГОСТ 12766.4-90"-->
<!--                         loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info"-->
<!--                   href="/product/pretsizionnyj-krug-s-vysokim-elektricheskim-soprotivleniem-10-mm-h27ju5t-gost-12766-4-90/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Прецизионный круг с высоким электрическим сопротивлением 10 мм Х27Ю5Т ГОСТ 12766.4-90</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Диаметр</td>-->
<!--                      <td>10 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>ГОСТ</td>-->
<!--                      <td>ГОСТ 12766.4-90</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Тип сплава</td>-->
<!--                      <td>с высоким электрическим сопротивлением</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>Х27Ю5Т</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="3509450">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img"-->
<!--                     href="/product/polirovannaja-svarochnaja-provoloka-3-mm-sv-06h19n9t-gost-2246-70/">-->
<!--                    <img src="images/polirovannaya-svarochnaya-provoloka_EMHJmMK.webp"-->
<!--                         alt="Полированная сварочная проволока 3 мм Св-06Х19Н9Т ГОСТ 2246-70"-->
<!--                         loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info"-->
<!--                   href="/product/polirovannaja-svarochnaja-provoloka-3-mm-sv-06h19n9t-gost-2246-70/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Полированная сварочная проволока 3 мм Св-06Х19Н9Т ГОСТ 2246-70</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Диаметр</td>-->
<!--                      <td>3 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>ГОСТ</td>-->
<!--                      <td>ГОСТ 2246-70</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>Св-06Х19Н9Т</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="3487255">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img" href="/product/nikelevaya-truba-05h005-np2/">-->
<!--                    <img src="images/nikelevye-truby_Av9lo35.webp" alt="Никелевая труба 0,5х0,05 мм НП2"-->
<!--                         loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info" href="/product/nikelevaya-truba-05h005-np2/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Никелевая труба 0,5х0,05 мм НП2</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Наружный диаметр</td>-->
<!--                      <td>0.5 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>НП2</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="2972578">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img" href="/product/sudovoj-list-5-mm-rsv/">-->
<!--                    <img src="images/%D0%91%D1%80%D0%BE%D0%BD%D0%B5%D0%BB%D0%B8%D1%81%D1%82%D1%8B_e2w1mB1.png"-->
<!--                         alt="Судовой лист 5 мм РСВ" loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info" href="/product/sudovoj-list-5-mm-rsv/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Судовой лист 5 мм РСВ</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Толщина</td>-->
<!--                      <td>5 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>РСВ</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="7434014">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img"-->
<!--                     href="/product/elektrod-dlja-svarki-stali-3-mm-uoni-1355-gost-9467-75/">-->
<!--                    <img src="images/elektrody-dlya-svarki-stali_U8lGG66.webp"-->
<!--                         alt="Электрод для сварки стали 3 мм УОНИ-13/55 ГОСТ 9467-75" loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info"-->
<!--                   href="/product/elektrod-dlja-svarki-stali-3-mm-uoni-1355-gost-9467-75/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Электрод для сварки стали 3 мм УОНИ-13/55 ГОСТ 9467-75</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Диаметр</td>-->
<!--                      <td>3 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>ГОСТ</td>-->
<!--                      <td>ГОСТ 9467-75</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>УОНИ-13/55</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="6151204">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img"-->
<!--                     href="/product/djuralevaja-kruglaja-truba-120-mm-d16t-gost-18482-2018/">-->
<!--                    <img src="images/dyuralyuminievye-truby_1T2ydXY_Bw5SA6T.webp"-->
<!--                         alt="Дюралевая круглая труба 120 мм Д16Т ГОСТ 18482-2018" loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info"-->
<!--                   href="/product/djuralevaja-kruglaja-truba-120-mm-d16t-gost-18482-2018/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Дюралевая круглая труба 120 мм Д16Т ГОСТ 18482-2018</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Наружный диаметр</td>-->
<!--                      <td>120 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>ГОСТ</td>-->
<!--                      <td>ГОСТ 18482-2018</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>Д16Т</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="1644967">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--            <div class="swiper-slide">-->
<!--              <div class="sentence-card">-->
<!--                <div class="sentence-card__top">-->
<!--                  <a class="sentence-card__img"-->
<!--                     href="/product/otsinkovannyj-list-0_8x1250-mm-08ps-gost-14918-2020/">-->
<!--                    <img src="images/ocinkovannye-listy_TYWU7oN.webp"-->
<!--                         alt="Оцинкованный лист 0.8x1250 мм 08пс ГОСТ 14918-2020" loading="lazy">-->
<!--                  </a>-->
<!--                  <button class="sentence-card__info-btn" data-tippy-content="<p>-->
<!--            Внешний вид изделия может отличаться от изображения, представленного на сайте-->

<!--            </p>-->
<!--        ">-->
<!--                    <svg class="icon icon_warning">-->
<!--                      <use xlink:href="images/sprite.svg#warning"></use>-->
<!--                    </svg>-->
<!--                  </button>-->
<!--                </div>-->
<!--                <a class="sentence-card__info"-->
<!--                   href="/product/otsinkovannyj-list-0_8x1250-mm-08ps-gost-14918-2020/">-->
<!--                  <span class="sentence-card__title ellipsis-js-50">Оцинкованный лист 0.8x1250 мм 08пс ГОСТ 14918-2020</span>-->

<!--                </a>-->
<!--                <a class="sentence-card__characteristics">-->
<!--                  <table>-->

<!--                    <tbody>-->
<!--                    <tr>-->
<!--                      <td>Толщина</td>-->
<!--                      <td>0.8 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Марка</td>-->
<!--                      <td>08пс</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>Ширина</td>-->
<!--                      <td>1250 мм</td>-->
<!--                    </tr>-->

<!--                    <tr>-->
<!--                      <td>ГОСТ</td>-->
<!--                      <td>ГОСТ 14918-2020</td>-->
<!--                    </tr>-->

<!--                    </tbody>-->
<!--                  </table>-->
<!--                </a>-->
<!--                <div class="sentence-card__price">-->
<!--                            <span class="sentence-card__price-link">-->
<!--                                <span class="sentence-card__price-label">-->
<!--                                    Цена-->
<!--                                </span>-->
<!--                                <b class="sentence-card__price-price">-->
<!--                                    По уточнению-->
<!--                                </b>-->
<!--                                <span class="sentence-card__price-info"-->
<!--                                      data-tippy-content="Не является публичной офертой">-->
<!--                                    <svg class="icon icon_question">-->
<!--                                      <use xlink:href="images/sprite.svg#question"></use>-->
<!--                                    </svg>-->
<!--                                </span>-->
<!--                            </span>-->
<!--                </div>-->
<!--                <div class="sentence-card__footer">-->
<!--                  <button class="sentence-card__add btn-slide" data-call-modal="cart"-->
<!--                          data-product-id="15316940">-->
<!--                                <span class="btn btn-slide__box">Купить-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                        <svg class="icon icon_add">-->
<!--                                            <use xlink:href="images/sprite.svg#add"></use>-->
<!--                                        </svg>-->
<!--                                        <svg class="btn-slide__box-preload icon icon_preload">-->
<!--                                            <use xlink:href="images/sprite.svg#preload"></use>-->
<!--                                        </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                    <span class="btn btn-slide__box">Добавлено-->
<!--                                    <span class="btn-slide__box-icons">-->
<!--                                      <svg class="icon icon_add-ok">-->
<!--                                        <use xlink:href="images/sprite.svg#add-ok"></use>-->
<!--                                      </svg>-->
<!--                                    </span>-->
<!--                                </span>-->
<!--                  </button>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->

<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->


    <!--    <section class="news">-->
    <!--        <div class="container news-related">-->
    <!--            <header class="activity__header">-->
    <!--                <div class="activity__header-top">-->
    <!--                    <h2 class="activity__title title">НОВОСТИ КОМПАНИИ</h2>-->
    <!--                    <div class="activity__btns">-->
    <!--                        <button class="news__prev btn-control">-->
    <!--                            <svg class="icon icon_prev">-->
    <!--                                <use xlink:href="images/sprite.svg#prev"></use>-->
    <!--                            </svg>-->
    <!--                        </button>-->
    <!--                        <button class="news__next btn-control">-->
    <!--                            <svg class="icon icon_next">-->
    <!--                                <use xlink:href="images/sprite.svg#next"></use>-->
    <!--                            </svg>-->
    <!--                        </button>-->
    <!--                    </div>-->
    <!--                </div>-->
    <!--                <div><a class="link-more" href="/news/">Все новости-->
    <!--                    <svg class="icon icon_arrow-right">-->
    <!--                        <use xlink:href="images/sprite.svg#arrow-right"></use>-->
    <!--                    </svg>-->
    <!--                </a></div>-->
    <!--            </header>-->
    <!--            <div class="news__slider swiper-container">-->
    <!--                <div class="swiper-wrapper">-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card"-->
    <!--                           href="/news/353-sibirskaya-promyshlennaya-gruppa-vnesla-svoj-vklad-v-sozdanie-atomnogo-ledokola-chukotka/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/1._%D0%A1%D0%B8%D0%B1%D0%B8%D1%80%D1%81%D0%BA%D0%B0%D1%8F.jpg"-->
    <!--                                     alt="Сибирская Промышленная Группа внесла свой вклад в создание атомного ледокола "-->
    <!--                                     Чукотка""="" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">03 December</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>638</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Сибирская Промышленная Группа внесла свой вклад в создание атомного ледокола "Чукотка"</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/348-s-dnem-respubliki-2024/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/1400%D1%85390_fMJFtjA.jpg" alt="С Днем Республики 2024!"-->
    <!--                                     loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">24 October</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>118</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">С Днем Республики 2024!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/339-uchastie-v-gonke-geroev/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/%D0%A3%D1%87%D0%B0%D1%81%D1%82%D0%B8%D0%B5_%D0%B2_%D0%93%D0%BE%D0%BD%D0%BA%D0%B5_%D0%93%D0%B5%D1%80%D0%BE%D0%B5%D0%B2.jpg"-->
    <!--                                     alt="Участие в гонке Героев!" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">17 September</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>3635</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Участие в гонке Героев!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card"-->
    <!--                           href="/news/338-v-ssha-podtverzhdeny-poshliny-na-tajvanskij-nerzhaveyushij-prokat/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/%D1%82%D0%B0%D0%B9%D0%B2%D0%B0%D0%BD%D1%8C%D1%81%D0%BA%D0%B8%D0%B9_%D0%BD%D0%B5%D1%80%D0%B6%D0%B0%D0%B2%D0%B5%D1%8E%D1%89%D0%B8%D0%B9_%D0%BF%D1%80%D0%BE%D0%BA%D0%B0%D1%82.jpg"-->
    <!--                                     alt="В США подтверждены пошлины на тайваньский нержавеющий прокат" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">17 September</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>2464</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">В США подтверждены пошлины на тайваньский нержавеющий прокат</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/335-mnaj-gaz-kesheni-yzmetkerlerini-kni-tty-bolsyn/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/%D0%A8%D0%B0%D0%BF%D0%BA%D0%B0_%D0%BD%D0%BE%D0%B2%D0%BE%D1%81%D1%82%D0%B8.jpg"-->
    <!--                                     alt="Мұнай-газ кешені қызметкерлерінің күні құтты болсын!" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">30 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>173</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Мұнай-газ кешені қызметкерлерінің күні құтты болсын!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/299-azastan-respublikasyny-konstituciya-kni-tty-bolsyn/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/%D1%81_%D0%B4%D0%BD%D0%B5%D0%BC_%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D0%B8%D1%82%D1%83%D1%86%D0%B8%D0%B8.jpg"-->
    <!--                                     alt="Қазақстан Республикасының Конституция күні құтты болсын!" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">29 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>231</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Қазақстан Республикасының Конституция күні құтты болсын!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/297-kenshiler-kni-tty-bolsyn/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/%D0%B4%D0%BB%D1%8F_%D0%BA%D0%B7_%D1%88%D0%B0%D0%BF%D0%BA%D0%B0.jpg"-->
    <!--                                     alt="Кеншілер күні құтты болсын!" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">23 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>261</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Кеншілер күні құтты болсын!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card"-->
    <!--                           href="/news/264-stroitelstvo-administrativnogo-zdaniya-volgo-vyatskogo-glavnogo-upravleniya-centralnogo-banka-rf-v-g-nizhnij-novgorod/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/news-buildings.jpg"-->
    <!--                                     alt="Строительство Административного здания Центрального Банка" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">21 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>3388</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Строительство Административного здания Центрального Банка</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/259-rylysshylar-kni-tty-bolsyn/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/1400%D1%85390_%D0%9A%D0%97.webp" alt="Құрылысшылар күні құтты болсын!"-->
    <!--                                     loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">09 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>192</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Құрылысшылар күні құтты болсын!</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                    <div class="swiper-slide">-->
    <!--                        <a class="news-card" href="/news/258-birzhevye-ceny-na-alyuminij-prodolzhayut-snizhatsya/">-->
    <!--                            <div class="news-card__img">-->
    <!--                                <img src="images/1400%D1%85390__8tVTxc9.webp"-->
    <!--                                     alt="Биржевые цены на алюминий продолжают снижаться" loading="lazy">-->
    <!--                            </div>-->
    <!--                            <div class="news-related__info">-->
    <!--                                <div class="news-related__info-time">08 August</div>-->
    <!--                                <div class="news-related__info-visible">-->
    <!--                                    <svg class="icon icon_eye">-->
    <!--                                        <use xlink:href="images/sprite.svg#eye"></use>-->
    <!--                                    </svg>-->
    <!--                                    <span>3653</span>-->
    <!--                                </div>-->
    <!--                            </div>-->
    <!--                            <span class="news-card__title">Биржевые цены на алюминий продолжают снижаться</span>-->
    <!--                        </a>-->
    <!--                    </div>-->

    <!--                </div>-->
    <!--            </div>-->
    <!--        </div>-->
    <!--    </section>-->

    <div class="container mt-5">
      <div class="row">
        <div class="col-12">
          <div class="catalog__promo-help-white promo-help-white"
               style="background-image: url(/static/img/content/promo-help-white.webp);">
            <div class="promo-help-white__inner">
              <div class="promo-help-white__title">Нужна помощь?</div>
              <div class="promo-help-white__desc">
                <p>Обсудить все вопросы, рассчитать стоимость доставки и договориться о способе оплаты вы
                  можете с
                  нашими специалистами.</p>
              </div>
              <div class="promo-help-white__controls">
                <button class="promo-help-white__order btn" data-modal-toggle="#modal-request" style="background-color: #c30a08;">
                  <span style="color: white;">Оставить заявку</span>

                </button>
                <a class="promo-help-white__consultant btn btn_outline" href="javascript:void(0);"
                   onclick="jivo_api.open()">
                  Онлайн консультант 👤
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </main>
</template>

<style scoped>

</style>


<script>
import Swiper from 'swiper';
import 'swiper/swiper-bundle.min.css';

export default {
  data() {
    return {
      swiper: null,
      items: [
        { /* Данные для карточек */ },
        { /* Данные для карточек */ },
        { /* Данные для карточек */ },
      ],
    };
  },
  mounted() {
    this.swiper = new Swiper('.swiper', {
      loop: true,
      slidesPerView: 1,
      spaceBetween: 10,
      navigation: {
        nextEl: '.slider-next',
        prevEl: '.slider-prev',
      },
    });
  },
};
</script>

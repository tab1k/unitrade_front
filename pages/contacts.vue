<style>

</style>

<template>
  <main>

    <div class="container">

      <div class="bread-crumbs">
        <div class="container">
          <ul class="bread-crumbs__list" itemscope="" itemtype="https://schema.org/BreadcrumbList">


            <li class="bread-crumbs__item" itemprop="itemListElement" itemscope=""
                itemtype="https://schema.org/ListItem">
              <a class="bread-crumbs__link" href="/" itemprop="item">
                      <span itemprop="name">
                          Главная
                      </span>
              </a>
              <meta itemprop="position" content="1">
            </li>


            <li class="bread-crumbs__item" itemprop="itemListElement" itemscope=""
                itemtype="https://schema.org/ListItem">
              <div class="bread-crumbs__link" itemprop="item"><span itemprop="name">Контакты</span></div>
              <meta itemprop="position" content="2">
            </li>


          </ul>
        </div>
      </div>

    </div>


    <div class="contacts">
      <div class="container">
        <h1 class="title title_page">Контакты</h1>
        <div class="row">
          <div class="col-12">
            <section class="contacts__map">
              <div class="contacts-map">
                <div id="contacts-map">
                  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2905.42732349898!2d76.89413907670125!3d43.26342267112328!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3883695fb8e9401f%3A0x20429f7741484b2c!2z0L_RgC3Rgi4g0KDQsNC50YvQvNCx0LXQutCwIDI1MSwg0JDQu9C80LDRgtGLIDA1MDAwMA!5e0!3m2!1sru!2skz!4v1735086414522!5m2!1sru!2skz" width="1180px" height="330px" style="border:0; border-radius: 15px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                  <div id="ymap_ctrl_display">
                    <h4>Чтобы изменить масштаб, прокручивайте карту, удерживая клавишу Ctrl.</h4>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>

        <div class="row">
          <div class="col-12">
            <section class="contacts__adress">
              <div class="contacts-adress">
                <div class="row contacts-adress__adress">
                  <div class="col-lg-5">
                    <h2 class="col-lg-12 contacts-adress__office">Отдел продаж</h2>
                    <div class="col-lg-12 contacts-adress__time">
                      <p>Пн-Чт: с 9:00 до 18:00, Пт: с 9:00 до 17:00</p>
                    </div>
                  </div>
                  <div class="col-lg-7">
                    <div class="row">
                      <div class="col-lg-12 contacts-adress__title">Адрес</div>
                      <div class="col-lg-12 contacts-adress__desc">Улица Сыганак, 54а, БЦ "А", офис 1001, 10 этаж</div>
                    </div>
                    <div class="row">
                      <div class="col-lg">
                        <div class="contacts-adress__title">
                          для Астаны
                        </div>
                        <div class="contacts-adress__desc">+7 (717) 264 02 97</div>
                      </div>
                      <div class="col-lg">
                        <div class="contacts-adress__title">Email</div>
                        <div class="contacts-adress__desc mgo-email" id="contacts-adress__email">
                          <span class="mgo-email">astana@isteels.kz</span>
                          <span data-tippy-content="Cкопировать">
                                                    <svg class="icon icon_copy">
                                                      <use xlink:href="/static/img/svg/symbol/sprite.svg#copy"></use>
                                                    </svg>
                                                </span>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="row contacts-adress__details">
                  <div class="col-lg-5">
                    <h2 class="col-lg-12 contacts-adress__detail">Реквизиты</h2>
                    <a class="col-lg-12 contacts-adress__download" href="/contacts_pdf/">
                      Скачать документом (.pdf)
                    </a>
                  </div>
                  <div class="col-lg-7">
                    <div class="row">

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">БИН</div>
                        <div class="contacts-adress__desc">221040008280</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">ИИК</div>
                        <div class="contacts-adress__desc">KZ808562203125974472</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">Банк</div>
                        <div class="contacts-adress__desc">АО «Банк ЦентрКредит»</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">БИК</div>
                        <div class="contacts-adress__desc">KCJBKZKX</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">Директор</div>
                        <div class="contacts-adress__desc">Иванов Павел Андреевич</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">Телефон</div>
                        <div class="contacts-adress__desc">+7 (717) 264 05 60</div>
                      </div>

                      <div class="col-lg" style="min-width: 50%">
                        <div class="contacts-adress__title">Адрес эл. почты</div>
                        <div class="contacts-adress__desc">ivanov@isteels.kz</div>
                      </div>

                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>
        <div class="container">
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
      </div>
    </div>


  </main>
</template>
<script setup lang="ts">
</script>

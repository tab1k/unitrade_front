<script setup>

</script>

<template>
  <footer class="footer" itemscope="" itemtype="https://schema.org/WPFooter">
    <div class="container">
      <div class="footer__top">
        <div class="row">
          <div class="col-lg-auto col-sm-6">

                    <span class="footer__logo logo">
                            <img style="height: 50px; width: 50px;" src="images/logo.png" alt="Стальфед">
                        </span>

          </div>
          <div class="footer__top_subscribe d-flex justify-content-end col-md col-sm-6">
            <div class="footer__top_subscribe_text">
              <div class="footer__menu-link">Подписка на рассылку</div>
              <div class="footer__menu-item_title-link">Регулярные спецпредложения и скидки</div>
            </div>
            <form class="need-validate footer__top_subscribe_input" id="subscribe_footer" method="post"
                  data-need-notification="true" data-action="/informer/form_send/subscribe_footer/">
              <input class="input__input" type="email" name="email" placeholder="Электронная почта"
                     required="">
              <button class="subscription_footer" type="submit">
                <svg class="icon icon_arrow-right">
                  <use xlink:href="images/sprite.svg#arrow-right"></use>
                </svg>
              </button>
            </form>
          </div>
        </div>
      </div>
      <div class="footer__middle">
        <div class="row" itemscope="" itemtype="https://schema.org/Organization">
          <meta itemprop="name" content="ООО ГК «Стальная федерация»">
          <div class="col-lg-6 col-md-6">
            <div class="footer__middle-up">
              <div class="footer__content-left" itemscope="" itemtype="https://schema.org/PostalAddress"
                   itemprop="address">
                <div class="footer__menu-item_title-link">Контакты</div>
                <meta itemprop="addressLocality" content="Алматы">
                <button class="footer__city link">
                                <span class="link__icon">
                                  <svg class="icon icon_mark">
                                    <use xlink:href="images/sprite.svg#mark"></use>
                                  </svg>
                                </span>
                  Астана
                </button>
                <address class="footer__address-city" itemprop="streetAddress">
                  Улица Райымбека
                </address>
              </div>
            </div>
            <div class="footer__middle-down">
              <a class="footer__phone link mgo-number" href="tel:+77172640297">
                            <span class="link__icon">
                                    <svg class="icon icon_phone">
                                      <use xlink:href="images/sprite.svg#phone"></use>
                                    </svg>
                            </span>
                <span class="mgo-number__target">+7 (707) 777 28 17</span>
              </a>
              <meta itemprop="telephone" content="+7 (707) 777 28 17">

              <a class="footer__email link mgo-email" itemprop="email" href="mailto:zakaz@steelfed.kz">
                            <span class="link__icon">
                                <svg class="icon icon_email">
                                  <use xlink:href="images/sprite.svg#email"></use>
                                </svg>
                            </span>
                <span class="mgo-email">zakaz@steelfed.kz</span>
              </a>
            </div>
          </div>
          <div class="ml-auto col-lg-6 col-md-6">
            <nav class="footer__nav">
              <div>
                <div class="footer__menu-item footer__menu-item_title">
                  <a class="footer__menu-link footer__menu-item_title-link" href="#">Покупателям</a>
                </div>
                <ol class="footer__menu">
                  <!--noindex-->
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/catalog/">
                      Весь каталог
                    </a>
                  </li>
                  <!--/noindex-->
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/contacts/">
                      Контакты
                    </a>
                  </li>
                </ol>
              </div>
              <div>
                <div class="footer__menu-item footer__menu-item_title">
                  <a class="footer__menu-link footer__menu-item_title-link" href="#">Меню сайта</a>
                </div>
                <ol class="footer__menu">
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/services/">
                      Услуги
                    </a>
                  </li>
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/spec/">
                      Спецпредложения
                    </a>
                  </li>
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="#">
                      Покупателям
                    </a>
                  </li>

                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/contacts/">
                      Контакты
                    </a>
                  </li>
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/about/">
                      О компании
                    </a>
                  </li>
                  <li class="footer__menu-item">
                    <a class="footer__menu-link" href="/careers/">Вакансии</a>
                  </li>
                </ol>
              </div>
            </nav>
          </div>
        </div>
      </div>
      <div class="footer__bottom">
        <div class="row justify-content-between">
          <div class="col-lg-6 col-md-6">
            <meta itemprop="copyrightYear" content="2024">
            <meta itemprop="copyrightHolder" content="ООО ГК «Стальная федерация»">
            <p class="footer__copy">ООО ГК «Стальная федерация»® 2019-2024.</p>
            <div class="footer__politic">

              <a class="footer__politic-link" href="/policy/">
                Политика персональных данных
              </a>
            </div>
          </div>
          <div class="col-lg-6 col-md-6">
            <ul class="social">

              <li class="social__item">
                <a class="social__link" href="https://t.me/isteelskz_bot" target="_blank">
                  <svg class=" icon icon_telegram">
                    <use xlink:href="images/sprite.svg#telegram"></use>
                  </svg>
                </a>
              </li>

              <li class="social__item">
                <a class="social__link" href="https://wa.me/77005330150" target="_blank">
                  <svg class=" icon icon_whatsapp">
                    <use xlink:href="images/sprite.svg#whatsapp"></use>
                  </svg>
                </a>
              </li>

            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>

</style>

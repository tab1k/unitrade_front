<script setup>

</script>

<template>
  <div class="header__middle-inner container" style="padding: 0;">
    <style>
      @media (max-width: 768px) {
        .header__middle-inner.container {
          display: none;
        }
      }

    </style>
    <div class="header__middle">

                <span class="header__logo logo" style="width: 35px;" href="/">
                        <img src="/images/logo.png" style="width: 40px; height: 40px;" alt="Интерстилс">
                    </span>

      <button class="header__expanding_list header__city link" data-modal-toggle="#modal-choice-city">

        <span class="expanding-list__option">📍 Астана</span>
        <svg class="header__expanding_list-icon icon icon_arrow-down">
          <use xlink:href="images/sprite.svg#arrow-down"></use>
        </svg>
      </button>

      <button class="header__expanding_list header__language link drop-menu">

        <span class="expanding-list__option js-language-title"> 🇷🇺 RU</span>
        <svg class="header__expanding_list-icon icon icon_arrow-down">
          <use xlink:href="images/sprite.svg#arrow-down"></use>
        </svg>
        <div class="drop-menu__content header__menu-sub">
                        <span class="header__menu-link" data-google-lang="ru"
                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_ru');">🇷🇺 Русский</span>
          <span class="header__menu-link" data-google-lang="en"
                onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_en');">🇺🇸 Английский</span>
          <span class="header__menu-link" data-google-lang="kk"
                onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_kz');">🇰🇿 Казахский</span>
        </div>
      </button>

      <div class="header__content-right flex-wrap">
        <div class="link-wrapper">

          <a href="https://t.me/isteelskz_bot" target="_blank">
            <svg class="icon icon_logos_telegram">
              <use xlink:href="images/sprite.svg#logos_telegram"></use>
            </svg>
          </a>

          <a href="https://wa.me/77005330150" target="_blank">
            <svg class="icon icon_logos_whatsapp">
              <use xlink:href="images/sprite.svg#logos_whatsapp"></use>
            </svg>
          </a>

        </div>
        <div class="drop-menu">
          <a class="header__phone link mgo-number" href="tel:+77172640297">
            <span class="mgo-number__target">📞 +7 (717) 264 02 97</span>
            <span class="header__phone-arrow-down">
                                <svg class="icon icon_arrow-down">
                                  <use xlink:href="images/sprite.svg#arrow-down"></use>
                                </svg>
                            </span>
          </a>
          <div class="drop-menu__content header__phone-menu">

            <div class="header__phone-menu-block">
              <div class="header__phone-main d-flex">
                <div>
                  <svg class="icon icon_time">
                    <use xlink:href="images/sprite.svg#time"></use>
                  </svg>
                </div>
                <div class="header__phone-main_time">
                  <p>Пн-Чт: с 9:00 до 18:00, Пт: с 9:00 до 17:00</p>
                </div>
              </div>
              <div class="header__phone-lable">Время работы</div>
            </div>
            <div class="d-flex header__phone-menu-block_social">

              <a class="btn btn_light" href="https://t.me/isteelskz_bot" target="_blank">
                <span>Telegram</span>
                <img loading="lazy" src="images/telegram.png" alt="Telegram">
              </a>

              <a class="btn btn_light" href="https://wa.me/77005330150" target="_blank">
                <span>WhatsApp</span>
                <img loading="lazy" src="images/whatsapp.png" alt="WhatsApp">
              </a>

            </div>
            <button class="btn btn_light-black header__phone-menu-block_btn"
                    onclick="ym(window.isteels.ym_id, 'reachGoal', 'click_callback');"
                    data-modal-toggle="#modal-call">
              Перезвонить
              <svg class="icon icon_callback">
                <use xlink:href="images/sprite.svg#callback"></use>
              </svg>
            </button>
          </div>
        </div>
        <a class="header__email link mgo-email" href="mailto:astana@isteels.kz">
          <span class="mgo-email">📥 tabik8585@gmail.com</span>
        </a>

      </div>
    </div>
  </div>
</template>

<style scoped>

</style>

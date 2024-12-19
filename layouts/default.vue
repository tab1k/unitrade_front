<template>
  <div>
    <Header/>

    <!--noindex-->
    <div class="my-modal order-click-modal" data-modal="order-click">
      <div class="my-modal__content">
        <button class="close-modal-btn">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M12 10.2322L4.88386 3.11612L3.11609 4.88389L10.2322 12L3.11609 19.1161L4.88386 20.8839L12 13.7678L19.1161 20.8839L20.8839 19.1161L13.7677 12L20.8839 4.88389L19.1161 3.11612L12 10.2322Z"
                  fill="#9DA1A6"></path>
          </svg>
        </button>
        <div class="filling-step">
          <form class="form order-click-form" data-action="/informer/form_send/speed-request/"
                onsubmit="ym(window.isteels.ym_id, 'reachGoal', 'sent_fast_order');">
            <p class="order-click-form__name">📞 Заказ в 1 клик</p>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title required">
                            Товар
                            <svg class="icon icon_required-input">
                              <use xlink:href="images/sprite.svg#required-input"></use>
                            </svg>
                        </span>
              <input class="modal-order__form-field-input input__input" type="text" name="product"
                     placeholder="Кабель силовой медный" required="" autocomplete="off">
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title required">
                            Количество
                            <svg class="icon icon_required-input">
                              <use xlink:href="images/sprite.svg#required-input"></use>
                            </svg>
                        </span>
              <input class="modal-order__form-field-input input__input" type="text" name="quantity"
                     placeholder="20" required="" autocomplete="off">
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title">
                            Номер телефона
                        </span>
              <input class="modal-order__form-field-input input__input" type="tel" name="phone" maxlength="21"
                     minlength="18" required="">
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title">
                            Email
                        </span>
              <input class="modal-order__form-field-input input__input" type="email" name="email"
                     placeholder="example@email.com">
            </label>
            <label class="input-file">
              Добавить файл
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M13.8835 2.56029C12.3945 1.07135 9.98048 1.07135 8.49155 2.56029L2.56045 8.49139C0.475943 10.5759 0.475944 13.9556 2.56045 16.0401C4.35899 17.8386 7.1217 18.0853 9.18478 16.7803V15.2503V14.8076L9.03074 14.9617C7.54181 16.4506 5.12777 16.4506 3.63883 14.9617C2.1499 13.4727 2.1499 11.0587 3.63883 9.56977L9.56993 3.63867C10.4633 2.74531 11.9117 2.74531 12.8051 3.63867C13.6984 4.53203 13.6984 5.98045 12.8051 6.87382L7.14357 12.5353C6.84579 12.8331 6.36298 12.8331 6.06519 12.5353C5.76741 12.2375 5.76741 11.7547 6.06519 11.4569L11.4571 6.06503L10.3787 4.98665L4.98681 10.3786C4.09345 11.2719 4.09345 12.7203 4.98681 13.6137C5.88017 14.5071 7.32859 14.5071 8.22195 13.6137L13.8835 7.9522C15.3724 6.46326 15.3724 4.04922 13.8835 2.56029Z"
                      fill="#262A31"></path>
                <path d="M14.0935 17.9592V15.2398H11.374V13.4268H14.0935V10.7074H15.9065V13.4268H18.6259V15.2398H15.9065V17.9592H14.0935Z"
                      fill="#383A44"></path>
              </svg>
              <input name="file_link" type="file" multiple="" data-inpfile="">
            </label>
            <div class="file-container"></div>
            <div class="modal-order__bottom">
              <button class="modal-order__form_submit btn btn-primary btn_100 send_fast_order" type="submit"
                      data-call-modal="order-processed">
                Отправить
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M17.82 5.66455L7.50008 15.9844L2.18018 10.6645L3.65331 9.19141L7.50008 13.0382L16.3468 4.19141L17.82 5.66455Z"
                        fill="black"></path>
                </svg>
              </button>
              <div class="modal-order__info-license">
                Нажимая «Отправить», вы соглашаетесь с
                <a href="/policy/" target="_blank"> политикой обработки персональных данных</a>
              </div>
            </div>
          </form>
        </div>
        <div class="data-sent-step hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80" fill="none">
            <g clip-path="url(#clip0_10585_65550)">
              <path d="M59.5994 30.8718C60.6072 29.864 60.6072 28.23 59.5994 27.2222C58.5916 26.2144 56.9576 26.2144 55.9498 27.2222L33.9036 49.2684L24.7607 40.1254C23.7529 39.1176 22.1189 39.1176 21.1111 40.1254C20.1033 41.1333 20.1033 42.7672 21.1111 43.775L32.0789 54.7428C33.0867 55.7506 34.7206 55.7506 35.7284 54.7428L59.5994 30.8718Z"
                    fill="#1AC17B"></path>
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M80 40C80 62.0914 62.0914 80 40 80C17.9086 80 0 62.0914 0 40C0 17.9086 17.9086 0 40 0C62.0914 0 80 17.9086 80 40ZM74.8387 40C74.8387 59.2409 59.2409 74.8387 40 74.8387C20.7591 74.8387 5.16129 59.2409 5.16129 40C5.16129 20.7591 20.7591 5.16129 40 5.16129C59.2409 5.16129 74.8387 20.7591 74.8387 40Z"
                    fill="#1AC17B"></path>
            </g>
            <defs>
              <clipPath id="clip0_10585_65550">
                <rect width="80" height="80" fill="white"></rect>
              </clipPath>
            </defs>
          </svg>
          <p class="data-sent-step__title">Данные отправлены</p>
          <p class="data-sent-step__descr">
            Наш менеджер свяжется с вами в ближайшее время.

          </p>

        </div>
      </div>
    </div>
    <div class="my-modal cart-modal" data-modal="cart">
      <div class="my-modal__content">
        <button class="close-modal-btn btn-reset">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M12 10.2322L4.88386 3.11612L3.11609 4.88389L10.2322 12L3.11609 19.1161L4.88386 20.8839L12 13.7678L19.1161 20.8839L20.8839 19.1161L13.7677 12L20.8839 4.88389L19.1161 3.11612L12 10.2322Z"
                  fill="#9DA1A6"></path>
          </svg>
        </button>
        <div class="step-one hidden">
          <div class="cart-modal__head">
            <p class="cart-modal__title">Мой заказ</p>
            <div class="cart-modal__head-content">
                        <span class="product-quantity" data-cart-total-quantity="">
                            <span class="button_cart_counter">0</span> товаров
                        </span>
              <div class="vertical-line"></div>
              <span class="download-link" style="cursor: pointer" onclick="clear_cart_items(event)">
                            Очистить весь список
                        </span>
              <div class="vertical-line"></div>
              <span class="download-link"
                    onclick="ym(window.isteels.ym_id, 'reachGoal', 'download_list'); window.open('/cart/order_download/', '_blank');"
                    style="cursor: pointer">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                            <path d="M15.833 17.5H3.33301V15.75H15.833V17.5ZM9.58301 14.8333L4.22586 9.58333L5.48479 8.34958L8.69015 11.4821V2.5H10.4759V11.4821L13.6812 8.34958L14.9402 9.58333L9.58301 14.8333Z"
                                  fill="#9DA1A6"></path>
                        </svg>
                        Скачать список
                    </span>
            </div>
          </div>
          <div class="basket-content__product">

          </div>
          <div class="cart-modal-control">
            <div class="btn-wrapper">
              <button class="btn submit-btn" onclick="ym(window.isteels.ym_id, 'reachGoal', 'fill_basket');">
                Оформить заявку
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                  <g clip-path="url(#clip0_10099_3809)">
                    <path d="M0 5.37508H13.6667V3.29175L0 3.29175V5.37508Z" fill="#262A31"></path>
                    <path d="M0 10.3751H13.6667V8.29175H0V10.3751Z" fill="#262A31"></path>
                    <path d="M8.50003 15.3751H0V13.2917H8.50003V15.3751Z" fill="#262A31"></path>
                    <path d="M16.4824 10.8333L18.2502 12.601L14.1254 16.7258L13.2415 15.8419L12.3576 14.958L16.4824 10.8333Z"
                          fill="#262A31"></path>
                    <path d="M11.1787 16.1367L11.7852 15.5303L13.5358 17.3151L12.9465 17.9045L10.8841 18.1991L11.1787 16.1367Z"
                          fill="#262A31"></path>
                  </g>
                  <defs>
                    <clipPath id="clip0_10099_3809">
                      <rect width="20" height="20" fill="white"></rect>
                    </clipPath>
                  </defs>
                </svg>
              </button>
              <a href="/catalog/">
                <button class="btn-reset btn_light add-product-btn">
                  Добавить товары
                  <svg width="20" height="20" viewBox="0 0 20 20" fill="none"
                       xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_10099_3965)">
                      <path d="M0 5.37508H13.6667V3.29175L0 3.29175V5.37508Z" fill="#262A31"></path>
                      <path d="M0 10.3751H12V8.29175H0V10.3751Z" fill="#262A31"></path>
                      <path d="M8.50003 15.3751H0V13.2917H8.50003V15.3751Z" fill="#262A31"></path>
                      <path d="M13.9583 18.5001V15.3751H10.8333V13.2917H13.9583V10.1667H16.0416V13.2917H19.1666V15.3751H16.0416V18.5001H13.9583Z"
                            fill="#262A31"></path>
                    </g>
                    <defs>
                      <clipPath id="clip0_10099_3965">
                        <rect width="20" height="20" fill="white"></rect>
                      </clipPath>
                    </defs>
                  </svg>
                </button>
              </a>

            </div>
            <div class="info">
              <p class="descr">Мин. заказ</p>
              <p class="value">
                100 000 ₸</p>
            </div>
          </div>

        </div>
        <div class="step-two hidden">
          <div class="cart-modal__head">
            <p class="cart-modal__title">Мои контакты</p>
            <div class="cart-modal__info">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                <g clip-path="url(#clip0_9472_110819)">
                  <path d="M10 4.79167C10.5753 4.79167 11.0417 5.25804 11.0417 5.83334V10.8333C11.0417 11.4086 10.5753 11.875 10 11.875C9.42471 11.875 8.95834 11.4086 8.95834 10.8333V5.83334C8.95834 5.25804 9.42471 4.79167 10 4.79167Z"
                        fill="#9DA1A6"></path>
                  <path d="M11.0417 14.1667C11.0417 13.5914 10.5753 13.125 10 13.125C9.42471 13.125 8.95834 13.5914 8.95834 14.1667V14.175C8.95834 14.7503 9.42471 15.2167 10 15.2167C10.5753 15.2167 11.0417 14.7503 11.0417 14.175V14.1667Z"
                        fill="#9DA1A6"></path>
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M19.375 10C19.375 15.1777 15.1777 19.375 10 19.375C4.82233 19.375 0.625 15.1777 0.625 10C0.625 4.82233 4.82233 0.625 10 0.625C15.1777 0.625 19.375 4.82233 19.375 10ZM10 17.2917C14.0271 17.2917 17.2917 14.0271 17.2917 10C17.2917 5.97292 14.0271 2.70833 10 2.70833C5.97292 2.70833 2.70833 5.97292 2.70833 10C2.70833 14.0271 5.97292 17.2917 10 17.2917Z"
                        fill="#9DA1A6"></path>
                </g>
                <defs>
                  <clipPath id="clip0_9472_110819">
                    <rect width="20" height="20" fill="white"></rect>
                  </clipPath>
                </defs>
              </svg>
              Работаем только с юридическими лицами
            </div>
          </div>
          <div class="cart-modal__form-wrapper">
            <form class="form" id="cart-form2" method="POST" data-action="/cart/"
                  onsubmit="ym(window.isteels.ym_id, 'reachGoal', 'sent_basket');">
              <label class="order-form__form-item-label">
                Телефон
              </label>
              <input class="order-form__form-item-input input__input" type="tel" name="phone" maxlength="21"
                     minlength="18" required="">
              <label class="order-form__form-item-label">
                Email
              </label>
              <input class="order-form__form-item-input input__input" type="email" placeholder="example@email.com"
                     name="email">
              <label class="order-form__form-item-label">Имя</label>
              <input class="order-form__form-item-input input__input" name="fio" type="text" placeholder="Иван">
              <label class="order-form__form-item-label">Комментарий</label>
              <textarea class="order-form__form-item-textarea input__input" name="comment"
                        placeholder="Напишите комментарии, которые могут уточнить заявку, если они нужны."
                        autocomplete="off"></textarea>
              <label class="input-file">
                Прикрепить реквизиты
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M13.8835 2.56029C12.3945 1.07135 9.98048 1.07135 8.49155 2.56029L2.56045 8.49139C0.475943 10.5759 0.475944 13.9556 2.56045 16.0401C4.35899 17.8386 7.1217 18.0853 9.18478 16.7803V15.2503V14.8076L9.03074 14.9617C7.54181 16.4506 5.12777 16.4506 3.63883 14.9617C2.1499 13.4727 2.1499 11.0587 3.63883 9.56977L9.56993 3.63867C10.4633 2.74531 11.9117 2.74531 12.8051 3.63867C13.6984 4.53203 13.6984 5.98045 12.8051 6.87382L7.14357 12.5353C6.84579 12.8331 6.36298 12.8331 6.06519 12.5353C5.76741 12.2375 5.76741 11.7547 6.06519 11.4569L11.4571 6.06503L10.3787 4.98665L4.98681 10.3786C4.09345 11.2719 4.09345 12.7203 4.98681 13.6137C5.88017 14.5071 7.32859 14.5071 8.22195 13.6137L13.8835 7.9522C15.3724 6.46326 15.3724 4.04922 13.8835 2.56029Z"
                        fill="#262A31"></path>
                  <path d="M14.0935 17.9592V15.2398H11.374V13.4268H14.0935V10.7074H15.9065V13.4268H18.6259V15.2398H15.9065V17.9592H14.0935Z"
                        fill="#383A44"></path>
                </svg>
                <input type="file" multiple="" data-inpfile="" name="file_link">
              </label>
              <div class="file-container"></div>
            </form>
            <div class="order-form__file"></div>
          </div>
          <div class="cart-modal-control">
            <div class="btn-wrapper">
              <button class="btn-reset btn_light back-btn">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M9.25274 2.96899L1.28418 10.0001L9.25274 17.0312L10.6311 15.469L5.61356 11.0417H17.8586V8.95841H5.61356L10.6311 4.53116L9.25274 2.96899Z"
                        fill="black"></path>
                </svg>
                Назад к списку
              </button>
              <button class="btn sent_basket" type="submit" form="cart-form2">
                Отправить
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M17.82 5.66455L7.50008 15.9844L2.18018 10.6645L3.65331 9.19141L7.50008 13.0382L16.3468 4.19141L17.82 5.66455Z"
                        fill="#262A31"></path>
                </svg>
              </button>
            </div>
            <div class="modal-order__info-license"> Нажимая «Отправить», вы соглашаетесь с
              <a href="/policy/" target="_blank"> политикой обработки персональных данных</a>
            </div>
          </div>
        </div>
        <div class="cart-empty">
          <section class="basket-page__empty-basket">
            <div class="row justify-content-center">
              <div class="col-8">
                <div class="empty-basket">
                  <a class="empty-basket__img" href="/catalog/"
                     style="background-image: url(images/card.webp);">
                  </a>
                  <span class="empty-basket__title">Вы ничего не добавили</span>
                  <div class="empty-basket__desc">
                    Воспользуйтесь поиском, чтобы найти всё, что нужно или посмотрите продукцию в
                    каталоге или услуги
                  </div>
                  <a class="empty-basket__btn-catalog btn btn_black" href="/catalog/">
                    Перейти в каталог 📕
                  </a>
                </div>
              </div>
            </div>
          </section>
        </div>
      </div>
    </div>
    <div class="my-modal order-processed" data-modal="order-processed">
      <div class="my-modal__content">
        <svg xmlns="http://www.w3.org/2000/svg" width="56" height="56" viewBox="0 0 56 56" fill="none">
          <g clip-path="url(#clip0_9475_131555)">
            <path d="M41.7196 21.6103C42.425 20.9048 42.425 19.761 41.7196 19.0556C41.0141 18.3501 39.8703 18.3501 39.1649 19.0556L23.7326 34.4879L17.3325 28.0878C16.627 27.3823 15.4832 27.3823 14.7778 28.0878C14.0723 28.7933 14.0723 29.9371 14.7778 30.6425L22.4552 38.3199C23.1607 39.0254 24.3044 39.0254 25.0099 38.3199L41.7196 21.6103Z"
                  fill="#1AC17B"></path>
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M56 28C56 43.464 43.464 56 28 56C12.536 56 0 43.464 0 28C0 12.536 12.536 0 28 0C43.464 0 56 12.536 56 28ZM52.3871 28C52.3871 41.4686 41.4686 52.3871 28 52.3871C14.5314 52.3871 3.6129 41.4686 3.6129 28C3.6129 14.5314 14.5314 3.6129 28 3.6129C41.4686 3.6129 52.3871 14.5314 52.3871 28Z"
                  fill="#1AC17B"></path>
          </g>
          <defs>
            <clipPath id="clip0_9475_131555">
              <rect width="56" height="56" fill="white"></rect>
            </clipPath>
          </defs>
        </svg>
        <div class="text-wrapper">
          <p class="text-top">Данные отправлены</p>
          <p class="text-low">
            Наш менеджер свяжется с вами в ближайшее время.

          </p>

        </div>
      </div>
    </div>
    <div class="my-modal order-click-modal" data-modal="find-price">
      <div class="my-modal__content">
        <button class="close-modal-btn">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none">
            <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M12 10.2322L4.88386 3.11612L3.11609 4.88389L10.2322 12L3.11609 19.1161L4.88386 20.8839L12 13.7678L19.1161 20.8839L20.8839 19.1161L13.7677 12L20.8839 4.88389L19.1161 3.11612L12 10.2322Z"
                  fill="#9DA1A6"></path>
          </svg>
        </button>
        <div class="filling-step">
          <p class="my-modal__title">Узнать цену</p>
          <p class="my-modal__descr">
            Минимальная сумма заказа
            100 000 ₸
          </p>
          <form class="form modal-order__form" id="form-find-price" data-action="/informer/form_send/find-price/"
                onsubmit="ym(window.isteels.ym_id, 'reachGoal', 'sent_product_price');">
            <label class="modal-order__form-field modal-order__form_head">
              <div class="modal-order__form_img">
                <img data-modal-img="" src="" alt="Товар">
              </div>
              <input class="d-none" name="product">
              <span data-modal-title=""></span>
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title required">
                            Количество
                              <svg class="icon icon_required-input">
                                <use xlink:href="images/sprite.svg#required-input"></use>
                              </svg>
                        </span>
              <input class="modal-order__form-field-input input__input" type="text" name="quantity"
                     placeholder="10" required="">
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title">
                            Номер телефона
                        </span>
              <input class="modal-order__form-field-input input__input" type="tel" name="phone" maxlength="21"
                     minlength="18" required="">
            </label>
            <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title">
                            Email
                        </span>
              <input class="modal-order__form-field-input input__input" type="email" name="email"
                     placeholder="example@mail.com">
            </label>
            <div class="modal-order__bottom">
              <button class="modal-order__form_submit btn btn-primary btn_100 find_price" type="submit">
                Отправить
                <svg class="icon icon_arrow-right">
                  <use xlink:href="images/sprite.svg#arrow-right"></use>
                </svg>
              </button>
              <div class="modal-order__info-license">
                Нажимая «Отправить», вы соглашаетесь с
                <a href="/policy/" target="_blank"> политикой обработки персональных данных</a>
              </div>
            </div>
          </form>
        </div>
        <div class="data-sent-step hidden">
          <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 80 80" fill="none">
            <g clip-path="url(#clip0_10585_65550)">
              <path d="M59.5994 30.8718C60.6072 29.864 60.6072 28.23 59.5994 27.2222C58.5916 26.2144 56.9576 26.2144 55.9498 27.2222L33.9036 49.2684L24.7607 40.1254C23.7529 39.1176 22.1189 39.1176 21.1111 40.1254C20.1033 41.1333 20.1033 42.7672 21.1111 43.775L32.0789 54.7428C33.0867 55.7506 34.7206 55.7506 35.7284 54.7428L59.5994 30.8718Z"
                    fill="#1AC17B"></path>
              <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M80 40C80 62.0914 62.0914 80 40 80C17.9086 80 0 62.0914 0 40C0 17.9086 17.9086 0 40 0C62.0914 0 80 17.9086 80 40ZM74.8387 40C74.8387 59.2409 59.2409 74.8387 40 74.8387C20.7591 74.8387 5.16129 59.2409 5.16129 40C5.16129 20.7591 20.7591 5.16129 40 5.16129C59.2409 5.16129 74.8387 20.7591 74.8387 40Z"
                    fill="#1AC17B"></path>
            </g>
            <defs>
              <clipPath id="clip0_10585_65550">
                <rect width="80" height="80" fill="white"></rect>
              </clipPath>
            </defs>
          </svg>
          <p class="data-sent-step__title">Данные отправлены</p>
          <p class="data-sent-step__descr">
            Наш менеджер свяжется с вами в ближайшее время.

          </p>

        </div>
      </div>
    </div>

    <!--/noindex-->

    <Nuxt/>
    <div class="container">
      <div class="page-up-holder">
        <a class="page-up" href="#" data-scroll="body">
          <svg class="icon icon_arrow-up">
            <use xlink:href="images/sprite.svg#arrow-up"></use>
          </svg>
        </a>
      </div>
    </div>

    <Footer/>

    <!--noindex-->
    <div class="modal modal-cookie" id="modal-cookie">
      <div class="modal__dialog">
        <div class="modal__container">
          <div class="modal__content modal-cookie__body row">
            <div class="modal-cookie__body_col col">
              <div class="modal-cookie__title">
                Этот сайт использует файлы cookie с целью повышения удобства для пользователя - <a
                href="/policy/">подробнее</a>
              </div>
            </div>
            <div class="modal-cookie__body_col">
              <div class="modal__close">
                <button class="btn btn_black">
                  <span>Ок</span>
                  <svg class=" icon icon_check">
                    <use xlink:href="images/sprite.svg#check"></use>
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="modal modal-success" id="modal-success">
      <div class="modal__dialog">
        <div class="modal__content">
          <div class="modal__success d-flex">
            <svg class=" icon icon_success">
              <use xlink:href="images/sprite.svg#success"></use>
            </svg>
            <div class="modal__success_info">
              <div class="modal__title">Заявка принята</div>
              <div class="modal__subtitle mt-2">Благодарим за обращение в группу компаний «Стальная федерация»!
                Наш эксперт
                свяжется с Вами в ближайшее время.

              </div>

            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="modal modal-mobile-menu" id="modal-mobile-menu">
      <div class="modal__overlay">
        <div class="modal__content animate__animated animate__slideInLeft">
          <div class="mobile-menu container">

            <button style="margin-bottom: 32px;" class="mobile-menu__button mobile-menu__catalog" type="button"
                    data-modal-show="#modal-header-catalog">
              Каталог 📕
            </button>


            <a href="/" class="mobile-menu__button mobile-menu__catalog" type="button"
               data-modal-show="#modal-header-catalog" style="background-image: none;">
              Главная
            </a>

            <a href="/articles.html" class="mobile-menu__button mobile-menu__catalog" type="button"
               data-modal-show="#modal-header-catalog" style="margin-bottom: 12px; background-image: none;">
              Статьи
            </a>
            <a class="mobile-menu__button mobile-menu__catalog" type="button"
               data-modal-show="#modal-header-catalog">
              Покупателям
            </a>
            <a class="mobile-menu__button mobile-menu__catalog" type="button"
               data-modal-show="#modal-header-catalog">
              О компании
            </a>
            <a href="/contacts.html" class="mobile-menu__button mobile-menu__catalog" type="button"
               data-modal-show="#modal-header-catalog">
              Контакты
            </a>

            <span class="mobile-menu__button header__menu-link" style="margin-top: 32px;">📞 Заказ в 1 клик</span>

            <!--                <button class="mobile-menu__city link" data-modal-show="#modal-choice-city">-->
            <!--                    📍 Астана-->
            <!--                </button>-->

            <!--                <button class="mobile-menu__city link mobile-menu-language" type="button">-->
            <!--                    <div class="mobile-language-title">🇷🇺 Русский</div>-->
            <!--                    <div class="drop-menu__content header__menu-sub">-->
            <!--                        <span class="header__menu-link" data-google-lang="ru"-->
            <!--                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_ru');">Русский</span>-->
            <!--                        <span class="header__menu-link" data-google-lang="en"-->
            <!--                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_en');">Английский</span>-->
            <!--                        <span class="header__menu-link" data-google-lang="kk"-->
            <!--                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_kk');">Казахский</span>-->
            <!--                        <span class="header__menu-link" data-google-lang="uz"-->
            <!--                              onclick="ym(window.isteels.ym_id, 'reachGoal', 'kz_uz');">Узбекский</span>-->
            <!--                    </div>-->
            <!--                </button>-->


            <!--                <a class="mobile-menu__email link mgo-email" href="mailto:zakaz@steelfed.kz">-->
            <!--                    <span class="mgo-email">zakaz@steelfed.kz</span>-->
            <!--                    <span class="link__icon">-->
            <!--                        <svg class=" icon icon_email">-->
            <!--                            <use xlink:href="images/sprite.svg#email"></use>-->
            <!--                        </svg>-->
            <!--                    </span>-->
            <!--                </a>-->

            <!--                <a class="mobile-menu__phone link" href="https://t.me/tab1k.k">Telegram-->
            <!--                    <span class="link__icon">-->
            <!--                            <svg class="icon icon_logos_telegram">-->
            <!--                              <use xlink:href="images/sprite.svg#logos_telegram"></use>-->
            <!--                            </svg>-->
            <!--                        </span>-->
            <!--                </a>-->

            <!--                <a class="mobile-menu__phone link" href="https://wa.me/77077772817">WhatsApp-->
            <!--                    <span class="link__icon">-->
            <!--                            <svg class="icon icon_logos_whatsapp">-->
            <!--                              <use xlink:href="images/sprite.svg#logos_whatsapp"></use>-->
            <!--                            </svg>-->
            <!--                        </span>-->
            <!--                </a>-->

            <!--                <button class="mobile-menu__callback" data-modal-show="#modal-callback">-->
            <!--                    Обратный звонок-->
            <!--                    <svg class=" icon icon_callback">-->
            <!--                        <use xlink:href="images/sprite.svg#callback"></use>-->
            <!--                    </svg>-->
            <!--                </button>-->
          </div>
        </div>
      </div>
    </div>
    <div class="modal header-modal callback-modal" id="modal-callback">
      <div class="modal__dialog">
        <div class="modal__content animate__animated animate__slideInUp">
          <div class="callback-modal__container container">
            <button class="modal__close header-modal-close" aria-label="Закрыть окно">
              <svg class="icon icon_close">
                <use xlink:href="images/sprite.svg#close"></use>
              </svg>
            </button>
            <div class="modal__title">Связаться с нами</div>
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

                <a class="btn btn_light" href="https://t.me/tab1k.k" target="_blank">
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
                <svg class=" icon icon_callback">
                  <use xlink:href="images/sprite.svg#callback"></use>
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="modal modal-order" id="modal-request">
      <div class="modal__dialog">
        <div class="modal__container">
          <div class="modal__content modal-order__container">
            <div class="modal__close">
              <svg class=" icon icon_close">
                <use xlink:href="images/sprite.svg#close"></use>
              </svg>
            </div>
            <div class="modal__title">
              <div>Оставить заявку</div>
              <div class="product__price_min">
                Минимальная сумма заказа
                100 000 ₸
              </div>
            </div>
            <form class="modal-order__form need-validate" data-need-notification="true" id="request" method="POST"
                  data-action="/informer/form_send/request/">
              <input type="text" name="first__name" class="d-none" value="">
              <label class="modal-order__form-field">
                <span class="modal-order__form-field-title">Фамилия Имя</span>
                <input class="order-form__form-item-input input__input" type="text" name="fio"
                       placeholder="Иванов Андрей">
                <span class="input__error">
                            <svg class="icon icon_error">
                                <use xlink:href="images/sprite.svg#error"></use>
                            </svg>
                        </span>
              </label>
              <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title required">
                            Телефон
                            <svg class="icon icon_required-input">
                                <use xlink:href="images/sprite.svg#required-input"></use>
                            </svg>
                        </span>
                <input name="phone" maxlength="21" minlength="18"
                       class="order-form__form-item-input input__input" type="tel" required="required"
                       placeholder="+7 ( ___ ) ___ - __ - __">
                <span class="input__error">
                            <svg class="icon icon_error">
                                <use xlink:href="images/sprite.svg#error"></use>
                            </svg>
                            Введите корректный номер
                        </span>
              </label>
              <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title" data-replace-content="">
                            <span>Комментарии к заказу</span>
                            <span>Необязательно</span>
                        </span>
                <textarea class="service-price__form-field-textarea order-form__form-item-input input__input"
                          name="comment" placeholder="" maxlength="2000"
                          data-tippy-content="Максимум 2 000 символов"></textarea>
              </label>
              <button class="modal-order__form_submit btn btn-primary btn_100 justify-content-center"
                      type="submit">
                <span>Отправить</span>
                <svg class=" icon icon_arrow-right">
                  <use xlink:href="images/sprite.svg#arrow-right"></use>
                </svg>
              </button>
            </form>
            <p class="modal-order__info-license modal-call__politics">
                        <span>
                            Нажимая на кнопку “Отправить”, вы соглашаетесь с
                            <a href="/policy/" target="_blank">политикой обработки персональных данных</a>
                        </span>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="modal modal-order" id="modal-call">
      <div class="modal__dialog">
        <div class="modal__container">
          <div class="modal__content modal-order__container">
            <div class="modal__close">
              <svg class=" icon icon_close">
                <use xlink:href="images/sprite.svg#close"></use>
              </svg>
            </div>
            <div class="modal__title">
              <div>Оставьте свой номер</div>
            </div>
            <form class="modal-order__form need-validate" data-need-notification="true" id="call" method="POST"
                  data-action="/informer/form_send/call/">
              <input type="text" name="first__name" class="d-none" value="">
              <label class="modal-order__form-field">
                        <span class="modal-order__form-field-title required">
                            Телефон
                            <svg class="icon icon_required-input">
                                <use xlink:href="images/sprite.svg#required-input"></use>
                            </svg>
                        </span>
                <input name="phone" maxlength="21" minlength="18"
                       class="order-form__form-item-input input__input" type="tel"
                       placeholder="+7 ( ___ ) ___ - __ - __" required="required">
                <span class="input__error">
                            <svg class="icon icon_error">
                                <use xlink:href="images/sprite.svg#error"></use>
                            </svg>
                            Введите корректный номер
                        </span>
              </label>
              <button class="modal-order__form_submit btn btn-primary btn_100 justify-content-center"
                      type="submit">
                <span>Отправить</span>
                <svg class=" icon icon_arrow-right">
                  <use xlink:href="images/sprite.svg#arrow-right"></use>
                </svg>
              </button>
            </form>
            <p class="modal-order__info-license modal-call__politics">
                        <span>Нажимая на кнопку “Отправить”, вы соглашаетесь с
                            <a href="/policy/" target="_blank">политикой обработки персональных данных</a>
                        </span>
            </p>
          </div>
        </div>
      </div>
    </div>
    <!--/noindex-->

  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style scoped>
/* Стили для вашего layout (опционально) */
</style>

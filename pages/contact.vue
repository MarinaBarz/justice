<template>
  <main>
    <section class="hero is-medium is-light">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Связаться с нами</h1>
          <div class="columns">
            <div class="column is-6">
              <figure>
                <img src="/public/img/contact.png" alt srcset>
              </figure>
            </div>
            <div class="column is-6">
              <div class="widget-contact">
                <div class="field">
                  <label class="label">Имя</label>
                  <p class="control">
                    <input class="input" type="text" placeholder="Ваше имя..">
                  </p>
                </div>

                <div class="field">
                  <label class="label">Email</label>
                  <p class="control has-icon has-icon-right">
                    <input class="input" type="text" placeholder="Email..">
                  </p>
                </div>

                <div class="field">
                  <label class="label">Сообщение</label>
                  <p class="control">
                    <textarea class="textarea" placeholder="Сообщение.."></textarea>
                  </p>
                </div>
                <div class="field is-grouped">
                  <label class="form-checkbox term">
                    <input type="checkbox">
                    Я согласен с правилами и условиями
                    <i class="form-icon"></i>
                  </label>
                  <p class="control">
                    <button class="button is-primary">Отправить →</button>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
<script>
export default {
  layout: "light"
};
</script>

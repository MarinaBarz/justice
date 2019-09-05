<template>
  <main>
    <section class="hero is-black is-medium banner">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-5">
              <p class="subtitle">Всегда рядом, когда нужно правильное решение</p>
              <p class="title">Комплексные юридические услуг для бизнеса и частных лиц</p>
              <a class="button is-primary is-medium is-uppercase">О компании →</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-medium">
      <div class="hero-body">
        <div class="container">
          <div class="columns is-centered is-multiline">
            <div class="column is-12 has-text-centered">
              <p class="title">Наши услуги</p>
              <p class="subtitle is-6 is-italic">Мы оказываем широкий спектр профессиональных услуг</p>
            </div>
          </div>
          <Tab/>
        </div>
      </div>
    </section>

    <section class="hero is-medium">
      <div class="hero-body">
        <div class="container is-fluid">
          <div class="columns is-centered is-multiline">
            <div class="column is-12 is-title">
              <p class="title">Экспертный состав</p>
              <p class="subtitle is-6 is-italic">Сильная команда профессионалов своего дела</p>
            </div>
            <div class="column is-6 team-is-1">
              <div class="media">
                <div class="media-content is-hidden-mobile">
                  <p>Красота правовых решений требует не жертв, а стратегии и логики.</p>
                </div>
                <div class="media-right">
                  <figure>
                    <img class="image" src="/public/img/team/ypartner1.png" alt srcset>
                  </figure>
                  <p class="title is-5">
                    Управляющий
                    <br>партнер
                  </p>
                  <p class="title is-6">Новицкий Артем Георгиевич</p>
                </div>
              </div>
            </div>
            <div class="column is-6 team-is-2">
              <div class="media">
                <div class="media-left">
                  <figure>
                    <img class="image" src="/public/img/team/partner2.png" alt srcset>
                  </figure>
                  <p class="title is-5">
                    Управляющий
                    <br>партнер
                  </p>
                  <p class="title is-6">Лебедева Анна Михайловна</p>
                </div>
                <div class="media-content is-hidden-mobile">
                  <p>Хороший юрист знает закон. Выдающийся юрист владеет судебной практикой.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="hero is-medium">
      <div class="hero-body">
        <div class="container">
          <p class="title has-text-centered">Наши клиенты</p>
          <Slider/>
        </div>
      </div>
    </section>

    <section class="hero is-medium is-light">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-6">
              <p class="title">Наш подход</p>
              <Accordion/>
            </div>
            <div class="column is-6">
              <p class="title">Консультация в подарок</p>
              <p
                class="subtitle is-6"
              >Заполните заявку прямо сейчас. Мы предложим лучшее решение Вашей проблемы</p>
              <form class="home-form">
                <div class="field is-grouped">
                  <p class="control is-expanded">
                    <input class="input is-medium" placeholder="Имя" type="text">
                  </p>
                  <p class="control is-expanded">
                    <input class="input is-medium" placeholder="Email" type="text">
                  </p>
                </div>
                <div class="field is-grouped">
                  <p class="control is-expanded">
                    <input class="input is-medium" placeholder="Телефон" type="text">
                  </p>
                  <p class="control is-expanded">
                    <input
                      class="input is-medium"
                      placeholder="Компания(не обязательно)"
                      type="text"
                    >
                  </p>
                </div>
                <div class="field is-grouped">
                  <p class="control">
                    <button class="button is-primary is-medium">Отправить</button>
                  </p>
                  <p class="control checkbox">
                    <label class="form-checkbox">
                      <input type="checkbox">
                      Я согласен с правилами и условиями
                      <i class="form-icon"></i>
                    </label>
                  </p>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import Tab from "~/components/Tab.vue";
import Slider from "~/components/Slider.vue";
import Accordion from "~/components/Accordion.vue";

export default {
  layout: "default",
  components: {
    Tab,
    Slider,
    Accordion
  },

  data() {
    return {
      cartitem: []
    };
  },
  methods: {}
};
</script>



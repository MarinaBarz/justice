<template>
  <div class="accordion">
    <div class="accordion-item">
      <div  class="accordion-item-head">
        <p class="accordion-counter">01</p>
        <p class="title">Изучаем ситуацию клиента</p>
      </div>
      <div class="accordion-item-content">
        Глубокий и всеобъемлющий анализ бизнеса, проблематики, организации и индустрии.
        Определение целей клиента.
      </div>
    </div>
    <div class="accordion-item">
      <div  class="accordion-item-head">
        <p class="accordion-counter">02</p>
        <p class="title">Разрабатываем стратегию</p>
      </div>
      <div
        class="accordion-item-content"
      >Определяем необходимый комплекс мер и оптимальную стратегию решения проблемы.</div>
    </div>
    <div class="accordion-item">
      <div class="accordion-item-head">
        <p class="accordion-counter">03</p>
        <p class="title">Реализовываем и сопровождаем</p>
      </div>
      <div
        class="accordion-item-content"
      >Реализовываем принятую стратегию и поддерживаем клиента на всех этапах.</div>
    </div>
  </div>
</template>
<script>
export default {

  methods: {

  },
  mounted() {
   
    /////

        const accordion = document.querySelectorAll('.accordion-item')
        const accordionHead = document.querySelectorAll('.accordion-item-head')
        const accordionBody = document.querySelectorAll('.accordion-item-content')

        for (let i = 0; i < accordionHead.length; i++) {
            accordionHead[i].onclick = (params) => open(i)
        }

        function open(elem) {
            for (let i = 0; i < accordion.length; i++) {
                accordion[i].classList.remove('active')
                accordionBody[i].style.height = 0
            }
            accordion[elem].classList.add('active')
            accordionBody[elem].style.height = accordionBody[0].scrollHeight + 'px';
        }

        window.onload = () => {
            accordion[0].classList.add('active')
            accordionBody[0].style.height = accordionBody[0].scrollHeight + 'px';
        }
  }
};
</script>


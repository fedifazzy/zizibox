<template>
  <div class="wrapper">
    <h1>
      Как ухаживать за изделиями?
    </h1>
    <div class="column">
      <div class="paragraph">
        Наша продукция сделана из дерева и пищевого силикона. Мы собираем аксессуары для малышей вручную из буковых и
        силиконовых бусин. Они безопасны для ребёнка, но в отличие от пластика требуют особого ухода.
      </div>

      <div class="paragraph">
        Перед тем как впервые дать грызунок ребёнку, протрите его влажной салфеткой или ополосните под струёй тёплой
        воды. Затем можно обработать изделие паром и вытереть насухо полотенцем или салфеткой.
      </div>

      <div class="paragraph">
        Мойте грызунки по мере загрязнения с детским мылом в тёплой воде. Также можно использовать антибактериальные
        детские салфетки. Не сушите изделия вблизи отопительных приборов, не замачивайте и не кипятите.
      </div>

      <div class="paragraph">
        Если деревянные детали стали шершавыми, зашлифуйте их полировочной пилочкой, самой мелкой наждачной бумагой (нулёвкой) или грубой безворсовой тканью (например, бязь или лён) до гладкости.
      </div>

      <div class="paragraph">
        Раз в месяц рекомендуем смазывать деревянные детали пищевым маслом, которое подходит вашему малышу (например,
        льняным или персиковым). Затем нужно промакнуть дерево сухой салфеткой, чтобы убрать излишки масла. Такие
        процедуры вернут изделию блеск и создадут защитное покрытие, благодаря которому деревянные составляющие
        прослужат дольше.
      </div>

      <div class="paragraph">
        Клипса держателя для пустышки или грызунка не предназначена для прорезывания зубов. Она должна быть закреплена
        на одежде/коляске или находиться в закрытом состоянии. Металлический зажим должен закрываться без усилий. Чтобы
        снять клипсу, расстегните её (не пытайтесь сорвать резким движением).
      </div>

      <div class="paragraph">
        Мы рекомендуем использовать изделия только под присмотром взрослых.
      </div>

      <div class="paragraph">
        Отмечайте нас в Instagram с хештегом #zizi_box
      </div>

      <div class="paragraph social-link-paragraph">
        <a href="https://www.instagram.com/zi.zi_box/" target="_blank" class="social-link">
          <svg class="social-link-icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
            version="1.1" id="mdi-instagram" viewBox="0 0 24 24">
            <path
              d="M7.8,2H16.2C19.4,2 22,4.6 22,7.8V16.2A5.8,5.8 0 0,1 16.2,22H7.8C4.6,22 2,19.4 2,16.2V7.8A5.8,5.8 0 0,1 7.8,2M7.6,4A3.6,3.6 0 0,0 4,7.6V16.4C4,18.39 5.61,20 7.6,20H16.4A3.6,3.6 0 0,0 20,16.4V7.6C20,5.61 18.39,4 16.4,4H7.6M17.25,5.5A1.25,1.25 0 0,1 18.5,6.75A1.25,1.25 0 0,1 17.25,8A1.25,1.25 0 0,1 16,6.75A1.25,1.25 0 0,1 17.25,5.5M12,7A5,5 0 0,1 17,12A5,5 0 0,1 12,17A5,5 0 0,1 7,12A5,5 0 0,1 12,7M12,9A3,3 0 0,0 9,12A3,3 0 0,0 12,15A3,3 0 0,0 15,12A3,3 0 0,0 12,9Z" />
          </svg>
          zi.zi_box
        </a>
        <a href="https://t.me/dorofeykin" target="_blank" class="social-link">
          <svg class="social-link-icon" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 512 512"
            style="enable-background:new 0 0 512 512;" xml:space="preserve">
            <g>
              <path d="M256,0C114.6,0,0,114.6,0,256s114.6,256,256,256c141.4,0,256-114.6,256-256S397.4,0,256,0z M381.7,175.4l-42,198
                      c-3.1,14-11.5,17.4-23.1,10.8l-64-47.2l-30.9,29.7c-3.4,3.4-6.3,6.3-12.9,6.3l4.5-65.1L332,200.8c5.2-4.5-1.1-7.1-8-2.6
                      l-146.6,92.3l-63.2-19.7c-13.7-4.3-14-13.7,2.9-20.3L364,155.2C375.4,151.1,385.4,158,381.7,175.4L381.7,175.4z" />
            </g>
          </svg>

          dorofeykin
        </a>
      </div>
    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String
  }
})
</script>

<style scoped lang="scss">
    h1 {
      margin: 30px 20px 30px;
    }

    .wrapper {
      display: flex;
      flex-direction: column;
      justify-content: space-around;
    }

    .column {
      width: 100%;
    }

    .paragraph {
      margin: auto 20px;
      padding: 20px 0;
      border-bottom: 1px solid #DCD9FC;
    }

    .paragraph:first-child {
      border-top: 1px solid #DCD9FC;
    }

    .social-link-paragraph {
      display: flex;
      justify-content: space-between;
    }

    .social-link {
      display: flex;
      align-items: center;
      color: rebeccapurple;
    }

    .social-link-icon {
      width: 32px;
      margin-right: 10px;
      fill: rebeccapurple;
    }

    @media only screen and (min-width: 600px) {
      .wrapper {
        margin: 50px auto 0;
        align-items: center;
      }

      .column {
        width: 50%;
      }
      .social-link-paragraph {
        justify-content: space-evenly;
      }

    }
</style>

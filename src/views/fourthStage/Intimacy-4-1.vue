<template>
    <div>
      <main>
        <!-- 麵包屑 -->
        <section class="container" data-aos="fade-down"  data-aos-delay="500">
          <nav style="--bs-breadcrumb-divider: '>'" aria-label="breadcrumb" class="badge">
            <ol class="breadcrumb">
            <li class="breadcrumb-item"><router-link to="/">首頁</router-link></li>
            <li class="breadcrumb-item" aria-current="page"><router-link to="unintended-2">我意外懷孕了</router-link></li>
            <li class="breadcrumb-item" aria-current="page"><router-link to="">我不知道該怎麼做</router-link></li>
            <li class="breadcrumb-item active" aria-current="page"><router-link to="talking-3">醫療議題</router-link></li>
            </ol>
          </nav>
        </section>

        <!-- 主要區塊 -->
        <section class="container step-rwd">
          <div class="step">
            <!-- 裝飾用圖片 -->
            <img class="step-circle" src="../../assets/image/front/image_circleword.svg">
            <img class="image1" src="../../assets/image/front/page02_image1.svg">
            <img class="image2" src="../../assets/image/front/page02_image2.svg">
            <img class="image3" src="../../assets/image/front/page02_image3.svg">
            <!-- 結束 -->
            <div class="title-box">
              <p class="step-text" data-aos="fade-up" >ANSEWR</p>
              <h2 class="step-title" data-aos="fade-up">選擇・答案</h2>
              <img class="title-line" src="../../assets/image/front/choose_title_line.svg" data-aos="fade-up" >
              <p class="step-sologan" data-aos="fade-up" >為自己所想，為自己所選。</p>
            </div>
            <div class="container step-box">
              <div class="step-box-inner">
                <div class="box-title" data-aos="fade-up">
                  <h2>｜15歲可以買保險套嗎｜</h2>
                </div>
                <div class="select-menu">
                  <img class="mb-60" data-aos="fade-up" src='../../assets/image/front/page02_pic3.jpg'>
                  <hr data-aos="fade-up">
                    <!-- 選項開始 -->
                    <ul class="select-item container-inner mt-60">
                      <li data-aos="fade-up">
                        <p>法律上為了保護未滿16歲的青少年們身心健康，規範這個年齡層不適合發生性行為，因此當診所、醫院知道這個狀況，就保護青少年的立場，還是會通知社會局社工人員關懷你的狀況喔</p>
                        <!-- <router-link to="act-3-1" class="fs-5 text-danger">>> 可以點我參考「性自主」及「法律相關」議題</router-link> -->
                      </li>
                      <li data-aos="fade-up">
                      <p><a class="fs-5 text-danger" href="https://reurl.cc/V14eyy" target="_blank">>> 點我了解更多「保險套」相關議題</a></p>
                      </li>
                      <!-- <li data-aos="fade-up">
                      <p><a class="fs-5 text-danger" href="http://www.8181.org.tw/contraception/qa-list.asp?cate=19" target="_blank">>> 點我了解更多「保險套」相關議題</a></p>
                      </li> -->
                    </ul>
                    <!-- 選項結束 -->
                    <hr data-aos="fade-up">
                    <div data-aos="fade-up">
                      <a class="goBack" onclick="history.back()" value="回到上一頁">回到上一頁</a>
                      <a class="goBack" href="#">返回首頁</a>
                    </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <Consult></Consult>
        <Circle></Circle>
      </main>
    </div>
</template>
<script>
import Consult from '../../components/Consult.vue'

export default {
  data () {
    return {

    }
  },
  mounted () {

  },
  components: {
    Consult
  }
}
</script>

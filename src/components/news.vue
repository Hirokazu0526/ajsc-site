<template>
  <section class="section-inner" id="News">
    <h2 class="section-title mb-sm animationTarget">News</h2>
    <div class="section-info animationTarget">
      <div class="slide">
        <div class="slide-item">
          <p class="slide-item-title sd">Super Division</p>
          <img
            class="slide-item-img"
            src="images/2019_open_S.jpg"
            alt="super"/>
          <div class="slide-item-info font-fmSg">
            <div class="slide-item-top">
              <h4 class="cm">優勝<span>SC TOKYO AXIS</span></h4>
              <p class="font-fmSg">（高野征也・岡本慧悟・増田稜・中塚智之）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="nd">準優勝<span>A.S.WAKABA A</span></h4>
              <p class="font-fmSg">（内藤利貴・太田駿一・小林裕和）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>SC TOKYO wings</span></h4>
              <p class="font-fmSg">
                （玉置大嗣・阿波龍一郎・小谷駿太・石塚雅之・鳥海大地）
              </p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>阪神酒販Dee's TC</span></h4>
              <p class="font-fmSg">
                （佐藤優樹・中村健人・中村達也・寺島武志）
              </p>
            </div>
          </div>
        </div>
        <div class="slide-item">
          <p class="slide-item-title md">Men’s Division</p>
          <img
            class="slide-item-img"
            src="images/2019_open_M.jpg"
            alt="super"
          />
          <div class="slide-item-info font-fmSg">
            <div class="slide-item-top">
              <h4 class="cm">優勝<span>東京大学A</span></h4>
              <p class="font-fmSg">（加藤圭悟・春原涼太・湯淺隼）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="nd">準優勝<span>大山セパタクロークラブ B</span></h4>
              <p class="font-fmSg">
                （坂倉江平・岡田良介・井上遼太・小後摩佑介）
              </p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>大山セパタクロークラブ A</span></h4>
              <p class="font-fmSg">（三田昂平・森陵斗・矢澤幸宗・大片篤志）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>三田会</span></h4>
              <p class="font-fmSg">（秦野智也・池本祐介・小野田脩平）</p>
            </div>
          </div>
        </div>
        <div class="slide-item">
          <p class="slide-item-title wd">Women’s Division</p>
          <img
            class="slide-item-img"
            src="images/2019_open_W.jpg"
            alt="super"
          />
          <div class="slide-item-info font-fmSg">
            <div class="slide-item-top">
              <h4 class="cm">優勝<span>東京ヴェルディ A</span></h4>
              <p class="font-fmSg">（川又ゆうみ・小林千夏・佐藤千夏）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="nd">準優勝<span>東京ヴェルディ B</span></h4>
              <p class="font-fmSg">
                （戸上佳代・太田直子・山口のはら・石原里美・村田有美）
              </p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>A.S.WAKABA a</span></h4>
              <p class="font-fmSg">（田中結理・三枝千夏・程田奈菜）</p>
            </div>
            <div class="slide-item-top">
              <h4 class="rd">3位<span>日本体育大学ｂ</span></h4>
              <p class="font-fmSg">（飯田笙乃・高橋日和・佐川舞）</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <p style="color:white;margin-top: 10px;">
      各ディビジョンの入賞レグの代表者のみで撮影<br /><span
        >photo TSUTOMU TAKASU</span
      >
    </p>
  </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .slide {
  -ms-scroll-snap-type: x mandatory;
      scroll-snap-type: x mandatory;
  white-space: nowrap;
  overflow: auto;
  margin: 0 auto;
}

.slide-item {
  scroll-snap-align: center;
  white-space: normal;
  margin: 0 auto 30px;
  background: white;
  border-radius: 10px;
  padding: 10px;
}

.slide-item:last-child {
  margin-bottom: 0;
}

.slide-item-title {
  font-size: 1.3rem;
  margin-bottom: 5px;
}

.slide-item-img {
  width: 400px;
}

.slide-item-info {
  color: black;
  font-size: 0.5rem;
  margin-top: 10px;
}

.slide-item-top h4 span {
  padding-left: 1.5em;
}

.slide-item-top p {
  text-indent: 9em;
}

.slide-item-top:nth-child(2) h4 span {
  padding-left: 1rem;
}

.slide-item-top:nth-child(3) h4 span {
  padding-left: 3rem;
}

.slide-item-top:nth-child(4) h4 span {
  padding-left: 3rem;
}
</style>

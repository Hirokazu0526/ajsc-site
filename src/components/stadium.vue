<template>
    <section class="section-inner" id="Stadium">
        <h2 class="section-title mb-sm animationTarget">Stadium</h2>
        <div class="section-info animationTarget">
            <div class="section-info-left">
                <h3 class="section-subttl  stadium font-fmSg mb-sm">埼玉県和光市総合体育館</h3>
                <div class="section-adress font-fmSg">
                    <h4>〒351-0106<br>
                    埼玉県和光市広沢2-1</h4>
                    <p>【東武東上線、東京メトロ有楽町線・副都心線】<br>
                        &nbsp;&nbsp;和光市駅下車徒歩20分</p>
                    <p>【東武バス】<br>
                        &nbsp;&nbsp;和光市駅南口発→和光市総合体育館行き<br>（所要時間5分)
                    </p>
                </div>
            </div>
            <div class="section-info-right">
                <div class="gmap">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3236.948028135602!2d139.6041603150866!3d35.776652980172074!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6018e9576d88789f%3A0x585190000ab7c957!2z5ZKM5YWJ5biC57eP5ZCI5L2T6IKy6aSo!5e0!3m2!1sja!2sjp!4v1595770956157!5m2!1sja!2sjp" width="100%" height="auto" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
                </div>
            </div> 
        </div> 
    </section> 
</template>

<script>
export default {
    
}
</script>

<style scoped>
.section-inner {
  padding-top: 90px;
}

.section-info {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
}

.section-title {
  background: -webkit-linear-gradient(0deg, #ff1100, #9A1D1D, #ff1100);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 1.8rem;
}

.section-subttl {
  color: white;
  font-size: 1rem;
}

.section-text p {
  color: white;
  font-size: 0.9rem;
}

.gmap {
  height: 0;
  overflow: hidden;
  padding-bottom: 80%;
  position: relative;
}

.gmap iframe {
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
}
</style>
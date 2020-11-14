<template>
    <div id="Sponsor">
                <div class="sponsor inner animationTarget">
                        <h2 class="section-title">Sponsor</h2>
                </div>
                <div class="sponsor-logo inner animationTarget">
                    <a href="https://lib-gate.co.jp/" target="_blank"><img src="/assets/img/libgate (1).png" alt="" class="sponsor-item"></a>
                    <a href="https://www.saraya.com/" target="_blank"><img src="/img/saraya_2.png" alt="" class="sponsor-item"></a>
                    <a href="https://www.shizensyokuhin.jp/" target="_blank"><img src="/img/setagaya_logo_2.png" alt="" class="sponsor-item"></a>
                    <a href="https://www.svolme.net/" target="_blank"><img src="/img/svolme_2.png" alt="" class="sponsor-item"></a>
                    <a href="https://www.bvd.jp/" target="_blank"><img src="/img/BVD_2.png" alt="" class="sponsor-item"></a>
                    <a href="http://billionaire.co.jp/index.html" target="_blank"><img src="/img/billionaire.png" alt="" class="sponsor-item"></a>
                    <a href="https://www.anytimefitness.co.jp/" target="_blank"><img src="/img/anytime_2.png" alt="" class="sponsor-item"></a>
                </div>
            </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    #Sponsor {
  background: #fff;
  margin-top: 80px;
  padding-top: 20px;
}

.sponsor-logo {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
}

.sponsor-logo a {
  display: block;
  width: 300px;
  margin: 0 auto;
}

.sponsor-logo a:nth-child(4) {
  width: 180px;
}

.sponsor-logo a:nth-child(5) {
  width: 180px;
}

.sponsor-logo a:nth-child(7) {
  width: 250px;
  margin-bottom: 50px;
}

.sponsor-item {
  width: 100%;
  margin-top: 60px;
}
</style>
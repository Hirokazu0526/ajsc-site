<template>
    <section class="section-inner" id="About">
        <h2 class="section-title mb-sm animationTarget">About</h2>
        <div class="section-info animationTarget">
            <div class="section-info-left">
                <h3 class="section-subttl font-fmSg mb-sm">第27回<br>
                    全日本セパタクローオープン選手権大会</h3>
                <div class="section-text font-fmSg">
                    <p>主催：一般社団法人日本セパタクロー協会<br>
                        協賛：Lib-Gate・SARAYA・世田谷自然食品<br>&nbsp;&nbsp;B.V.D.・SVOLME・宝くじのビリオネア<br>
                        協力：ANYTIME FITNESS・了徳寺大学<br>
                            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大会実行委員会<br>
                        日時：2020年9月20日(日)・21日(月)<br>
                        会場：和光市総合体育館<br>
                    </p>
                    <br>
                    <p><span class="font-fmSg">
                      本大会は無観客大会となっており、事前に手続きを行なっている選手・監督・コーチ・大会関係者以外のご入場は不可となっておりますので、予めご了承ください。
                    </span></p>
                    <br>
                </div>
            </div>
            <div class="section-info-right">
                <div class="kv">
                    <img src="/img/sepak_kv.png" alt="キービジュアル">
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

.kv {
  width: 100%;
  margin-top: 10px;
}
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
</style>
<template>
    <section class="section-inner" id="Schedule">
        <h2 class="section-title mb-sm animationTarget">Schedule</h2>
        <div class="section-info schedule">
            <div class="section-info-left">
                <h3 class="section-subttl font-gd animationTarget">2020.09.20(Sun)</h3><br>
                <p style="color:red; font-size: 25px;" class="animationTarget">★Winner★</p>
                <div class="section-img font-fmSg">
                    <img class="pc animationTarget" src="/img/Day1_1.png" alt="キービジュアル">
                    <img class="pc animationTarget" src="/img/Day1_2.png" alt="キービジュアル">
                    <img class="pc animationTarget" src="/img/Day1_3.png" alt="キービジュアル">
                    <img class="pc animationTarget" src="/img/Day1_4.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_1.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_2.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_3.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_4.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_5.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_6.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day1_7.png" alt="キービジュアル">
                </div>
            </div>
            <div class="section-info-right">
                <h3 class="section-subttl font-gd mt animationTarget">2020.09.21(Mon)</h3>
                <div class="section-img font-fmSg">
                    <img class="pc animationTarget" src="/img/Day2_1_1.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day2_1_1.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day2_2_1.png" alt="キービジュアル">
                    <img class="sp animationTarget" src="/img/SP_Day2_3_1.png" alt="キービジュアル">
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
</style>
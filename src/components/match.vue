<template>
    <section class="section-inner " id="Match">
        <h2 class="section-title mb-sm animationTarget">Match Result</h2>
        <div class="macth-info ">
            <div class="match-info animationTarget">
                <h3 class="section-subttl mb-sm sdiv">Super Division</h3>
                <img src="images/tornament_Sdiv_2.png" alt="" class="mb-sm">
            </div>
            <div class="match-info animationTarget">
                <h3 class="section-subttl mb-sm mdiv">Men’s Division</h3>
                <img src="images/tornament_Mdiv_2.png" alt="" class="mb-sm">
            </div>
            <div class="match-info animationTarget">
                <h3 class="section-subttl mb-sm wdiv">Women’s Division</h3>
                <img src="images/tornament_Wdiv_2.png" alt="" class="mb-sm">
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
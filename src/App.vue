<template>
  <div class="container">
    <myheader></myheader>
    <mainkv></mainkv>  
    <news></news>
    <about></about>
    <schedule></schedule>
    <match></match>
    <stadium></stadium>
    <sponsor></sponsor>
    <myfooter></myfooter>
  </div>
</template>

<script>
import myheader from './components/myheader'
import mainkv from './components/mainkv'
import news from './components/news'
import about from './components/about'
import schedule from './components/schedule'
import match from './components/match'
import stadium from './components/stadium'
import sponsor from './components/sponsor'
import myfooter from './components/myfooter'

export default {
  components: {
    myheader,
    mainkv,
    news,
    about,
    schedule,
    match,
    stadium,
    sponsor,
    myfooter
  }
}
</script>

<style>
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
.container {
  /* height: 100vh; */
  background: #02001c;
  background: -webkit-gradient(linear, left top, right top, color-stop(21%, #001b27), color-stop(50%, #003001), color-stop(79%, #2b0000), to(#160000));
  background: linear-gradient(90deg, #001b27 21%, #003001 50%, #2b0000 79%, #160000 100%);
}

.abl {
  position: absolute;
}


</style>
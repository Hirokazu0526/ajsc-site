 <template>
    <header>
        <div class="header_wrapper">
            <div class="header_title">
                <h1>ALL JAPAN<br>SEPAKTAKRAW<br>CHAMPIONSHIP</h1>
            </div>
            <nav>
                <ul class="header_nav_list">
                    <li class="header_nav_list_item"><a href="#">About</a></li>
                    <li class="header_nav_list_item"><a href="#">Live</a></li>
                    <li class="header_nav_list_item"><a href="#">Match</a></li>
                    <li class="header_nav_list_item"><a href="#">Result</a></li>
                    <li class="header_nav_list_item"><a href="#">Access</a></li>
                    <li class="header_nav_list_item"><a href="#">News</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style scoped>

header {
  position: relative;
}

.header_wrapper {
  width: 1200px;
  height: 50px;
  margin: 0 auto;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: end;
      -ms-flex-pack: end;
          justify-content: flex-end;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  position: relative;
}

.header_title {
  position: absolute;
  top: 10px;
  left: 0;
  display: inline-block;
  font-size: 2rem;
  line-height: 35px;
  color: white;
  font-weight: bold;
}

.header_nav_list {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  width: 500px;
  height: 20px;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  -ms-flex-wrap: nowrap;
      flex-wrap: nowrap;
  list-style: none;
}

.header_nav_list_item {
  height: 100%;
}

.header_nav_list_item:nth-child(2) a {
  color: red;
  font-size: 1.2rem;
}

.header_nav_list_item a {
  text-decoration: none;
  display: block;
  width: 100%;
  height: 100%;
  line-height: 20px;
  font-size: 1.2rem;
  color: aqua;
}
</style>
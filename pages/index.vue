<template>
  <div class="site-wrapper">
    <div class="doc-loader"></div>

    <MenuHolderFront></MenuHolderFront>
    <MenuHolderBack></MenuHolderBack>
  

    <!-- Page Content Holder -->
    <div id="content" class="site-content">
      <div class="content-holder center-relative content-1170">
        <div id="portfolio-wrapper">
          <ul class="grid" id="portfolio-grid">
            <li class="grid-sizer"></li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="single-portfolio.html">
                <img src="/images/home_01.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">PHOTOGRAPHY</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="/images/home_02B.jpg" data-rel="prettyPhoto[portfolio]">
                <img src="/images/home_02.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">MOCKUP</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="https://vimeo.com/199192931" data-rel="prettyPhoto[portfolio]">
                <img src="/images/home_03.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">SNEAKERS</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one animate">
              <a class="item-link" href="/images/home_04.jpg" data-rel="prettyPhoto[portfolio]">
                <img src="/images/home_04.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">ARCHITECTURE</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="single-portfolio.html">
                <img src="/images/home_05.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">ART</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="/images/home_06.jpg" data-rel="prettyPhoto[portfolio]">
                <img src="/images/home_06.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">OFFICE</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="single-portfolio.html">
                <img src="/images/home_07.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">MODEL</p>
                </div>
              </a>
            </li>

            <li class="grid-item p_one_hlaf animate">
              <a class="item-link" href="single-portfolio.html">
                <img src="/images/home_08.jpg" alt="" />
                <div class="portfolio-text-holder">
                  <p class="portfolio-title">MOCKUP</p>
                </div>
              </a>
            </li>

          </ul>
        </div>
      </div>
    </div>
    <!-- End Page Content Holder -->

    <Footer></Footer>


  </div>
</template>

<script>
  import MenuHolderFront from "~/components/organisms/MenuHolderFront"
  import MenuHolderBack from "~/components/organisms/MenuHolderBack"
  import Footer from "~/components/organisms/Footer"

  export default {
    components: {
      MenuHolderFront,
      MenuHolderBack,
      Footer
    }
  }
</script>


<style>
</style>
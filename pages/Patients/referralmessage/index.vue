<template>
  <div>
    <body
      class="vertical-layout vertical-menu-modern 2-columns  navbar-floating footer-static  "
      data-open="click"
      data-menu="vertical-menu-modern"
      data-col="2-columns"
    >
      <Header></Header>
      <side-bar></side-bar>

      <div class="app-content content">
        <div class="content-overlay"></div>
        <div class="header-navbar-shadow"></div>
        <div class="content-wrapper">
          <div class="content-header row justify-content-center">
            <div class="content-header-left col-md-5 col-12 mb-2">
              <div class="row breadcrumbs-top">
                <div class="col-12">
                  <h4 class="content-header-title float-left mb-0">Referral</h4>
                </div>
              </div>
            </div>
          </div>
          <div class="content-body">
            <section class="page-users-view">
              <div class="row justify-content-center">
                <!-- account start -->
                <div class="col-12 col-md-5 col-lg-5">
                  <div class="card justify-content-center">
                    <div class="card-header">
                      <!-- <div class="card-title">Help</div> -->
                    </div>
                    <div class="card-body">
                      <div class="row">
                        <div class="col-12">
                          <h5>Thank You</h5>
                          <hr />
                        </div>
                        <div class="col-12 col-sm-12 col-md-12 col-lg-12">
                          <p class="text-justify" style="line-height: 20px;">
                            Thank you for extending our act of kindness to your
                            family and freinds.
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>
      </div>
      <!-- END: Content-->

      <div class="sidenav-overlay"></div>
      <div class="drag-target"></div>

      <Footer></Footer>
    </body>
  </div>
</template>
<script>
import Header from '~/components/customer/Header.vue'
import Footer from '~/components/customer/Footer.vue'
import SideBar from '~/components/customer/SideBar.vue'

export default {
  name: 'Dashboard',
  components: {
    Header,
    Footer,
    SideBar
  }
}
</script>
<style>
.other-link {
  position: fixed;
  bottom: 0;
  left: 0;
}
</style>

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
            <div class="content-header-left col-md-6 col-12 mb-2">
              <div class="row breadcrumbs-top">
                <div class="col-12">
                  <h4 class="content-header-title float-left mb-0">
                    Case File
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="content-body">
            <div class="row justify-content-md-center">
              <div class="col-lg-6">
                <section class="card">
                  <div class="row ">
                    <!-- account start -->
                    <div class="col-12 col-md-12 col-lg-12 pb-0">
                      <div class="card">
                        <div class="card-header">
                          <!-- <div class="card-title">Case File</div> -->
                        </div>
                        <div class="card-body pb-0">
                          <div class="row pb-0">
                            <div
                              class="col-12 col-sm-12 col-md-12 col-lg-12 pb-0"
                            ></div>
                          </div>
                          <ul
                            id="myTab2"
                            class="nav nav-tabs nav-justified"
                            role="tablist"
                          >
                            <li class="nav-item">
                              <a
                                id="home-tab-justified"
                                class="nav-link active"
                                data-toggle="tab"
                                href="#home-just"
                                role="tab"
                                aria-controls="home-just"
                                aria-selected="true"
                                style="font-size: 16px;"
                                >Pending<sup>(4)</sup></a
                              >
                            </li>
                            <li class="nav-item">
                              <a
                                id="profile-tab-justified"
                                class="nav-link"
                                data-toggle="tab"
                                href="#profile-just"
                                role="tab"
                                aria-controls="profile-just"
                                aria-selected="true"
                                style="font-size: 16px;"
                                >Completed<sup>(5)</sup></a
                              >
                            </li>
                          </ul>
                          <!-- Tab panes -->
                          <div class="tab-content pt-1">
                            <div
                              id="home-just"
                              class="tab-pane active"
                              role="tabpanel"
                              aria-labelledby="home-tab-justified"
                            >
                              <div class="col-lg-12 col-md-12 col-12">
                                <section class="mb-50">
                                  <div class="card-header">
                                    <!-- <h4 class="card-title">Description</h4> -->
                                  </div>
                                  <div class="card">
                                    <table class="table data-list-view">
                                    <tbody>
                                      <tr>
                                        <td class="product-name">1. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="/doctor/casefile/singlefile"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">2. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="/doctor/casefile/singlefile"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link>
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">3. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="/doctor/casefile/singlefile"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">4. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="/doctor/casefile/singlefile"
                                            class="btn btn-sm btn-primary float-right"
                                            >view</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                    </tbody>
                                  </table>
                                  </div>
                                </section>
                              </div>
                            </div>
                            <div
                              id="profile-just"
                              class="tab-pane"
                              role="tabpanel"
                              aria-labelledby="profile-tab-justified"
                            >
                            <div class="col-lg-12 col-md-12 col-12">
                              <section class="mb-50">
                                <div class="card-header">
                                  <!-- <h4 class="card-title">Description</h4> -->
                                </div>
                                <div class="card">
                                    <table class="table data-list-view">
                                    <tbody>
                                      <tr>
                                        <td class="product-name">1. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="/doctor/casefile/completed"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">2. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="schedulehome"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link>
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">3. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="casefile"
                                            class="btn btn-sm btn-primary float-right"
                                            >View</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                      <tr>
                                        <td class="product-name">4. Call with Mr Ahmed Haruna</td>
                                        <td>
                                          <nuxt-link
                                            to="requestnurse"
                                            class="btn btn-sm btn-primary float-right"
                                            >view</nuxt-link
                                          >
                                        </td>
                                      </tr>
                                    </tbody>
                                  </table>
                                  </div>
                              </section>
                            </div>
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
import Header from '~/components/doctor/Header'
import Footer from '~/components/doctor/Footer'
import SideBar from '~/components/doctor/SideBar'

export default {
  name: 'Casefile',
  components: {
    Header,
    Footer,
    SideBar
  }
}
</script>

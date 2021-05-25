<template>
  <div>
    <div id="wrapper">
      <Header />
      <div class="page-title lb single-wrapper">
        <div class="container">
          <div class="row">
            <div class="col-lg-8 col-md-8 col-sm-12 col-xs-12">
              <h2>
                <i class="fa fa-envelope-open-o bg-orange"></i> Contact us
                <small class="hidden-xs-down hidden-sm-down"
                  >Nulla felis eros, varius sit amet volutpat non.
                </small>
              </h2>
            </div>
            <!-- end col -->
            <div
              class="col-lg-4 col-md-4 col-sm-12 hidden-xs-down hidden-sm-down"
            >
              <ol class="breadcrumb">
                <li class="breadcrumb-item"><a href="#">Home</a></li>
                <li class="breadcrumb-item active">Contact</li>
              </ol>
            </div>
            <!-- end col -->
          </div>
          <!-- end row -->
        </div>
        <!-- end container -->
      </div>
      <!-- end page-title -->

      <section class="section wb">
        <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <div class="page-wrapper">
                <div class="row">
                  <div class="col-lg-5">
                    <h4>What is the website for?</h4>
                    <p>
                      Tech Blog is a personal blog for sharing the skills
                      regarding the trending technologies like vue.js, Node.js.
                    </p>

                    <h4>How this website will help you?</h4>
                    <p>
                      Etiam vulputate urna id libero auctor maximus. Nulla
                      dignissim ligula diam, in sollicitudin ligula congue quis
                      turpis dui urna nibhs.
                    </p>
                  </div>
                  <div class="col-lg-7">
                    <form class="form-wrapper">
                      <input
                        type="text"
                        class="form-control"
                        placeholder="Your name"
                      />
                      <input
                        type="text"
                        class="form-control"
                        placeholder="Email address"
                      />
                      <input
                        type="text"
                        class="form-control"
                        placeholder="Phone"
                      />
                      <input
                        type="text"
                        class="form-control"
                        placeholder="Subject"
                      />
                      <textarea
                        class="form-control"
                        placeholder="Your message"
                      ></textarea>
                      <button type="submit" class="btn btn-primary">
                        Send <i class="fa fa-envelope-open-o"></i>
                      </button>
                    </form>
                  </div>
                </div>
              </div>
              <!-- end page-wrapper -->
            </div>
            <!-- end col -->
          </div>
          <!-- end row -->
        </div>
        <!-- end container -->
      </section>
      <Footer />
    </div>
    <!-- end wrapper -->
  </div>
</template>
<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
export default {
  name: "DetailPage",
  components: {
    Header,
    Footer,
  },
};
</script>

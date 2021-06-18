<template>
  <main role="main">
    <!-- CSS WebSlides -->

    <article id="webslides" class="vertical">
      <!-- Quick Guide
          - Each parent <section> in the <article id="webslides"> element is an individual slide.
          - Vertical sliding = <article id="webslides" class="vertical">
          - <div class="wrap"> = container 90% / <div class="wrap size-50"> = 45%;
        -->

      <section>
        <span
          class="background"
          style="background-image:url('https://webslides.tv/static/images/nature.jpg')"
        ></span>
        <!--.wrap = container (width: 90%) -->
        <div class="wrap aligncenter">
          <h1>
            <strong
              >Ceres N Meses <br />
              Science-Engineering Project</strong
            >
          </h1>
          <p class="text-intro" style="margin-top: 20px;">
            MTs TechnoNatura Science-Engineering Team Project called Ceres N
            Meses<br />
          </p>
        </div>
        <!-- .end .wrap -->
      </section>

      <section>
        <div class="wrap">
          <h3>Team</h3>
          <p>Ceres N Meses Team</p>
          <ul class="flexblock gallery">
            <li>
              <a href="#">
                <figure>
                  <img
                    alt="Thumbnail"
                    src="https://avatars.githubusercontent.com/u/67791514?v=4"
                  />
                  <figcaption>
                    <h2>Aldhanekaa</h2>
                    <p>Programmer & Mechanic</p>
                  </figcaption>
                </figure>
              </a>
            </li>
            <li>
              <a href="#">
                <figure>
                  <img
                    alt="Thumbnail"
                    src="https://avatars.githubusercontent.com/u/67791514?v=4"
                  />
                  <figcaption>
                    <h2>Nabil</h2>
                    <p>Mechanic</p>
                  </figcaption>
                </figure>
              </a>
            </li>

            <li>
              <a href="#">
                <figure>
                  <img
                    alt="Thumbnail"
                    src="https://avatars.githubusercontent.com/u/67791514?v=4"
                  />
                  <figcaption>
                    <h2>Asyilah</h2>
                    <p>Designer</p>
                  </figcaption>
                </figure>
              </a>
            </li>
            <li>
              <a href="#">
                <figure>
                  <img
                    alt="Thumbnail"
                    src="https://avatars.githubusercontent.com/u/67791514?v=4"
                  />
                  <figcaption>
                    <h2>Sasa</h2>
                    <p>Conceptor</p>
                  </figcaption>
                </figure>
              </a>
            </li>
          </ul>
        </div>
        <!-- .end .wrap -->
      </section>

      <section>
        <div class="wrap">
          <h2><strong>Ceres N Meses Projects</strong></h2>

          <ul class="flexblock gallery">
            <li>
              <a href="#">
                <div class="overlay">
                  <h2>Acclimatisation</h2>
                  <p>Dec 18, 2020</p>
                </div>
                <img
                  alt="Thumbnail "
                  src="https://source.unsplash.com/A5-Xr7WyktQ/800x600"
                />
              </a>
            </li>
            <li>
              <a href="#">
                <div class="overlay">
                  <h2>Arduino Project</h2>
                  <p>Feb 18, 2021</p>
                </div>
                <img
                  alt="Thumbnail "
                  src="https://source.unsplash.com/kt_s46DVgJA/800x600"
                />
              </a>
            </li>
          </ul>
        </div>
        <!-- .end .wrap -->
      </section>

      <section class="slide-bottom">
        <div class="wrap">
          <div class="content-right text-serif">
            <h2>
              <strong>Thanks.</strong>
              <a
                target="_blank"
                title="Share on Twitter"
                href="https://twitter.com/intent/tweet?text=https://twitter.com/intent/tweet?text=Hello%20there%20👋%0A%0ACheck%20out%20https://ceres-n-meses.now.sh%20by%20https://github.com/aldhanekaa%0A%0A"
              >
                <svg class="fa-twitter">
                  <use xlink:href="#fa-twitter"></use>
                </svg>
              </a>
            </h2>
            <p>
              People share content that makes them feel inspired. WebSlides is a
              very effective way to engage young audiences, customers, and
              teams.
            </p>
            <p>
              Best Regard,<br />
              <a href="https://github/aldhanekaa">Aldhanekaa</a>,
              <a href="https://www.instagram.com/nabilradityya/">Nabil</a>,
              <a>Sasa</a>, and <a>Asyilah</a>.
            </p>
          </div>
          <!-- .end .content-right -->
        </div>
        <!-- .end .wrap -->
      </section>
    </article>
    <!-- end article -->
  </main>
</template>
<script>
import Vue from "vue";
import VueMeta from "vue-meta";

Vue.use(VueMeta, {
  // optional pluginOptions
  refreshOnceOnNavigation: true
});

export default Vue.extend({
  layout: "webslide",

  head() {
    return {
      title: "Ceres N Meses Projects",
      description:
        "The Ceres N Meses MTs TechnoNatura Grade 7 Science-Engineering group webslides.",
      script: [
        {
          hid: "webslides",
          src:
            "https://res.cloudinary.com/dsg8ufk2s/raw/upload/v1623638702/webslides_pxcuxs.js",
          // Changed after script load
          callback: () => {
            // @ts-ignore
            window.ws = new WebSlides();
          }
        },
        {
          hid: "svg",
          src:
            "https://res.cloudinary.com/dsg8ufk2s/raw/upload/v1623638751/svg-icons_qknm7l.js",
          defer: true
        }
      ]
    };
  }
});
</script>

<template>
<div id="stars"></div>
<div id="star2"></div>
<div id="star3"></div>
  <div id="app">
    <div class="uk-section-primary tm-section-texture">
      <div
        uk-sticky="media: 960"
        class="
          uk-navbar-container
          tm-navbar-container
          uk-navbar-transparent uk-sticky uk-sticky-fixed
        "
        style="position: fixed; top: 0px; width: 1440px"
      >
        <div class="uk-container uk-container-expand">
          <nav class="uk-navbar">
            <div class="uk-navbar-left">
              <a
                href="/"
                aria-current="page"
                class="
                  uk-navbar-item uk-logo
                  router-link-exact-active
                  uk-active
                "
                ><canvas
                  width="28"
                  height="34"
                  uk-svg=""
                  src="./images/netcraft.svg"
                  class="uk-margin-small-right"
                  hidden=""
                ></canvas
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="28"
                  height="34"
                  viewBox="0 0 28 34"
                  class="uk-margin-small-right uk-svg"
                >
                  <polygon
                    points="19.1 4.1 13.75 1 8.17 4.45 13.6 7.44 19.1 4.1"
                    fill="#fff"
                  ></polygon>
                  <path
                    d="M21.67,5.43,16.14,8.77,22.4,12.4v9.52l-8.44,4.76L5.6,21.93V14.55L0,11.7V25.21l13.75,8.08L28,25.21V9.07Z"
                    fill="#fff"
                  ></path>
                </svg>
                NetCraft 
              </a>
            </div>
            <div class="uk-navbar-right">
              <ul class="uk-navbar-nav uk-visible@m">
                <li class=""><a href="/pro">Company</a></li>
                <li><a href="docs/introduction">Services</a></li>
                <li class=""><a href="/changelog">Projects</a></li>
                <li class=""><a href="/changelog">Support</a></li>
                <li class=""><a href="/changelog">Contact</a></li>
              </ul>
              <div class="uk-navbar-item uk-visible@m">
                <a
                  href="/download"
                  class="uk-button uk-button-default tm-button-default uk-icon"
                >
                  Download
                  <canvas
                    uk-icon="download"
                    width="20"
                    height="20"
                    class="uk-icon"
                    hidden=""
                  ></canvas
                  ><svg
                    width="20"
                    height="20"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <polyline
                      fill="none"
                      stroke="#000"
                      points="14,10 9.5,14.5 5,10"
                    ></polyline>
                    <rect x="3" y="17" width="13" height="1"></rect>
                    <line
                      fill="none"
                      stroke="#000"
                      x1="9.5"
                      y1="13.91"
                      x2="9.5"
                      y2="3"
                    ></line></svg
                ></a>
              </div>
              <a
                uk-navbar-toggle-icon=""
                href="#offcanvas"
                uk-toggle=""
                class="
                  uk-navbar-toggle uk-hidden@m uk-icon uk-navbar-toggle-icon
                "
                aria-expanded="false"
                ><svg
                  width="20"
                  height="20"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <rect y="9" width="20" height="2"></rect>
                  <rect y="3" width="20" height="2"></rect>
                  <rect y="15" width="20" height="2"></rect></svg
              ></a>
            </div>
          </nav>
        </div>
      </div>
      <div
        class="uk-sticky-placeholder"
        style="height: 80px; margin: 0px"
      ></div>
      <div
        uk-height-viewport="offset-top: true; offset-bottom: true"
        class="
          uk-section
          uk-section-small
          uk-flex
          uk-flex-middle
          uk-text-center
          uk-height-viewport
        "
        style="min-height: calc(-182px + 100vh)"
      >
        <div class="uk-width-1-1">
          <div class="uk-container">
            <p>
              <canvas
                width="168"
                height="155"
                uk-svg=""
                src="./images/uikit-logo-large.svg"
                style="color: rgb(255, 255, 255)"
                hidden=""
              ></canvas
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="168"
                height="155"
                viewBox="0 0 168 155"
                style="color: rgb(255, 255, 255)"
                class="uk-svg"
              >
                <path
                  d="M117.4,33.3,93.3,47.9l27.8,15.8v41.5L83.8,126,47.1,105.2V73L23,60.7v58.9l59.9,35.2L145,119.6V49.2Zm-11.2-5.8L82.9,14,58.6,29.1l23.6,13Z"
                  fill="#fff"
                ></path>
              </svg>
            </p>
            <p class="uk-margin-medium uk-text-lead">
              Full Stack Project<br
                class="uk-visible@s"
              />Developed Bpy<br>
              Montgomery James Kern
            </p>

            <div
              class="uk-flex-center uk-grid-small uk-child-width-auto"
              uk-grid
              uk-countdown="date: 2022-05-31T03:29:11+00:00"
            >
              <div>
                <div class="uk-countdown-number uk-countdown-days"></div>
                <div
                  class="
                    uk-countdown-label
                    uk-margin-small
                    uk-text-center
                    uk-visible@s
                  "
                >
                  Days
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                <div class="uk-countdown-number uk-countdown-hours"></div>
                <div
                  class="
                    uk-countdown-label
                    uk-margin-small
                    uk-text-center
                    uk-visible@s
                  "
                >
                  Hours
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                <div class="uk-countdown-number uk-countdown-minutes"></div>
                <div
                  class="
                    uk-countdown-label
                    uk-margin-small
                    uk-text-center
                    uk-visible@s
                  "
                >
                  Minutes
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                <div class="uk-countdown-number uk-countdown-seconds"></div>
                <div
                  class="
                    uk-countdown-label
                    uk-margin-small
                    uk-text-center
                    uk-visible@s
                  "
                >
                  Seconds
                </div>
              </div>
            </div>

            <div
              uk-grid=""
              class="
                uk-child-width-auto
                uk-grid-medium
                uk-flex-inline
                uk-flex-center
                uk-grid
              "
            >
              <div class="uk-first-column">
                <a
                  href="docs/introduction"
                  class="
                    uk-button uk-button-primary
                    tm-button-primary
                    uk-button-large
                    tm-button-large
                    uk-visible@s
                  "
                  >Get Started</a
                >
                <a
                  href="docs/introduction"
                  class="
                    uk-button uk-button-primary
                    tm-button-primary
                    uk-hidden@s
                  "
                  >Get Started</a
                >
              </div>
              <div>
                <a
                  href="https://github.com/montgomerykern"
                  class="
                    uk-button uk-button-default
                    tm-button-default
                    uk-button-large
                    tm-button-large
                    uk-visible@s
                  "
                  >GitHub</a
                >
                <a
                  href="https://github.com/montgomerykern/"
                  class="
                    uk-button uk-button-default
                    tm-button-default
                    uk-hidden@s
                  "
                  >GitHub</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="uk-section-small">
        <div
          class="
            uk-container uk-container-expand uk-text-center uk-position-relative
          "
        >
          <ul
            uk-margin=""
            class="
              uk-subnav
              tm-subnav
              uk-flex-inline uk-flex-center uk-margin-remove-bottom
            "
          >
            <li class="uk-first-column">
              <span>Version <span>1.01 Beta</span></span>
            </li>
            <li>
              <a href="https://github.com/uikit/uikit/stargazers"
                ><span uk-icon="star" class="uk-margin-small-right uk-icon"
                  ><svg
                    width="20"
                    height="20"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <polygon
                      fill="none"
                      stroke="#000"
                      stroke-width="1.01"
                      points="10 2 12.63 7.27 18.5 8.12 14.25 12.22 15.25 18 10 15.27 4.75 18 5.75 12.22 1.5 8.12 7.37 7.27"
                    ></polygon></svg></span
                ><span>17432</span> Stargazers</a
              >
            </li>
            <li>
              <a href="https://twitter.com/montgomerykern" class="uk-text-lowercase"
                ><span uk-icon="twitter" class="uk-margin-small-right uk-icon"
                  ><svg
                    width="20"
                    height="20"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M19,4.74 C18.339,5.029 17.626,5.229 16.881,5.32 C17.644,4.86 18.227,4.139 18.503,3.28 C17.79,3.7 17.001,4.009 16.159,4.17 C15.485,3.45 14.526,3 13.464,3 C11.423,3 9.771,4.66 9.771,6.7 C9.771,6.99 9.804,7.269 9.868,7.539 C6.795,7.38 4.076,5.919 2.254,3.679 C1.936,4.219 1.754,4.86 1.754,5.539 C1.754,6.82 2.405,7.95 3.397,8.61 C2.79,8.589 2.22,8.429 1.723,8.149 L1.723,8.189 C1.723,9.978 2.997,11.478 4.686,11.82 C4.376,11.899 4.049,11.939 3.713,11.939 C3.475,11.939 3.245,11.919 3.018,11.88 C3.49,13.349 4.852,14.419 6.469,14.449 C5.205,15.429 3.612,16.019 1.882,16.019 C1.583,16.019 1.29,16.009 1,15.969 C2.635,17.019 4.576,17.629 6.662,17.629 C13.454,17.629 17.17,12 17.17,7.129 C17.17,6.969 17.166,6.809 17.157,6.649 C17.879,6.129 18.504,5.478 19,4.74"
                    ></path></svg></span
                >@NetCraft</a
              >
            </li>
            <li>
              <a href="https://discordapp.com/invite/NEt4Pv7"
                ><span
                  uk-icon="commenting"
                  class="uk-margin-small-right uk-icon"
                  ><svg
                    width="20"
                    height="20"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <polygon
                      fill="none"
                      stroke="#000"
                      points="1.5,1.5 18.5,1.5 18.5,13.5 10.5,13.5 6.5,17.5 6.5,13.5 1.5,13.5"
                    ></polygon>
                    <circle cx="10" cy="8" r="1"></circle>
                    <circle cx="6" cy="8" r="1"></circle>
                    <circle cx="14" cy="8" r="1"></circle></svg></span
                >Community</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import UIkit from "uikit";
import Icons from "uikit/dist/js/uikit-icons";
UIkit.use(Icons);
export default {
  name: "App",
};
</script>>
<style lang="less">
@import "../node_modules/uikit/src/less/uikit.less";
@import "./assets/less/theme.less";
</style>
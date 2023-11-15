<template>
  <div class="header">
    <v-layout class="header-container">
      <v-flex class="header-logo align-self-center">
        <a href="/">
          <svg
            viewBox="0 0 130 55"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            id="logo"
            class="icon-svg"
            style="width: 160px; height: 40px; margin-left: 5px"
          >
            <path
              d="M45.006 9.732a51.401 51.401 0 00-.454-4.665A52.67 52.67 0 0040.22 3.25a53.243 53.243 0 00-4.385-1.38c.35 1.432.629 2.882.838 4.367a43.86 43.86 0 01.42 6.115c0 12.93-5.643 24.548-14.571 32.567a44.198 44.198 0 01-3.128 2.55 41.69 41.69 0 01-3.302 2.202c1.014.961 1.992 1.94 3.075 2.813A46.59 46.59 0 0022.521 55a46.567 46.567 0 003.354-2.516 58.456 58.456 0 003.128-2.743c9.434-8.998 15.462-21.507 15.986-35.414.017-.647.035-1.31.035-1.975.052-.873.017-1.747-.018-2.62z"
              fill="url(#paint0_linear)"
            ></path>
            <path
              d="M45.006 9.61a51.401 51.401 0 00-.454-4.666 52.67 52.67 0 00-4.333-1.817 53.253 53.253 0 00-4.385-1.38A51.382 51.382 0 0022.538 0c-4.595 0-9.05.611-13.296 1.747a53.24 53.24 0 00-4.385 1.38A55.33 55.33 0 00.524 4.944 51.412 51.412 0 00.07 9.61 43.93 43.93 0 000 12.248c0 .663.017 1.31.035 1.974a42.376 42.376 0 013.931-2.097 40.36 40.36 0 014.018-1.642 43.568 43.568 0 0114.537-2.481c5.101 0 9.993.873 14.536 2.48 1.363.49 2.708 1.032 4.018 1.643a47.013 47.013 0 013.931 2.097c.018-.647.035-1.31.035-1.974.035-.874 0-1.765-.035-2.639z"
              fill="url(#paint1_linear)"
            ></path>
            <path
              d="M25.683 47.487a44.2 44.2 0 01-3.127-2.55C13.61 36.934 7.984 25.299 7.984 12.37c0-.594.018-1.188.035-1.782.07-1.468.193-2.9.385-4.333.21-1.485.489-3.075.838-4.508-1.485.402-2.97.891-4.402 1.415-1.468.542-2.883 1.101-4.298 1.765a48.241 48.241 0 00-.437 4.787c-.053.874-.07 1.747-.07 2.638 0 .664.017 1.31.035 1.974.524 13.908 6.57 26.417 15.986 35.415a51.68 51.68 0 003.128 2.743A59.908 59.908 0 0022.538 55a52.453 52.453 0 003.355-2.516 51.65 51.65 0 003.127-2.743 46.546 46.546 0 01-3.337-2.254z"
              fill="url(#paint2_linear)"
            ></path>
            <path
              d="M19.743 35.048V26.73h-8.387v-5.73h8.387v-8.317h5.59v8.317h8.404v5.73h-8.404v8.317h-5.59z"
              fill="url(#paint3_linear)"
            ></path>
            <path
              d="M62.95 36.786L52.938 8.779h6.133L66.164 29.5l6.867-20.72h5.992L68.995 36.785h-6.046zM81.958 36.786V8.779h5.504l11.461 18.695V8.779h5.259v28.007h-5.678L87.217 18.528v18.258h-5.259zM117.303 36.786L107.292 8.779h6.132l7.094 20.721 6.866-20.72h5.993l-10.029 28.006h-6.045zM154.168 26.495l5.486 1.73c-.839 3.057-2.237 5.329-4.193 6.814-1.957 1.485-4.438 2.218-7.443 2.218-3.722 0-6.779-1.275-9.173-3.808-2.393-2.534-3.599-6.01-3.599-10.413 0-4.665 1.206-8.282 3.617-10.867 2.411-2.586 5.573-3.862 9.487-3.862 3.424 0 6.202 1.014 8.351 3.04 1.275 1.206 2.236 2.918 2.865 5.155l-5.59 1.345c-.332-1.45-1.014-2.603-2.08-3.442-1.048-.839-2.323-1.258-3.826-1.258-2.079 0-3.756.751-5.049 2.236-1.293 1.485-1.939 3.896-1.939 7.233 0 3.547.629 6.063 1.904 7.566 1.275 1.502 2.935 2.253 4.962 2.253 1.502 0 2.795-.471 3.879-1.432 1.1-.961 1.869-2.464 2.341-4.508zM57.848 49.26l-2.638-7.268h1.59l1.869 5.382 1.747-5.4h1.555l-2.568 7.304-1.555-.018zM62.548 43.25v-1.293h1.397v1.293h-1.397zm.035 5.993l-.035-5.276h1.397l.035 5.276h-1.397zM68.453 47.53l1.398.228c-.175.506-.455.908-.839 1.17-.384.263-.874.402-1.45.402-.926 0-1.59-.297-2.044-.89-.35-.472-.524-1.084-.524-1.818 0-.873.227-1.555.681-2.061a2.273 2.273 0 011.73-.752c.786 0 1.397.245 1.87.77.453.523.68 1.31.663 2.375l-3.494.018c.017.419.122.733.35.96.209.228.488.35.803.35.227 0 .402-.07.559-.175a1.47 1.47 0 00.297-.576zm.07-1.414c-.018-.402-.123-.717-.315-.926a.952.952 0 00-.733-.315c-.297 0-.56.122-.752.332-.192.227-.297.524-.28.909h2.08zM73.45 43.897v1.118h-.961l.017 2.131c0 .437.018.682.035.752.018.07.053.122.123.174.07.053.14.07.244.07.123 0 .315-.052.56-.14l.122 1.084a2.81 2.81 0 01-1.101.21c-.245 0-.472-.036-.681-.123a1.027 1.027 0 01-.455-.332 1.406 1.406 0 01-.192-.541c-.035-.158-.052-.49-.052-.979l-.018-2.306h-.646v-1.118h.646v-1.049l1.398-.82.017 1.869h.944zM79.25 49.156h-1.397l-.018-2.691c0-.577-.035-.944-.087-1.1a.665.665 0 00-.297-.385.894.894 0 00-.49-.14c-.244 0-.454.07-.646.21-.192.14-.314.314-.384.524-.07.227-.105.629-.105 1.205l.017 2.394h-1.397l-.035-5.276h1.293v.768c.454-.594 1.03-.908 1.73-.908.314 0 .593.052.838.157.262.105.454.245.576.42.14.174.228.366.28.576.052.227.087.524.087.944l.035 3.302zM81.696 45.47l-1.275-.228c.14-.507.384-.891.734-1.136.35-.244.856-.367 1.555-.384.629 0 1.083.07 1.397.21.297.14.525.332.647.559.122.227.192.646.192 1.24v1.625c0 .472.035.804.07 1.03.052.228.14.455.262.7h-1.38a3.822 3.822 0 01-.14-.42c-.018-.087-.035-.14-.052-.157-.245.227-.49.402-.77.524a2.11 2.11 0 01-.873.175c-.541 0-.978-.14-1.293-.437a1.465 1.465 0 01-.471-1.118c0-.297.07-.56.21-.804.139-.227.331-.419.593-.541a4.629 4.629 0 011.101-.332c.646-.123 1.1-.245 1.363-.35v-.14c0-.261-.07-.454-.21-.576-.14-.105-.384-.175-.751-.175-.245 0-.437.053-.577.157-.14.158-.244.332-.332.577zm1.87 1.117c-.175.053-.454.14-.856.21-.385.087-.647.175-.752.245-.174.122-.28.297-.262.489 0 .192.07.367.227.506.14.14.332.21.56.21.244 0 .489-.087.716-.245a.816.816 0 00.332-.471c.035-.123.052-.35.052-.682l-.017-.262zM86.204 43.827h1.293v.716c.454-.559.996-.838 1.642-.856.332 0 .63.07.874.21.244.14.454.35.611.629.227-.28.472-.49.752-.63.261-.14.558-.209.856-.209.384 0 .716.07.978.227s.472.384.612.681c.104.228.14.595.157 1.101l.017 3.372H92.6l-.018-3.022c0-.524-.052-.856-.157-1.014-.123-.192-.332-.297-.594-.297-.192 0-.385.07-.56.175a.961.961 0 00-.366.524c-.07.227-.105.594-.105 1.083l.017 2.534H89.42l-.018-2.9c0-.507-.035-.84-.087-.996-.053-.158-.122-.263-.227-.332a.745.745 0 00-.42-.105.975.975 0 00-.576.174.918.918 0 00-.367.507c-.07.227-.105.577-.105 1.083l.018 2.569h-1.398l-.035-5.224zM100.076 49.033l-2.638-7.268h1.59l1.869 5.381 1.748-5.398h1.554l-2.568 7.303-1.555-.018zM105.457 45.347l-1.275-.227c.14-.507.384-.891.734-1.136.349-.245.856-.367 1.555-.384.629 0 1.083.07 1.397.21.297.14.525.331.647.558.122.227.192.647.192 1.24v1.626c0 .471.035.803.07 1.03.052.228.14.455.262.7h-1.38a3.7 3.7 0 01-.14-.42c-.017-.087-.035-.14-.052-.157-.245.227-.49.402-.769.524-.28.122-.559.175-.874.175-.541 0-.978-.14-1.293-.437a1.466 1.466 0 01-.471-1.118c0-.297.07-.56.209-.804.14-.227.332-.42.594-.542a4.629 4.629 0 011.101-.332c.647-.122 1.101-.244 1.363-.349v-.14c0-.262-.07-.454-.21-.576-.14-.105-.384-.175-.751-.175-.245 0-.437.052-.577.157a1.691 1.691 0 00-.332.577zm1.87 1.118c-.175.052-.454.14-.856.21-.385.087-.647.174-.752.244-.174.123-.279.297-.262.49 0 .192.07.366.228.506.139.14.331.21.559.21.244 0 .489-.088.716-.245a.818.818 0 00.332-.472c.035-.122.052-.349.052-.68l-.017-.263zM114.665 45.242l-1.38.262c-.053-.28-.158-.49-.315-.611-.157-.14-.384-.21-.646-.21-.35 0-.629.122-.839.367-.21.244-.314.646-.297 1.205 0 .63.105 1.066.315 1.328.209.262.489.385.856.385.262 0 .489-.07.646-.228.175-.157.28-.419.35-.786l1.38.227c-.14.63-.402 1.101-.804 1.433-.402.332-.943.49-1.625.49-.769 0-1.38-.228-1.852-.717-.454-.49-.699-1.153-.699-2.027 0-.873.227-1.555.682-2.044.454-.49 1.083-.734 1.869-.734.647 0 1.153.14 1.538.402.384.262.664.681.821 1.258zM120.326 45.207l-1.381.262c-.052-.28-.157-.49-.314-.611-.157-.14-.384-.21-.647-.21-.349 0-.629.122-.838.367-.21.244-.315.646-.297 1.205 0 .63.105 1.066.314 1.328.21.262.489.385.856.385.262 0 .49-.07.647-.228.175-.157.279-.419.349-.786l1.38.227c-.139.63-.401 1.101-.803 1.433-.402.332-.944.49-1.625.49-.769 0-1.38-.228-1.852-.717-.454-.49-.699-1.153-.699-2.027 0-.873.227-1.555.682-2.044.454-.49 1.083-.734 1.869-.734.646 0 1.153.14 1.537.402.385.28.664.699.822 1.258zM121.374 42.918v-1.293h1.398v1.293h-1.398zm.035 5.993l-.035-5.276h1.398l.034 5.276h-1.397zM129.044 48.876h-1.398l-.017-2.69c0-.577-.035-.944-.088-1.101a.662.662 0 00-.297-.385.894.894 0 00-.489-.14c-.245 0-.454.07-.646.21a1.03 1.03 0 00-.385.524c-.07.228-.105.63-.105 1.206l.018 2.394h-1.398l-.035-5.277h1.293v.769c.454-.594 1.031-.909 1.73-.909.314 0 .594.053.838.158.262.104.455.244.577.419.14.175.227.367.279.576.053.228.088.525.088.944l.035 3.302zM133.499 47.181l1.398.227c-.175.507-.455.909-.839 1.171-.384.262-.873.402-1.45.402-.926 0-1.607-.297-2.044-.891-.35-.472-.524-1.083-.524-1.817 0-.874.227-1.555.681-2.062a2.273 2.273 0 011.73-.751c.786 0 1.397.245 1.869.769.454.524.682 1.31.664 2.376l-3.494.017c.017.42.122.734.349.961.21.227.489.35.804.35.227 0 .402-.07.559-.175a1.47 1.47 0 00.297-.577zm.07-1.415c-.018-.402-.122-.716-.315-.926a.95.95 0 00-.733-.314c-.297 0-.559.122-.752.332-.192.227-.297.524-.297.908h2.097zM141.536 41.52h1.467l.018 4.613c0 .611-.052 1.066-.157 1.398a2.05 2.05 0 01-.769 1.03c-.367.263-.874.385-1.485.402-.716 0-1.276-.192-1.66-.594-.384-.401-.594-.995-.594-1.764l1.38-.175c.018.42.088.716.192.891.158.262.402.384.734.384.332 0 .559-.104.699-.28.14-.191.192-.576.192-1.17l-.017-4.734zM144.226 46.43l1.433-.14c.087.472.262.839.524 1.049.262.21.629.331 1.066.331.472 0 .839-.104 1.066-.314.244-.21.349-.437.349-.699a.638.638 0 00-.157-.437c-.105-.122-.28-.227-.524-.314a30.912 30.912 0 00-1.188-.315c-.786-.192-1.346-.436-1.66-.716-.454-.402-.681-.891-.681-1.468 0-.366.104-.716.314-1.048.21-.332.507-.576.909-.751.401-.175.873-.262 1.432-.262.909 0 1.608.192 2.062.594.472.402.716.926.734 1.607l-1.468.07c-.07-.367-.21-.646-.402-.804-.209-.157-.524-.244-.926-.244-.419 0-.768.087-.996.262a.513.513 0 00-.227.454c0 .175.07.315.227.437.193.157.647.314 1.363.472.716.157 1.241.332 1.59.524.349.174.612.42.804.734.192.314.297.699.297 1.153 0 .419-.105.803-.35 1.17a2.059 2.059 0 01-.978.822c-.419.174-.944.279-1.59.279-.926 0-1.625-.21-2.131-.629-.507-.42-.787-1.013-.892-1.817zM156.037 46.046l1.433.436c-.21.804-.577 1.38-1.083 1.782-.507.385-1.154.577-1.94.595-.961 0-1.764-.315-2.393-.979-.629-.664-.944-1.555-.944-2.708 0-1.205.297-2.149.926-2.83.629-.682 1.45-1.014 2.464-1.014.891 0 1.625.262 2.184.787.332.314.576.75.751 1.345l-1.45.35c-.088-.385-.262-.682-.542-.892a1.509 1.509 0 00-.996-.314c-.541 0-.978.192-1.31.594-.332.384-.507 1.013-.489 1.887 0 .926.174 1.572.506 1.956.332.385.769.577 1.293.577.385 0 .734-.122 1.014-.384.262-.262.471-.647.576-1.188z"
              fill="#fff"
            ></path>
            <defs>
              <linearGradient
                id="paint0_linear"
                x1="42.384"
                y1="14.504"
                x2="-12.506"
                y2="77.956"
                gradientUnits="userSpaceOnUse"
              >
                <stop stop-color="#FFF337"></stop>
                <stop offset=".248" stop-color="#FBC743"></stop>
                <stop offset=".494" stop-color="#F3A346"></stop>
                <stop offset=".709" stop-color="#EE8A46"></stop>
                <stop offset=".885" stop-color="#EC7B46"></stop>
                <stop offset="1" stop-color="#EB7646"></stop>
              </linearGradient>
              <linearGradient
                id="paint1_linear"
                x1=".024"
                y1="7.124"
                x2="45.072"
                y2="7.124"
                gradientUnits="userSpaceOnUse"
              >
                <stop stop-color="#FFF20F"></stop>
                <stop offset="1" stop-color="#EB7533"></stop>
              </linearGradient>
              <linearGradient
                id="paint2_linear"
                x1="20.984"
                y1="25.259"
                x2="4.498"
                y2="33.501"
                gradientUnits="userSpaceOnUse"
              >
                <stop stop-color="#FFF20F"></stop>
                <stop offset="1" stop-color="#EB7533"></stop>
              </linearGradient>
              <linearGradient
                id="paint3_linear"
                x1="30.189"
                y1="17.02"
                x2="14.897"
                y2="30.683"
                gradientUnits="userSpaceOnUse"
              >
                <stop offset=".002" stop-color="#FFF20F"></stop>
                <stop offset="1" stop-color="#EB7533"></stop>
              </linearGradient>
            </defs></svg
        ></a>
      </v-flex>
      <!-- <div class="header-boderline"></div> -->
      <v-flex sm10 class="align-self-center header-nav">
        <v-layout class="header-nav-container">
          <v-flex md3 class="header-working px-1 align-self-center">
            <v-layout>
              <v-flex lg2 class="align-self-center text-center">
                <v-icon size="40" class="header-working-icon">
                  {{ icons.calendar }}
                </v-icon>
              </v-flex>
              <v-flex lg10 class="align-self-center header-working-item">
                <p class="ma-0 header-working-text">
                  <span class="span-text">Giờ làm việc:</span> Từ thứ 2 đến chủ
                  nhật
                </p>
                <p class="ma-0 header-working-text">
                  Từ 7h30 - 17h00 (Không nghỉ trưa)
                </p>
              </v-flex>
            </v-layout>
          </v-flex>

          <v-flex md9>
            <ul class="navbar">
              <li
                v-for="(item, index) in navItems"
                :key="index"
                class="navbar-item"
              >
                <a :href="item.link" class="navbar-link">
                  <v-icon size="32" color="rgb(129, 187, 250)">{{
                    item.icon
                  }}</v-icon>
                  <p class="navbar-text">{{ item.text }}</p>
                </a>
              </li>

              <div class="navbar-phone">
                <a href="/" class="navbar-link">
                 <svg
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                class="icon-svg mr-2"
                style="width: 32px"
              >
                <path
                  d="M17.228 8.267h-.05V7.054a7.054 7.054 0 00-14.108 0v1.213h-.297c-1.09 0-1.931.966-1.931 2.08v3.094a1.956 1.956 0 001.93 2.004h1.832a.47.47 0 00.446-.52V8.862c0-.297-.173-.594-.446-.594H4.06V7.054a6.064 6.064 0 0112.129 0v1.213h-.545c-.272 0-.446.297-.446.594v6.065a.47.47 0 00.446.52h.57l-.05.074a3.911 3.911 0 01-3.144 1.56 2.45 2.45 0 00-4.851.47A2.475 2.475 0 0010.644 20a2.55 2.55 0 001.782-.767c.317-.325.525-.74.594-1.189a4.9 4.9 0 003.936-1.955l.47-.693c1.064-.074 1.733-.743 1.733-1.708v-3.094c0-1.064-.792-2.327-1.93-2.327zM4.06 14.455H2.773a.965.965 0 01-.941-1.014v-3.095c0-.569.396-1.089.94-1.089H4.06v5.198zm7.648 4.085a1.46 1.46 0 01-1.064.47 1.51 1.51 0 01-1.485-1.46 1.46 1.46 0 112.92-.002v.002c.021.367-.114.726-.37.99zm6.46-4.852c0 .668-.643.767-.94.767h-1.04V9.257h1.04c.545 0 .94.768.94 1.337v3.094z"
                  fill="url(#paint0_linear)"
                ></path>
                <defs>
                  <linearGradient
                    id="paint0_linear"
                    x1="17.472"
                    y1="4.756"
                    x2=".477"
                    y2="37.766"
                    gradientUnits="userSpaceOnUse"
                  >
                    <stop stop-color="#FFF337"></stop>
                    <stop offset=".248" stop-color="#FBC743"></stop>
                    <stop offset=".494" stop-color="#F3A346"></stop>
                    <stop offset=".709" stop-color="#EE8A46"></stop>
                    <stop offset=".885" stop-color="#EC7B46"></stop>
                    <stop offset="1" stop-color="#EB7646"></stop>
                  </linearGradient>
                </defs>
              </svg>
                  <p class="navbar-text">HOTLINE: 028 7102 6595</p>
                </a>
              </div>
            </ul>
          </v-flex>
        </v-layout>

        <div class="header-navigation-bar">
          <v-layout class="justify-end">
            <div class="header-navigation-bar-phone">
              <div>
                <svg
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                class="icon-svg mr-2"
                style="width: 28px"
              >
                <path
                  d="M17.228 8.267h-.05V7.054a7.054 7.054 0 00-14.108 0v1.213h-.297c-1.09 0-1.931.966-1.931 2.08v3.094a1.956 1.956 0 001.93 2.004h1.832a.47.47 0 00.446-.52V8.862c0-.297-.173-.594-.446-.594H4.06V7.054a6.064 6.064 0 0112.129 0v1.213h-.545c-.272 0-.446.297-.446.594v6.065a.47.47 0 00.446.52h.57l-.05.074a3.911 3.911 0 01-3.144 1.56 2.45 2.45 0 00-4.851.47A2.475 2.475 0 0010.644 20a2.55 2.55 0 001.782-.767c.317-.325.525-.74.594-1.189a4.9 4.9 0 003.936-1.955l.47-.693c1.064-.074 1.733-.743 1.733-1.708v-3.094c0-1.064-.792-2.327-1.93-2.327zM4.06 14.455H2.773a.965.965 0 01-.941-1.014v-3.095c0-.569.396-1.089.94-1.089H4.06v5.198zm7.648 4.085a1.46 1.46 0 01-1.064.47 1.51 1.51 0 01-1.485-1.46 1.46 1.46 0 112.92-.002v.002c.021.367-.114.726-.37.99zm6.46-4.852c0 .668-.643.767-.94.767h-1.04V9.257h1.04c.545 0 .94.768.94 1.337v3.094z"
                  fill="url(#paint0_linear)"
                ></path>
                <defs>
                  <linearGradient
                    id="paint0_linear"
                    x1="17.472"
                    y1="4.756"
                    x2=".477"
                    y2="37.766"
                    gradientUnits="userSpaceOnUse"
                  >
                    <stop stop-color="#FFF337"></stop>
                    <stop offset=".248" stop-color="#FBC743"></stop>
                    <stop offset=".494" stop-color="#F3A346"></stop>
                    <stop offset=".709" stop-color="#EE8A46"></stop>
                    <stop offset=".885" stop-color="#EC7B46"></stop>
                    <stop offset="1" stop-color="#EB7646"></stop>
                  </linearGradient>
                </defs>
              </svg>
              </div>

              <div><p class="header-navigation-bar-phonenumber">028 7102 6595</p></div>
            </div>
            <v-btn
              @click.stop="drawer = !drawer"
              class="mr-5"
              color="transparent"
              text
            >
              <v-icon class="white--text" size="32">{{ icons.menu }}</v-icon>
            </v-btn>
          </v-layout>

          <v-navigation-drawer
            v-if="drawer"
            v-model="drawer"
            absolute
            temporary
            right
            color="#2a388f"
            class="header-navigation-side-bar"
          >
            <div class="header-navigation-phone">
              <svg
                viewBox="0 0 20 20"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                class="icon-svg mr-2"
                style="width: 28px"
              >
                <path
                  d="M17.228 8.267h-.05V7.054a7.054 7.054 0 00-14.108 0v1.213h-.297c-1.09 0-1.931.966-1.931 2.08v3.094a1.956 1.956 0 001.93 2.004h1.832a.47.47 0 00.446-.52V8.862c0-.297-.173-.594-.446-.594H4.06V7.054a6.064 6.064 0 0112.129 0v1.213h-.545c-.272 0-.446.297-.446.594v6.065a.47.47 0 00.446.52h.57l-.05.074a3.911 3.911 0 01-3.144 1.56 2.45 2.45 0 00-4.851.47A2.475 2.475 0 0010.644 20a2.55 2.55 0 001.782-.767c.317-.325.525-.74.594-1.189a4.9 4.9 0 003.936-1.955l.47-.693c1.064-.074 1.733-.743 1.733-1.708v-3.094c0-1.064-.792-2.327-1.93-2.327zM4.06 14.455H2.773a.965.965 0 01-.941-1.014v-3.095c0-.569.396-1.089.94-1.089H4.06v5.198zm7.648 4.085a1.46 1.46 0 01-1.064.47 1.51 1.51 0 01-1.485-1.46 1.46 1.46 0 112.92-.002v.002c.021.367-.114.726-.37.99zm6.46-4.852c0 .668-.643.767-.94.767h-1.04V9.257h1.04c.545 0 .94.768.94 1.337v3.094z"
                  fill="url(#paint0_linear)"
                ></path>
                <defs>
                  <linearGradient
                    id="paint0_linear"
                    x1="17.472"
                    y1="4.756"
                    x2=".477"
                    y2="37.766"
                    gradientUnits="userSpaceOnUse"
                  >
                    <stop stop-color="#FFF337"></stop>
                    <stop offset=".248" stop-color="#FBC743"></stop>
                    <stop offset=".494" stop-color="#F3A346"></stop>
                    <stop offset=".709" stop-color="#EE8A46"></stop>
                    <stop offset=".885" stop-color="#EC7B46"></stop>
                    <stop offset="1" stop-color="#EB7646"></stop>
                  </linearGradient>
                </defs>
              </svg>
              <span class="header-navigation-phone-number">028 7102 6595</span>
            </div>
            <div class="header-navigation-content">
              <div
                v-for="(item, index) in navSideBarItems"
                :key="index"
                class="header-navigation-content-container"
              >
                <v-icon size="28" class="header-navigation-content-icon">
                  {{ item.icon }}
                </v-icon>
                <span class="header-navigation-content-text">{{
                  item.text
                }}</span>
              </div>
            </div>

            <div class="header-navigation-work">
              <div>
                <v-icon size="40" class="header-navigation-work-icon">
                  {{ icons.calendar }}
                </v-icon>
              </div>
              <div class="header-navigation-timework">
                <h3>Giờ làm việc</h3>
                <p>
                  Từ thứ 2 đến chủ nhật
                  <br />
                  Từ 7h30 đến 17h00
                  <br />
                  (không nghỉ trưa)
                </p>
              </div>
            </div>

            <div></div>
          </v-navigation-drawer>
        </div>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
import {
  mdiCalendarMonthOutline,
  mdiHomeVariant,
  mdiShieldCheck,
  mdiAccountSearch,
  mdiListBox,
  mdiPhone,
  mdiNoteText,
  mdiMenu,
} from "@mdi/js";

export default {
  name: "my-component",
  components: {},
  data() {
    return {
      drawer: null,
      items: [
        { title: "Home", icon: "mdi-view-dashboard" },
        { title: "About", icon: "mdi-forum" },
      ],
      icons: {
        calendar: mdiCalendarMonthOutline,
        mdiPhone: mdiPhone,
        menu: mdiMenu,
      },
      navItems: [
        {
          text: "TRANG CHỦ VNVC",
          link: "/",
          icon: mdiHomeVariant,
        },
        {
          text: "Danh mục Vắc xin",
          link: "/",
          icon: mdiShieldCheck,
        },
        {
          text: "Tra cứu",
          link: "/",
          icon: mdiAccountSearch,
        },
        {
          text: "FAQ",
          link: "/",
          icon: mdiListBox,
        },

        // {
        //   text: "HOTLINE: 028 7102 6595",
        //   link: "/",
        //   icon: mdiPhone,
        // },
      ],

      navSideBarItems: [
        {
          text: "TRANG CHỦ VNVC",
          link: "/",
          icon: mdiHomeVariant,
        },
        {
          text: "Danh mục Vắc xin",
          link: "/",
          icon: mdiShieldCheck,
        },
        {
          text: "Tra cứu",
          link: "/",
          icon: mdiAccountSearch,
        },
        {
          text: "Mua thẻ quà tặng",
          link: "/",
          icon: mdiNoteText,
        },
        {
          text: "Đăng ký thành viên",
          link: "/",
          icon: mdiNoteText,
        },
      ],
    };
  },
};
</script>


<style scoped>
.header {
  background-color: #2a388f;
}
.header-container {
  height: 90px;
  justify-content: center;
}
.header-logo {
  justify-content: center;
  align-items: center;
}

.header-link {
  padding: 20px;
}

.header-boderline {
  width: 1px;
  background: rgba(255, 255, 255, 0.3);
}

.header-working-text {
  font-size: 14px;
}

.header-working {
  color: rgb(227, 240, 254);
  padding: 0 12px;
}
.header-working-item {
  min-width: 250px;
}

.header-working .span-text {
  color: rgb(227, 240, 254);
  font-size: 16px;
}

.header-working-icon {
  color: #81bbfa;
}

.navbar {
  list-style: none;
  display: flex;
  height: 100%;
  align-items: center;
  padding: 0px 12px;
  justify-content: space-around;
}
.navbar-item {
  padding: 8px;
}
.navbar-link {
  display: flex;
  align-items: center;
}

.navbar-text {
  color: white;
  font-weight: 500;
  margin: 0;
  font-size: 16px;
  text-transform: uppercase;
  padding-left: 8px;
}

.navbar-phone {
  border-left: 1px solid rgba(255, 255, 255, 0.3);
  padding: 0 12px;
}
.header-navigation-bar {
  display: none;
}

.header-navigation-side-bar {
  color: white;
  padding: 20px 0;
  text-align: left;
}

.header-navigation-phone {
  padding: 20px;
  display: flex;
  align-items: center;
}

.header-navigation-icon {
  color: #fdd93e;
  margin-right: 6px;
}

.header-navigation-phone-number {
  font-size: 18px;
}

.header-navigation-content {
  padding: 24px 0;
}
.header-navigation-content-container {
  padding: 12px 0 12px 20px;

  border-bottom: 1px solid rgba(255, 255, 255, 0.3);
}
.header-navigation-content-icon {
  color: #81bbfa;

  margin-right: 8px;
}
.header-navigation-content-text {
  font-size: 12px;
  text-transform: uppercase;
}

.header-navigation-work {
  text-align: center;
  padding: 24px 0;
}

.header-navigation-work-icon {
  color: #fdd93e;
}

.header-navigation-timework h3 {
  padding-bottom: 14px;
  font-weight: 500;
}

.header-navigation-timework p {
  font-size: 12px;
}

.header-navigation-bar-phone{
  display: flex;
  align-items: center;
}
.header-navigation-bar-phonenumber{
  color: white;
}

@media screen and (max-width: 1430px) {
  .navbar-phone {
    display: none;
  }
  .header-nav {
    justify-content: space-around;
  }
  .navbar {
    justify-content: flex-end;
    padding-right: 24px;
  }
}

@media screen and (max-width: 1100px) {
  .navbar-text {
    font-size: 14px;
    padding-left: 6px;
  }

  .header-working-text {
    font-size: 12px;
  }
}

@media screen and (max-width: 1020px) {
  .header-working {
    display: none;
  }
  .header-nav-container {
    justify-content: flex-end;
  }
  ul.navbar {
  }
}

@media screen and (max-width: 780px) {
  .header-navigation-bar {
    display: block;
  }
  .header-navigation-bar {
    text-align: right;
  }
  .header-nav-container {
    display: none;
  }
}

@media screen and (max-width: 780px){
  .header-navigation-bar-phonenumber{
    font-size: 14px;
  }
}
</style>
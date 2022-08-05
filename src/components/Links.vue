<template>
  <div class="flex-row">
    <p @click="directToTwitch" class="text-3xl font-medium p-4 cursor-pointer">
      @Auzzydq
    </p>
    <!--Src image here -->
    <p class="font-light p-4">
      Hey guys! Here you can find links to my other platforms.
    </p>
    <div class="flex flex-row justify-center items-center">
      <aside class="w-64" aria-label="Sidebar">
        <div class="px-3 py-4 overflow-y-auto rounde">
          <ul class="space-y-2">
            <li>
              <a
                href="https://instagram.com/auzzydq?igshid=YmMyMTA2M2Y="
                class="links-tag"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  x="0px"
                  y="0px"
                  width="30"
                  height="24"
                  viewBox="0 0 24 24"
                  style="fill: #2405d9"
                >
                  <path
                    d="M 8 3 C 5.243 3 3 5.243 3 8 L 3 16 C 3 18.757 5.243 21 8 21 L 16 21 C 18.757 21 21 18.757 21 16 L 21 8 C 21 5.243 18.757 3 16 3 L 8 3 z M 8 5 L 16 5 C 17.654 5 19 6.346 19 8 L 19 16 C 19 17.654 17.654 19 16 19 L 8 19 C 6.346 19 5 17.654 5 16 L 5 8 C 5 6.346 6.346 5 8 5 z M 17 6 A 1 1 0 0 0 16 7 A 1 1 0 0 0 17 8 A 1 1 0 0 0 18 7 A 1 1 0 0 0 17 6 z M 12 7 C 9.243 7 7 9.243 7 12 C 7 14.757 9.243 17 12 17 C 14.757 17 17 14.757 17 12 C 17 9.243 14.757 7 12 7 z M 12 9 C 13.654 9 15 10.346 15 12 C 15 13.654 13.654 15 12 15 C 10.346 15 9 13.654 9 12 C 9 10.346 10.346 9 12 9 z"
                  ></path>
                </svg>
                <span class="flex-1 ml-3 whitespace-nowrap">Instagram</span>
              </a>
            </li>
            <li>
              <a
                href="https://www.tiktok.com/@auzzydq?_t=8UWou4HuH4Y&_r=1"
                class="links-tag"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  x="0px"
                  y="0px"
                  width="30"
                  height="30"
                  viewBox="0 0 30 30"
                  style="fill: #000000"
                >
                  <path
                    d="M24,4H6C4.895,4,4,4.895,4,6v18c0,1.105,0.895,2,2,2h18c1.105,0,2-0.895,2-2V6C26,4.895,25.104,4,24,4z M22.689,13.474 c-0.13,0.012-0.261,0.02-0.393,0.02c-1.495,0-2.809-0.768-3.574-1.931c0,3.049,0,6.519,0,6.577c0,2.685-2.177,4.861-4.861,4.861 C11.177,23,9,20.823,9,18.139c0-2.685,2.177-4.861,4.861-4.861c0.102,0,0.201,0.009,0.3,0.015v2.396c-0.1-0.012-0.197-0.03-0.3-0.03 c-1.37,0-2.481,1.111-2.481,2.481s1.11,2.481,2.481,2.481c1.371,0,2.581-1.08,2.581-2.45c0-0.055,0.024-11.17,0.024-11.17h2.289 c0.215,2.047,1.868,3.663,3.934,3.811V13.474z"
                  ></path>
                </svg>
                <span class="flex-1 ml-3 whitespace-nowrap">TikTok</span>
              </a>
            </li>
            <li>
              <a href="https://www.twitch.tv/auzzydq" class="links-tag">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  x="0px"
                  y="0px"
                  width="30"
                  height="30"
                  viewBox="0 0 30 30"
                  style="fill: #6a0dad"
                >
                  <path
                    d="M 6 4 L 4 8 L 4 24 L 9 24 L 9 27 L 13 27 L 16 24 L 20 24 L 26 18 L 26 4 L 6 4 z M 8 6 L 24 6 L 24 17 L 21 20 L 15 20 L 12 23 L 12 20 L 8 20 L 8 6 z M 13 9 L 13 16 L 15 16 L 15 9 L 13 9 z M 17 9 L 17 16 L 19 16 L 19 9 L 17 9 z"
                  ></path>
                </svg>
                <span class="flex-1 ml-3 whitespace-nowrap">Twitch</span>
              </a>
            </li>
            <li>
              <a href="https://twitter.com/Rap_Profit" class="links-tag">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  style="fill: #1da1f2"
                >
                  <path
                    d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"
                  />
                </svg>
                <span class="flex-1 ml-3 whitespace-nowrap">Twitter</span>
              </a>
            </li>
            <li>
              <a href="https://soundcloud.com/syn-lofi" class="links-tag">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  x="0px"
                  y="0px"
                  width="30"
                  height="24"
                  viewBox="0 0 48 48"
                  style="fill: #000000"
                >
                  <linearGradient
                    id="Ke5cRwe9ua_Q0F8Xn-Y0ua_fL0lnkfCeZWT_gr1"
                    x1="24.083"
                    x2="24.083"
                    y1="8.738"
                    y2="34.67"
                    gradientUnits="userSpaceOnUse"
                  >
                    <stop offset="0" stop-color="#ffac00"></stop>
                    <stop offset=".966" stop-color="#fe651e"></stop>
                  </linearGradient>
                  <path
                    fill="url(#Ke5cRwe9ua_Q0F8Xn-Y0ua_fL0lnkfCeZWT_gr1)"
                    d="M10,33.018c0.596,0,1.265,0,2,0V19.041c-1.11,1.001-1.699,2.212-2,3.121V33.018z M21,18.105	c-0.675-0.316-1.752-0.715-3-0.837v15.749c0.976,0,1.98,0,3,0V18.105z M14,33.018c0.943,0,1.95,0,3,0V17.24	c-1.173,0.03-2.171,0.23-3,0.558V33.018z M4,23.953c-1.178,0.896-2,2.35-2,4.039c0,1.586,0.795,2.987,2,3.905V23.953z M40.995,22.016c-1.444,0-2.283,0.521-2.283,0.521s-0.839-8.488-9.271-8.488c-4.906,0-6.83,2.704-7.441,3.897v15.071	c8.825,0,18.297,0,18.297,0s5.869-0.094,5.869-5.453C46.166,23.439,42.439,22.016,40.995,22.016z M8,23.1	c-0.395-0.051-0.842-0.088-1.341-0.088c-0.223,0-0.441,0.037-0.659,0.073v9.767c0.423,0.104,0.861,0.166,1.311,0.166	c0.151,0,0.393,0,0.689,0V23.1z"
                  ></path>
                </svg>
                <span class="flex-1 ml-3 whitespace-nowrap">Soundcloud</span>
              </a>
            </li>
            <li v-show="false">
              <a href="#" class="links-tag">
                <svg
                  width="24"
                  height="24"
                  xmlns="http://www.w3.org/2000/svg"
                  style="fill: #1db954"
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                >
                  <path
                    d="M19.098 10.638c-3.868-2.297-10.248-2.508-13.941-1.387-.593.18-1.22-.155-1.399-.748-.18-.593.154-1.22.748-1.4 4.239-1.287 11.285-1.038 15.738 1.605.533.317.708 1.005.392 1.538-.316.533-1.005.709-1.538.392zm-.126 3.403c-.272.44-.847.578-1.287.308-3.225-1.982-8.142-2.557-11.958-1.399-.494.15-1.017-.129-1.167-.623-.149-.495.13-1.016.624-1.167 4.358-1.322 9.776-.682 13.48 1.595.44.27.578.847.308 1.286zm-1.469 3.267c-.215.354-.676.465-1.028.249-2.818-1.722-6.365-2.111-10.542-1.157-.402.092-.803-.16-.895-.562-.092-.403.159-.804.562-.896 4.571-1.045 8.492-.595 11.655 1.338.353.215.464.676.248 1.028zm-5.503-17.308c-6.627 0-12 5.373-12 12 0 6.628 5.373 12 12 12 6.628 0 12-5.372 12-12 0-6.627-5.372-12-12-12z"
                  /></svg
                ><span class="flex-1 ml-3 whitespace-nowrap">Spotify</span>
              </a>
            </li>
            <li>
              <a href="https://github.com/Life75" class="links-tag">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
                  /></svg
                ><span class="flex-1 ml-3 whitespace-nowrap">Github</span>
              </a>
            </li>
          </ul>
        </div>
      </aside>
    </div>
  </div>
</template>

<script lang="ts" setup>
function directToTwitch() {
  window.location.href = "https://www.twitch.tv/auzzydq";
}
</script>

<style>
p {
  @apply text-slate-800;
}

a {
  @apply text-slate-800;
}

.links-tag {
  @apply flex items-center p-2 text-base font-normal text-gray-900 rounded-lg border shadow-lg decoration-inherit;
}
</style>

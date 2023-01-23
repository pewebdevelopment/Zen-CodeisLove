<template>
  <body class="bg-gray-100 antialiased">
    <main class="main-container">
      <div class="grid gap-5 lg:grid-cols-3">
        <div class="space-y-5">
          <!-- Start Left Side -->

          <div class="shadow rounded-xl overflow-hidden">
            <!-- Start User Block -->
            <div
              class="h-32 bg-cover"
              style="background-image: url('assets/img/cover.jpg')"
            ></div>
            <div class="pt-14 p-7 bg-white relative">
              <span class="status-badge bg-gray-400">Busy</span>
              <a href="/"
                ><img
                  src="assets/img/avatar.jpg"
                  alt="Avatar"
                  class="user-photo"
              /></a>
              <div class="text-lg font-semibold mb-1.5">Cristopher Abbott</div>
              <div class="text-sm text-gray-400 mb-7">Senior Developer</div>
              <div class="flex group">
                <button class="download-btn">Download CV</button>
                <button class="download-btn-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-6 w-6"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="1.8"
                      d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"
                    />
                  </svg>
                </button>
              </div>
            </div>
          </div>
          <!-- End User Block -->

          <div class="p-7 block-section">
            <!-- Start Info Block -->
            <h2 class="block-title">Information</h2>
            <div class="space-y-4">
              <div class="flex justify-between">
                <div class="text-gray-400">Location</div>
                <div class="font-medium text-right text-gray-600">London</div>
              </div>
              <div class="flex justify-between">
                <div class="text-gray-400">Experience</div>
                <div class="font-medium text-right text-gray-600">3+ years</div>
              </div>
              <div class="flex justify-between">
                <div class="text-gray-400">Availability</div>
                <div class="font-medium text-right text-gray-600">1 week</div>
              </div>
              <div class="flex justify-between">
                <div class="text-gray-400">Relocation</div>
                <div class="font-medium text-right text-gray-600">No</div>
              </div>
            </div>
          </div>
          <!-- End Info Block -->

          <div class="p-7 block-section flow-root">
            <!-- Start Skills Block -->
            <h2 class="block-title">Skills</h2>
            <div class="-m-2 flex flex-wrap">
              <span class="skill-tag">JavaScript</span>
              <span class="skill-tag">React</span>
              <span class="skill-tag">Vue</span>
              <span class="skill-tag">SQL</span>
              <span class="skill-tag">HTML/CSS</span>
              <span class="skill-tag">Java</span>
            </div>
          </div>
          <!-- End Skills Block -->
        </div>
        <!-- End Left Side -->

        <div class="space-y-5 lg:col-span-2">
          <!-- Start Right Side -->

          <div class="p-7 pb-0 block-section">
            <!-- Start About Me Block -->
            <h2 class="block-title">About me</h2>
            <p class="text-gray-600 mb-5">
              Libero quas veritatis nulla distinctio fuga nihil temporibus et.
              Quia dicta sapiente qui porro molestiae nobis incidunt voluptatem.
              Et voluptas sunt nihil. At perferendis voluptatem dolores nulla.
              Adipisci dolore non. Praesentium ipsa magnam ut quia explicabo
              voluptates.
            </p>

            <div class="flex flex-col space-y-4">
              <a href="#0" class="mail-link social-link-hover">
                <i class="bx bx-at text-xl"></i>
                <span>crisabbott@email.com</span>
              </a>

              <ul class="flex space-x-5">
                <li>
                  <a href="#0" class="social-link-hover">
                    <i class="bx bxl-facebook-circle text-2xl"></i>
                  </a>
                </li>
                <li>
                  <a href="#0" class="social-link-hover">
                    <i class="bx bxl-twitter text-2xl"></i>
                  </a>
                </li>
                <li>
                  <a href="#0" class="social-link-hover">
                    <i class="bx bxl-github text-2xl"></i>
                  </a>
                </li>
              </ul>
            </div>

            <div class="border-t border-gray-200 my-5"></div>

            <ul class="flex space-x-8 font-medium">
              <li>
                <a href="/public/index.html" class="menu-link menu-link-hover"
                  >Resume</a
                >
              </li>
              <li>
                <a
                  href="/public/products.html"
                  class="menu-link menu-link-hover"
                  >Products</a
                >
              </li>
              <li>
                <a
                  href="/public/blog.html"
                  class="menu-link-active menu-link-hover"
                  >Blog</a
                >
              </li>
            </ul>
          </div>
          <!-- End About Me Block -->

          <article class="single-article-section">
            <!-- Start Articles Block -->
            <div class="single-article-img rounded-t-xl">
              <img
                src="https://images.unsplash.com/photo-1589149098258-3e9102cd63d3?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80"
                alt=""
              />
            </div>
            <div class="space-y-7 mb-5 p-7 pb-0">
              <div class="space-y-2">
                <h2 class="text-lg font-semibold">
                  Qui quasi aut iure provident occaecati dignissimos et illo.
                </h2>
                <p>
                  <time
                    datetime="2021-05-09 19:00"
                    class="text-sm text-gray-400"
                    >May 09, 2021</time
                  >
                </p>
              </div>
              <p class="text-gray-600">
                Numquam cumque ut excepturi. Nihil ea officiis. Voluptate cum
                velit quibusdam sed ducimus qui. Quis ut non hic facilis eum ut
                voluptatibus eveniet. Repellat accusantium non maxime sequi
                dignissimos magnam et quos. Consequatur vel numquam.
                <br /><br />
                Numquam cumque ut excepturi. Nihil ea officiis. Voluptate cum
                velit quibusdam sed ducimus qui. Quis ut non hic facilis eum ut
                voluptatibus eveniet. Repellat accusantium non maxime sequi
                dignissimos magnam et quos. Consequatur vel numquam. Numquam
                cumque ut excepturi. Nihil ea officiis. Voluptate cum velit
                quibusdam sed ducimus qui. Quis ut non hic facilis eum ut
                voluptatibus eveniet. Repellat accusantium non maxime sequi
                dignissimos magnam et quos. Consequatur vel numquam.
                <br /><br />
                Numquam cumque ut excepturi. Nihil ea officiis. Voluptate cum
                velit quibusdam sed ducimus qui. Quis ut non hic facilis eum ut
                voluptatibus eveniet. Repellat accusantium non maxime sequi
                dignissimos magnam et quos. Consequatur vel numquam.
              </p>
            </div>
          </article>
          <!-- Start Articles Block -->
        </div>
        <!-- End Right Side -->
      </div>
    </main>
  </body></template
>

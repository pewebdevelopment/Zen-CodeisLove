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

          <div class="p-7 bg-white shadow rounded-xl flow-root">
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
                  class="menu-link-active menu-link-hover"
                  >Products</a
                >
              </li>
              <li>
                <a href="/public/blog.html" class="menu-link menu-link-hover"
                  >Blog</a
                >
              </li>
            </ul>
          </div>
          <!-- End About Me Block -->

          <div class="p-7 block-section">
            <!-- Start Products Block -->
            <h2 class="block-title">Products</h2>
            <div class="mb-5 item-section">
              <div class="company-logo bg-blue-500">
                <span class="text-2xl">S</span>
              </div>

              <div class="w-full space-y-5">
                <div class="item-header">
                  <div class="space-y-1.5">
                    <div class="font-medium">Sapiente</div>
                    <div class="flex space-x-5">
                      <div class="item-header-info">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          class="h-4 w-4"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                          />
                        </svg>
                        <span>Tools</span>
                      </div>
                      <div class="item-header-info">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          class="h-4 w-4"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                          />
                        </svg>
                        <span>Founder</span>
                      </div>
                    </div>
                  </div>
                </div>
                <p class="text-gray-600">
                  Aut omnis voluptatem sit sequi. Voluptatem temporibus repellat
                  voluptatem voluptatibus enim voluptas necessitatibus. Aut
                  quasi sunt dolor. Commodi dolores saepe asperiores beatae
                  voluptate corporis est ea voluptatem. Enim quo sed et sint
                  aspernatur distinctio qui quam.
                </p>
                <button
                  class="flex items-center space-x-3 px-3.5 py-1.5 rounded-lg group border border-purple-500 bg-white text-purple-500 text-sm font-medium transition duration-200 hover:border-purple-600 hover:text-white hover:bg-purple-600"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"
                    />
                  </svg>
                  <span>https://sapiente.space</span>
                </button>
                <div class="border-b border-gray-200"></div>
              </div>
            </div>

            <div class="mb-5 item-section">
              <div class="company-logo bg-green-700">
                <span class="text-2xl">D</span>
              </div>

              <div class="w-full space-y-5">
                <div class="item-header">
                  <div class="space-y-1.5">
                    <div class="font-medium">Deserunt</div>
                    <div class="flex space-x-5">
                      <div class="item-header-info">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          class="h-4 w-4"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                          />
                        </svg>
                        <span>E-commerce</span>
                      </div>
                      <div class="item-header-info">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          class="h-4 w-4"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                          />
                        </svg>
                        <span>Co-founder</span>
                      </div>
                    </div>
                  </div>
                </div>
                <p class="text-gray-600">
                  Aut omnis voluptatem sit sequi. Voluptatem temporibus repellat
                  voluptatem voluptatibus enim voluptas necessitatibus. Aut
                  quasi sunt dolor. Commodi dolores saepe asperiores beatae
                  voluptate corporis est ea voluptatem. Enim quo sed et sint
                  aspernatur distinctio qui quam.
                </p>
                <button
                  class="flex items-center space-x-3 px-3.5 py-1.5 rounded-lg group border border-purple-500 bg-white text-purple-500 text-sm font-medium transition duration-200 hover:border-purple-600 hover:text-white hover:bg-purple-600"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-4 w-4"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"
                    />
                  </svg>
                  <span>https://deserunt.io</span>
                </button>
              </div>
            </div>
          </div>
          <!-- Start Products Block -->
        </div>
        <!-- End Right Side -->
      </div>
    </main>
  </body>
</template>

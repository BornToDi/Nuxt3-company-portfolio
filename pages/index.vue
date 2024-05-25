<template>
  <div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-32">
    <img
      src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&crop=focalpoint&fp-y=.8&w=2830&h=1500&q=80&blend=111827&sat=-100&exp=15&blend-mode=multiply"
      alt=""
      class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center"
    />
    <div
      class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl"
      aria-hidden="true"
    >
      <div
        class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20"
        style="
          clip-path: polygon(
            74.1% 44.1%,
            100% 61.6%,
            97.5% 26.9%,
            85.5% 0.1%,
            80.7% 2%,
            72.5% 32.5%,
            60.2% 62.4%,
            52.4% 68.1%,
            47.5% 58.3%,
            45.2% 34.5%,
            27.5% 76.7%,
            0.1% 64.9%,
            17.9% 100%,
            27.6% 76.8%,
            76.1% 97.7%,
            74.1% 44.1%
          );
        "
      />
    </div>
    <div
      class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu"
      aria-hidden="true"
    >
      <div
        class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20"
        style="
          clip-path: polygon(
            74.1% 44.1%,
            100% 61.6%,
            97.5% 26.9%,
            85.5% 0.1%,
            80.7% 2%,
            72.5% 32.5%,
            60.2% 62.4%,
            52.4% 68.1%,
            47.5% 58.3%,
            45.2% 34.5%,
            27.5% 76.7%,
            0.1% 64.9%,
            17.9% 100%,
            27.6% 76.8%,
            76.1% 97.7%,
            74.1% 44.1%
          );
        "
      />
    </div>
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl lg:mx-0">
        <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">
          Work with us
        </h2>
        <p class="mt-6 text-lg leading-8 text-gray-300">
          Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem
          cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat
          aliqua.
        </p>
      </div>
      <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
        <div
          class="grid grid-cols-1 gap-x-8 gap-y-6 text-base font-semibold leading-7 text-white sm:grid-cols-2 md:flex lg:gap-x-10"
        >
          <a v-for="link in links" :key="link.name" :href="link.href"
            >{{ link.name }} <span aria-hidden="true">&rarr;</span></a
          >
        </div>
        <dl
          class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4"
        >
          <div
            v-for="stat in stats"
            :key="stat.name"
            class="flex flex-col-reverse"
          >
            <dt class="text-base leading-7 text-gray-300">{{ stat.name }}</dt>
            <dd class="text-2xl font-bold leading-9 tracking-tight text-white">
              {{ stat.value }}
            </dd>
          </div>
        </dl>
      </div>
    </div>
    <!--partners-->

    <div class="py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <h2 class="text-center text-lg font-semibold leading-8 text-white">
          Trusted by the world’s most innovative teams
        </h2>
        <div
          class="mx-auto mt-10 grid max-w-lg grid-cols-4 items-center gap-x-8 gap-y-10 sm:max-w-xl sm:grid-cols-6 sm:gap-x-10 lg:mx-0 lg:max-w-none lg:grid-cols-5"
        >
          <img
            class="text-white col-span-2 max-h-12 w-full object-contain lg:col-span-1"
            src="https://tailwindui.com/img/logos/158x48/transistor-logo-gray-900.svg"
            alt="Transistor"
            width="158"
            height="48"
            style="filter: invert(100%)"
          />
          <img
            class="col-span-2 max-h-12 w-full object-contain lg:col-span-1"
            src="https://tailwindui.com/img/logos/158x48/reform-logo-gray-900.svg"
            alt="Reform"
            width="158"
            height="48"
            style="filter: invert(100%)"
          />
          <img
            class="col-span-2 max-h-12 w-full object-contain lg:col-span-1"
            src="https://tailwindui.com/img/logos/158x48/tuple-logo-gray-900.svg"
            alt="Tuple"
            width="158"
            height="48"
            style="filter: invert(100%)"
          />
          <img
            class="col-span-2 max-h-12 w-full object-contain sm:col-start-2 lg:col-span-1"
            src="https://tailwindui.com/img/logos/158x48/savvycal-logo-gray-900.svg"
            alt="SavvyCal"
            width="158"
            height="48"
            style="filter: invert(100%)"
          />
          <img
            class="col-span-2 col-start-2 max-h-12 w-full object-contain sm:col-start-auto lg:col-span-1"
            src="https://tailwindui.com/img/logos/158x48/statamic-logo-gray-900.svg"
            alt="Statamic"
            width="158"
            height="48"
            style="filter: invert(100%)"
          />
        </div>
      </div>
    </div>
  </div>

  <!--about us n mission-->
  <div class="bg-white">
    <main class="isolate">
      <!-- Hero section -->
      <div class="py-16 bg-white">
    <div class="container mx-auto px-6 text-gray-600 md:px-12 xl:px-6">
      <div class="space-y-6 md:space-y-0 md:flex md:gap-6  lg:gap-12">
        <div class="md:w-5/12 lg:w-5/12">
          <img src="https://tailus.io/sources/blocks/left-image/preview/images/startup.png" alt="image" loading="lazy">
        </div>
        <div class="md:w-7/12 lg:w-6/12 pt-5">
          <span class="text-gray-500 border-b-2 border-indigo-600 uppercase">About us</span>
          <h2 class="my-4 font-bold text-3xl sm:text-4xl">About <span class="text-indigo-600">Our Company</span></h2>
          <div class="text-justify">
            <p>Redcat UK, established in February 2024, is a prominent supplier of all-inclusive IT services. We are committed to providing cutting-edge, highly valuable solutions that are suited to our clients' various needs. Our goal is to enable people and companies alike with personalized technology solutions that promote productivity and expansion.</p>
            <p>Custom software development, network engineering, system administration, database management, data science, UI/UX design, and technical support are just a few of the many services we provide. Every project benefits from the depth of knowledge, experience, and creativity that our team of talented professionals brings to the table, guaranteeing outstanding results and service.</p>
            <div v-if="showMore">
              <p>Our client-focused approach at Redcat UK guarantees that we fully comprehend your business to provide precisely aligned solutions. We put your success first and keep on the cutting edge of technology by innovating constantly. We offer ecologically friendly and efficient solutions since we are dedicated to sustainable practices.</p>
              <p>Selecting Redcat UK means working with a group of people who respect excellence, dependability, and trust. We genuinely care about using technology to change the world, and we cultivate enduring partnerships with our clients. Get in touch with us right now to find out how Redcat UK can help you with your tech requirements and grow your company.</p>
              <p>We appreciate your interest in Redcat UK as a potential technology partner. We're excited to work with you and support your success together.</p>
            </div>
          </div>
          <button @click="toggleContent" class="text-indigo-600 font-bold mt-4">
            {{ showMore ? 'Read less' : 'Read more' }}
          </button>
        </div>
      </div>
    </div>
  </div>
      <!-- Timeline section -->
      <div class="mx-auto md:w-[1400px] px-6 lg:px-8 ">
        <div
          class="mx-auto grid max-w-2xl grid-cols-1 gap-8 overflow-hidden lg:mx-0 lg:max-w-none lg:grid-cols-4"
        >
          <div>
            <time
              datetime="2021-08"
              class="flex items-center text-sm font-semibold leading-6 text-indigo-600"
            >
              <svg
                viewBox="0 0 4 4"
                class="mr-4 h-1 w-1 flex-none"
                aria-hidden="true"
              >
                <circle cx="2" cy="2" r="2" fill="currentColor"></circle>
              </svg>
              Feb 2024
              <div
                class="absolute -ml-2 h-px w-screen -translate-x-full bg-gray-900/10 sm:-ml-4 lg:static lg:-mr-6 lg:ml-8 lg:w-auto lg:flex-auto lg:translate-x-0"
                aria-hidden="true"
              ></div>
            </time>
            <p
              class="mt-6 text-lg font-semibold leading-8 tracking-tight text-gray-900"
            >
              Founded company
            </p>
            <p class="mt-1 text-base leading-7 text-gray-600">
              Redcat, established on February 24th, is a leading provider of comprehensive IT services.
            </p>
          </div>
          <div>
            <time
              datetime="2021-12"
              class="flex items-center text-sm font-semibold leading-6 text-indigo-600"
            >
              <svg
                viewBox="0 0 4 4"
                class="mr-4 h-1 w-1 flex-none"
                aria-hidden="true"
              >
                <circle cx="2" cy="2" r="2" fill="currentColor"></circle>
              </svg>
              Dec 2021
              <div
                class="absolute -ml-2 h-px w-screen -translate-x-full bg-gray-900/10 sm:-ml-4 lg:static lg:-mr-6 lg:ml-8 lg:w-auto lg:flex-auto lg:translate-x-0"
                aria-hidden="true"
              ></div>
            </time>
            <p
              class="mt-6 text-lg font-semibold leading-8 tracking-tight text-gray-900"
            >
              Secured $65m in funding
            </p>
            <p class="mt-1 text-base leading-7 text-gray-600">
              Provident quia ut esse. Vero vel eos repudiandae aspernatur.
              Cumque minima impedit sapiente a architecto nihil.
            </p>
          </div>
          <div>
            <time
              datetime="2022-02"
              class="flex items-center text-sm font-semibold leading-6 text-indigo-600"
            >
              <svg
                viewBox="0 0 4 4"
                class="mr-4 h-1 w-1 flex-none"
                aria-hidden="true"
              >
                <circle cx="2" cy="2" r="2" fill="currentColor"></circle>
              </svg>
              Feb 2022
              <div
                class="absolute -ml-2 h-px w-screen -translate-x-full bg-gray-900/10 sm:-ml-4 lg:static lg:-mr-6 lg:ml-8 lg:w-auto lg:flex-auto lg:translate-x-0"
                aria-hidden="true"
              ></div>
            </time>
            <p
              class="mt-6 text-lg font-semibold leading-8 tracking-tight text-gray-900"
            >
              Released beta
            </p>
            <p class="mt-1 text-base leading-7 text-gray-600">
              Sunt perspiciatis incidunt. Non necessitatibus aliquid.
              Consequatur ut officiis earum eum quia facilis. Hic deleniti
              dolorem quia et.
            </p>
          </div>
          <div>
            <time
              datetime="2022-12"
              class="flex items-center text-sm font-semibold leading-6 text-indigo-600"
            >
              <svg
                viewBox="0 0 4 4"
                class="mr-4 h-1 w-1 flex-none"
                aria-hidden="true"
              >
                <circle cx="2" cy="2" r="2" fill="currentColor"></circle>
              </svg>
              Dec 2022
              <div
                class="absolute -ml-2 h-px w-screen -translate-x-full bg-gray-900/10 sm:-ml-4 lg:static lg:-mr-6 lg:ml-8 lg:w-auto lg:flex-auto lg:translate-x-0"
                aria-hidden="true"
              ></div>
            </time>
            <p
              class="mt-6 text-lg font-semibold leading-8 tracking-tight text-gray-900"
            >
              Global launch of product
            </p>
            <p class="mt-1 text-base leading-7 text-gray-600">
              Ut ipsa sint distinctio quod itaque nam qui. Possimus aut unde id
              architecto voluptatem hic aut pariatur velit.
            </p>
          </div>
        </div>
      </div>

      <!-- Logo cloud -->
      <div class="mx-auto mt-32 max-w-7xl sm:mt-40 sm:px-6 lg:px-8">
        <div
          class="relative isolate overflow-hidden bg-gray-900 px-6 py-24 text-center shadow-2xl sm:rounded-3xl sm:px-16"
        >
          <h2
            class="mx-auto max-w-2xl text-3xl font-bold tracking-tight text-white sm:text-4xl"
          >
            Our customers love us
          </h2>
          <p class="mx-auto mt-6 max-w-xl text-lg leading-8 text-gray-300">
            Aliquip reprehenderit incididunt amet quis fugiat ut velit. Sit
            occaecat labore proident cillum in nisi adipisicing officia
            excepteur tempor deserunt.
          </p>
          <div
            class="mx-auto mt-20 grid max-w-lg grid-cols-4 items-center gap-x-8 gap-y-12 sm:max-w-xl sm:grid-cols-6 sm:gap-x-10 sm:gap-y-14 lg:max-w-4xl lg:grid-cols-5"
          >
            <img
              class="col-span-2 max-h-12 w-full object-contain lg:col-span-1"
              src="https://tailwindui.com/img/logos/158x48/transistor-logo-white.svg"
              alt="Transistor"
              width="158"
              height="48"
            />
            <img
              class="col-span-2 max-h-12 w-full object-contain lg:col-span-1"
              src="https://tailwindui.com/img/logos/158x48/reform-logo-white.svg"
              alt="Reform"
              width="158"
              height="48"
            />
            <img
              class="col-span-2 max-h-12 w-full object-contain lg:col-span-1"
              src="https://tailwindui.com/img/logos/158x48/tuple-logo-white.svg"
              alt="Tuple"
              width="158"
              height="48"
            />
            <img
              class="col-span-2 max-h-12 w-full object-contain sm:col-start-2 lg:col-span-1"
              src="https://tailwindui.com/img/logos/158x48/savvycal-logo-white.svg"
              alt="SavvyCal"
              width="158"
              height="48"
            />
            <img
              class="col-span-2 col-start-2 max-h-12 w-full object-contain sm:col-start-auto lg:col-span-1"
              src="https://tailwindui.com/img/logos/158x48/statamic-logo-white.svg"
              alt="Statamic"
              width="158"
              height="48"
            />
          </div>
          <div
            class="absolute -top-24 right-0 -z-10 transform-gpu blur-3xl"
            aria-hidden="true"
          >
            <div
              class="aspect-[1404/767] w-[87.75rem] bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-25"
              style="
                clip-path: polygon(
                  73.6% 51.7%,
                  91.7% 11.8%,
                  100% 46.4%,
                  97.4% 82.2%,
                  92.5% 84.9%,
                  75.7% 64%,
                  55.3% 47.5%,
                  46.5% 49.4%,
                  45% 62.9%,
                  50.3% 87.2%,
                  21.3% 64.1%,
                  0.1% 100%,
                  5.4% 51.1%,
                  21.4% 63.9%,
                  58.9% 0.2%,
                  73.6% 51.7%
                );
              "
            ></div>
          </div>
        </div>
      </div>

      <!-- Content section -->
      <div class="mt-32 overflow-hidden sm:mt-40">
        <div class="mx-auto max-w-7xl px-6 lg:flex lg:px-8">
          <div
            class="mx-auto grid max-w-2xl grid-cols-1 gap-x-12 gap-y-16 lg:mx-0 lg:min-w-full lg:max-w-none lg:flex-none lg:gap-y-8"
          >
            <div class="lg:col-end-1 lg:w-full lg:max-w-lg lg:pb-8">
              <h2
                class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl"
              >
                Our people
              </h2>
              <p class="mt-6 text-xl leading-8 text-gray-600">
                Quasi est quaerat. Sit molestiae et. Provident ad dolorem
                occaecati eos iste. Soluta rerum quidem minus ut molestiae velit
                error quod. Excepturi quidem expedita molestias quas.
              </p>
              <p class="mt-6 text-base leading-7 text-gray-600">
                Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui
                lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat
                fugiat. Quasi aperiam sit non sit neque reprehenderit.
              </p>
            </div>
            <div
              class="flex flex-wrap items-start justify-end gap-6 sm:gap-8 lg:contents"
            >
              <div
                class="w-0 flex-auto lg:ml-auto lg:w-auto lg:flex-none lg:self-end"
              >
                <img
                  src="https://images.unsplash.com/photo-1670272502246-768d249768ca?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1152&amp;q=80"
                  alt=""
                  class="aspect-[7/5] w-[37rem] max-w-none rounded-2xl bg-gray-50 object-cover"
                />
              </div>
              <div
                class="contents lg:col-span-2 lg:col-end-2 lg:ml-auto lg:flex lg:w-[37rem] lg:items-start lg:justify-end lg:gap-x-8"
              >
                <div
                  class="order-first flex w-64 flex-none justify-end self-end lg:w-auto"
                >
                  <img
                    src="https://images.unsplash.com/photo-1605656816944-971cd5c1407f?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=768&amp;h=604&amp;q=80"
                    alt=""
                    class="aspect-[4/3] w-[24rem] max-w-none flex-none rounded-2xl bg-gray-50 object-cover"
                  />
                </div>
                <div
                  class="flex w-96 flex-auto justify-end lg:w-auto lg:flex-none"
                >
                  <img
                    src="https://images.unsplash.com/photo-1568992687947-868a62a9f521?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1152&amp;h=842&amp;q=80"
                    alt=""
                    class="aspect-[7/5] w-[37rem] max-w-none flex-none rounded-2xl bg-gray-50 object-cover"
                  />
                </div>
                <div
                  class="hidden sm:block sm:w-0 sm:flex-auto lg:w-auto lg:flex-none"
                >
                  <img
                    src="https://images.unsplash.com/photo-1612872087720-bb876e2e67d1?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=768&amp;h=604&amp;q=80"
                    alt=""
                    class="aspect-[4/3] w-[24rem] max-w-none rounded-2xl bg-gray-50 object-cover"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Stats -->
      <div class="mx-auto mt-32 max-w-7xl px-6 sm:mt-40 lg:px-8">
        <div class="mx-auto max-w-2xl lg:mx-0">
          <h2
            class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl"
          >
            We approach the workplace as something that adds to our lives and
            adds value to world.
          </h2>
          <p class="mt-6 text-base leading-7 text-gray-600">
            Diam nunc lacus lacus aliquam turpis enim. Eget hac velit est
            euismod lacus. Est non placerat nam arcu. Cras purus nibh cursus sit
            eu in id. Integer vel nibh.
          </p>
        </div>
        <div
          class="mx-auto mt-16 flex max-w-2xl flex-col gap-8 lg:mx-0 lg:mt-20 lg:max-w-none lg:flex-row lg:items-end"
        >
          <div
            class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-gray-50 p-8 sm:w-3/4 sm:max-w-md sm:flex-row-reverse sm:items-end lg:w-72 lg:max-w-none lg:flex-none lg:flex-col lg:items-start"
          >
            <p
              class="flex-none text-3xl font-bold tracking-tight text-gray-900"
            >
              250k
            </p>
            <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
              <p class="text-lg font-semibold tracking-tight text-gray-900">
                Users on the platform
              </p>
              <p class="mt-2 text-base leading-7 text-gray-600">
                Vel labore deleniti veniam consequuntur sunt nobis.
              </p>
            </div>
          </div>
          <div
            class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-gray-900 p-8 sm:flex-row-reverse sm:items-end lg:w-full lg:max-w-sm lg:flex-auto lg:flex-col lg:items-start lg:gap-y-44"
          >
            <p class="flex-none text-3xl font-bold tracking-tight text-white">
              $8.9 billion
            </p>
            <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
              <p class="text-lg font-semibold tracking-tight text-white">
                We’re proud that our customers have made over $8 billion in
                total revenue.
              </p>
              <p class="mt-2 text-base leading-7 text-gray-400">
                Eu duis porta aliquam ornare. Elementum eget magna egestas.
              </p>
            </div>
          </div>
          <div
            class="flex flex-col-reverse justify-between gap-x-16 gap-y-8 rounded-2xl bg-indigo-600 p-8 sm:w-11/12 sm:max-w-xl sm:flex-row-reverse sm:items-end lg:w-full lg:max-w-none lg:flex-auto lg:flex-col lg:items-start lg:gap-y-28"
          >
            <p class="flex-none text-3xl font-bold tracking-tight text-white">
              401,093
            </p>
            <div class="sm:w-80 sm:shrink lg:w-auto lg:flex-none">
              <p class="text-lg font-semibold tracking-tight text-white">
                Transactions this year
              </p>
              <p class="mt-2 text-base leading-7 text-indigo-200">
                Eu duis porta aliquam ornare. Elementum eget magna egestas. Eu
                duis porta aliquam ornare.
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Content section -->
      <div class="mx-auto mt-32 max-w-7xl px-6 sm:mt-40 lg:px-8">
        <div
          class="mx-auto flex max-w-2xl flex-col items-end justify-between gap-16 lg:mx-0 lg:max-w-none lg:flex-row"
        >
          <div class="w-full lg:max-w-lg lg:flex-auto">
            <h2
              class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl"
            >
              We’re always looking for awesome people to join us
            </h2>
            <p class="mt-6 text-xl leading-8 text-gray-600">
              Diam nunc lacus lacus aliquam turpis enim. Eget hac velit est
              euismod lacus. Est non placerat nam arcu. Cras purus nibh cursus
              sit eu in id.
            </p>
            <img
              src="https://images.unsplash.com/photo-1606857521015-7f9fcf423740?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1344&amp;h=1104&amp;q=80"
              alt=""
              class="mt-16 aspect-[6/5] w-full rounded-2xl bg-gray-50 object-cover lg:aspect-auto lg:h-[34.5rem]"
            />
          </div>
          <div class="w-full lg:max-w-xl lg:flex-auto">
            <h3 class="sr-only">Job openings</h3>
            <ul class="-my-8 divide-y divide-gray-100">
              <li class="py-8">
                <dl class="relative flex flex-wrap gap-x-3">
                  <dt class="sr-only">Role</dt>
                  <dd
                    class="w-full flex-none text-lg font-semibold tracking-tight text-gray-900"
                  >
                    <a href="#">
                      Full-time designer
                      <span class="absolute inset-0" aria-hidden="true"></span>
                    </a>
                  </dd>
                  <dt class="sr-only">Description</dt>
                  <dd
                    class="mt-2 w-full flex-none text-base leading-7 text-gray-600"
                  >
                    Quos sunt ad dolore ullam qui. Enim et quisquam dicta
                    molestias. Corrupti quo voluptatum eligendi autem labore.
                  </dd>
                  <dt class="sr-only">Salary</dt>
                  <dd
                    class="mt-4 text-base font-semibold leading-7 text-gray-900"
                  >
                    $75,000 USD
                  </dd>
                  <dt class="sr-only">Location</dt>
                  <dd
                    class="mt-4 flex items-center gap-x-3 text-base leading-7 text-gray-500"
                  >
                    <svg
                      viewBox="0 0 2 2"
                      class="h-0.5 w-0.5 flex-none fill-gray-300"
                      aria-hidden="true"
                    >
                      <circle cx="1" cy="1" r="1"></circle>
                    </svg>
                    San Francisco, CA
                  </dd>
                </dl>
              </li>
              <li class="py-8">
                <dl class="relative flex flex-wrap gap-x-3">
                  <dt class="sr-only">Role</dt>
                  <dd
                    class="w-full flex-none text-lg font-semibold tracking-tight text-gray-900"
                  >
                    <a href="#">
                      Laravel developer
                      <span class="absolute inset-0" aria-hidden="true"></span>
                    </a>
                  </dd>
                  <dt class="sr-only">Description</dt>
                  <dd
                    class="mt-2 w-full flex-none text-base leading-7 text-gray-600"
                  >
                    Et veniam et officia dolorum rerum. Et voluptas consequatur
                    magni sapiente amet voluptates dolorum. Ut porro aut
                    eveniet.
                  </dd>
                  <dt class="sr-only">Salary</dt>
                  <dd
                    class="mt-4 text-base font-semibold leading-7 text-gray-900"
                  >
                    $125,000 USD
                  </dd>
                  <dt class="sr-only">Location</dt>
                  <dd
                    class="mt-4 flex items-center gap-x-3 text-base leading-7 text-gray-500"
                  >
                    <svg
                      viewBox="0 0 2 2"
                      class="h-0.5 w-0.5 flex-none fill-gray-300"
                      aria-hidden="true"
                    >
                      <circle cx="1" cy="1" r="1"></circle>
                    </svg>
                    San Francisco, CA
                  </dd>
                </dl>
              </li>
              <li class="py-8">
                <dl class="relative flex flex-wrap gap-x-3">
                  <dt class="sr-only">Role</dt>
                  <dd
                    class="w-full flex-none text-lg font-semibold tracking-tight text-gray-900"
                  >
                    <a href="#">
                      React Native developer
                      <span class="absolute inset-0" aria-hidden="true"></span>
                    </a>
                  </dd>
                  <dt class="sr-only">Description</dt>
                  <dd
                    class="mt-2 w-full flex-none text-base leading-7 text-gray-600"
                  >
                    Veniam ipsam nisi quas architecto eos non voluptatem in
                    nemo. Est occaecati nihil omnis delectus illum est.
                  </dd>
                  <dt class="sr-only">Salary</dt>
                  <dd
                    class="mt-4 text-base font-semibold leading-7 text-gray-900"
                  >
                    $105,000 USD
                  </dd>
                  <dt class="sr-only">Location</dt>
                  <dd
                    class="mt-4 flex items-center gap-x-3 text-base leading-7 text-gray-500"
                  >
                    <svg
                      viewBox="0 0 2 2"
                      class="h-0.5 w-0.5 flex-none fill-gray-300"
                      aria-hidden="true"
                    >
                      <circle cx="1" cy="1" r="1"></circle>
                    </svg>
                    San Francisco, CA
                  </dd>
                </dl>
              </li>
            </ul>
            <div class="mt-8 flex border-t border-gray-100 pt-8">
              <Nuxt-link
                to="/formPage"
                class="text-sm font-semibold leading-6 text-indigo-600 hover:text-indigo-500"
                >View all openings <span aria-hidden="true">→</span></Nuxt-link
              >
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script setup>
import { ref } from "vue";
import {
  Dialog,
  DialogPanel,
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
  Popover,
  PopoverButton,
  PopoverGroup,
  PopoverPanel,
} from "@headlessui/vue";
import {
  ArrowPathIcon,
  Bars3Icon,
  ChartPieIcon,
  CursorArrowRaysIcon,
  FingerPrintIcon,
  SquaresPlusIcon,
  XMarkIcon,
} from "@heroicons/vue/24/outline";
import {
  ChevronDownIcon,
  PhoneIcon,
  PlayCircleIcon,
} from "@heroicons/vue/20/solid";

const products = [
  {
    name: "Analytics",
    description: "Get a better understanding of your traffic",
    href: "#",
    icon: ChartPieIcon,
  },
  {
    name: "Engagement",
    description: "Speak directly to your customers",
    href: "#",
    icon: CursorArrowRaysIcon,
  },
  {
    name: "Security",
    description: "Your customers’ data will be safe and secure",
    href: "#",
    icon: FingerPrintIcon,
  },
  {
    name: "Integrations",
    description: "Connect with third-party tools",
    href: "#",
    icon: SquaresPlusIcon,
  },
  {
    name: "Automations",
    description: "Build strategic funnels that will convert",
    href: "#",
    icon: ArrowPathIcon,
  },
];
const callsToAction = [
  { name: "Watch demo", href: "#", icon: PlayCircleIcon },
  { name: "Contact sales", href: "#", icon: PhoneIcon },
];

const mobileMenuOpen = ref(false);

const links = [
  { name: "Open roles", href: "#" },
  { name: "Internship program", href: "#" },
  { name: "Our values", href: "#" },
  { name: "Meet our leadership", href: "#" },
];
const stats = [
  { name: "Offices worldwide", value: "12" },
  { name: "Full-time colleagues", value: "300+" },
  { name: "Hours per week", value: "40" },
  { name: "Paid time off", value: "Unlimited" },
];

const showMore = ref(false)

function toggleContent() {
  showMore.value = !showMore.value
}
</script>

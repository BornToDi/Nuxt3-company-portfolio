<template>
    <div class="relative isolate bg-white px-6 py-24 sm:py-32 lg:px-8">
    <svg class="absolute inset-0 -z-10 h-full w-full stroke-gray-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
      <defs>
        <pattern id="83fd4e5a-9d52-42fc-97b6-718e5d7ee527" width="200" height="200" x="50%" y="-64" patternUnits="userSpaceOnUse">
          <path d="M100 200V.5M.5 .5H200" fill="none"></path>
        </pattern>
      </defs>
      <svg x="50%" y="-64" class="overflow-visible fill-gray-50">
        <path d="M-100.5 0h201v201h-201Z M699.5 0h201v201h-201Z M499.5 400h201v201h-201Z M299.5 800h201v201h-201Z" stroke-width="0"></path>
      </svg>
      <rect width="100%" height="100%" stroke-width="0" fill="url(#83fd4e5a-9d52-42fc-97b6-718e5d7ee527)"></rect>
    </svg>
    <div class="mx-auto max-w-xl lg:max-w-7xl">
      <h2 class="text-4xl font-bold tracking-tight text-gray-900">Let’s talk about your project</h2>
      <p class="mt-2 text-lg leading-8 text-gray-600">We help companies and individuals build out their brand guidelines.</p>
      <div class="mt-16 flex flex-col gap-20 sm:gap-y-20 lg:flex-row">
        <form action="#" method="POST" class="lg:flex-auto">
          <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
            <div>
              <label for="first-name" class="block text-sm font-semibold leading-6 text-gray-900">First name</label>
              <div class="mt-2.5">
                <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div>
              <label for="last-name" class="block text-sm font-semibold leading-6 text-gray-900">Last name</label>
              <div class="mt-2.5">
                <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div>
              <label for="budget" class="block text-sm font-semibold leading-6 text-gray-900">Budget</label>
              <div class="mt-2.5">
                <input id="budget" name="budget" type="text" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div>
              <label for="website" class="block text-sm font-semibold leading-6 text-gray-900">Website</label>
              <div class="mt-2.5">
                <input type="url" name="website" id="website" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
              </div>
            </div>
            <div class="sm:col-span-2">
              <label for="message" class="block text-sm font-semibold leading-6 text-gray-900">Message</label>
              <div class="mt-2.5">
                <textarea id="message" name="message" rows="4" class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"></textarea>
              </div>
            </div>
          </div>
          <div class="mt-10">
            <button type="submit" class="block mx-auto w-96 rounded-md bg-indigo-600 px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Let’s talk</button>
          </div>
          <p class="mt-4 text-sm leading-6 text-gray-500">By submitting this form, I agree to the <a href="#" class="font-semibold text-indigo-600">privacy&nbsp;policy</a>.</p>
        </form>
        <div class="lg:mt-6 lg:w-80 lg:flex-none">
          <img class="h-12 w-auto" src="https://tailwindui.com/img/logos/workcation-logo-indigo-600.svg" alt="">
          <figure class="mt-10">
            <blockquote class="text-lg font-semibold leading-8 text-gray-900 text-justify">
              <p>“Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo expedita voluptas culpa sapiente alias molestiae. Numquam corrupti in laborum sed rerum et corporis.”</p>
            </blockquote>
            <figcaption class="mt-10 flex gap-x-6">
              <img src="https://images.unsplash.com/photo-1550525811-e5869dd03032?ixlib=rb-=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=2&amp;w=96&amp;h=96&amp;q=80" alt="" class="h-12 w-12 flex-none rounded-full bg-gray-50">
              <div>
                <div class="text-base font-semibold text-gray-900">Brenna Goyette</div>
                <div class="text-sm leading-6 text-gray-600">CEO of Workcation</div>
              </div>
            </figcaption>
          </figure>
        </div>
      </div>
    </div>
  </div>
    <div class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto max-w-2xl space-y-16 divide-y divide-gray-100 lg:mx-0 lg:max-w-none">
        <div class="grid grid-cols-1 gap-x-8 gap-y-10 lg:grid-cols-3">
          <div>
            <h2 class="text-3xl font-bold tracking-tight text-gray-900">Get in touch</h2>
            <p class="mt-4 leading-7 text-gray-600">Quam nunc nunc eu sed. Sed rhoncus quis ultricies ac pellentesque.</p>
          </div>
          <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:col-span-2 lg:gap-8">
            <div class="rounded-2xl bg-gray-50 p-10">
              <h3 class="text-base font-semibold leading-7 text-gray-900">Collaborate</h3>
              <dl class="mt-3 space-y-1 text-sm leading-6 text-gray-600">
                <div>
                  <dt class="sr-only">Email</dt>
                  <dd><a class="font-semibold text-indigo-600" href="mailto:collaborate@example.com">collaborate@example.com</a></dd>
                </div>
                <div class="mt-1">
                  <dt class="sr-only">Phone number</dt>
                  <dd>+1 (555) 905-2345</dd>
                </div>
              </dl>
            </div>
            <div class="rounded-2xl bg-gray-50 p-10">
              <h3 class="text-base font-semibold leading-7 text-gray-900">Press</h3>
              <dl class="mt-3 space-y-1 text-sm leading-6 text-gray-600">
                <div>
                  <dt class="sr-only">Email</dt>
                  <dd><a class="font-semibold text-indigo-600" href="mailto:press@example.com">press@example.com</a></dd>
                </div>
                <div class="mt-1">
                  <dt class="sr-only">Phone number</dt>
                  <dd>+1 (555) 905-3456</dd>
                </div>
              </dl>
            </div>
            <div class="rounded-2xl bg-gray-50 p-10">
              <h3 class="text-base font-semibold leading-7 text-gray-900">Join our team</h3>
              <dl class="mt-3 space-y-1 text-sm leading-6 text-gray-600">
                <div>
                  <dt class="sr-only">Email</dt>
                  <dd><a class="font-semibold text-indigo-600" href="mailto:careers@example.com">careers@example.com</a></dd>
                </div>
                <div class="mt-1">
                  <dt class="sr-only">Phone number</dt>
                  <dd>+1 (555) 905-4567</dd>
                </div>
              </dl>
            </div>
            <div class="rounded-2xl bg-gray-50 p-10">
              <h3 class="text-base font-semibold leading-7 text-gray-900">Say hello</h3>
              <dl class="mt-3 space-y-1 text-sm leading-6 text-gray-600">
                <div>
                  <dt class="sr-only">Email</dt>
                  <dd><a class="font-semibold text-indigo-600" href="mailto:hello@example.com">hello@example.com</a></dd>
                </div>
                <div class="mt-1">
                  <dt class="sr-only">Phone number</dt>
                  <dd>+1 (555) 905-5678</dd>
                </div>
              </dl>
            </div>
          </div>
        </div>
        
      </div>
    </div>
  </div>

  <!--join our team-->
  <div class="bg-gray-900 py-24 sm:py-32">
    <div class="relative isolate">
      <div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
        <div class="mx-auto flex max-w-2xl flex-col gap-16 bg-white/5 px-6 py-16 ring-1 ring-white/10 sm:rounded-3xl sm:p-8 lg:mx-0 lg:max-w-none lg:flex-row lg:items-center lg:py-20 xl:gap-x-20 xl:px-20">
          <img class="h-96 w-full flex-none rounded-2xl object-cover shadow-xl lg:aspect-square lg:h-auto lg:max-w-sm" src="https://images.unsplash.com/photo-1519338381761-c7523edc1f46?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=800&amp;q=80" alt="">
          <div class="w-full flex-auto">
            <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">Join our team</h2>
            <p class="mt-6 text-lg leading-8 text-gray-300">Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>
            <ul role="list" class="mt-10 grid grid-cols-1 gap-x-8 gap-y-3 text-base leading-7 text-white sm:grid-cols-2">
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  Competitive salaries
                </li>
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  Flexible work hours
                </li>
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  30 days of paid vacation
                </li>
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  Annual team retreats
                </li>
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  Benefits for you and your family
                </li>
              <li class="flex gap-x-3">
                  <svg class="h-7 w-5 flex-none" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z" clip-rule="evenodd"></path>
</svg>
                  A great work environment
                </li>
              
            </ul>
            <div class="mt-10 flex">
              <a href="#" class="text-sm font-semibold leading-6 text-indigo-400">See our job postings <span aria-hidden="true">→</span></a>
            </div>
          </div>
        </div>
      </div>
      <div class="absolute inset-x-0 -top-16 -z-10 flex transform-gpu justify-center overflow-hidden blur-3xl" aria-hidden="true">
        <div class="aspect-[1318/752] w-[82.375rem] flex-none bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-25" style="clip-path: polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)"></div>
      </div>
    </div>
  </div>
</template>
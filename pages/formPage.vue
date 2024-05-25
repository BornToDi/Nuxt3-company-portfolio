<template>
  <div class="grid grid-cols-1 md:grid-cols-3 bg-white">
    <div class="col-span-2 max-h-screen px-8 pt-32">
    <div class="max-w-2xl mx-auto bg-white p-8  rounded-lg">
        <h2 class="text-2xl font-semibold mb-6">Tell Us About Your Project</h2>
        <form>
            <div class="grid grid-cols-2 gap-4 mb-4">
                <div>
                    <label for="project-name" class="block text-gray-700">Name your project</label>
                    <input type="text" id="project-name" class="w-full mt-1 p-2 border rounded-lg">
                </div>
                <div>
                    <label for="budget" class="block text-gray-700">Budget</label>
                    <input type="text" id="budget" class="w-full mt-1 p-2 border rounded-lg">
                </div>
                <div>
                    <label for="start-time" class="block text-gray-700">When do you want to start?</label>
                    <input type="text" id="start-time" class="w-full mt-1 p-2 border rounded-lg" value="Immediate">
                </div>
                <div>
                    <label for="project-type" class="block text-gray-700">Project Type</label>
                    <input type="text" id="project-type" class="w-full mt-1 p-2 border rounded-lg" placeholder="Android App, Web App, ERP etc.">
                </div>
                <div>
                    <label for="preferred-location" class="block text-gray-700">Your Preferred Location</label>
                    <input type="text" id="preferred-location" class="w-full mt-1 p-2 border rounded-lg" value="Asia">
                </div>
                <div>
                    <label for="name" class="block text-gray-700">Your Name</label>
                    <input type="text" id="name" class="w-full mt-1 p-2 border rounded-lg">
                </div>
                <div>
                    <label for="email" class="block text-gray-700">Email Id</label>
                    <input type="email" id="email" class="w-full mt-1 p-2 border rounded-lg">
                </div>
                <div>
                    <label for="mobile-number" class="block text-gray-700">Mobile Number</label>
                    <div class="flex">
                        <input type="text" id="country-code" class="w-1/4 mt-1 p-2 border rounded-lg" value="US" readonly>
                        <input type="text" id="phone-number" class="w-3/4 mt-1 p-2 border rounded-lg" placeholder="0987654321">
                    </div>
                </div>
                <div>
                    <label for="intro-call-time" class="block text-gray-700">Time of Introductory Call (EST)</label>
                    <input type="time" id="intro-call-time" class="w-full mt-1 p-2 border rounded-lg" value="11:00">
                </div>
                <div>
                    <label for="hear-about-us" class="block text-gray-700">How did you hear about us</label>
                    <input type="text" id="hear-about-us" class="w-full mt-1 p-2 border rounded-lg" value="Facebook">
                </div>
            </div>
            <div class="mb-4">
                <label for="attachment" class="block text-gray-700">Attachment</label>
                <input type="file" id="attachment" class="w-full mt-1 p-2 border rounded-lg">
            </div>
            <div class="mb-4">
                <div class="g-recaptcha" data-sitekey="YOUR_SITE_KEY"></div>
            </div>
            <div class="flex justify-between items-center">
                <button type="submit" class="bg-orange-500 text-white py-2 px-4 rounded-lg">Submit</button>
                <button type="button" class="bg-orange-500 text-white py-2 px-4 rounded-lg">Download Our NDA</button>
            </div>
        </form>
    </div>
</div>

<div class="bg-gray-100 ">
    <div >
        <div class="text-2xl font-semibold mb-8 text-center pt-32">TRUSTED BY THE WORLD'S LEADING BRANDS</div>
        <div class="grid grid-cols-2 gap-8 justify-items-center">
            <img src="https://logos-world.net/wp-content/uploads/2022/01/BBC-Logo.png" alt="BBC" class="h-12">
            <img src="https://cdn2.hubspot.net/hubfs/53/image8-2.jpg" alt="Google" class="h-12">
            <img src="https://toppng.com/uploads/preview/apple-logo-logo-png-transparent-background-11659045662t6m4u3uiwq.png" alt="Apple" class="h-12">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVKVHKDeQFT_VblRhezwRzSqp0zVqsP6e9qksSlYtVJQ&s" alt="Canon" class="h-12">
            <img src="https://i.pinimg.com/736x/42/75/49/427549f6f22470ff93ca714479d180c2.jpg" alt="Facebook" class="h-12">
            <img src="https://image.similarpng.com/very-thumbnail/2020/09/Audi-logo-icon-on-transparent-background-PNG.png" alt="Audi" class="h-12">
            <img src="https://p7.hiclipart.com/preview/15/887/633/5bbc130a30388.jpg" alt="Vimeo" class="h-12">
            <img src="https://banner2.cleanpng.com/20181118/ifj/kisspng-logo-of-nbc-television-image-partial-client-list-glenn-bill-5bf0f8d1082644.7236942115425189930334.jpg" alt="NBC" class="h-12">
            <img src="https://toppng.com/uploads/preview/microsoft-logo-wihout-background-11660471222kqsdeneeuy.png" alt="Microsoft" class="h-12">
            <img src="https://p1.hiclipart.com/preview/162/693/101/a-collection-of-warner-bros-shield-logos-png-clipart-thumbnail.jpg" alt="Warner Bros" class="h-12">
        </div>
    </div>
</div>
  </div>



</template>
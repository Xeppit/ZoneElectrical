<template>
    <section class="py-16 px-4 bg-gray-100" id="ContactUs"> 
      <div class="container mx-auto px-12">
        <h2 class="text-4xl mb-12 text-center font-heading">Contact Us</h2>
        <div class="flex flex-wrap -mx-6">
          <div class="w-full lg:w-1/2 px-6 mb-8 lg:mb-0">
            <h3 class="text-2xl mb-2 font-heading">Get in contact with us</h3>
            <p class="mb-8"></p>
            <ul>
              <li class="mb-2"><img class="inline-block w-8 h-8 pr-2" src="placeholders/icons/home.svg" alt="home"><span>Zone Electrical, Waterloo House, Merthyr Tidfil, CF47 0SX</span></li>
              <li class="mb-2"><img class="inline-block w-8 h-8 pr-2" src="placeholders/icons/mobile.svg" alt="mobile"><span>01685 377484</span></li>
              <li class="mb-2"><img class="inline-block w-8 h-8 pr-2" src="placeholders/icons/message.svg" alt="message"><span>ContactUs@ZoneElectrical.co.uk</span></li>
            </ul>
          </div>
          <div class="w-full lg:w-1/2 px-6">
            <form action="https://formspree.io/mrgyvqqj" method="POST">
              <div class="mb-4">
                <input class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none" type="email" placeholder="Email" name="_replyto">
              </div>
              <div class="mb-4">
                <textarea class="appearance-none block w-full py-3 px-4 leading-tight text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded focus:outline-none" placeholder="Write something..." rows="5" name="message"></textarea>
              </div>
              <input type="hidden" name="_next" value="https://www.google.com/">
              <div>
                <button class="inline-block w-full py-4 px-8 leading-none text-white bg-green-500 hover:bg-green-600 rounded shadow" type="submit">Submit</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
</template>
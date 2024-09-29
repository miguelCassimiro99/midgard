<template>
  <div class="min-h-screen bg-gradient-to-b from-blue-50 to-indigo-100">
    <header class="bg-white shadow-sm sticky top-0 z-10">
      <nav class="container mx-auto px-4 py-2 flex justify-between items-center">
        <div class="flex justify-center items-center">
          <NuxtImg src="/rateio.svg" class="w-14 h-14" />
          <h1 class="text-2xl font-bold text-indigo-600 flex">Rate <span class="text-orange-600 w-fit">.</span>io</h1>
        </div>
        <div class="space-x-4">
          <a href="#how-work" class="text-gray-600 hover:text-indigo-600 transition duration-300">How It Works</a>
          <a href="#features" class="text-gray-600 hover:text-indigo-600 transition duration-300">Features</a>
          <button class="bg-indigo-600 text-white px-4 py-2 rounded-md hover:bg-indigo-700 transition duration-300">
            Get Started
          </button>
        </div>
      </nav>
    </header>

    <main>
      <section class="bg-indigo-700 text-white py-20">
        <div class="container mx-auto px-4 text-center">
          <h2 class="text-4xl md:text-5xl font-bold mb-6">Split Expenses, Keep Smiling</h2>
          <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">
            SplitSmart makes sharing costs for group activities a breeze. No more awkward money talks or complex calculations.
          </p>
          <button class="bg-white text-orange-600 px-8 py-3 rounded-md text-lg font-semibold hover:bg-indigo-100 transition duration-300">
            Start Splitting Now
          </button>
        </div>
      </section>

      <section id="how-work" class="py-16 bg-white">
        <div class="container mx-auto px-4">
          <h3 class="text-3xl font-bold text-center text-gray-800 mb-12">How SplitSmart Works</h3>
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
              <div class="flex items-start">
                <div class="bg-indigo-600 text-white rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">1</div>
                <div>
                  <h4 class="text-xl font-semibold mb-2">Create Your Event</h4>
                  <p class="text-gray-600">Enter the event name and add all participants involved in the expense sharing.</p>
                </div>
              </div>
              <div class="flex items-start">
                <div class="bg-indigo-600 text-white rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">2</div>
                <div>
                  <h4 class="text-xl font-semibold mb-2">Add Expenses</h4>
                  <p class="text-gray-600">Input each expense with its name, amount, and who paid for it.</p>
                </div>
              </div>
              <div class="flex items-start">
                <div class="bg-indigo-600 text-white rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">3</div>
                <div>
                  <h4 class="text-xl font-semibold mb-2">Calculate and Review</h4>
                  <p class="text-gray-600">Hit 'Calculate Split' to see a breakdown of who owes what to whom.</p>
                </div>
              </div>
              <div class="flex items-start">
                <div class="bg-indigo-600 text-white rounded-full w-10 h-10 flex items-center justify-center mr-4 flex-shrink-0">4</div>
                <div>
                  <h4 class="text-xl font-semibold mb-2">Settle Up</h4>
                  <p class="text-gray-600">Use our transfer recommendations to easily settle all debts.</p>
                </div>
              </div>
            </div>
            <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
              <img src="/placeholder.svg?height=400&width=500" alt="SplitSmart app interface" class="w-full h-auto rounded-md">
            </div>
          </div>
        </div>
      </section>

      <section id="features" class="py-16 bg-indigo-50">
        <div class="container mx-auto px-4">
          <h3 class="text-3xl font-bold text-center text-gray-800 mb-12">Why Users Love SplitSmart</h3>
          <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="text-indigo-600 text-4xl mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
              </div>
              <h4 class="text-xl font-semibold mb-2 text-center">Lightning Fast</h4>
              <p class="text-gray-600 text-center">Split expenses in seconds, not minutes. Our intuitive interface makes expense sharing a breeze.</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="text-indigo-600 text-4xl mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z" />
                </svg>
              </div>
              <h4 class="text-xl font-semibold mb-2 text-center">Smart Calculations</h4>
              <p class="text-gray-600 text-center">Our algorithm ensures fair splits and provides clear transfer recommendations.</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md">
              <div class="text-indigo-600 text-4xl mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
                </svg>
              </div>
              <h4 class="text-xl font-semibold mb-2 text-center">Group Friendly</h4>
              <p class="text-gray-600 text-center">Whether it's 2 friends or 20, SplitSmart handles groups of any size with ease.</p>
            </div>
          </div>
        </div>
      </section>

      <section class="py-16 bg-white">
        <div class="container mx-auto px-4 text-center">
          <h3 class="text-3xl font-bold text-gray-800 mb-6">Ready to Split Smarter?</h3>
          <p class="text-xl text-gray-600 mb-8 max-w-2xl mx-auto">
            Join thousands of happy users and start sharing expenses fairly today. No more awkward conversations or complex math!
          </p>
          <button class="bg-indigo-600 text-white px-8 py-3 rounded-md text-lg font-semibold hover:bg-indigo-700 transition duration-300">
            Get Started for Free
          </button>
        </div>
      </section>
    </main>

    <footer class="bg-gray-800 text-white py-8">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-between items-center">
          <div class="w-full md:w-1/3 text-center md:text-left mb-4 md:mb-0">
            <h2 class="text-2xl font-bold">SplitSmart</h2>
            <p class="mt-2">Simplifying group expenses</p>
          </div>
          <div class="w-full md:w-1/3 text-center mb-4 md:mb-0">
            <a href="#" class="text-gray-300 hover:text-white mx-3">About</a>
            <a href="#" class="text-gray-300 hover:text-white mx-3">Features</a>
            <a href="#" class="text-gray-300 hover:text-white mx-3">Contact</a>
          </div>
          <div class="w-full md:w-1/3 text-center md:text-right">
            <p>&copy; 2023 SplitSmart. All rights reserved.</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
// No additional script needed for this static home page
</script>
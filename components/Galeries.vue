<template>
  <main>
    <section class="bg-white">
      <div class="max-w-5xl px-6 py-16 mx-auto text-center">
        <h2 class="text-3xl font-semibold text-gray-800">
          Lorem ipsum dolor sit amet, <br />
          consectetur adipiscing
        </h2>
        <p class="max-w-lg mx-auto mt-4 text-gray-600">
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
          dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est
          laborum.
        </p>

        <div
          class="parallax object-cover object-center w-full mt-16 rounded-md shadow"
        />
      </div>
    </section>
    <section class="bg-white">
      <div
        class="max-w-5xl px-6 py-16 mx-auto space-y-8 md:flex md:items-center md:space-y-0"
      >
        <div class="md:w-2/3">
          <div class="hidden md:flex md:items-center md:space-x-10">
            <img
              class="object-cover object-center rounded-md shadow w-72 h-72"
              src="https://images.unsplash.com/photo-1614030126544-b79b92e29e98?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
            />
            <img
              class="object-cover object-center w-64 rounded-md shadow h-96"
              src="https://images.unsplash.com/photo-1618506469810-282bef2b30b3?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80"
            />
          </div>
          <h2 class="text-3xl font-semibold text-gray-800 md:mt-6">
            Project Photos
          </h2>
          <p class="max-w-lg mt-4 text-gray-600">
            We've taken some photos during our project action.
          </p>
          <div class="flex flex-col w-2/4 lg:flex-row">
            <p class="mt-2 text-sm text-left text-blueGray-600 md:mt-4">
              <a
                href="#"
                class="inline-flex items-center font-semibold text-blue-600 md:mb-2 lg:mb-0 hover:text-black "
                title="read more"
              >
                See More »
              </a>
            </p>
          </div>
        </div>
        <div class="md:w-1/3">
          <img
            class="object-cover object-center w-full rounded-md shadow"
            style="height: 700px;"
            src="https://images.unsplash.com/photo-1593352216840-1aee13f45818?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
          />
        </div>
      </div>
    </section>
  </main>
</template>

<style scope>
.parallax {
  height: 300px !important;
  /* The image used */
  background-image: url("https://images.unsplash.com/photo-1600069226367-412873fb0637?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1350&amp;q=80");

  /* Full height */
  height: 100%;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>

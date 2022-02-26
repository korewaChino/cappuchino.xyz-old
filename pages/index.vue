<template>
  <div class="flex h-screen" style="
  background-color: #2b3e58;
  background-image: url(background.jpg);
  /* blur the background image ONLY */
  background-blend-mode: multiply;

  background-position: center;
  ">
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
      integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <div class="shadow-2xl m-auto">
      <!-- make a box -->
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-8">
        <h1 class="text-3xl font-bold mb-4">
          Cappy Ishihara
        </h1>
        <p class="mb-4">
          Struggling student by day, 10x developer by night.
        </p>
        <!-- Social links -->
        <div class="flex justify-center">
          <a
            class="text-gray-600  fab fa-twitter dark:text-gray-200 hover:text-blue-600 dark:hover:text-blue-200"
            href="https://twitter.com/CappyIshihara"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

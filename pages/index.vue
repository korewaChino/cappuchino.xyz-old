<template>
  <div
    class="flex h-screen"
    style="
      background-color: #2b3e58;
      background-image: url(background.jpg);
      /* blur the background image ONLY */
      background-blend-mode: multiply;

      background-position: center;
    "
  >
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
      integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <div class="shadow-2xl m-auto">
      <!-- make a box -->
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-11">
        <h1 class="text-3xl font-bold mb-5">Cappy Ishihara</h1>
        <p class="mb-4">
          Struggling student by day, 10x developer by night.
          <br />
          Languages: Python, Vue, Rust and C.
          <br />
          <br />
          <a class="text-green-400" href="portfolio">Portfolio</a>
          <br />
          <a class="text-green-400" href="https://en.pronouns.page/@korewachino"
            >Pronouns</a
          >
        </p>

        <!-- A Ko-fi button -->
        <a
          href="https://ko-fi.com/korewachino"
          target="_blank"
          rel="noopener noreferrer"
        >
          <img
            src="https://cdn.ko-fi.com/cdn/kofi5.png"
            border="0"
            alt="Buy Me a Coffee at ko-fi.com"
            width="150px"
            class="my-3"
          />
        </a>

        <!-- Social links -->
        <div class="flex justify-center text-gray-600 text-3xl">
          <a
            class="
              fab
              fa-twitter
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="https://twitter.com/CappyIshihara"
          />
          <a
            class="
              fab
              fa-github
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="https://github.com/korewaChino"
          />
          <a
            class="
              fab
              fa-gitlab
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="https://gitlab.com/korewaChino"
          />
          <a
            class="
              fab
              fa-soundcloud
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="https://soundcloud.com/c4ppucc1n0"
          />
          <!-- email -->
          <a
            class="
              fa
              fa-envelope
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="mailto:cappy@cappuchino.xyz"
          />
          <!--youtube-->
          <a
            class="
              fab
              fa-youtube
              dark:text-gray-200
              hover:text-blue-600
              dark:hover:text-blue-200
              mx-1
            "
            href="https://www.youtube.com/c/cupochinomusic"
          />
        </div>
        <div>

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

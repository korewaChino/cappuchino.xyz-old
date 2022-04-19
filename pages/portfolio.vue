<template>
  <div
    class="flex h-screen"
    style="
      background-color: #2b3e58;
      background-image: url(/background.jpg);
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
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-8">
        <h1 class="text-3xl font-bold mb-4">Portfolio</h1>
        <!-- <article>
          <nuxt-content :document="page" />
        </article> -->

        I go on the internet as Cappy Ishihara.
        <br/>
        I'm a high school student studying an English major at the Srinakharinwirot University
        (Demonstration School).
        <br/>
        For privacy reasons, I will not be sharing my real name.
        <br/>
        I speak fluent English and Thai, and I am a native Thai speaker. I have experience in the following areas:
        <!-- list -->
        <ul class="list-disc ml-8">
          <li>
            Software development
          </li>
          <li>
            Operating systems
          </li>
          <li>
            Audio engineering
          </li>
          <li>
            Package maintenance
          </li>
        </ul>
        I am the founder of the Ultramarine Linux project, and I used to be the project maintainer for
        it.
        <br/>
        I also work on the Virtual Puppet Project (see below).
        <br/>
        I'm
        interested in the software development community, and my projects are
        open source.
        <br/>
        I'm also non-binary and pansexual! If that discourages you from hiring me, then please don't hire me.
        <br/>
        <br/>

        <h2 class="text-xl mb-4">
          List of projects and stuff I've done that are worth noting.
        </h2>
        <!-- make a list -->
        <ul class="list-disc ml-8">
          <li class="mb-4">
            <a class="text-green-400" href="https://ultramarine-linux.org">
              Ultramarine Linux
            </a>
            : A simple Fedora-based Linux distribution designed for beginners
            and power users alike.
          </li>
          <li class="mb-4">
            <a class="text-green-400" href="https://github.com/Fedora-Jam-Plus">
              Fedora Jam+
            </a>
            : A collection of audio production packages for Fedora.
          </li>
          <li class="mb-4">
            <a
              class="text-green-400"
              href="https://github.com/korewaChino/libpolymc"
            >
              libpolymc
            </a>
            : A library for making your own Minecraft launcher.
          </li>
          <li class="mb-4">
            <a class="text-green-400" href="https://vss-project.com/">
              VP3 (Virtual Puppet Project)
            </a>
            : Virtual YouTuber production software made with Godot.
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
  async asyncData({ $content }) {
    const page = await $content('hello').fetch()

    return {
      page,
    }
  },
}
</script>

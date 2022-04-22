<template>
  <div
    class="flex h-screen"
    style="

      color: #fff;
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
    <div class="m-auto grid">
      <!-- make a box -->
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-16 text-5xl">
        Cappy Ishihara <p class="text-xl">(Real name Redacted)</p>
      </div>
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-7 m-8">
        <h1 class="text-3xl">
          Technologies and Languages
        </h1>
        <br>
        Programming Languages: Python, Vue, Rust, C, C++, JavaScript
        <br>
        Frameworks: Flask, Nuxt.js, TailwindCSS, Bootstrap, Bulma
        <br>
        Tools: Git, Docker, ZSH, Bash, Selenium, RPM, Ansible
        <br>
        Other: GCP, Heroku, GitLab CI
      </div>
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-7 m-5">
        <h1 class="text-3xl">
          Education
        </h1>
        English Major, Srinakharinwirot University Demonstration School (2021-2023)
      </div>
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-7 m-5">
        <h1 class="text-3xl">
          Experience
        </h1>
        <br/>
        <ul class="list-disc ml-8">
          <li>
            2021-2022 - Ultramarine Linux - Founder, Core Maintainer
            <ul class="list-disc ml-8">
              <li>Maintained the core RPM packages for Ultramarine Linux</li>
              <li>DevOps Services using Koji and GitLab CI</li>
              <li>Open-source coordination</li>
            </ul>
          </li>
        </ul>
      </div>
      <div class="bg-gray-900 text-gray-50 shadow-xl rounded-2xl p-7 m-5">
        <h1 class="text-3xl">
          Projects
        </h1>
        <br/>
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

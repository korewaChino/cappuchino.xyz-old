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
          Portfolio
        </h1>
        <h2 class="text-xl mb-4">
          This is a list of projects and stuff I've done that are worth noting. Might be useful when I get a job.
        </h2>
        <!-- make a list -->
        <ul class="list-disc ml-8">
          <li class="mb-4">
            <a class="text-green-400" href="https://ultramarine-linux.org">
              Ultramarine Linux
            </a>
            : A simple Fedora-based Linux distribution designed for beginners and power users alike.
          </li>
          <li class="mb-4">
            <a class="text-green-400" href="https://github.com/Fedora-Jam-Plus">
              Fedora Jam+
            </a>
            : A collection of audio production packages for Fedora.
          </li>
          <li class="mb-4">
            <a class="text-green-400" href="https://github.com/korewaChino/libpolymc">
              libpolymc
            </a>
            : A library for making your own Minecraft launcher.
          </li>
          <li class="mb-4">
            <a class="text-green-400" href="https://vss-project.com/">
              VSS (Virtual Streamer Software)
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
}
</script>

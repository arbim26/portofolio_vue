<script setup>
  import WelcomeItem from './WelcomeItem.vue'
  import HTML from './icons/HTML.vue'
  import CSS from './icons/CSS.vue'
  import JS from './icons/JS.vue'
  import PHP from './icons/PHP.vue'
  import Figma from './icons/Figma.vue'
  import Indo from './icons/Indo.vue'
  import Britain from './icons/Britain.vue'
</script>

<template>
  <div class="education">
    <h1 style="text-align: center; font-weight: 500; margin-bottom: 10px;">EDUCATION</h1>
    <h3 style="font-weight: 500;">Software Engineering</h3>
    <h5>Taruna Bhakti Vocational High School.</h5>
    <hr style="margin-top: 10px;">
  </div>


  <h1 style="text-align: center; font-weight: 500; margin-bottom: 10px;">LANGUAGE </h1>

  <WelcomeItem>
    <template #icon>
      <Indo />
    </template>
    <template #heading>Indonesian</template>
    <h5>Native</h5>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <Britain />
    </template>
    <template #heading>English</template>
    <h5>Intermediate</h5>
  </WelcomeItem>

  <hr style="margin-top: 20px;">

  <h1 style="text-align: center; font-weight: 500; margin-bottom: 10px;">SKILL</h1>

  <WelcomeItem>
    <template #icon>
      <HTML />
    </template>
    <!-- <template #heading>HTML</template> -->
    <div class="progress-element">
      <p class="progress-label">HTML</p>
      <div class="progress-container">
        <progress max="100" value="85">85%</progress>
      </div>
    </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CSS />
    </template>
      <p class="progress-label">CSS</p>
      <div class="progress-container">
        <progress max="100" value="85">85%</progress>
      </div>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <JS />
    </template>
      <p class="progress-label">JavaScript</p>
      <div class="progress-container">
        <progress max="100" value="85">65%</progress>
      </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <PHP />
    </template>
      <p class="progress-label">PHP</p>
      <div class="progress-container">
        <progress max="100" value="85">65%</progress>
      </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <Figma />
    </template>
      <p class="progress-label">Figma</p>
      <div class="progress-container">
        <progress max="100" value="85">65%</progress>
      </div>
  </WelcomeItem>
</template>

<style>
  .education {
    text-align: center;
    padding-bottom: 10px;
  }

  progress {
  accent-color: #293462;
}

  .progress-label {
    position: relative;
  }

  .progress-label::after {
    content: "85%";
    position: absolute;
    top:0;
    right: 0;
  }
</style>
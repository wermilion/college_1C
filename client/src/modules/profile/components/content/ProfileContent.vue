<template>
  <section class="grid grid-cols-1 _2xl:grid-cols-2 gap-5 _2xl:gap-7.5">
    <ProfileDisciplines />
    <ProfileAbout />
  </section>
</template>

<script setup lang="ts">
import ProfileAbout from "@/modules/profile/components/content/about/ProfileAbout.vue";
import ProfileDisciplines from "@/modules/profile/components/content/disciplines/ProfileDisciplines.vue";
</script>
<template>
  <div class="border p-5 my-5 gap-6 flex flex-col justify-center items-center py-10 hover:shadow-lg">
    <img class="w-24 rounded-full" :src="photo" />
    <h3 class="text-xl">{{ name }}</h3>
    <h4>{{ destination }}</h4>
  </div>
</template>

<script>
export default {
  props: {
    name: String,
    destination: String,
    photo: String,
    twitter: {
      default: "#",
      type: String,
    },
    facebook: {
      default: "#",
      type: String,
    },
    instagram: {
      default: "#",
      type: String,
    },
    google_plus: {
      default: "#",
      type: String,
    },
  },
};
</script>

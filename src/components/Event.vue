<template>
  <div class="border-b-2">
    <h2 class="text-center text-xl font-semibold py-5">{{ title }}</h2>
    <p>{{ text }}
    </p>
    <div class="flex justify-center pb-5">
      <img :src="image" class="pt-10" >
    </div>
  </div>
</template>

<script>
export default {  
  name: "Event",
  props: [
    "title",
    "text",
    "image"
  ]
}
</script>

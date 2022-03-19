<template>
  <modals>
    <template #title>
      <h3>Ben bir Başlığıms</h3>
    </template>
    <template v-slot:content>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Accusantium
        soluta, a eius quidem temporibus optio rem sit?
      </p>
    </template>
  </modals>
</template>

<script>
import modals from "@/components/modals";
export default {
  components: {
    modals,
  },
};
</script>
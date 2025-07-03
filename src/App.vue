<template>
  <div class="bg-white dark:bg-dim-900">
    <div class="container mx-auto h-screen">
      <div class="flex flex-row justify-center">
        <LeftSide />
        <Middle />
        <RightSide />
      </div>
    </div>
  </div>
</template>
<script>
import LeftSide from '@/components/LeftSide.vue';
import Middle from '@/components/Middle.vue';
import RightSide from '@/components/RightSide.vue';
export default {
  components: {
    LeftSide,
    RightSide,
    Middle
  }
}
</script>
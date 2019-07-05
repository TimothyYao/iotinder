<template>
  <div class="home">
    <SwipeableCards />
  </div>
</template>

<script>
// @ is an alias to /src
import SwipeableCards from '@/components/SwipeableCards.vue';

export default {
  name: 'game',
  components: {
    SwipeableCards,
  },
};
</script>

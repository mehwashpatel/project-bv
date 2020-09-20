<template>
  <div class="home">
     <b-container>
        <b-row>
          <custom-card v-for="index in 3" :key="index"></custom-card>
        </b-row>
     </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
import CustomCard from "@/components/custom-card.vue";

export default {
  name: 'Home',
  components: { "custom-card": CustomCard },
}
</script>

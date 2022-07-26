<template>
  <Heading message="Mert Şişmanoğlu"/>
  <ProfileCard/>
</template>

<script>
// @ is an alias to /src
import Heading from '@/components/Heading.vue'
import ProfileCard from '@/components/ProfileCard.vue'

export default {
  name: 'HomeView',
  components: {
    Heading,
    ProfileCard
  }
}
</script>

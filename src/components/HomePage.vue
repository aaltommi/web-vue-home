<template>
    <div class="main">
    <ProfileCard></ProfileCard>
    <div class="content">
    <h1>Hello!</h1>
    <p>I've created online CV for you!</p>
    <p>You can find all professional information about me and my skills on this page.</p>
    <p>For other intrest check my political and social blog and my social media from here:</p>
    
    <div>

    </div>

    <p>Sincerely, <br>
      <span style="margin-left: 20px;"><em id="signature">Tommi Aalto</em></span>
    </p>
    </div>
    </div>
</template>

<script>
import ProfileCard from './ProfileCard.vue'
export default {
  name: 'HomePage',
  props: {
    msg: String
  },
  components: {
    ProfileCard
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
template {
        
        background-image: url("../assets/background_tracks.jpg");
      }
</style>

<template>
    <div class="main">
    <div class="card">
        <img class="profile-pic" src="../assets/profile-pic2.jpg" alt="Tommi">
        <p>Tommi Aalto</p>
        <p>Software Engineer</p>
    </div>
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
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
template {
        
        background-image: url("../assets/background_tracks.jpg");
      }
      
      .card {
        margin: auto;
        width: 40%;
        border: 1px solid black;
      }
      .profile-pic {
        margin: 24px 48px 24px 48px;
        width: 40%;
        height: 40%;
        border-radius: 50%;
        border: 2px solid black;
        text-align: center;
      } 
</style>

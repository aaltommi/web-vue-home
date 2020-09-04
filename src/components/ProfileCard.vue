<template>
    <div class="card">
        <img class="profile-pic" src="../assets/profile-pic2.jpg" alt="Tommi">
        <div class="description">
        <p>Tommi Aalto</p>
        <p>Software Engineer. Currently working for Opentext in Tampere, Finland as an Test Automation / Software Engineer</p>
        <p>This is my cv. I'm open for new opportunities and challenges also abroad.</p>
        </div>
    </div>
</template>
<script>
export default {
  name: 'ProfileCard',
  props: {
    msg: String
  }
}
</script>
<style scoped>
.card {
    display: flex;
    margin: auto;
    width: 80%;
    border-radius: 10px;
    border: 1px solid black;
}
.profile-pic {
    flex: 50%;
    margin: 24px 48px 24px 48px;
    width: 20%;
    height: 20%;
    border-radius: 50%;
    border: 2px solid black;
    text-align: center;
} 
.description {
    flex: 50%;
}

</style>
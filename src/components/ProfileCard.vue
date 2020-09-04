<template>
    <div class="card">
        <img class="profile-pic" src="../assets/profile-pic2.jpg" alt="Tommi">
        <p>Tommi Aalto</p>
        <p>Software Engineer</p>
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
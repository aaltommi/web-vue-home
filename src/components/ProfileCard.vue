<template>
    <div class="card">
        <img class="profile-pic" src="../assets/profile-pic2.jpg" alt="Tommi">
        <div class="description">
        <p>Tommi Aalto</p>
        <p>Software Engineer. Currently working for Opentext in Tampere, Finland as an Test Automation / Software Engineer</p>
        <p>This is my cv. I'm open for new opportunities and challenges also abroad.</p>
        <p> More text bla bla bal More text bla bla bal More text bla bla bal More text bla bla bal</p>
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
}
.profile-pic {
    flex: 30%;
    margin: 24px 48px 24px 48px;
    width: 10%;
    height: 10%;
    border-radius: 50%;
    border: 2px solid black;
    text-align: center;
} 
.description {
    flex: 50%;
}

</style>
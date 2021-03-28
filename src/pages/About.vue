<template>
  <Layout>
    <h1>Say hi!</h1>
    <p>Leave me a note with any questions you might have, I'll get back to you as soon as possible.</p>
    <div>
      <form action="">
        <div class="top">
          <div class="top-name">
            <p>Your name</p>
            <input type="text">
          </div>
          <div class="top-email">
            <p>Your email</p>
            <input type="text">
          </div>
        </div>
        <div>
          <p>Message</p>
          <textarea name="" id="" cols="30" rows="10"></textarea>
        </div>
        <input class="btn" type="submit" value="Submit form">
      </form>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Say hi!'
  }
}
</script>
<style scoped>
  .top {
    display: flex;
  }
  .top>div input {
    height: 30px;
    width: 365px;
  }
  .top-name {
    margin-right: 20px;
  }
  textarea {
    width: 760px;
  }
  .btn {
    width: 140px;
    height: 40px;
    border-radius: 8px;
    color: #fff;
    background-color: black;
    margin-top: 30px;
    margin-bottom: 60px;
  }
</style>

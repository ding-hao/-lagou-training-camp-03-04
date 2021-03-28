<template>
  <Layout>
    <div class="box">
        <h1>a wise person once said...</h1>
        <ul>
            <li>
                <div>
                    <h2>Gridsome with Forestry CMS</h2>
                    <p>Get up and running with Forestry CMS, a git-backed headless CMS with a slick editing interface.</p>
                </div>
            </li>
            <li>
                <div>
                    <h2>VueJS for your next project</h2>
                    <p>Vue (pronounced /vjuː/, like view) is a progressive framework for building user interfaces.</p>
                </div>
            </li>
            <li>
                <div>
                    <h2>macOS development</h2>
                    <p>Get up and running with a fresh macOS Catalina install</p>
                </div>
            </li>
            <li>
                <div>
                    <h2>About Typography</h2>
                    <p>Font face, vertical rythm, readability, this long fake text should flow.</p>
                </div>
            </li>
        </ul>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Journal'
  }
}
</script>
<style scoped>
.box {
    text-align: center;
}
li {
    list-style: none;
    height: 150px;
}
li div {
    width: 400px;
    margin: 0 auto;
    transition: all .6s;
}
li:hover {
    background-color: #eee;
}
li:hover div {
    padding-left: 20px;
}
  h1 {
      padding-top: 100px;
      opacity: .1;
  }
</style>

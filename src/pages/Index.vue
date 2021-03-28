<template>
      <Layout>

      <!-- Learn how to use images here: https://gridsome.org/docs/images -->
      <div class="index">
        <h1>Simplicity. <br/>Aesthetics.Value.</h1>

        <p class="des">
          Hi there, I'm an independent Digital Designer & Art Director focused on digital design for brands that like to have fun.
        </p>
      </div>
      <div class="box">
        <div>    
      <g-link to='/'>
        <g-image class="img" alt="Example image" src="../../static/img/mike-dorner.jpg" width="760" />
      </g-link>
      <h3>Banana</h3>
      <p><span>photography</span>&nbsp;<span>pink</span></p>
        </div>
      </div>
      <div class="box spe">
        <div>    
      <g-link to='/'>
        <g-image class="img" alt="Example image" src="../../static/img/cody-davis.jpg" width="360" height="480" />
      </g-link>
      <h3>Banana</h3>
      <p><span>photography</span>&nbsp;<span>pink</span></p>
        </div>
        <div>    
      <g-link to='/'>
        <g-image class="img" alt="Example image" src="../../static/img/ian-dooley.jpg" width="360" height="480" />
      </g-link>
      <h3>Banana</h3>
      <p><span>photography</span>&nbsp;<span>pink</span></p>
        </div>
      </div>
      <div class="box">
        <div>    
      <g-link to='/'>
        <g-image class="img" alt="Example image" src="../../static/img/markus-spiske.jpg" width="760" />
      </g-link>
      <h3>Banana</h3>
      <p><span>photography</span>&nbsp;<span>pink</span></p>
        </div>
      </div>
      <div>
        <h5>LATEST AND GREATEST</h5>
        <ul>
          <li>
            <g-link to="/">
              Gridsome with Forestry CMS
            </g-link>
          </li>
          <li>
            <g-link to="/">
              VueJS for your next project
            </g-link>
          </li>
          <li>
            <g-link to="/">
              macOS development
            </g-link>
          </li>
          <li>
            <g-link to="/">
              About Typography
            </g-link>
          </li>
        </ul>
      </div>

    </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style scoped>
ul {
  display: flex;
  border-top: 1px solid #eee;
  border-bottom: 1px solid #eee;
}
li {
  list-style: none;
  box-sizing: border-box;
  height: 100px;
  width: 200px;
  padding: 30px 30px;
}
a {
  text-decoration: none;
}
li a {
  font-size: 16px;
  font-weight: bold;
  color: black;
}
li:hover {
  background-color: #eee;
}
.box {
  display: flex;
  text-align: center;
  justify-content: center;
  margin-top: 20px;
}
.spe {
  justify-content: space-between;
}
.home-links a {
  margin-right: 1rem;
}
.index {
  max-width: 450px;
  text-align: center;
  margin: 0 auto;
}
.des {
  opacity: .6;
}
.img {
  transition: all 0.6s;
}
.img:hover{  
  transform: scale(1.05);  
}  
</style>

<template>
  <div class="layout">
    <header class="header">
      <g-link to='/' class="fl">
        <g-image alt="Example image" src="../../static/img/logo.svg" width="135" />
      </g-link>
      <nav class="nav">
        <g-link class="nav__link" to="/journal/">Journal</g-link>
        <g-link class="nav__link" to="/about/">Say Hi!</g-link>
      </nav>
    </header>
    <slot/>
    <footer>
      <p>Copyright © 2021</p>
      
    </footer>
  </div>
</template>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.header {
  position: fixed;
  width: 760px;
  margin-bottom: 20px;
  height: 80px;
  z-index: 99999;
}

.fl {
  float: left;
}

.nav__link {
  margin-left: 20px;
}
.nav {
  color: inherit;
  float: right;
}
</style>

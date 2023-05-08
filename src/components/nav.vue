<template>
  <div id="navbar">
    <img src="@/assets/logo.png" alt="">
    <div class="header-container">
      <h1>LilyOS</h1>
      <p>Lorem, ipsum.</p>
    </div>
    <div class="seperator"></div>
    <div class="nav-container">
      <ul>
        <li><a href="#">Features</a></li>
        <li><a href="#">Documentation</a></li>
        <li><a href="#">Contribute</a></li>
        <li><a href="#">Download LilyOS</a></li>
      </ul>
        <div class="nav-end">
          <p>Follow</p>
          <p>placeholder</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'navbar',
};
</script>
<style>
#navbar{
  font-family: 'space mono';
  color: var(--text);
}

</style>
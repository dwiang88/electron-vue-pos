<template>
  <ul>
    <li><router-link :to="{ name: 'dashboard-page'}">เข้าสูหน้า dashboard</router-link></li>
  </ul>
</template>

<style scoped>
  a {
    color: rgb(50, 174, 110);
    text-decoration: none;
  }

  a:hover {
    color: rgb(40, 56, 76);
  }

  ul {
    list-style-type: none;
    margin-top: 10px;
  }

  li { display: inline-block; }
</style>

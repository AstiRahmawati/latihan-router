<!-- <template>
    <div id="navbar">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </template> -->
  
  <template>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/contact">Contact</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/produk">Produk</router-link></li>
      <li><router-link to="/kategori">Kategori</router-link></li>
      <li><router-link to="/login">login</router-link></li>
    </ul>
  </template>
  
  <script>
  export default {
  
  }
  </script>
  
  <style scoped>
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
  }
  
  li {
    float: left;
  }
  
  li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  li a:hover:not(.active) {
    background-color: #25a830;
  }
  
  .active {
    background-color: #4CAF50;
  }
  </style>
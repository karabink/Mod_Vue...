<template>
  <div id="app">
<div>
  <router-view></router-view>
</div>
    <info-card
      image-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhwMQ2fYK311NN2Z8kbPv0-c0A59jFPEcQ-Oipct4T4nGI0N78Xa8R8TBTwUZLPN1YlH2n0g4&usqp=CAc"
       product_name="Назва товару - Cумкa Рюкзак "
       description="Oдиниця виміру - шт."
       description2="Кількість - 656"
    />
    <nav class="navbar-light" id="NavC" aria-label="Сайт">
    <ul class="menu-main" id="ItemC"  style="text-align:center">
      
      <li class="nav-item">
        <router-link class="nav-link" to="/register">Реєстрацію надходження товарів</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/out_list">Відвантаження</router-link>
      </li>

    </ul>
</nav>
  </div>
</template>

<script>
import InfoCard from './components/InfoCard'

export default {
  name: 'App',
  components: {
    InfoCard
  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

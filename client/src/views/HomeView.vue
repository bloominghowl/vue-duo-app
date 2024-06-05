<script>
export default {
  methods: {
    goToFinanceTracker() {
      window.location.href = 'https://finance-track-vue.vercel.app';
    },
    goToTodoList() {
      window.location.href = 'https://dziku.vercel.app';
    }
  }
}
</script>

<template>
<header>
    <nav>
      <ul>
        <li>Vue Duo App</li>
      </ul>
    </nav>
</header>

  <div class="greeting">
    <h1> Hello there! </h1>
  </div>

  <div class="enquiry"> 
    <h3>What will you be doing today?</h3>
  </div>

  <div class="btn-click">
    <button @click="goToFinanceTracker">Track Your Finances</button>
    <button @click="goToTodoList">Manage Your Todo List</button>
  </div>
</template>

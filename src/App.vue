<template>
  <div id="app">
   <Header />
   <div class="container">
     <Balance />
     <IncomeExpenses />
     <TransactionList />
     <AddTransaction />
   </div>
  </div>
</template>

<script>

import '@/assets/style.css';
import Header from '@/components/Header.vue';
import Balance from '@/components/Balance.vue';
import TransactionList from '@/components/TransactionList.vue';
import IncomeExpenses from '@/components/IncomeExpenses.vue';
import AddTransaction from '@/components/AddTransaction.vue';

export default {
  name: 'App',
  components: {
    Header,
    Balance,
    TransactionList,
    IncomeExpenses,
    AddTransaction,
  },
};
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

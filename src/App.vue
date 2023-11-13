<template>
  <Header />
  <div class="container">
    <Balance />
    <IncomeExpense />
    <TransactionList />
    <AddTransaction />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Balance from "./components/Balance.vue";
import IncomeExpense from "./components/IncomeExpenses.vue";
import TransactionList from "./components/TransactionList.vue";
import AddTransaction from "./components/AddTransaction.vue";

export default {
  components: {
    Header,
    Balance,
    IncomeExpense,
    TransactionList,
    AddTransaction,
  },
};
</script>

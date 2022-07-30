<template>
  <Layout>
    <ToDoList />
  </Layout>
</template>

<script>
import Layout from "../components/Layout.vue";
import ToDoList from "../components/ToDoList.vue";
export default {
  name: "IndexPage",
  components: { Layout, ToDoList }
}
</script>

<template>
  <div class="container mt-5">
    <server-header></server-header>

    <hr>

    <div class="row">
      <div class="col-md-6">
        <server-list></server-list>
      </div>

      <div class="col-md-6">
        <p>
          <em>Server Details are not current supported.</em>
        </p>
      </div>
    </div>

    <hr>

    <server-footer></server-footer>
  </div>
</template>

<script>
import ServerHeader from "./ServerHeader.vue";
import ServerFooter from "./ServerFooter.vue";
import ServerList from "./ServerList.vue";

export default {
  components: {
    "server-header": ServerHeader,
    "server-footer": ServerFooter,
    "server-list": ServerList
  }
};
</script>

<style>
</style>

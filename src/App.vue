<template>
  <div class="app">
    <!-- <div class="mt-10 text-center container">
        <button @click="showDialog=true" class="btn btn-success ">Delete Task</button>
        <button @click="showDia" class="btn btn-danger ">Delete User</button>
    </div> -->
    <HelloWorld/>
    <!-- <MyDialog :show="showDialog" :cancel="cancel" :confirm="confirm" title="Delete a task?" description="Dynamical description" /> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
// import MyDialog from "./components/MyDialog.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  data() {
    return {
      showDialog:false
    }

  },
  methods:{
    cancel() {
      console.log("cancel");
      this.showDialog=false;
    },
    confirm() {
      console.log("confirm");
      this.showDialog=false;
    },
    showDia() {
      console.log("show dialog");
      this.showDialog=true;
    }
  }
};
</script>



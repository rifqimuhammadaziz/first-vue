<template>
  <div id="nav">
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/profile">Profile</router-link> |
    <router-link to="/about">About</router-link> -->
    <div class="container">
      <div class="row header mb-5 p-3">
        <div class="col-12">
          <h2>What I do Today?</h2>
        </div>
      </div>
      <div class="row content text-start">
        <div class="col-lg-4">
          <div class="this-is-task mb-3" v-for="myTask in task" v-bind:key="myTask.id">
            <div class="form-check">
              <ItemTask v-bind:myTask="myTask" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <!-- <router-view/> -->
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import ItemTask from "./components/ItemTask.vue";


export default {
  name: "app",
  data: function() {
    return {
      task: [
        {
          id: 1,
          name: "Membersihkan kamar mandi",
          isDone: false
        },
        {
          id: 2,
          name: "Memandikan kucing",
          isDone: false
        },
        {
          id: 3,
          name: "Prepare BCA Hackathon",
          isDone: false
        },
      ]
    }
  },
  components: {
    ItemTask
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
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.header {
  background-color: #1abc9c;
}
.header .h2 {
  margin: 0;
}
.this-is-task .item{
  font-size: 20px;
}
.item-completed {
    color: #1abc9c;
}
</style>

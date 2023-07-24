<template>
  <router-view />
</template>

<script>
import Login from './views/Login.vue'
import Register from './views/Register.vue'
import Main from './views/Main.vue'

export default {
  components: {
    Login,
    Register,
    Main,
  },
  data() {
    return {
      authenticated: false,
      home: 1,
      user: null,
      firebaseConfig: {
        apiKey: "AIzaSyAKzBQ7M5swyszSTff81637vkx2iZp0gE4",
        authDomain: "my-web-app-868a4.firebaseapp.com",
        projectId: "my-web-app-868a4",
        storageBucket: "my-web-app-868a4.appspot.com",
        messagingSenderId: "638728251568",
        appId: "1:638728251568:web:d4f7a1c13bc8cffb88f375"
      },
    }
  },

}
</script>

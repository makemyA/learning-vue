<template>
  <div>
    <h1> {{message}}</h1>
    <h2>Hello {{person.firstname}} {{person.lastname}}</h2>
    <label> FirstName <input type="text" v-model= "person.firstname"/></label>
    <label> LastName <input type="text" v-model= "person.lastname"/></label>
    <label> Message <input type="text" v-model= "message"/></label>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String
  },
  data () {
    return {
      person: {
        firstname: '',
        lastname: ''  
      },
      message: 'Welcome!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

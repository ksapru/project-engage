 <template>
  <div class="hello">

 
    
 
    <h1> User Login </h1>
    <h3> Username: </h3>  
    <h3> Password: </h3> <button type="button" v-on:click="login()">Login</button>


  <md-content md-theme="selection-orange">
      <p>Also works when the theme is dark.</p>
    </md-content>
  </div>
 
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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


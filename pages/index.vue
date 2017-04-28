<template>
  <section class="section">
    <div class="container">
      <div class="columns is-multiline is-flex-mobile is-flex-tablet">
        <div class="column is-half is-offset-one-quarter images">
          <img :src="image" />
          <div class="column is-half is-offset-one-quarter">
            <a class="button is-success">ซ่อมรถยนต์</a><br/>
            <a class="button is-warning second">ซ่อมรถมอไซต์</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import 'bulma/css/bulma.css'

export default {
  name: 'app',
  data () {
    return {
      image: 'zomdai.jpg'
    }
  }
}
</script>

<style>
.second
{
  top:10px;
  left:-2px;
}

.images
{
  margin-bottom:200px;
  align:center;
  width:inherit;
  height:inherit;
}

.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>

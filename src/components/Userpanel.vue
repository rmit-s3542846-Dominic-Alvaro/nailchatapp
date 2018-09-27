<template>
    <aside class="column is-2 aside hero is-fullheight">
      <div>
          <!-- <div class="compose has-text-centered">
              <a class="button is-danger is-block is-bold">
                <span class="compose">Compose</span>
              </a>
          </div> -->
          <div class="main">
              <a v-on:dblclick = "createACunt('cunt')" href="#" class="item"><span class="icon"><i class="fa fa-inbox"></i></span><span class="name">Aiden</span></a>
              <a href="#" class="item"><span class="icon"><i class="fa fa-star"></i></span><span class="name">Dominic</span></a>
              <a href="#" class="item"><span class="icon"><i class="fa fa-envelope-o"></i></span><span class="name">Homy</span></a>
              <a href="#" class="item active"><span class="icon"><i class="fa fa-folder-o"></i></span><span class="name">Miranda</span></a>
          </div>
      </div>
  </aside>
</template>

<script>
export default {
 
  methods: {
    createACunt(cuntsName) {
      console.log(cuntsName)
    }
  }
}
</script>

<style scoped>
.aside {
  display:block;
  background-color:#6895fc;
  border-right: 1px solid #DEDEDE;
}

.aside .compose {
  height: 95px;
  margin:0 -10px;
  padding: 25px 30px;
}
.aside .compose .button {
  color: #F6F7F7;
}
.aside .compose .button .compose {
  font-size: 14px;
  font-weight: 700;
}
.aside .main {
  padding: 40px;
  color: white;
}
.aside .title {
  color: white;
  font-size: 12px;
  font-weight: bold;
  text-transform: uppercase;
}
.aside .main .item {
  display: block;
  padding: 12px;
  color: #5D5D5D;
  /*Displaying users ontop of each other*/
}
.aside .main .item.active {
  background-color: #4c7aed;
  margin: 0 -50px;
  padding-left: 60px;
  color: black;
  /*Currecntly selected user (active)*/
}
.aside .main .item:active,.aside .main .item:hover {
  background-color:#fc5577;
  margin: 0 -50px;
  padding-left: 70px;
  /*This is hovering tool to choose user*/
}
.aside .main .icon {
  font-size: 20px;
  padding-right: 30px;
  color: white;
  /* This is where it styles the icon next to the users which will be profile pic */
}
.aside .main .name {
  font-size: 20px;
  color: white;
  font-weight: 500;
  /* this is where u can adjust text for users */
}
</style>


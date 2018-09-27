<template>
    <aside class="column is-2 aside hero is-fullheight">
      <div>
          <div class="compose has-text-centered">
              <a class="button is-danger is-block is-bold">
                <span class="compose">Compose</span>
              </a>
          </div>
          <div class="main">
              <a href="#" class="item"><span class="icon"><i class="fa fa-inbox"></i></span><span class="name">Aiden</span></a>
              <a href="#" class="item"><span class="icon"><i class="fa fa-star"></i></span><span class="name">Dominic</span></a>
              <a href="#" class="item"><span class="icon"><i class="fa fa-envelope-o"></i></span><span class="name">Homy</span></a>
              <a href="#" class="item active"><span class="icon"><i class="fa fa-folder-o"></i></span><span class="name">Miranda</span></a>
          </div>
      </div>
  </aside>
</template>

<script>
export default {
    
}
</script>

<style>
.aside {
  display:block;
  background-color: #F9F9F9;
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
  color: #6F7B7E;
}
.aside .title {
  color: #6F7B7E;
  font-size: 12px;
  font-weight: bold;
  text-transform: uppercase;
}
.aside .main .item {
  display: block;
  padding: 10px 0;
  color: #6F7B7E;
  /*Displaying users ontop of each other*/
}
.aside .main .item.active {
  background-color: #F1F1F1;
  margin: 0 -50px;
  padding-left: 50px;
  /*Currecntly selected user (active)*/
}
.aside .main .item:active,.aside .main .item:hover {
  background-color: #F2F2F2;
  margin: 0 -50px;
  padding-left: 50px;
  /*This is hovering tool to choose user*/
}
.aside .main .icon {
  font-size: 19px;
  padding-right: 30px;
  color: #A0A0A0;
  /* This is where it styles the icon next to the users which will be profile pic */
}
.aside .main .name {
  font-size: 15px;
  color: #5D5D5D;
  font-weight: 500;
  /* this is where u can adjust text for users */
}
</style>


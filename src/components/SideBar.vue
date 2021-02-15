<template>
<div class="side-bar">
    <div class="side-bar-header">
          <img src="../assets/img/logo.svg"/>
    </div>
    <ul class="list-group">
        <li class="list-group-item list-item"><img src="../assets/icons/Plus.svg" ><a href="/">Orders</a><span class="counters">13</span></li>
        <li class="list-group-item list-item"><img src="../assets/icons/Document.svg" ><a href="/">Clients</a><span class="counters">27</span></li>
        <li class="list-group-item list-item"><img src="../assets/icons/Game.svg" ><a href="/">Loyalty program</a></li>
        <li class="list-group-item list-item"><img src="../assets/icons/Discovery.svg" ><a href="/">Online</a></li>
        <li class="list-group-item list-item"><img src="../assets/icons/MoreSquare.svg" ><a href="/">Chats</a><span class="counters">2</span></li>
        <li class="list-group-item list-item"><img src="../assets/icons/Chart.svg" ><a href="/">Reports</a></li>
        <li class="list-group-item list-item "><img src="../assets/icons/Setting.svg" ><a href="/">Settings</a></li>
    </ul>
</div>
</template>

<script>
export default {
name: "SideBar"
}
</script>

<style scoped>
.side-bar{
  background: #30303A;
  height: 100vh;
}
.side-bar-header{
  text-align: center;
  background: #4257D0;
  padding:10px 0;
  height:50px;
  margin-bottom: 20px;
}
.list-item{
  border-left:3px solid transparent;
  border-radius: 0 !important;
  border-bottom: none;
  border-top: none;
  background: none;
  font-weight: lighter;
  margin-left: 15px;
  padding:8px 20px;
  color:#fff;
}

.list-item:last-child{
  position: absolute;
  bottom:10px;
  left: 0;
  padding-left:40px;
  width: 100%;
  margin-left:0;

}
.list-item a{
  text-decoration: none;
  color:#fff;
  font-size: 14px;
  margin-left: 10px;

}
.list-item:hover{
  border-left:3px solid blue;
  transition: .4s;
  background: #2A2A31;
}
.counters{
  width:24px;
  height: 22px;
  background: #D87575;
  border-radius: 5px;
  font-size: 13px;
  display: inline-block;
  vertical-align: center;
  padding-top:2px ;
  text-align: center;
  position: absolute;
  right:20px;
}

</style>
<template>

  <div class="container-fluid conteiner">
    <div class="row myRow">
      <div class="col-2">
        <SideBar/>
      </div>
      <div class="col-10">
        <MainPage/>
      </div>
    </div>



  </div>
</template>

<script>
import SideBar from "@/components/SideBar";
import MainPage from "@/components/MainPage";
export default {
  name: 'HomePage',
  components: {
    SideBar,
    MainPage

  }
}
</script>

<style scoped>

.conteiner{
  padding-left: 0;
  background: #F2F6FA;
}
.myRow>*{
  padding-left: 0;
  padding-right: 0;
}
</style>
<template>
<tr>
  <td><input type="checkbox"/></td>
  <td class="name-info"><span>T</span>Tomas Levins</td>
  <td>996550425563</td>
  <td>VIP</td>
  <td>19.01.2021</td>
  <td>999999</td>
  <td>43989898</td>
</tr>
</template>

<script>

export default {
  name: "OrderItem"
}
</script>

<style scoped>

tr td{
  font-size: 14px;
  border-top:none;
  border-bottom:1px solid #dee2e6;
  vertical-align: middle;
}
tr:hover{
  background: #F8F9FF;

}
.name-info span{
  width:30px;
  height:30px;
  border-radius:30px;
  background: #B2BDFD;
  margin-right: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.name-info{
  display: flex;
  align-items: center;
  margin-bottom: -1px;
}
</style>
<template>
  <div id="app">
    <el-row>
      <el-col :span="6"><div id="nav"></div></el-col>
      <el-col :span="18">
        <el-header>前台</el-header>
        <el-main>aaaaaaaaaaaaaaaaa</el-main>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
</style>
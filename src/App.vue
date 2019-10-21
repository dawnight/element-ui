<template>
  <div id="app">
    <el-row>
      <el-col :span="8">
        <h3>这是第一块区域</h3>
      </el-col>
      <el-col :span="8">
        <h3>这是第二块区域</h3>
      </el-col>
      <el-col :span="8">
        <h3>这是第一块区域</h3>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import ElRow from './components/el-row';
import ElCol from './components/el-row';
export default {
  name: 'app',
  components: {
    ElRow,
    ElCol
  }
}
</script>

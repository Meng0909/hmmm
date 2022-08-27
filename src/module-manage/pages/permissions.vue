<template class="userrs">
  <div class="users">
    <div>
      <el-form :inline="true" :model="formInline" class="demo-form-inline">
        <el-form-item>
          <el-input placeholder="根据用户名搜索"></el-input>
        </el-form-item>
        <el-form-item>
          <el-button type="primary" class="box">清空</el-button>
          <el-button type="primary">搜索</el-button>
        </el-form-item>
      </el-form>
      <el-button type="success" class="el-icon-edit">新增用户</el-button>
      <div>
        <el-alert class="el-icon-info" title="消息提示的文案"> </el-alert>
      </div>
      <el-table style="width: 100%">
        <el-table-column type="index" width="100"> </el-table-column>
        <el-table-column property="date" label="序号" width="200">
        </el-table-column>
        <el-table-column property="name" label="邮箱" width="100">
        </el-table-column>
        <el-table-column property="address" label="联系电话" width="300">
        </el-table-column>
        <el-table-column property="address" label="用户名" width="100">
        </el-table-column>
        <el-table-column property="address" label="权限组名称" width="300">
        </el-table-column>
        <el-table-column property="address" label="角色" width="100">
        </el-table-column>
        <el-table-column property="address" label="操作"> </el-table-column>
      </el-table>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },

  created() {},

  methods: {},
};
</script>

<style scoped lang="less">
.userrs {
  background-color: #f0f2f5;
}
.users {
  background-color: #fff;
}
.box {
  color: #000;
  background-color: #fff;
}
</style>
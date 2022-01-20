<template>
  <div class="login">
    <el-form class="login-form el-form-item">
      <h3 class="title">若依后台管理系统</h3>
      <el-form-item >
        <el-input class="el-input" type="text" auto-complete="off" placeholder="账号">
        </el-input>
        <el-input class="el-input" type="text" auto-complete="off" placeholder="密码">
        </el-input>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.login {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  background-image: url("../assets/images/login-background.jpg");
  background-size: cover;
}

.login-form {
  border-radius: 6px;
  background: #ffffff;
  width: 400px;
  padding: 25px 25px 5px 25px;

  .el-input {
    height: 38px;

    input {
      height: 38px;
    }
  }

  .input-icon {
    height: 39px;
    width: 14px;
    margin-left: 2px;
  }
}

.title {
  margin: 0px auto 30px auto;
  text-align: center;
  color: #707070;
}

.el-form-item {
  margin-bottom: 22px;
}
</style>

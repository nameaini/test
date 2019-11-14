<template>
    <div class="login_container">
        <div class="login_box">
            <!-- 头像区 -->
            <div class="avatar_box">
                <img src="../assets/audi-galerie-4.jpg" alt="">
            </div>
            <!-- 登录表单区 -->
            <el-form  label-width="80px">
                <el-form-item label="活动名称">
                  <el-input ></el-input>
                </el-form-item>
                </el-form>
        </div>
    </div>
</template>
<script>
export default {
    

}
</script>

<style lang="less" scoped>
    .login_container {
        background-color: #14bF75;
        height: 100%;
    }
    .login_box {
        width: 450px;
        height: 300px;
        background-color: #fff;
        border-radius: 3px;
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%,-50%);
        box-shadow: 0 0 15px yellow;

        .avatar_box {
            height: 130px;
            width: 130px;
            border:1px solid #ccc;
            border-radius: 50%;
            padding: 10px;
            box-shadow: 0 0 10px skyblue;
            position: absolute;
            left: 50%;
            transform: translate(-50%,-50%);
            background-color: yellowgreen;
            img {
                width: 100%;
                height: 100%;
                border-radius: 50%;
                background-color: #eee;
            }
        }
    }
</style>
<template>
    <div>
        <el-form :label-position="left" label-width="80px" :model="userInfo">
            <h2>用户登陆</h2>
            <el-form-item label="账号">
                <el-input v-model="userInfo.userName"></el-input>
            </el-form-item>
            <el-form-item label="密码">
                <el-input v-model="userInfo.uPwd"></el-input>
            </el-form-item>
            <el-button type="primary" disabled>主要按钮</el-button>
        </el-form>
    </div>
</template>

<script>
export default {
    data() {
        return {
            labelPosition: 'right',
            formLabelAlign: {
                userName: '',
                uPwd: '',
            }
        };
    }
}
</script>

<style>

</style>

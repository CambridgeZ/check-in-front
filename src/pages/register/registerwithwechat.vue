<template>
    <div>
        <h1>登录</h1>
        <button @click="loginWithWeChat">使用微信账号登录</button>
    </div>
</template>

<script>
export default {
    methods: {
        name : "registerwithwechat",
        loginWithWeChat() {
            // 在这里编写使用微信账号登录的逻辑
            // 调用微信登录接口，获取用户信息等操作
            // ...
            // 登录成功后，跳转到首页
            
        }
    }
}
</script>

<style scoped>
h1 {
    text-align: center;
}
button {
    margin: 20px auto;
    display: block;
    color : #1AAD19;
}
</style>

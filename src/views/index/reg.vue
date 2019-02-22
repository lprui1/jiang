<template>
    <div class="reg-container">
        <div class="reghead"></div>
        <div class="regmain">
            <div class="logo">
                <p><img src="../../assets/images/logo.jpg" alt=""></p>
                <p>会员商店</p>
                <div class="reg">手机号码注册</div>
            </div>
            <!--表单-->
            <div class="msg">
                <ul>
                    <li>
                        <input type="text" name="" id="" placeholder="请输入用户名">
                    </li>
                    <li>
                        <input type="text" name="" id="" placeholder="请输入验证码">
                    </li>
                    <li>
                        <input type="text" placeholder="请输入密码">
                    </li>
                </ul>
            </div>
            <!--同意协议与按钮-->
            <div class="xieyi">
                <div class="agree">
                    <p><i class="el-icon-circle-check" :class="{che:!isShow,no:isShow}" @click="isShow=!isShow"></i></p>
                    <p>我已经阅读并同意<a href="#">服务声明</a></p>
                </div>
                <!-- 登录按钮 -->
                <p><button>登录</button></p>
            </div>
        </div>
        
        
    </div>
    
    
</template>

<script>
export default {
    data() {
        return {
            isShow:true
        }
    },
    methods: {
        

    }
}
</script>

<style scoped lang="scss">
    .che{
        color:#ccc;
    }
    .no{
        color:#00c05b;
    }
    
</style>

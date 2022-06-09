<template>
    <div class="header-container">
        <div class="banner">
            <div>
                <span>Shoppe欢迎您！</span>
                <span>请</span><span>登陆</span><span>免费注册</span>
            </div>
            <div class="typeList">
                <a href="###">我的订单</a>
                <a href="###">我的购物车</a>
                <a href="###">我的尚品汇</a>
                <a href="###">尚品汇会员</a>
                <a href="###">企业采购</a>
                <a href="###">关注尚品汇</a>
                <a href="###">合作招商</a>
                <a href="###">商家后台</a>
            </div>
        </div>
        <div class="search"></div>
    </div>
</template>
<script>
export default {
    name: "Header"
}
</script>
<style scoped lang="less">
.header-container {
    .banner {
        display: flex;
        justify-content: space-between;

        .typeList a {
            margin-left: 5px;
        }
    }
}
</style>
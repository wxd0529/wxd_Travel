<template>
    <div class="header">
        <div class="header-left">
            <div class="iconfont back-icon">&#xe624;</div>
        </div>
        <div class="header-input">
            <span class="iconfont">&#xe632;</span>
            输入城市/景点/游玩主题
        </div>
        <div class="header-right">
            城市
            <span class="iconfont arrow-icon">&#xe64a;</span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>
<!--scoped 用宇限制使用css样式的组件为当前组件 -->
<!--1rem = html font-size = 50px -->
<!--@b表示src 如果需要在css中引入别的css样式需要在@前面加一个~-->
<style lang="stylus" scoped>
    @import '~styles/varibles.styl'
    .header
        display: flex
        line-height: .86rem
        background: $bgColor
        color: #fff
    .header-left
        width: .64rem
        float: left
        .back-icon
            text-align: center
            font-size: .4rem
    .header-input
        flex: 1
        margin-top: .12rem
        margin-left: .2rem
        padding-left: .2rem
        line-height: .64rem
        height: .64rem
        background: #ffffff
        border-radius: .1rem
        color: #ccc
    .header-right
        width: 1.24rem
        float: right
        text-align: center
        .arrow-icon
            margin-left: -.04rem
            font-size: .24rem
</style>

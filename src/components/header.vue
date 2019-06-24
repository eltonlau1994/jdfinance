<template>
    <div :class="$style.header">
        <span :class="$style.left">
            <em>註冊</em>&nbsp;|&nbsp;<em>登錄</em>
        </span>
        <btn :class="$style.btnDownload">APP 下載</btn>
    </div>
</template>

<script>
import btn from '@/components/core/btn.vue';
export default {
    components:{
        btn
    },

}
</script>

<style lang="scss" module>
    .header {
        color: #666;
        height: 100px;
        line-height: 100px;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        font-size: 32px;
        background: #fff url(https://sourcingjournal.com/wp-content/uploads/2015/10/3170-toubau.jpg) center center no-repeat;
        background-size: auto 50%;
        z-index: 100;
        .left {
            font-size: 20px;
            height: 30px;
            height: 30px;
            margin: 17px 0 0 18px;
        }
        .btnDownload {
            float: right;
            font-size: 24px;
            border-width: 0;
            height: 56px;
            line-height: 56px;
            min-width: 120px;
            padding: 0;
            border-radius: 4px;
            margin: 28px 24px 0 0;
        }
    }
</style>

<template>
  <div class="m-header">
      <div class="icon"></div>
      <div class="text">Vue Music</div>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
}
</script>
<style scoped lang="less">
    @import '../../common/less/variable.less';

    .m-header{
        position: relative;
        height: 44px;
        text-align: center;
        color: #999;
        font-size :0;
        .icon{
            display :inline-block;
            vertical-align :top;
            margin-top: 6px;
            width:30px;
            height:32px;
            margin-right: 9px;
            background-image :url('logo.png');
            background-size:30px 32px;
        }
        .text{
            display :inline-block;
            vertical-align :top;
            line-height :44px;
            font-size: 28px;
        }
        .mine{
            position: absolute;
            top: 0;
            right: 0;
            .icon-mine{
                display: block;
                padding: 12px;
                font-size: 20px;
                color: #999;
            }
        }
    }
</style>
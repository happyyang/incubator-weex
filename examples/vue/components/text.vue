<template>
  <scroller>
    <panel title="color" type="primary">
      <text class="txt">default is black</text>
      <text class="txt" style="color:#286090">#286090</text>
      <text class="txt" style="color:#0f0">#0f0</text>
      <text class="txt" style="color:red">keyword</text>
      <text class="txt" style="color:rgb(238, 162, 54)">rgb(238, 162, 54)</text>
      <text class="txt" style="color:rgba(238, 162, 54, 0.5)">rgba(238, 162, 54, 0.5)</text>
    </panel>
    <panel title="font-size" type="primary">
      <text class="txt" style="font-size: 32px;">32</text>
      <text class="txt" style="font-size: 64px;">64</text>
      <text class="txt" style="font-size: 100px;">100</text>
    </panel>
    <panel title="font-style" type="primary">
      <text class="txt" style="font-style: normal">normal</text>
      <text class="txt" style="font-style: italic">italic</text>
    </panel>
    <panel title="font-weight" type="primary">
      <text class="txt" style="font-weight: normal">normal</text>
      <text class="txt" style="font-weight: bold">bold</text>
    </panel>
    <panel title="text-decoration" type="primary">
      <text class="txt" style="text-decoration: none">none</text>
      <text class="txt" style="text-decoration: underline">underline</text>
      <text class="txt" style="text-decoration: line-through">line-through</text>
    </panel>
    <panel title="text-align" type="primary">
      <text class="txt" style="text-align: left">left</text>
      <text class="txt" style="text-align: center">center</text>
      <text class="txt" style="text-align: right">right</text>
    </panel>
    <panel title="text-overflow" type="primary">
      <text class="txt" style="lines:1">no text-overflow, no text-overflow</text>
      <text class="txt" style="text-overflow:clip;width:450px;lines:1">text-overflow: clip, text-overflow: clip</text>
      <text class="txt" style="text-overflow:ellipsis;width:450px;lines:1">text-overflow: ellipsis, text-overflow: ellipsis</text>
    </panel>
    <panel title="line-height" type="primary">
      <text class="txt">no lineheight setting</text>
      <text class="txt" style="line-height: 50">lineheight 50</text>
      <text class="txt" style="line-height: 80"> lineheight 80</text>
    </panel>
  </scroller>
</template>

<style>
  .txt {
    margin-bottom: 12px;
    font-size: 40px;
  }
</style>

<script>
  module.exports = {
    components: {
      panel: require('../include/panel.vue')
    }
  }
</script>

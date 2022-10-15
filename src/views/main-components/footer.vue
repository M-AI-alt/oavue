<template>
  <div class="foot">
    <Row type="flex" justify="space-around" class="help">
      <a class="item" href="" target="_blank">CSDN</a>
      <a class="item" href="" target="_blank">码云</a>
      <a class="item" href="" target="_blank">B站</a>
    </Row>
    <Row type="flex" justify="center" class="copyright">
      民师院数计院 物联网工程181
      <a
        href=""
        target="_blank"
        style="margin:0 5px;"
      >宁飞</a>
    </Row>
  </div>
</template>

<script>
export default {
  name: "footer"
};
</script>

<style lang="less">
.foot {
  width: 100%;
  margin-top: 5vh;
  margin-bottom: 3vh;
  color: rgba(0, 0, 0, 0.45);
  font-size: 18px;
  .help {
    margin: 0 auto;
    margin-bottom: 1vh;
    width: 60%;
    .item {
      color: rgba(0, 0, 0, 0.45);
    }
    :hover {
      color: rgba(0, 0, 0, 0.65);
    }
  }
}
</style>

<template>
  <footer id="the-footer">
    <div class="container">
      <div class="row">
        <div class="col-sm-6">
          Powered by Spectrum Branch
        </div>
        <div class="col-sm-6">
          © 2019 Copyright
        </div>
      </div> 
    </div>
  </footer>
</template>

<script>
export default {
  name: 'theFooter',
  props: {
    msg: String
  }
}
</script>

<style lang="less">
@import '~../less/variables.less';

#the-footer{
  background-color: @bgcolor;
  padding: 10px 0px;
}
</style>
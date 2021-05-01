<template>
  <div>
    <div style="background: transparent;height: 100px;">
      12312312
      <pdf
        ref="pdf"
        :src="url"
        style="z-index: -1"
      >
      </pdf>
    </div>
  </div>
</template>

<script>
import pdf from 'vue-pdf'
export default {
  components: {
    pdf
  },
  data: function () {
    return {
      url: 'https://dakaname.oss-cn-hangzhou.aliyuncs.com/file/2018-12-28/1546003237411.pdf'
    }
  }
}
</script>

<style>

</style>

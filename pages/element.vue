<template>
  <div style="padding: 30px;">
  <el-button @click="visible=true">ダイアログを開く</el-button>
  <el-dialog :visible.sync="visible" title="確認">
    <p>処理されました</p>
  </el-dialog>
  <el-row>
  <el-button>Default</el-button>
  <el-button type="primary">Primary</el-button>
  <el-button type="success">Success</el-button>
  <el-button type="info">Info</el-button>
  <el-button type="warning">Warning</el-button>
  <el-button type="danger">Danger</el-button>
</el-row>

  </div>
</template>

<script>
export default {
  data: function() {
    return {
      visible: true
    }
  }
}
</script>
<script setup lang="ts">
import { onLaunch, onShow, onHide } from "@dcloudio/uni-app";
onLaunch(() => {
  console.log("App Launch");
});
onShow(() => {
  console.log("App Show");
});
onHide(() => {
  console.log("App Hide");
});
</script>
<style>
page {
  width: 100%;
  height: 100%;
}

.flex {
  display: flex;
}

.flex_c {
  display: flex;
  flex-direction: column;
}
</style>

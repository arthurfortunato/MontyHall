<template>
  <div class="gift">
    <div class="gift-bow-H"></div>
    <div class="gift-bow-V"></div>
    <div class="gift-cover"></div>
    <div class="gift-body"></div>
  </div>
</template>

<script>
export default {
  name: "Gift",
};
</script>

<style>
.gift {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  z-index: 10;
}

.gift-cover {
  width: 100px;
  height: 25px;
  background-color: #7aa944;
}

.gift-body {
  width: 90px;
  height: 60px;
  background-color: #5c7e32;
}

.gift-bow-V {
  position: absolute;
  width: 15px;
  height: 85px;
  background-color: red;
  border-radius: 3px;
}

.gift-bow-H {
  position: absolute;
  top: 40px;
  width: 90px;
  height: 15px;
  background-color: red;
  border-radius: 3px;
}
</style>
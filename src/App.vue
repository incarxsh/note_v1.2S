<template>
    <div id="app">
        <router-view />
    </div>
</template>

<script>
export default {}
</script>

<style lang="less">
body {
    color: #515a6e;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    font-weight: normal;
}

.header {
    position: fixed;
    width: 100%;
    height: 50px;
    line-height: 50px;
    z-index: 901;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .08);

    .h2 {
        font-size: 18px;
        text-align: center;
    }
}

.cont {
  position: relative;
  top: 50px;
}
</style>

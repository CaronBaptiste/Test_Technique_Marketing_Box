<template>
  <header class="bcg paddingZero">
    <container>
      <row>
        <div> </div>
        <div class="bcg paddingZer">
          <p style="background-color: red" class="hw">  </p>
        </div>
        <div> </div>
      </row>
    </container>
  </header>
</template>

<script>
export default {
  name: "HeaderList",
};
</script>

<style scoped>
.paddingZero {
  padding: 0px;
}
.padding {
  padding-left: 1em;
  padding-right: 1em;
}
.bcg {
  background-color: blue;
  height: 6em;
}

.hw {
  height: 6em;
}
</style>

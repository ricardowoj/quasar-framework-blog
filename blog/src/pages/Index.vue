<template>
  <q-page class="container">
    <div class="row justify-center q-gutter-sm q-mt-md">
      <div class="col-xs-12 col-sm-9 col-md-3">
        <q-btn class="full-width shadow-up-24" color="dark" label="Button" />
      </div>
      <div class="col-xs-12 col-sm-9 col-md-3">
        <q-btn class="full-width" color="dark" label="Button" push glossy />
      </div>
      <div class="col-xs-12 col-sm-9 col-md-3">
        <q-btn class="full-width" color="dark" label="Button" />
      </div>
    </div>
  </q-page>
</template>

<style lang="stylus">
.border-black {
  border: 1px solid black;
}
</style>

<script lang="ts">
export default {
  name: "pageIndex",
};
</script>

<template>
  <div>
    <h1 class="mb-5">詳細表示</h1>

    <b-row class="detail">
      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">値4</b-col>
      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">値4</b-col>

      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">値4</b-col>
      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">値4</b-col>

      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">
        値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4,
        値4, 値4, 値4, 値4, 値4, 値4,
      </b-col>
      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">
        値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4,
        値4, 値4, 値4, 値4, 値4, 値4,
      </b-col>

      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="4" class="value">
        値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4, 値4,
        値4, 値4, 値4, 値4, 値4, 値4,
      </b-col>

      <div class="divider"></div>

      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="10" class="value">値10</b-col>

      <b-col cols="2" class="label">ラベル2：</b-col>
      <b-col cols="10" class="value"
        >値10, 値10, 値10, 値10, 値10, 値10, 値10, 値10, 値10, 値10, 値10, 値10,
        値10, 値10, 値10, 値10, 値10,
      </b-col>
    </b-row>
  </div>
</template>

<style lang="scss" scoped>
.row.detail {
  .label,
  .value {
    margin: 10px 0;

    /* 枠を付けて見てみよう */
    /* border: solid 1px; */
  }
  .label {
    padding-right: 0;
    text-align: right;
    font-weight: bold;
  }
  .value {
    padding-left: 5px;
  }
  .divider {
    width: 100%;

    /* 枠を付けて見てみよう */
    /* border: solid 1px; */
  }
}
</style>

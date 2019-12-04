<template>
  <div class="OtherIncome">
    <b-row>
      <b-col cols="2">
        <b-form-group label="รายได้่จาก" label-align="left"> </b-form-group>
      </b-col>
      <b-col>
        <b-form-input> </b-form-input>
      </b-col>
      <b-col cols="6"></b-col>
    </b-row>
    <b-row>
      <b-col cols="2">
        <b-form-group label="จำนวน" label-align="left"> </b-form-group>
      </b-col>
      <b-col cols="2">
        <b-input-group>
          <b-form-input> </b-form-input>
        </b-input-group>
      </b-col>
      <b-col cols="1">
          <b-form-group label="บาท/เดือน"> </b-form-group>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: 'OtherIncome',
  props: {
    name: String,
    bio: String
  }
};
</script>

<style scoped></style>

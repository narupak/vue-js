<template>
  <div class="RegularIncome">
    <b-form @submit="onSubmit" @reset="onReset" v-if="show">
      <div class="">
        <b-row>
          <b-col cols="2"
            ><b-form-group
              id="input-group-1"
              label="เงินเดือน"
              label-align-lg="left"
              class="mb-0"
            ></b-form-group
          ></b-col>
          <b-col cols="7">
          </b-col>
          <b-col cols="2">
             <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
            </b-col>
          <b-col cols="1">
            <b-form-group
                  id="input-group-1"
                  label="บาท/เดือน"
                ></b-form-group>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="2"
            ><b-form-group
              id="input-group-1"
              label="ค่าตอบแทนประจำเดือน"
              label-align-lg="left"
              class="mb-0"
            ></b-form-group
          ></b-col>
          <b-col cols="7"></b-col>
          <b-col cols="2"
            >
          <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
          </b-col>
          <b-col cols="1">
             <b-form-group
                  id="input-group-1"
                  label="บาท/เดือน"
                ></b-form-group>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="2"
            ><b-form-group
              id="input-group-1"
              label="รายได้แปรผัน เฉลี่ย"
              label-align-lg="left"
              class="mb-0"
            ></b-form-group
          ></b-col>
          <b-col cols="1">
            <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
              <b-input-group>
                
               
              </b-input-group>
          </b-col>
          <b-col cols="1"> <b-form-group
                  id="input-group-1"
                  label="เดือน"
                ></b-form-group>
          </b-col>
          <b-col cols="5">
          </b-col>
          <b-col cols="2">
             <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
          </b-col>
          <b-col cols="1">
                            <b-form-group
                  id="input-group-1"
                  label="บาท/เดือน"
                ></b-form-group>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="2"
            ><b-form-group
              id="input-group-1"
              label="รายได้แปรผัน เฉลี่ย"
              label-align-lg="left"
              class="mb-0"
            ></b-form-group
          ></b-col>
          <b-col cols="1">
            <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
              <b-input-group>
                
               
              </b-input-group>
          </b-col>
          <b-col cols="1"> <b-form-group
                  id="input-group-1"
                  label="เดือน"
                ></b-form-group>
          </b-col>
          <b-col cols="5">
             <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
          </b-col>
          <b-col cols="2">
             <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
          </b-col>
          <b-col cols="1">
                            <b-form-group
                  id="input-group-1"
                  label="บาท/เดือน"
                ></b-form-group>
          </b-col>
        </b-row>
        <b-row>
          <b-col cols="2"></b-col>
          <b-col cols="1"></b-col>
          <b-col cols="1"> <b-form-group
                  id="input-group-1"
                  label="รายได้รวม"
                ></b-form-group>
          </b-col>
          <b-col cols="5"></b-col>
          <b-col cols="2">
             <b-form-input
                  id="input-1"
                  v-model="form.salary"
                  type="number"
                  required
                  placeholder="0"
                ></b-form-input>
          </b-col>
          <b-col cols="1">
                <b-form-group
                  id="input-group-1"
                  label="บาท/เดือน"
                ></b-form-group>
          </b-col>
        </b-row>
      </div>
    </b-form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      form: {
        salary: 0,
        salaryMonth: 0
      },
      show: true
    };
  }
};
</script>

<style scoped></style>

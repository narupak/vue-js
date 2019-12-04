<template>
  <div id="app">
    <b-card no-body>
      <b-tabs card>
        <b-tab title="ข้อมูลหลัก" active>
          <b-card-text><h3>ข้อมูลหลัก</h3></b-card-text>
        </b-tab>
        <b-tab title="สถานภาพสมรส">
          <b-card-text><h3>สถานภาพสมรส</h3></b-card-text>
        </b-tab>
        <b-tab title="ที่อยู่" active>
          <b-card-text><h3>ที่อยู่</h3></b-card-text>
        </b-tab>
        <b-tab title="รายได้">
          <div style="text-align:left;">
            <b-form-checkbox
              id="checkbox-1"
              v-model="status"
              name="checkbox-1"
              value="accepted"
              unchecked-value="not_accepted"
            >
              รายได้ประจำ
            </b-form-checkbox>
          </div>
          <b-card bg-variant="light">
          <RegularIncome></RegularIncome>
          </b-card>
          <div style="text-align:left;">
            <b-form-checkbox
              id="checkbox-1"
              v-model="status"
              name="checkbox-1"
              value="accepted"
              unchecked-value="not_accepted"
            >
              รายได้จากวิชาชีพเฉพาะ/วิชาอิสระ
            </b-form-checkbox>
          </div>
          <b-card bg-variant="light">
          <ProfessionalIncome></ProfessionalIncome>
          </b-card>
          <div style="text-align:left;">
            <b-form-checkbox
              id="checkbox-1"
              v-model="status"
              name="checkbox-1"
              value="accepted"
              unchecked-value="not_accepted"
            >
              รายได้จากธุรกิจส่วนตัว/หุ้นส่วน
            </b-form-checkbox>
          </div>
          <b-card bg-variant="light">
          <PersonnalBusinessIncome></PersonnalBusinessIncome>
          </b-card>
          <div style="text-align:left;">
            <b-form-checkbox
              id="checkbox-1"
              v-model="status"
              name="checkbox-1"
              value="accepted"
              unchecked-value="not_accepted"
            >
              รายได้อื่นๆ (ถ้ามี)
            </b-form-checkbox>
          </div>
          <b-card bg-variant="light">
          <OtherIncome></OtherIncome>
          </b-card>
        </b-tab>
        <b-tab title="เอกสารแนบ">
          <b-card-text>เอกสารแนบ</b-card-text>
        </b-tab>
      </b-tabs>
    </b-card>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
//import User from './components/User.vue';
import RegularIncome from './components/RegularIncome.vue';
import ProfessionalIncome from './components/ProfessionalIncome.vue';
import PersonnalBusinessIncome from './components/PersonnalBusinessIncome.vue';
import OtherIncome from './components/OtherIncome.vue';
import Vue from 'vue';
import BootstrapVue from 'bootstrap-vue';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';
import { FormGroupPlugin } from 'bootstrap-vue'

Vue.use(BootstrapVue);
Vue.use(FormGroupPlugin);
export default {
  name: 'app',
  components: {
    //User
    RegularIncome,
    ProfessionalIncome,
    PersonnalBusinessIncome,
    OtherIncome
  },
  methods: {}
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
/* Style the tab */
</style>

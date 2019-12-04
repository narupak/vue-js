<template>
    <div class="PersonnalBusinessIncome">
         <div>
             <b-row>
                 <b-col cols="2">
                     <b-form-group
                     label="ลักษณะธุรกิจ"
                     label-align-lg="left">
                     </b-form-group>
                 </b-col>
                 <b-col cols="4">
                     <b-form-input>
                     </b-form-input>
                 </b-col>
                 <b-col></b-col>
                 <b-col></b-col>
             </b-row>
             <b-row>
                 <b-col cols="4">
                     <b-form-group
                     label="สัดส่วนการถือหุ้น"
                     label-align-lg="left">
                     </b-form-group>
                 </b-col>
                 <b-col cols="2">
                     <b-form-input>
                     </b-form-input>
                 </b-col>
                 <b-col cols="1">
                     <b-form-group
                     label="%">
                     </b-form-group>
                 </b-col>
             </b-row>
             <b-row>
                 <b-col cols="4">
                     <b-form-group
                     label="รายได้ / ยอดขาย"
                     label-align-lg="left">
                     </b-form-group>
                 </b-col>
                 <b-col cols="2">
                     <b-form-input>
                     </b-form-input>
                 </b-col>
                 <b-col cols="1">
                     <b-form-group
                     label="บาท/เดือน">
                     </b-form-group>
                 </b-col>
             </b-row>
             <b-row>
                 <b-col cols="4">
                     <b-form-group
                     label="อัตรากำไรของธุรกิจ"
                     label-align-lg="left">
                     </b-form-group>
                 </b-col>
                 <b-col cols="2">
                     <b-form-input>
                     </b-form-input>
                 </b-col>
                 <b-col cols="1">
                     <b-form-group
                     label="%">
                     </b-form-group>
                 </b-col>
                 <b-col></b-col>
             </b-row>
             <b-row>
                 <b-col cols="4">
                     <b-form-group
                     label="รายได้สุทธิ"
                     label-align-lg="left">
                     </b-form-group>
                 </b-col>
                 <b-col cols="2">
                     <b-form-input>
                     </b-form-input>
                 </b-col>
                 <b-col cols="1">
                      <b-form-group
                     label="บาท/เดือน">
                     </b-form-group>
                 </b-col>
                 <b-col></b-col>
             </b-row>
         </div>
    </div>    
</template>

<script>
export default {
    name: 'PersonnalBusinessIncome',
    props: {
      name: String,
      bio: String
    }
}
</script>

<style scoped>

</style>
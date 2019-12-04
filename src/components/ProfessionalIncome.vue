<template>
    <div class="ProfessionalIncome">
         <div class="">
               <b-row>
                    <b-col cols="1">
                        <b-form-group
                        label="รายได้วิชาชีพเฉพาะ"
                        label-align-lg="left">
                        </b-form-group>
                    </b-col>
                    <b-col cols="1">
                        <b-form-group
                        label="เฉลี่ย"
                        label-align-lg="left">
                        </b-form-group></b-col>
                    <b-col cols="1">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                        <b-form-group
                        label="เดือน">
                        </b-form-group>
                    </b-col>
                    <b-col cols="2">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                         <b-form-group
                        label="บาท/เดือน">
                        </b-form-group>
                    </b-col>
               </b-row>
               <b-row>
                    <b-col cols="1">
                        <b-form-group
                        label="รายได้วิชาชีพอิสระ"
                        label-align-lg="left">
                        </b-form-group>
                    </b-col>
                    <b-col cols="1">
                        <b-form-group
                        label="เฉลี่ย"
                        label-align-lg="left">
                        </b-form-group></b-col>
                    <b-col cols="1">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                        <b-form-group
                        label="เดือน">
                        </b-form-group>
                    </b-col>
                    <b-col cols="2">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                         <b-form-group
                        label="บาท/เดือน">
                        </b-form-group>
                    </b-col>
               </b-row>
               <b-row>
                    <b-col cols="1"></b-col>
                    <b-col cols="1"></b-col>
                    <b-col cols="1">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                        <b-form-group
                        label="รายได้รวม">
                        </b-form-group>
                    </b-col>
                    <b-col cols="2">
                        <b-form-input
                        id="input-1"
                        type="number"
                        required
                        placeholder="0">
                        </b-form-input>
                    </b-col>
                    <b-col cols="1">
                         <b-form-group
                        label="บาท/เดือน">
                        </b-form-group>
                    </b-col>
               </b-row>
         </div>
    </div>    
</template>

<script>
export default {
    name: 'ProfessionalIncome',
    props: {
      name: String,
      bio: String
    }
}
</script>

<style scoped>

</style>
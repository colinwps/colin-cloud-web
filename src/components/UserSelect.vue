<template>
   <el-checkbox v-model="checked">{{checked}}</el-checkbox>
</template>

<script>
export default {
    name: 'UserSelect',
    data(){
        return{
            checked: true

        }
    },
    mounted:{

    },
    //props:['departmentId','departmentName','userId','userName'],
    props:{
        departmentName: String
    },
    methods:{

    },
 
}
</script>

<style lang="less" scoped>

</style>>
<template>
    <el-row>
      <span>{{departmentName}}</span>
    </el-row>
</template>

<script>
export default {
    name: 'UserSelect',
    data(){
        return{

        }
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
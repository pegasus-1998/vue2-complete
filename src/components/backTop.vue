<template>
  　<el-backtop
        target="#main"
        :right="150"
        :bottom="300"
        :visibility-height="40"
    >
    　　　<i class="el-icon-top"></i> 　　
    </el-backtop>
</template>

 <style lang="scss" scoped>
    .el-backtop {
        transition: all .3s;
        padding: 23px;
        border: 3px solid $default-color;
        background: pink;
        i {
            font-size: 35px;
            font-weight: bold;
        }
        &:hover {
            transform: scale(1.1);
        }
    }
 </style>
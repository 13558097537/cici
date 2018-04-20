<template>
    <div>
        <p class="jj">点击我，会发生点事情</p>
        <router-view></router-view>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                
            };
        },
        mounted() {

        },
        beforeDestroy() {

        },
        methods: {
         $:( function () {
          $(".jj").click(function(){
            $(this).hide();
        });       
        })
        }
    };
</script>
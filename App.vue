<template>
    <view class="body">
        <header/>
        <content/>

    </view>

</template>

<script>
    import Header from "./src/components/Header";
    import Content from "./src/components/Content";
    export default {
        components: {Content, Header},

    };
</script>

<style>
    .body {
        background-color: #c37dc4;
    }
    .container {


    }


</style>

<template>
    <view class="content">
        <text class="text-color-primary" >{{message}}</text>

        <text-input class="input" v-model="message"></text-input>
        <text class="text-color-primary" :on-press="counter++">{{counter}}</text>
    </view>

</template>

<script>
    export default {
        name: "Content",
        data: function () {
            return {
                message: "Hello World",
                counter: 0
            };
        }
    };
</script>

<style scoped>
    .content {
        padding: 10px;
        height: 100%;
    }
    .text-color-primary {
        color: #544f69;
        font-weight: bold;
        font-size: 25px;
        margin-bottom: 10px;
    }
    .input {
        border-color: #ccc;
        border-width: 1px;
        font-size: 20px;
        padding: 5px;
        background-color: #fff;
    }

</style>

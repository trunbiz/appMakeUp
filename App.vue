<template>
<!--    <view class="container">-->
<!--        <button-->
<!--            title="Learn More"-->
<!--            color="#841584"-->
<!--            accessibility-label="Learn more about this purple button"/>-->
<!--&lt;!&ndash;            <web-view :source="{uri:'https://google.com'}"/>&ndash;&gt;-->
<!--    </view>-->
    <web-view :source="{uri:'https://beauty-makeup.moonfarmviet.com'}"/>-->
</template>
<script>
import {WebView} from "react-native-webview";

export default {
    name: "myComponent",
    components: {
        "web-view": WebView
    }
};
</script>
<style>
.container {
    background-color: white;
    align-items: center;
    justify-content: center;
    flex: 1;
}

.text-color-primary {
    color: blue;
}
</style>

<template>
    <div @click="open_page">点击我打开网页</div>
</template>

<script>
    export default {
        name: "search",
        data: function () {
            return {
                url: 'https://www.zhihu.com/search?type=content&q=666'
            }
        },
        methods: {
            open_page: function () {
                window.open(this.url)
            }
        }
    }
</script>

<style scoped>

</style>

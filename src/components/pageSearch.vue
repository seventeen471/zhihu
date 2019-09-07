<template>
    <div class="page-search">
        <mt-search
                :value.sync="value"
                cancel-text="取消"
                placeholder="搜索">
        </mt-search>
    </div>
</template>

<script>
    export default {
        name: "pageSearch"
    }
</script>

<style scoped>

</style>

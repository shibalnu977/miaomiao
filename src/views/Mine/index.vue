<template>
    <div id="main">
        <Header title="我的猪猪"></Header>
        <div id="content">
            <login />
        </div>
        <TabBar />
    </div>
</template>

<script>
import Header from '@/components/header';
import TabBar from '@/components/TabBar';
import Login from '@/components/login'
export default {
    name : 'Mine',
    components:{
        Header,
        TabBar,
        Login
    }
}
</script>

<style lang="scss" scoped>

</style>
<template>
    <v-app>
        <AppHeader></AppHeader>
        <RouterView></RouterView>
        <AppFooter></AppFooter>
    </v-app>
</template>

<script>
    import AppHeader from './components/AppHeader';
    import AppFooter from "./components/AppFooter";

    export default {
        name: 'App',
        components: {
            AppFooter,
            AppHeader
        }
    };
</script>

<style>
    #app {
        background-color: #FAFAFA;
    }
</style>

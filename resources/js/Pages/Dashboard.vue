<template>
    <div class="contianer mt-5">
        <p class="p-4 bg-green-200">{{ $page.props.flash.greet }}</p>
        <h1 class="title"> wellcome back {{ $page.props.auth.user.name }}</h1>
    </div>
</template>

<script setup>

</script>

<style  scoped>

</style>
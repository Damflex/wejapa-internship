<template>
    <div class="center">
         <h1>Hello! My name is <br> <strong> {{ name }} </strong>. </h1>
    </div>
</template>


<script>
export default {
    name: 'MyName',
    props: ['name']
}
</script>

<style>
    .center {
        font-weight:300;
        justify-content: center;
        align-items: center;
    }
    h1 {
        font-weight:200;
        justify-content: center;
        align-items: center;
    }
</style>
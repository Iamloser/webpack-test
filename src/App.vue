<template>
    <div class="hello hello-style">
        hello, {{name}}
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'alex'
        }
    }
}
</script>

<style>
.hello {
    font-size: 36px;
    color: red;
}
</style>


<style lang="scss">

.hello-style {
    width: 500px;
    height: 500px;
    background-color: #eee;
}
</style>





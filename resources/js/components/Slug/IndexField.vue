<template>
    <span>{{ field.value }}</span>
</template>

<script>
export default {
    props: ['resourceName', 'field'],
    mounted(){
        console.log(this.field);
    }
}
</script>

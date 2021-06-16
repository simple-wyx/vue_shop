<template>
    <div>
        <button v-on:click="count++">{{ count }}</button>
    </div>
</template>
<script>
export default {
    data: function(){
        return {
            count:0
        }
    }
}
</script>
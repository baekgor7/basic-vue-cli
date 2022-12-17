<template>
    <div>
        <p>{{ name }}</p>
        <button @click="updatedName">Change</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Kossie coder'
        }        
    },  
    methods: {
        updatedName() {
            this.name = 'Kossie Coder Updated';
        }
    }
}
</script>

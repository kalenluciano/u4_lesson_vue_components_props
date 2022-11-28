<template>
    <div>
        <h4>{{msg}}</h4>
    </div>
</template>

<script>
export default {
    name: 'MySecondComponent',
    props: {
        msg: {
            type: String,
            required: true
        }
    }
}
</script>
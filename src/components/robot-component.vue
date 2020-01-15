<template>
    <div>
    <h5> This is what is just wrote in vue </h5>
    <div>My name is {{name}}</div>
        </div>
</template>>

<script>
export default {
    props: {
        name: { type: String, default: "Manzil" }
    }
};
</script>>
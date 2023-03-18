<template>
    <div class="container">
        <div>
           <h1>
            Error 404.
            Page not Found
           </h1>
           <button type="button" @click="redirectMe()" class="btn btn-secondary"  >Back To Homepage</button>
        </div>
    </div>
</template>

<script>
export default {
    name: "users",
    methods: {
        redirectMe(){
            this.$router.push({ name: "Home" });
        },

    },
};
</script>
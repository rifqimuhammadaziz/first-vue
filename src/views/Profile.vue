<template>
<div class="profile">
    <div class="container">
        <div class="d-flex justify-content-center">
            <div class="">
                <img src="../assets/rifqi.jpg" class="user-pic">
            </div>
            <div class="col-lg-4 text-start ms-4">
                <h5>{{ firstName }} {{lastName}}</h5>
                <p>{{ bio }}</p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'

export default {
    name: 'Home',
    data: function() {
        return {
            firstName: 'Rifqi',
            lastName: 'Muhammad Aziz',
            bio: 'This is some content from a media component. You can replace this with any content and adjust it as needed.'
        }
    },
    components: {}
}
</script>

<style scoped>
.user-pic {
    height: 80px;
    width: 80px;
    border-radius: 50%;
}
</style>
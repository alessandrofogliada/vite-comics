<script>
export default {
    name:'AppCard',
    props :{
        infoCard : Object
    },
}
</script>


<template>
    <div class="card">
        <img :src="infoCard.thumb" alt="infoCard.series">
        <div> 
            <h4>{{infoCard.series}}</h4>
        </div>
    </div> 
   
</template>


<style>
.card img {
    width: 100%;
    height: 100px;
}
h4{
    color: grey;
    text-align: center;
}

</style>
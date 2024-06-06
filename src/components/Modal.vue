
<template>
    <div class="backdrop">
        <div class="modal">
            <h1>learing props in vue</h1>
            <p>{{ jovic }}</p>
        </div>
    </div>
</template>



<script>

export default{
    props : ['jovic']
}

</script>

<style >

    .modal{
        width:400px;
        padding: 20px;
        margin:100 auto;
        background: white;
        border-radius:10px;
    }

    .backdrop{
        top:0px;
        position:fixed;
        background:black;
        width: 100%;
        height:100%;
    }

</style>
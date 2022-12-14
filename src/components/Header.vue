<template>
    <header id="header">
        <div id="left">
            <img id="img-vue" src="../assets/images/vue.png" />
            <h1>WebBook</h1>
            <h4></h4>
           
        </div>
        <div id="right">
            <h2>Le réseau social des développeurs web</h2>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

#header {
    width: 100%;
    height: 10vh;
    background-color: #317AC1;
    display: flex;
    flex-direction: row;
}

#left {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 30px;
    color: white
}

#right {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    padding-right: 20px;
    color: white;
    text-transform: uppercase;
}



#img-vue {
    width: 50px;
    height: 50px;
    margin-right: 10px;
 

}

</style>
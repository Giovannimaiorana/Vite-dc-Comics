<script>
Data(){

}






</script>

<template>
    <div class="container_header">
        <nav class="container_nav">
            <div>
                <img src="../pubb" alt="">
            </div>
            <div>
                <ul>
                    <li v-for=" element in nav">{{ name }}</li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<style lang="scss" scoped>
nav {
    display: flex;
    justify-content: space-between;
}

.container_nav {
    width: 800px;
    margin: auto;
}

.container_header {
    width: 100%;
    background-color: white;
}
</style>
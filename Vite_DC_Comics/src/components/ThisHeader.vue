<script>
export default {
    data() {
        return {
            nav: [
                {
                    name: 'CHARACTERS',
                },
                {
                    name: 'COMICS',
                },
                {
                    name: 'MOVIES',
                },
                {
                    name: 'TV',
                },
                {
                    name: 'GAMES',
                },
                {
                    name: 'COLLECTIBLES',
                },
                {
                    name: 'VIDEOS',
                },
                {
                    name: 'FANS',
                },
                {
                    name: 'NEWS',
                },
                {
                    name: 'SHOP',
                },

            ]

        }
    }

}






</script>

<template>
    <div class="container_header">
        <nav class="container_nav">
            <div class="logoHead">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div>
                <ul>
                    <li v-for=" element in nav ">{{ element.name }}</li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<style lang="scss" scoped>
nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.container_nav {
    width: 1300px;
    height: 100px;
    margin: auto;
    background-color: white;
}

.logoHead img {
    width: 80px;
    padding: 10px;
}

ul {
    list-style: none;
    display: flex;
}

li {
    margin-left: 15px;
}

li:hover {
    color: blue;
}

.container_header {
    width: 100%;
    background-color: white;
}
</style>
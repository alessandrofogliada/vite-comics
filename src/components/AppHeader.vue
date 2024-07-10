<script>
export default {
    name: 'AppHeader',
    data() {
    return {
        links: [{
                text: "characters",
                url: "#",
                state: false,
            },
            {
                text: "comics",
                url: "#",
                state: true,
            },
            {
                text: "movies",
                url: "#",
                state: false,
            },
            {
                text: "tv",
                url: "#",
                state: false,
            },
            {
                text: "games",
                url: "#",
                state: false,
            },
            {
                text: "collectibles",
                url: "#",
                state: false,
            },
            {
                text: "videos",
                url: "#",
                state: false,
            },
            {
                text: "fans",
                url: "#",
                state: false,
            },
            {
                text: "news",
                url: "#",
                state: false,
            },
            {
                text: "shop",
                url: "#",
                state: false,
            },
            ]
            }
        }
}
</script>

<template>
    <header>

        <div class="container">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>

            <div>
                <nav>
                    <ul>
                        <li v-for="link in links" :class="link.state === true ? 'active' : '' ">
                            <a :href="link.url">{{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
// aggiugniamo scoped perchè vogliamo che le modifiche di css che attuiamo saranno esclusivamente per questo parte , ovvero Header 
@use '/src/styles/general.scss' as *;
@use '/src/styles/partials/mixing' as *;

header{
    // width: 1000px;
    height: 120px;
    background-color: white;
}

header img{
    width: 100px;
}

.container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    // margin: 0 300px;
}

ul{
    list-style-type: none;
    display: flex;
}

a{
    color: black;
    margin: 0 5px;
}

li :hover{
    color: blue;
    border-bottom: 2px solid blue;
}

</style>
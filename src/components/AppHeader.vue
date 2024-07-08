<script>
export default {
    name: 'AppHeader',
}
</script>

<template>
    <header>

        <div class="container">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>

            <div>
                <nav>s
                    <ul>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <li>
                            <a href="">Comics</a>
                        </li>
                        <a href="">Comics</a>
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
}

</style>
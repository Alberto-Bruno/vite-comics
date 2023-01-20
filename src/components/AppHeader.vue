<script>
export default {
    data() {
        return {
            menu: [
                {
                    label: 'CHARACTERS',
                    url: '#',
                    active: false
                },
                {
                    label: 'COMICS',
                    url: '#',
                    active: true
                },
                {
                    label: 'MOVIES',
                    url: '#',
                    active: false
                },
                {
                    label: 'TV',
                    url: '#',
                    active: false
                },
                {
                    label: 'GAMES',
                    url: '#',
                    active: false
                },
                {
                    label: 'COLLECTIOBLES',
                    url: '#',
                    active: false
                },
                {
                    label: 'VIDEOS',
                    url: '#',
                    active: false
                },
                {
                    label: 'FANS',
                    url: '#',
                    active: false
                },
                {
                    label: 'NEWS',
                    url: '#',
                    active: false
                },
                {
                    label: 'SHOP',
                    url: '#',
                    active: false
                }
            ]
        }
    }
}
</script>

<template>
    <header class="container">
        <a href="">
            <img class="logo" src="../assets/img/dc-logo.png" alt="DC Comics Main Logo">
        </a>
        <nav>
            <ul>
                <li v-for="(item, index) in menu" :key="index" :class="item.active ? 'active' : ''">
                    <a :href="item.url">
                        {{ item.label }}
                    </a>
                </li>
            </ul>
        </nav>
    </header>
</template>


<style lang="scss">
header {
    height: 250px;
    margin: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    nav {
        display: flex;
        align-items: center;
        height: 100%;

        ul {
            height: 100%;
            list-style: none;
            margin: 2rem 1rem;
            display: flex;
            align-items: center;

            li {
                height: 100%;
                padding: 1rem;
                font-size: 13px;
                font-family: 'Roboto', sans-serif;
                font-weight: 500;
            }
        }

    }

}
</style>
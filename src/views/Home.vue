<template>
    <div>
        <section class="hero is-primary is-bold is-info">
            <div class="hero-body">
                <div class="container">
                    <h1 class="title">
                        Primary bold title
                    </h1>
                    <h2 class="subtitle">
                        Primary bold subtitle
                    </h2>
                </div>
            </div>
        </section>
        <section class="section main-content">
            <div class="container">
                <!-- Main container -->
                <nav class="columns">
                    <!-- Left side -->
                    <div class="column is-narrow is-hidden-mobile main-content-aside">
                        <aside class="menu">
                            <ul class="menu-list">
                                <li><a class="is-active">首页</a></li>
                                <li>
                                    <a class="is-disabled">导航</a>


                                    <ul>
                                        <li><a>问题</a></li>
                                        <li><a>标签</a></li>
                                        <li><a>用户</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </aside>
                    </div>

                    <!-- Right side -->
                    <div class="column">

                        <HelloWorld msg="Welcome to Your Vue.js App"/>
                    </div>
                    <div class="column is-narrow is-one-fifth">
                        <div class="notification">
                            Lorem ipsum dolor sit amet, consectetur
                            adipiscing elit lorem ipsum dolor. <strong>Pellentesque risus mi</strong>, tempus quis
                            placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida
                            purus diam, et dictum <a>felis venenatis</a> efficitur. Sit amet,
                            consectetur adipiscing elit
                        </div>
                    </div>
                </nav>

            </div>
        </section>
    </div>
</template>

<script>
    // @ is an alias to /src
    import HelloWorld from '@/components/HelloWorld.vue'

    export default {
        name: 'home',
        components: {
            HelloWorld
        }
    }
</script>
<style lang="scss">
</style>

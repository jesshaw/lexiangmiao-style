<template>
    <div>
        <nav class="navbar has-shadow is-transparent is-fixed-top" role="navigation" aria-label="main navigation">
            <div class="container">
                <div class="navbar-brand">
                    <router-link to="/" class="navbar-item" @click.native="triggerNav">
                        <font-awesome-icon icon="cat" size="2x"/>
                    </router-link>
                    <a role="button" class="navbar-burger burger" :class="{'is-active':navIsActive}" aria-label="menu"
                       aria-expanded="false"
                       @click="triggerNav">
                        <span aria-hidden="true"></span>
                        <span aria-hidden="true"></span>
                        <span aria-hidden="true"></span>
                    </a>
                </div>

                <div class="navbar-menu" :class="{'is-active':navIsActive}">
                    <div class="navbar-start">
                        <router-link to="/" class="navbar-item" @click.native="triggerNav">
                            <span class="icon has-text-info"><font-awesome-icon icon="home" fixed-width/></span>
                            <span>首页</span>
                        </router-link>
                        <router-link to="/about" class="navbar-item" @click.native="triggerNav">
                            <span class="icon has-text-warning">
                                <font-awesome-icon icon="building" fixed-width/></span>
                            <span>关于我们</span>
                        </router-link>
                        <div class="navbar-item has-dropdown is-hoverable">
                            <a class="navbar-link">
                                更多
                            </a>

                            <div class="navbar-dropdown">
                                <a class="navbar-item">
                                     <span class="icon has-text-danger">
                                <font-awesome-icon icon="user-md" fixed-width/></span>
                                    <span>工作机会</span>
                                </a>
                                <a class="navbar-item">

                                     <span class="icon has-text-success">
                                <font-awesome-icon icon="phone" fixed-width/></span>
                                    <span>联系我们</span>

                                </a>
                                <hr class="navbar-divider">
                                <a class="navbar-item">


                                     <span class="icon has-text-grey-dark">
                                <font-awesome-icon icon="question" fixed-width/></span>
                                    <span>建议</span>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="navbar-end">
                        <div class="navbar-item">
                            <div class="buttons">
                                <a class="button is-info">
                                    <span class="icon">
                                        <font-awesome-icon icon="user-plus" fixed-width/>
                                    </span>
                                    <span>
                                        注册
                                    </span>
                                </a>
                                <a class="button is-light">
                                    <span class="icon">
                                        <font-awesome-icon icon="sign-in-alt" fixed-width/>
                                    </span>
                                    <span>
                                        登录
                                    </span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
        <router-view/>
        <footer class="footer">
            <div class="content has-text-centered">
                <p>
                    <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is
                    licensed
                    <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
                    is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
                </p>
            </div>
        </footer>
    </div>
</template>

<script>
    export default {
        data() {
            return {navIsActive: false}
        },
        methods: {
            triggerNav: function () {
                this.navIsActive = !this.navIsActive;
            }
        }
    }
</script>

<style lang="scss">
    @import "~bulma/bulma";

    .main-content {
        padding-top: 1.5rem;
    }

    .main-content-aside{
        width: 164px;border-right: 2px solid whitesmoke;
    }
</style>

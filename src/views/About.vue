<template>
    <div>
        <section class="section main-content">
            <div class="container">
                <!-- Main container -->
                <nav class="columns">
                    <!-- Left side -->
                    <div class="column is-narrow is-hidden-mobile main-content-aside">
                        <aside class="menu">
                            <ul class="menu-list">
                                <li><a>首页</a></li>
                                <li>
                                    <a class="is-disabled">导航</a>
                                    <ul>
                                        <li><a class="is-active">问题</a></li>
                                        <li><a>标签</a></li>
                                        <li><a>用户</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </aside>
                    </div>

                    <!-- Right side -->
                    <div class="column">
                        <div class="columns is-multiline">
                            <div class="column is-full">
                                <div class="columns">
                                    <div class="column is-10">
                                        <p class="title">
                                            When I am executing Scenario Outline it is executin
                                            g multiple times from given statements(JVM Cuumber)Outline it is executing
                                            multiple times</p>
                                    </div>
                                    <div class="column has-text-right"><a class="button is-link">立即提问</a></div>
                                </div>
                            </div>
                            <div class="column">
                                <article class="media">
                                    <figure class="media-left">
                                        <div class=" vote has-text-centered">
                                            <a class="icon has-text-grey-lighter" title="经常碰到此类问题">
                                                <font-awesome-icon icon="caret-up" size="3x"/>
                                            </a>
                                            <span class="vote-count-post">10</span>
                                            <a class="icon has-text-grey-lighter" title="从未经常碰到此类问题">
                                                <font-awesome-icon icon="caret-down" size="3x"/>
                                            </a>
                                            <a class="icon has-text-grey-lighter">
                                                <font-awesome-icon icon="star" size="2x"/>
                                            </a>
                                        </div>
                                    </figure>
                                    <div class="media-content">
                                        <div class="content">
                                            <p>
                                                <strong>Barbara Middleton</strong>
                                                <br>
                                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis porta eros
                                                lacus, nec ultricies elit blandit non. Suspendisse pellentesque mauris
                                                sit amet dolor blandit rutrum. Nunc in tempus turpis.
                                                <br>
                                                <small><a>Like</a> · <a>Reply</a> · 3 hrs</small>
                                            </p>
                                        </div>
                                    </div>
                                </article>
                                <article class="media">
                                    <figure class="media-left">
                                        <div class=" vote has-text-centered">
                                            <a class="icon has-text-grey-lighter" title="经常碰到此类问题">
                                                <font-awesome-icon icon="caret-up" size="3x"/>
                                            </a>
                                            <span class="vote-count-post">1</span>
                                            <a class="icon has-text-grey-lighter" title="从未经常碰到此类问题">
                                                <font-awesome-icon icon="caret-down" size="3x"/>
                                            </a>
                                        </div>
                                    </figure>
                                    <div class="media-content">
                                        <div class="content">
                                            <p>
                                                <strong>Barbara Middleton</strong>
                                                <br>
                                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis porta eros
                                                lacus, nec ultricies elit blandit non. Suspendisse pellentesque mauris
                                                sit amet dolor blandit rutrum. Nunc in tempus turpis.
                                                <br>
                                                <small><a>Like</a> · <a>Reply</a> · 3 hrs</small>
                                            </p>
                                        </div>
                                    </div>
                                </article>
                                <article class="media">
                                    <div class="media-content">
                                        <div class="field">
                                            <p class="control">
                                                <textarea class="textarea" placeholder="回答内容..."></textarea>
                                            </p>
                                        </div>
                                        <div class="field">
                                            <p class="control">
                                                <button class="button is-info">提交</button>
                                            </p>
                                        </div>
                                    </div>
                                </article>
                            </div>
                            <div class="column is-narrow is-one-fifth">
                                <nav class="panel">
                                    <p class="panel-heading">sdfsafsaf</p>
                                    <p class="panel-block">
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit lorem ipsum dolor. Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit lorem ipsum dolor. Lorem ipsum dolor sit amet, consectetur
                                        adipiscing elit lorem ipsum dolor.
                                        Lorem ipsum dolor sit amet, consectetur
                                        Lorem ipsum dolor sit amet, consectetur
                                    </p>
                                </nav>
                            </div>
                        </div>
                    </div>
                </nav>
            </div>
        </section>
    </div>
</template>


<style lang="scss">
    .vote{
        width: 32px;
    }
    .vote-count-post{
        display: block;
        font-size: 20px;
        margin: 0 0 3px;
    }
</style>

<template>
    <div>
        <div class="columns question-summary">
            <div class="column is-narrow">
                <div class="columns has-text-centered" style="width: 176px;">
                    <div class="column votes">
                        <div>6</div>
                        <div>点赞</div>
                    </div>
                    <div class="column status answered">
                        <div>1</div>
                        <div>回答</div>
                    </div>
                    <div class="column views">
                        <div>10</div>
                        <div>查看</div>
                    </div>
                </div>
            </div>
            <div class="column">
                <div class="tile">{{ msg }}fdsafd  asffds afad sfasfdasfasf asfas dfsafdasf asfdasff dsafdsf adsfa
                    sfdasfd asfasfasfas fasfa sfsafsf kk
                </div>
                <div class="columns">
                    <div class="column">
                        <div class="tags">
                            <a class="tag">saf</a>
                            <a class="tag">cc</a>
                            <a class="tag">dd</a>
                        </div>
                    </div>
                    <div class="column">
                        modified 1 min ago Daniel Larsson 537
                    </div>
                </div>
            </div>
        </div>
        <div class="columns question-summary">
            <div class="column is-narrow">
                <div class="columns has-text-centered" style="width: 176px;">
                    <div class="column votes">
                        <div>6</div>
                        <div>点赞</div>
                    </div>
                    <div class="column status answered-accepted">
                        <div>1</div>
                        <div>回答</div>
                    </div>
                    <div class="column views">
                        <div>10</div>
                        <div>查看</div>
                    </div>
                </div>
            </div>
            <div class="column">
                <div class="tile">{{ msg }}fdsafd  asffds afad sfasfdasfasf asfas dfsafdasf asfdasff dsafdsf adsfa
                    sfdasfd asfasfasfas fasfa sfsafsf kk
                </div>
                <div class="columns">
                    <div class="column">
                        <div class="tags">
                            <a class="tag">saf</a>
                            <a class="tag">cc</a>
                            <a class="tag">dd</a>
                        </div>
                    </div>
                    <div class="column">
                        modified 1 min ago Daniel Larsson 537
                    </div>
                </div>
            </div>
        </div>
        <div class="columns question-summary">
            <div class="column is-narrow">
                <div class="columns has-text-centered" style="width: 176px;">
                    <div class="column votes">
                        <div>6</div>
                        <div>点赞</div>
                    </div>
                    <div class="column status unanswered">
                        <div>0</div>
                        <div>回答</div>
                    </div>
                    <div class="column views">
                        <div>10</div>
                        <div>查看</div>
                    </div>
                </div>
            </div>
            <div class="column">
                <div class="tile">{{ msg }}fdsafd  asffds afad sfasfdasfasf asfas dfsafdasf asfdasff dsafdsf adsfa
                    sfdasfd asfasfasfas fasfa sfsafsf kk
                </div>
                <div class="columns">
                    <div class="column">
                        <div class="tags">
                            <a class="tag">saf</a>
                            <a class="tag">cc</a>
                            <a class="tag">dd</a>
                        </div>
                    </div>
                    <div class="column">
                        modified 1 min ago Daniel Larsson 537
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .question-summary {
        border-bottom: 1px solid #f5f5f5;
    }

    .votes, .status, .views {
        min-height: 40px;
        min-width: 40px;
        margin-top: 10px;
        padding-top: 5px;
        padding-left: 0;
        padding-right: 0;
        padding-bottom: 5px;
    }

    .unanswered {
    }

    .answered {
        border: 1px solid transparent;
        color: #45A163;
        border-color: rgba(69, 161, 99, 0.5);
        border-radius: 4px;
    }

    .answered-accepted {
        color: #fff;
        background-color: #5fba7d;
        border-radius: 4px;
    }
</style>

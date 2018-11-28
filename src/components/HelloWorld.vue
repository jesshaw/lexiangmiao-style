<template>
  <div class="columns">
    <div class="column">
      <nav class="level is-mobile" style="width: 100px;">
        <div class="level-item has-text-centered">
          <div class="content is-small">
            <a class="tag is-white">
              6<br/>
              点赞
            </a>
          </div>
        </div>
        <div class="level-item has-text-centered is-bordered">
          <a class="tag is-white">
            6<br/>
            回答
          </a>
        </div>
        <div class="level-item has-text-centered">
          <div class="buttons has-addons is-vertical">
            <span class="button">6</span>
            <span class="button">查看</span>

          </div>
        </div>
      </nav>
    </div>
    <div class="column">
      <h1>{{ msg }}</h1>
      <div class="tags">
        <a class="tag">saf</a>
        <a class="tag">saf</a>
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
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }

</style>

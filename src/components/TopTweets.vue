<template>
    <div class="list">
        <h4>Top Tweets</h4>
        <b-table striped hover :items="items"></b-table>
    </div>
</template>

<script>
export default {
  name: 'TopTweets',
  data() {
      return {
        items: [
          { username: '@user1', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user2', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user3', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user4', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user1', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user2', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user3', tweet: 'Hey Whatsuppppp, im fine ok'},
          { username: '@user4', tweet: 'Hey Whatsuppppp, im fine ok'},
        ]
      }
    }
}
</script>


<template>
  <div class="home">
    <b-container>
      <b-row class="mt-3 mb-5">
        <b-col cols="4">
          <b-card title="Number Of Tweets">
            <b-card-text>
              <h1>4k</h1>
            </b-card-text>
          </b-card>
        </b-col>
        <b-col cols="4">
          <b-card title="Positive Sentiments">
            <b-card-text>
              <h1>1k</h1>
            </b-card-text>
          </b-card>
        </b-col>
        <b-col cols="4">
          <b-card title="Negative Sentiments">
            <b-card-text>
              <h1>3k</h1>
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>
      <div class="mb-5">
        <line-chart/>
      </div>
      <b-row class="mt-5">
        <b-col cols="5">
          <pie-chart/>
        </b-col>
        <b-col cols="7">
          <top-tweets/>
        </b-col>
      </b-row>
      
    </b-container>
  </div>
</template>

<script>
import LineChart from '@/components/LineChart.vue' 
import PieChart from '@/components/PieChart.vue' 
import TopTweets from '@/components/TopTweets.vue' 
export default {
  name: 'Home',
  components: {
    'line-chart':LineChart,
    'pie-chart':PieChart,
    'top-tweets':TopTweets,
  }
}
</script>

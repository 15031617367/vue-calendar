<template>

     <vue-event-calendar :events="demoEvents"></vue-event-calendar>
   
</template>

<script>
export default {
  data () {
    return {
         demoEvents: [
         {
          date: '2018/7/2',
          title: '考试成绩',
          desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum, omnis accusamus quidem ullam ea voluptatem itaque qui ad dignissimos optio, nostrum tempore dolores odio nulla reiciendis consequuntur ipsum quis nobis?'
        },
        {
          date: '2018/7/4',
          title: '全校通报'
        }
      ]
    }
  }
}
</script>


<style scoped>

</style>

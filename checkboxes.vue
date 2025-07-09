<template>
    <div v-for="item in questionArray" :key="item.number" class="flex-vert">
        <div class="vfor"> 
            <h2>{{ item.number }}. {{ item.question }} </h2> 

        </div>
        <div v-for="option in options" class="vfor"> 
            <h3>{{ option }}</h3> 
            <Checkbox10 />
        </div>
    </div>


</template>

<style scoped>
h2 {
    max-width: 30ch;
}



.flex-vert {
    display: flex;
    flex-direction: column;

    width: fit-content;
}
.vfor {
    display: flex;
}

</style>

<script>
import { Checkbox10 } from '#components';

export default {
  data() {
    return {
      questionArray: [
        {
          number: 1,
          question: 'Wie zufrieden sind Sie mit dem Endergebnis des Designs?'
        },
        {
          number: 2,
          question: 'Wie zufrieden sind Sie mit dem Endergebnis des Designs?'
        }
      ] ,
      options: [
        
            'good' , 'bad' , 'worse' , 'worst'
        
      ]
    }
  }
}
</script>
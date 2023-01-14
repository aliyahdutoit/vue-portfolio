<template>
<h1>Testimonials</h1>
   <card class="d-flex justify-content-evenly" id="card-container">
    <div v-for="(testimonial, id) in testimonials" :key="id" class="card" style="width: 18rem;">
        <img id="index" :src="testimonial.img" class="card-img-top img-fluid" alt="...">
        <div class="card-body">
          <h5 class="card-title text-dark">{{testimonial.name}}</h5>
          <p class="card-text text-dark">{{testimonial.quote}}</p>
        </div>
      </div>
   </card>
</template>

<script>
    export default {
       data(){
            return{
                testimonials:[ 
                    {
                    id: 1,
                    name:'Savannah Samuels',
                    img:'https://i.postimg.cc/V6wBnZ22/IMG-20220904-134609-306.jpg',
                    quote:'Aliyah is a soft and gentle individual who is always keen on learning new things and is always hard-working.'
                    // contact: ''
                    },
                    {
                    id: 2,
                    name:'Ryan Thomas',
                    img:'https://i.postimg.cc/yYFfFhm5/ryan-Thomas.jpg',
                    quote:'Aliyah is a great student and a fast learner.One of her greatest traits is asking the same question in multiple different ways in order to make sure she understands the task at hand. She is also a really good team player and always tries to assist her peers. She is shy, but once engaged into conversation with, her bubbly personality truly shows.'
                    },
                    {
                    id: 3,
                    name:'Seaba Mafestire',
                    img:'https://i.postimg.cc/T3FjCYjs/seaba.jpg',
                    quote:'Aliyah has a lovely personality that makes it easy to engage and work with her, she follows rules and always gets her work done.'
                    },
                    {
                    id:4,
                    name:'Candice Amon',
                    img:'https://i.postimg.cc/9M5zs5s1/candice-amon.jpg',
                    quote:'Very kind hearted and going the extra mile for others and displays great care and concern for those around her. A strength of Aliyah is that she has great self awareness. When an opportunity presents itself she is able to make use of it to the best of her ability. It is always a pleasure having Aliyah around.'
                    },
                    {
                    id:5,
                    name:'Kauthar  Brandt',
                    img:'https://i.postimg.cc/k4mXfNtp/kauthar-brandt.jpg',
                    quote:'I have had the pleasure of working alongside Aliyah and I can definitely say that she is a determined individual who never fails to help her peers. Her supportive character uplifts the environment she is in, thus creating an efficient working process. These characteristics are beneficial for any work environment.'
                    },
                    {
                    id:6,
                    name:'Sadia Alam',
                    img:'https://i.postimg.cc/pT5VWGMr/sadia-alam.jpg',
                    quote:'Aliyah is a very kind and talented person. She is very determined about her work and always willing to growth. She is cares about the people around her and helps others whenever she can. She will a great asset to any company.'
                    }
                ]    
                }
        }
    }
    
    
       
</script>

<style>
#testimonials {
    font-family: 'Times New Roman', Times, serif; 
    padding-left: 300px; 
    font-size: 100px; 
    color: #b09cd1;
  }
  
  #card-container {
    display:flex; 
    flex-wrap: wrap; 
    padding: 90px; 
    border-spacing: 50px; 
    justify-content: space-between; 
    align-content: center; 
    column-gap: 100px; 
    row-gap: 20px;
    margin-right: 10px;
  }
  
  #card-look {
    height: 600px; 
    width: 300px;
  }
  
  #card-image {
    height: 300px;
  }
  h1 {
    font-weight: bolder;
  }
</style> 
   
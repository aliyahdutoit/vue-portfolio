<template>
    <h1>Projects</h1>
       <card class="d-flex justify-content-evenly" id="card-container">
        <div v-for="(project, id) in projects" :key="id" class="card" style="width: 18rem;">
            <img id="index" :src="project.img" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title text-dark">{{project.name}}</h5>
              <p class="card-text">
                <br><a href="{{ project.github }}" class="projectlinks">Github</a>
               <br><a href="{{ project.netlify }}" class="projectlinks">Netlify</a>
              </p>
                </div>
               </div>
           </card>
    </template>

<script>
    export default {
        data(){
            return{
                projects:[ 
                    {
                        id: '1',
                        name: 'Cat Portfolio',
                        img : 'https://i.postimg.cc/YSGgWfQL/catportfolio.png',
                        github: 'https://github.com/aliyahdutoit/AliyahPortfolio.git',
                        netlify: 'https://reliable-cheesecake-517165.netlify.app/'
                    },
                    {
                        id: '2',
                        name: 'Sneaker Site',
                        img : 'https://i.postimg.cc/432grV0P/sneakersite.png',
                        github: 'https://github.com/aliyahdutoit/sneakers.git',
                        netlify: 'https://tubular-pegasus-973183.netlify.app/'
                    },
                    {
                        id: '3',
                        name: 'Netflix Promo Website',
                        img : 'https://i.postimg.cc/26g0WSqr/netflixpromosite.png',
                        github: 'https://github.com/aliyahdutoit/NetflixPromo.git',
                        netlify: 'https://delightful-pothos-0d5e63.netlify.app/'
                    },
                    {
                        id: '4',
                        name: 'Book Bound',
                        img : 'https://i.postimg.cc/k5XY3Z33/bookboundsite.png',
                        github: 'https://github.com/aliyahdutoit/JavaScript_BookBound.git',
                        netlify: 'https://book-bound.netlify.app/'
                    },
                    {
                        id: '5',
                        name: 'First Portfolio',
                        img : 'https://i.postimg.cc/pX5t3mQY/firstportfolio.png',
                        github: 'https://github.com/aliyahdutoit/Aliyah-Portfolio.git',
                        netlify: 'https://aliyah-portfolio.netlify.app/'
                    },
                    {
                        id: '6',
                        name: 'Siamese Society',
                        img : 'https://i.postimg.cc/908Fbshm/siamesesociety.png',
                        github: 'https://github.com/aliyahdutoit/Siamese-Society.git',
                        netlify: 'https://ephemeral-raindrop-326d27.netlify.app/'
                    },
                    {
                        id: '7',
                        name: 'Founders Wildlife Conntact Page',
                        img : 'https://i.postimg.cc/pXHZM7zG/founderswildlifecontactpage.png',
                        github: 'https://github.com/aliyahdutoit/contact-founderswildlife.git',
                        netlify: 'https://app.netlify.com/sites/resplendent-cajeta-958c6f'
                    },
                    {
                        id: '8',
                        name: 'JavaScript Calculator',
                        img : 'https://i.postimg.cc/HsSKBd7D/Screenshot-20230113-101038.png',
                        github: 'github: https://github.com/aliyahdutoit/jscalculator.git',
                        netlify: 'https://aliyah-javascript-calculator.netlify.app/'
                    },
            ]
            }
        }
    }
</script>

<style scoped>
h1 {
    font-weight: bolder;
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
    height: 400px; 
    width: 200px;
    box-shadow: 0 1rem 2rem rgba(0, 0, 0, .67);
  }
  .projectlinks{
    text-decoration: none;
    color: black;
  }
  .projectlinks a {
    color: #63458A;
  }
</style>
<template>
    <h1>Projects</h1>
       <card class="d-flex justify-content-evenly" id="card-container">
        <div v-for="(project, id) in projects" :key="id" class="card" style="width: 18rem;">
            <img id="index" :src="project.img" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title text-dark">{{project.name}}</h5>
              <p class="card-text">{{project.quote}}</p>
              <a href="#" class="btn btn-primary">
                <!-- Button trigger modal -->
                <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                  View Details
                </button>
                
                <!-- Modal -->
                <div  class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                  <div class="modal-dialog">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-5" id="exampleModalLabel">{{project.name}}</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                       
                      </div>
                      <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                      </div>
                    </div>
                  </div>
                </div></a>
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

</style>
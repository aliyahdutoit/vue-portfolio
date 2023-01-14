<template>
    <h1>Aliyah's Résumé</h1>    
    <div>
        <a class="btn btn" href="../assets/CV of Aliyah Du Toit (2).docx" role="button"><a href="../assets/CV of Aliyah Du Toit (2).docx" download="CV of Aliyah Du Toit.docx" class="resumebuttons">Download CV</a></a>
        <a class="btn btn" href="../assets/Aliyah du Toit cover letter (1).docx" role="button"><a href="../assets/Aliyah du Toit cover letter (1).docx" download="Aliyah du Toit Cover Letter" class="resumebuttons">Download Cover Letter</a></a>
    </div>
    <div class="container text-center">
        <div class="row">
          <div class="col-6">
            <h3>Soft Skills</h3>
            <ul>
                <li>Attentive</li>
                <li>Assertive</li>
                <li>Effective Organizational skills</li>
                <li>Time-Management Skills</li>
                <li>Persistent</li>
                <li>Problem-Solving</li>
                <li>communication</li>
                <li>Stress Management</li>
                <li>Critical Thinking</li>
                <li>Team-Work</li>
               
            </ul>
          </div>
          <div  class="col-6" id="progressbars">
             <h3>Coding Skills</h3>
             <div v-for="(bar, id) in bars" :key="id">
             <h4>{{bar.name}}</h4>
        <div class="progress" >
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" :aria-valuenow="bar.value" id="progressbars" aria-valuemin="0" aria-valuemax="100" :style="{width: bar.value + '%'}"></div>
          </div>
          </div>
        </div>
      </div>
    </div>
<br>
<br>
    <!-- Timeline -->
    <div class="container">                      
        <div class="row text-center justify-content-center mb-5">
            <div class="col-xl-6 col-lg-8">
                <h2 class="font-weight-bold">Aliyah's Work Experience</h2>
            </div>
        </div>
    <div>
        <ul>
            <li>Student at Life Choices Academy in Lansdowne, Cape Town.
              <br><text-muted> Sept 2022 - current</text-muted>
            </li>
            <li>Volunteer at Vista Nova School for the Special Needs.
              <br><text-muted>2018 - current</text-muted>
            </li>
            <li>Volunteer for a feeding program based in Goodwood, Cape Town.
              <br><text-muted>2019 - current</text-muted>
            </li>
            <li>Matriculated from Groote Schuur High School.
              <br><text-muted>Dec 2021</text-muted>
            </li>
            <li>Assisted guests at a social music event, Kenilworth Racecourse DJ Gathering.
              <br><text-muted>Nov 2021</text-muted>
            </li>
            <li>A Promotor for Hair-Care products.
              <br><text-muted>Oct 2019</text-muted>
            </li>
        </ul>
    </div>
    </div>
   
</template>

<script>
    export default {
      data(){
            return{
                bars:[ 
                    {
                    id: 1,
                    name:'HTML',
                    value: 96
                    },
                    {
                    id: 2,
                    name:'CSS',
                    value: 92
                    },
                    {
                    id: 3,
                    name:'BootStrap',
                    value: 98
                    },
                    {
                    id: 4,
                    name:'JavaScript',
                    value: 60
                    },
                    {
                    id: 5,
                    name:'Vue.js',
                    value: 75
                    },
                    {
                    id: 6,
                    name:'Node.js',
                    value: 100
                    }
                  ]
            }
          }
            }
</script>

<style scoped>

h1 {
    font-weight: bolder;
  }

  .progress {
    --bs-progress-bar-bg: #63458A;
  }

.resumebuttons {
    float: right;
    color: #E4B7E5;
    border-radius: 5px;
    text-decoration: none;
    padding: 6px;
    background-color: #63458A;
  }
  li {
    list-style: none;
  }
#progressbars {
    padding: 10px;
    justify-content: space-between;
}

body{margin-top:20px;}

#progressbar {
    margin: 0 0 10px 0;
}
#progressbars {
  color: #7E5A9B !important;
}
</style>
<!-- <h4>HTML</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="96" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 96%"></div>
          </div>
             <h4>CSS</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="92" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 92%"></div>
          </div>
             <h4>BootStrap</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="98" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 98%"></div>
          </div>
             <h4>JavaScript</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="60" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 60%"></div>
          </div>
             <h4>Vue.js</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
          </div>
             <h4>Node.js</h4>
        <div class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="100" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 100%"></div>
          </div> -->
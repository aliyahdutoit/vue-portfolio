<template>
    <h1>Aliyah's Résumé</h1>    
    <div>
        <a href="../assets/CV of Aliyah Du Toit (2).docx" download="CV of Aliyah Du Toit.docx"></a>
        <a class="btn btn" href="../assets/CV of Aliyah Du Toit (2).docx" role="button"><a href="../assets/CV of Aliyah Du Toit (2).docx" download="CV of Aliyah Du Toit.docx" class="resumebuttons">Download CV</a></a>
        <a class="btn btn" href="../assets/Aliyah du Toit cover letter (1).docx" role="button"><a href="../assets/Aliyah du Toit cover letter (1).docx" download="Aliyah du Toit Cover Letter" class="resumebuttons">Download Cover Letter</a></a>
    </div>
    <div class="container text-center">
        <div class="row">
          <div class="col">
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
          <div class="col">
             <h3>Coding Skills</h3>
             <h4>{{progressbars.name}}</h4>
        <div v-for="(progressbar, id) in progressbars" :key="id" class="progress">
            
            <div  class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="{{progressbars.progress}}" id="progressbars" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
          </div>
          </div>
        </div>
    </div>
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
              <br><text-muted>2022 - current</text-muted>
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
                    
            }
</script>

<style scoped>

h1 {
    font-weight: bolder;
  }
.resumebuttons {
    float: right;
    color: white;
    border-radius: 5px;
}
#progressbars {
    padding: 10px;
    justify-content: space-between;
}

body{margin-top:20px;}

#progressbar {
    margin: 0 0 10px 0;
}
</style>
<template>
  <div id="keynote">
    <!-- Main Title -->
    <div class="main-title">
    	<h1>Keynote</h1>
		  <div class="main-title-deco"></div>
    </div>
    <!-- Main Title End -->

    <!-- Preliminary Keynotes -->
		<div v-if="currentYear === '2025'">
      <div id="keynotes">
			<!-- <h2>Keynotes</h2><hr> -->
			<div id="keynote-container">
        <div class="keynote-box">
					<div class="keynote-title">AI-driven Drug Discovery in the LLM Era</div>
          <div class="profile-box">
            <img src="@/assets/keynotes/Prof_Jaewoo_Kang.jpg" class="profile" style="object-position: top;">
            <div class="">
              <div class="keynote-speaker">Prof. Jaewoo Kang</div>
              <div class="affiliation"><i>Korea University, Republic of Korea</i></div>
            </div>
          </div>
          <div class="speaker-bio">
            <b>Abstract.</b> Large Language Models (LLMs) are emerging as transformative tools across various industries, with significant implications for healthcare and pharmaceuticals. The pharmaceutical sector, characterized by its reliance on extensive knowledge, stands to gain substantial benefits from LLMs. This presentation will delve into how LLMs can enhance productivity in drug discovery by enabling comprehensive analysis of scientific papers and patents, facilitating the generation of novel scientific hypotheses, design of novel drugs, accurate prediction of the pharmacological properties of the designed drugs, and streamlining the drafting of regulatory approval documents. Building upon the speaker's expertise in AI-driven precision medicine and drug discovery, and recent advancements in biomedically specialized LLMs, this talk will provide insights into the current state and future directions of LLMs in drug discovery.
            <br><b>Bio.</b> Dr. Jaewoo Kang is a Professor of Computer Science at Korea University (since 2006) and CEO of AIGEN Sciences (founded in 2021), where he leads AI-driven precision medicine and drug discovery efforts. His expertise is in biomedical AI, with a focus on advancing AI solutions for healthcare. He holds a Ph.D. in Computer Science from the University of Wisconsin-Madison (2003) and was previously an Assistant Professor at North Carolina State University (2003-2006). Dr. Kang has made significant contributions to biomedical AI, notably the development of BioBERT (over 7,000 citations). His research team has achieved remarkable success in global precision medicine and drug discovery challenges, securing seven wins in prestigious competitions including Dream Challenges, BioASQ, and BioCreative over the past eight years. At AIGEN Sciences, he is focused on integrating AI technologies with biomedical research to advance drug discovery and personalized medicine.
          </div>
				</div>
				<div class="keynote-box">
					<!-- <div class="keynote-title">Pre-Foundation-Model-Era for Medical Imaging Analysis: Studies on Self-supervised Learning</div> -->
          <div class="profile-box">
            <img src="@/assets/keynotes/Jin_Ke.jpg" class="profile">
            <div>
              <div class="keynote-speaker">Dr Jin Ke</div>
              <div class="affiliation"><i>Shanghai Jiao Tong University, China</i></div>
            </div>
          </div>
          <div class="speaker-bio">
            Jing Ke is a tenured associate professor at Shanghai Jiao Tong University and holds the academic title of Adjunct Senior Lecturer at the University of New South Wales. Her primary research focus is computer-assisted pathology image analysis, with more than fifty published papers in top journals and conferences, including IEEE Transactions on Medical Imaging (TMI), Medical Image Analysis (MedIA), and MICCAI. Also, Jing has extensive commercial experience in GPU technology, having worked with leading companies like AMD. She has also published over ten papers on computer architectures and parallel computing in renowned venues such as MICRO, DAC, and IPDPS., and authored a book on GPU architecture analysis.
          </div>
				</div>
			</div>
    </div>
  </div>
  <div v-else>
    <div id="keynotes">
			<!-- <h2>Keynotes</h2><hr> -->
      <div class="keynote-box">
        <div class="keynote-title">Towards Human Centered AI: Large Language Models and Domain Knowledge</div>
      <div class="profile-box">
        <img src="@/assets/keynotes/dimitris.jpg" class="profile" style="object-position: top;">
        <div class="">
          <div class="keynote-speaker">
            <a href="https://people.cs.rutgers.edu/~dnm/bio.html" target="_blank">Prof. Dimitris Metaxas</a>
          </div>
          <div class="affiliation"><i>Department of Computer Science, Rutgers The State University of New Jersey</i></div>
        </div>
      </div>
      <div class="speaker-bio">
        <b>Bio.</b> Dr. Dimitris Metaxas is a Distinguished Professor in the Department of Computer Science at Rutgers University since July 2007. From September 2001 to June 2007 he was a Professor in the same department. He is currently directing the Center for Computational Biomedicine, Imaging and Modeling (CBIM). From January 1998 to September 2001 he was a tenured Associate Professor in the Computer and Information Science Department of the University of Pennsylvania and Director of the VAST Lab. Prior to this he was an Assistant Professor in the same department since 1992. Prof. Metaxas received a Diploma in Electrical Engineering from the National Technical University of Athens of Athens Greece in 1986, an M.Sc. in Computer Science from the University of Maryland, College Park in 1988, and a Ph.D. in Computer Science from the University of Toronto, Ontario, Canada in 1992.
      </div>
      </div>
			<div id="keynote-container">
				<div class="keynote-box">
          <div class="keynote-title">Foundation Models for Medical Image Analysis – Preparing for the Next “iPhone Moment” in MICCAI</div>
          <div class="profile-box">
            <img src="@/assets/keynotes/mathias.jpg" class="profile">
            <div>
              <div class="keynote-speaker">
                <a href="https://arcade.cs.jhu.edu/members/mathias-unberath.html" target="_blank">Prof. Mathias Unberath</a>
              </div>
              <div class="affiliation"><i>Department of Computer Science, Johns Hopkins University</i></div>
            </div>
          </div>
          <div class="speaker-bio">
            <b>Keynote Slide: </b>[<a :href="require('@/assets/keynotes/mathias_slide.pdf').default" target="_blank" rel="noopener noreferrer">slide (PDF)</a>]<br>
            <!-- <b>Keynote Slide:</b><a href="@/assets/papers_2024/P1.pdf" target="_blank" class="slides-button"> [slides]</a><br> -->
            <b>Abstract.</b> A new class of machine learning models, often termed foundation models, has started to receive widespread attention in -- and well beyond MICCAI. Trained in flexible manner on large and diverse datasets, foundation models offer unprecedented generalization ability, and if leveraged correctly, broad utility. In this talk, I will first paint a picture of how foundation models may set us off on a trajectory towards the next iPhone moment in MICCAI. I will then substantiate this by providing recent examples of how we develop and use foundation models to tame perpetually challenging problems across MICCAI, concluding with an elaborate discussion of open challenges and opportunities.
            <br><b>Bio.</b> Mathias Unberath is the John C. Malone Associate Professor of Computer Science at Johns Hopkins University, core faculty in the Malone Center for Engineering in Healthcare and the Laboratory for Computational Sensing and Robotics, and affiliate faculty in the Institute for Assured Autonomy. He holds secondary appointments in the School of Medicine. With his team, the ARCADE research group on Advanced Robotics and Computationally AugmenteD Environments, he builds the future of computer-assisted medicine. Through synergistic research on imaging, computer vision, machine learning, and interaction design, they create human-centered solutions that are embodied in emerging technology such as mixed reality and robotics. Mathias has published more than 175 journal and conference articles, and has received numerous awards, grants, and fellowships, including the NSF Career, NIH NIBIB R21 Trailblazer and Google Research Scholar Award, and more than 20 international paper awards.
          </div>
				</div>

			</div>
    </div>
    </div>
    <!-- Preliminary Keynotes End -->
  </div>
</template>

<style scoped>
@media screen and (min-width: 1280px) {
  #keynote {
    width: 1280px;
    min-height: calc(100vh - 80px);
    margin: 0 calc(50vw - 640px);
    padding-bottom: 120px;
    padding-top: 80px;
    background-color: white;
  }

  .main-title {
    margin-top : 44px;
    margin-bottom: 40px;
  }

  h1 {
    font-family: Helvetica;
    margin: 0;
    font-size: 40px;
  }

  .main-title-deco {
    width: 28px;
    height: 1px;
    border: solid 2px #000000;
    background-color: #5b5b5b;
  }

  h2 {
    font-family: Helvetica;
    margin-bottom: 0px;
    font-family: Helvetica;
    font-size: 28px;
  }

  hr {
    border: 1px solid black;
  }

  /* Preliminary Keynote */
  #keynote-container {
    padding: 20px;
  }

  .keynote-box {
    margin-bottom: 50px;
  }

  .keynote-title {
    font-family: Helvetica;
    font-size: 32px;
    font-weight: bold;
    color: #000;
    padding-bottom: 10px;
  }

  .profile-box {
    display: flex;
    align-items: flex-end;
    margin: 10px 15px;
  }

  .profile {
    width: 100px;
    height: 100px;
    margin-right: 20px;
    border-radius: 50px;
    border: solid 1px #979797;
    object-fit: cover;
  }

  .keynote-speaker {
    font-family: Helvetica;
    font-size: 20px;
    font-weight: 300;
    color: #000;
    padding-bottom: 5px;
  }

  .affiliation {
    font-family: Helvetica;
    font-size: 14px;
    font-weight: 300;
    color: #797979;
    padding-bottom: 10px;
  }

  .speaker-bio {
    padding-left:10px;
    padding-top: 5px;
    padding-bottom: 10px;
    font-family: Helvetica;
    font-size: 18px;
    line-height: 1.4;
    color: #000;
  }
  /* Preliminary Keynote End */
}

@media screen and (min-width: 768px) and (max-width: 1279px) {
  #keynote {
    width: 720px;
    min-height: calc(100vh - 64px);
    margin: 0 calc(50vw - 360px);
    padding-bottom: 100px;
    padding-top: 64px;
    background-color: white;
  }

  .main-title {
    margin-top : 44px;
    margin-bottom: 30px;
  }

  h1 {
    font-family: Helvetica;
    margin: 0;
    font-size: 36px;
  }

  .main-title-deco {
    width: 28px;
    height: 1px;
    border: solid 2px #000000;
    background-color: #5b5b5b;
  }

  h2 {
    margin-bottom: 0px;
    font-family: Helvetica;
    font-size: 28px;
  }

  hr {
    border: 1px solid black;
  }

  /* Preliminary Keynote */
  #keynote-container {
    padding: 10px 0;
  }

  .keynote-box {
    margin-bottom: 30px;
  }

  .keynote-title {
    font-family: Helvetica;
    font-size: 28px;
    font-weight: bold;
    color: #000;
    padding-bottom: 10px;
  }


  .profile-box {
    display: flex;
    align-items: center;
    margin: 10px 0;
  }

  .profile {
    width: 100px;
    height: 100px;
    margin-right: 20px;
    border-radius: 50px;
    border: solid 1px #979797;
    object-fit: cover;
  }


  .keynote-speaker {
    font-family: Helvetica;
    font-size: 16px;
    font-weight: 300;
    color: #000;
    padding-bottom: 5px;
  }

  .affiliation {
    font-family: Helvetica;
    font-size: 14px;
    font-weight: 300;
    color: #797979;
  }

  .speaker-bio {
    padding-left:10px;
    padding-top: 10px;
    padding-bottom: 10px;
    font-family: Helvetica;
    font-size: 16px;
    line-height: 1.4;
    color: #000;
  }
  /* Preliminary Keynote End */
}

@media screen and (max-width: 767px) {
  #keynote {
    width: 360px;
    min-height: calc(100vh - 84px);
    margin: 0 calc(50vw - 180px);
    padding-top: 54px;
    padding-bottom: 30px;
  }

  .main-title {
    margin-top : 24px;
    margin-bottom: 30px;
  }

  h1 {
    font-family: Helvetica;
    margin: 0;
    font-size: 24px;
  }

  .main-title-deco {
    width: 20px;
    height: 1px;
    border: solid 2px #000000;
    background-color: #5b5b5b;
  }

  h2 {
    margin-bottom: 0px;
    font-family: Helvetica;
    font-size: 20px;
  }

  hr {
    border: 1px solid black;
  }

  /* Preliminary Keynote */
  #keynote-container {
    padding: 10px 0;
  }

  .keynote-box {
    margin-bottom: 30px;
  }

  .keynote-title {
    font-family: Helvetica;
    font-size: 20px;
    font-weight: bold;
    color: #000;
    padding-bottom: 5px;
  }

  .profile-box {
    display: flex;
    flex-direction: column;
    margin: 10px 0px;
  }

  .profile {
    width: 60px;
    height: 60px;
    margin-bottom: 10px;
    border-radius: 50px;
    border: solid 1px #979797;
    object-fit: cover;
  }


  .keynote-speaker {
    font-family: Helvetica;
    font-size: 16px;
    font-weight: 300;
    color: #000;
    padding-bottom: 5px;
  }

  .affiliation {
    font-family: Helvetica;
    font-size: 12px;
    font-weight: 300;
    color: #797979;
  }

  .speaker-bio {
    padding-left:10px;
    padding-bottom: 10px;
    font-family: Helvetica;
    font-size: 14px;
    line-height: 1.4;
    color: #000;
  }
  /* Preliminary Keynote End */
}
</style>

<script>
export default {
  computed: {
  currentYear() {
    return this.$route.params.year || new Date().getFullYear().toString();
    }
  },
  methods: {
      fetchData() {
      // Use the currentYear computed property to determine which data to fetch
      const year = this.currentYear;
      if (year === '2023') {
        // Fetch and set the data for the 2023 archive
      } else {
        // Fetch and set the data for the current year
      }
    }
  },
  created(){
    this.fetchData();
  },
}
</script>
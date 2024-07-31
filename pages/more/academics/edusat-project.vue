<template>
  <AppContainer>
    <Header title="Edusat Project" />

    <section class="probootstrap-section" style="padding-top: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstrap-flex">
              <div class="probootstrap-text probootstrap-animate">
                <div class="panel panel-grey">
                  <div class="panel-body">
                    <p style="text-align: justify" v-for="(project, index) in projects" :key="index">{{ project }}</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </AppContainer>
</template>

<script>
export default {
  data() {
    return {
      projects:[
        'RGPV along with ISRO has started a Programme of E-education under the EDUSAT Project. The details of the project is available on website www.rgtu.net. RGPV has made all the 62 Colleges of M.P. as his partner in this project. Our college HCET is also one of the partner institutes in this project. Similar type of programmers are running in various other statesb including Maharashtra and Karnataka for last 2 years and it has reported to be giving goodb results.',
        'As we know that there is, in general, shortage of expert faculty in various institutes in M.P. To overcome this gap RGPV has started this project for telecast of lectures from the experts on various enigmatic topics in the curriculum of the engineering in M.P. The government has granted Rs. 300 crores for this project.',
        'Under this project lectures on selected enigmatic topics will be telecast and will be available on the EDUSAT Class Room of all the 62 partner colleges of M.P. The telecast of these topics will be at the selected time well informed in advance to these partner institutes. The students of these institutes will be able to participate in these live lecture telecast and will also be able to interact with the faculty.',
        'For this project Room No. 210 of the Core Block at upper ground floor has been selected for the E Class room. The infrastructure for the class room in the form of 60 computers connected in LAN and the facility of internet broad band is being made available in this room.',
        'Under this project the faculty for delivering lectures from the HCET studio is being selected amongst the available faculty of the Partner Institutes. The Primary faculty will deliver the lecture at the HCET studio and the secondary faculties will manage the E class room at the partner institutes in various colleges at the time of telecast.',
        'For this project the infrastructure and technical support for the infrastructure required will be provided by the ISRO. ISRO has provided the Antenna and one set of LCD with handicam to the partner institutes and these will be installed by the expert team of the ISRO at these partner institutes.',
        'The other necessary infrastructure shall be arranged by the partner institutes. These lectures will be telecast during 11.00 AM to 1.00 PM and will be retelecast on some suitable time on predefined days.',
        'It is expected that this telecast will be available from 15th August, 2007.',
        'The telecast will be highly beneficial for the students as they will be exposed to the expert lectures of selected enigmatic topics. As also this will be beneficial to the young faculty who will get the benefit to learn to deliver expert lectures and to enhance there knowledge.'
      ]
    }
  },
}
</script>

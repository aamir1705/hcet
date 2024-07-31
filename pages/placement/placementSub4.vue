<template>
  <AppContainer>
    <Header title="Our Vision" />
    <section class="probootstrap-section" style="padding-top: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstrap-flex">
              <div class="probootstrap-text probootstrap-animate">
                <div class="panel panel-grey">
                  <div class="panel-heading">
                    <h4 class="panel-title">Our Mission ...</h4>
                  </div>
                  <div class="panel-body">
                    <p style="text-align:justify;">The mission of the training and placement cell of HCET is to develop
                      the students into future leaders who are technically sound, and turn into positive human being
                      with
                      a vision in life. The overall emphasis is laid on ...
                    </p>
                    <ul>
                      <li v-for="(item, index) in items" :key="index">{{ item }}</li>
                    </ul>
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
      items:[
        "Understand the basic needs of a particular company and preparing students accordingly.",
        "Differentiate between IT sectors and core companies and yearly need.",
        "Designing various training methods as per students caliber and preparing them accordingly thereby making them competent to find placements in various companies.",
        "Develop an understanding of the criterias of companies and their needs from any technical institution in developing students as per industrial projects and changing market scenario.",
        "To develop the students skill in facing interviews.",
        "To develop the overall personality.",
        "To expose them to all the experts in various engineering fields.",
        "To keep them abreast of all the latest happenings in the field of latest technology.",
        "To provide necessary infrastructure and platform to the students to improve their  knowledge.",
        "Incessantly exploring the possibilities of creative potential of every student through the unified field based integrated training for maximizing placement by campus selection.",
        "Time, for the career to seek new heights.",
        "To provide expert exposure to candidates in various engineering fields.",
        "To keep the candidates abreast with the latest in the art of technology.",
        "To provide necessary literature / magazines / books / video tapes, CDs etc",
      ]
    }
  },
}
</script>
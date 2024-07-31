<template>
  <AppContainer>
    <Header title="Teaching Learning Process" />
    <section class="probootstrap-section" style="padding-top: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstrap-flex">
              <div class="probootstrap-text probootstrap-animate">
                <div class="panel panel-grey">
                  <div class="panel-body">
                    <h4>Stress on Academics along with Discipline and overall personality Development.</h4>
                    <h3>PROGRESSIVE PRACTICE</h3>
                    <p v-for="item in items">{item}</p>
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
      items: [
        "Suggestions and Feedback from Students and Staff given due consideration.",
        "Numerous rewards and incentives for students and faculty members to promote excellence in performance in respective areasRegular expansion and up gradations of Library, Lab Equipments, Technological devices and IT Equipments.",
        "Encouragement for hands on experience by involving students in projects.",
        "Inclusion of project experience from fourth semester onwards.",
        "Encouragement of use of Digital and Electronic aids of learning and teaching by Students and Faculty.",
        "Regular exposure for students and Faculty for seminars and expert lectures.",
        "Orientation program for new students.",
        "Extra and remedial classes for the required.",
        "Regular communication with parents.",
        "Access and purposeful interaction of the students with Faculty.",
        "Monthly Audit Meeting called by High Power Committee of the Management for review &amp; planning of departmental activities.",
        "A specialized department 'III &amp; SSD' - Industry Institute Interaction and Student and staff Development has been created to forge better Industry Institute Interactions and ensure continuous developments of students and staff.",
        "The college has fully functional centers for Innovation &amp; Entrepreneurship.",
        "College conducts regularly JOB FAIR- A unique placement extravaganza wherein students from not only our college but students from all across the state get to participate in it for placements.",
        'A Unique indigenously developed tool "Teaching Diary" for purpose of academic planning and monitoring of subject delivery in a class implemented for every subject in all semesters. The Teaching Diary helps implementers of teaching process to keep track of progress and take corrective measures for any variation in time.',
        "Laboratories and libraries are open for twelve hours a day.",
        "Counseling for carrier guidance and monitoring of the Student progress by specially formed team of the Faculty.",
      ]
    }
  },
}
</script>

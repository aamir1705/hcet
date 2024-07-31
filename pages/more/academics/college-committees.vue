<template>
  <AppContainer>
    <Header title="College Committees" />

    <section class="probootstrap-section" style="padding-top: 25px">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="probootstrap-flex">
              <div class="probootstrap-text probootstrap-animate">

                <div class="panel panel-grey">

                  <div class="panel-body">
                    <h4 align="center"> The Committees Shown below will function</h4>
                    <ul>
                      <li v-for="item in items">{item}</li>
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
      items: [
        "Discipline Committee",
        "Literary Activities Committee",
        "Admission Committee",
        " Academic Calendar, Time Table Preparation, paper and Result Analysis Committee",
        "Press and Publication Committee",
        "Website Development and Maintenance Committee",
        "Attendance Monitoring Committee",
        "Inter College and College Level Sports Committee",
        "Hitkarini Vidya Parishad Mtg. Members Committee",
        "Anti Ragging Committee",
        "Purchase Committee",
        "Social Gathering and Cultural Activities Committee",
        "Seminar / Guest Lecturer / Technical Visit Conference Organizing Committee",
        "Condemnation Committee",
        "Central Networking and Network Maintenance Committee",
        "Library and E-Journals Committee",
        "HECCA Committee"
      ]
    }
  },
}
</script>

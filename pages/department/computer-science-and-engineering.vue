<template>
  <AppContainer>
    <Header title="Department of Computer Science" />

    <Department>
      <section>
        <img alt="" class="" src="/img/nitin.jpg" />
        <p><strong>Prof. Nitin Jharbade</strong></p>
        <p><strong>HOD, CS Dept.</strong></p>
      </section>
      <section>
        <p class="text-justify">
          There are 6 computer centres,well equipped with 6 powerful servers for
          Networking in Win NT 4.0, SCO UNIX and Windows 2000 , connectivity
          using the advantages of star topology. In addition the computer
          centres have 250 Pentium-IV systems with high configuration, connected
          to these networks.
        </p>

        <p class="text-justify">
          H.C.E.T. has the latest software like ORACLE 8 I Workgroup Server 8.0,
          Developer 2000, Visual Studio 6.0, Turbo C++/ Turbo assembler, Auto
          Desk, AutoCad R14, Cobol, Pascal, Fortran77, MS Office 2000 running on
          OS like Win NT, Win 98, Win ME and Windows 2000.
        </p>

        <p class="text-justify">
          All the systems are backed up with safety and security features.
          Anti-Virus software like Norton 2001, PC Cillin 2000 and McAFee are
          guarding the systems.
        </p>

        <p class="text-justify">
          Generally Speaking, the courses related with the word"Computing" come
          with a variety of titles. Courses with the word 'computing' in their
          title will be more biased towards practical applications, and courses
          based around 'computer science' will have a more theoretical content.
          Computer Science and Engineering covers Software Engineering,Computer
          systems, Artificial Intelligence, Information System Management,
          Computer Science and Mathematics.
        </p>
      </section>
    </Department>

    <Table :table_row_names="table_row" :data_sets="data" />

    <H3Light>Major Project Presentation</H3Light>

    <section class="flexslider">
      <ul class="slides">
        <li style="background-image: url(img/cs1.JPG)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center"></div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/csDept1.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1
                    style="
                      font-size: 70px;
                      font-display: block;
                      font-weight: 400;
                      margin: 10px;
                      color: cornsilk;
                    "
                  >
                    DOM Lab
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li style="background-image: url(img/csDept2.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1
                    style="
                      font-size: 70px;
                      font-display: block;
                      font-weight: 400;
                      margin: 10px;
                      color: cornsilk;
                    "
                  >
                    VLSI Lab
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </section>
  </AppContainer>
</template>

<script>
export default {
  data() {
    return {
      table_row: ["#", "Name", "Designatiom"],
      data: [
        ["1", "PROF. NITIN JHARBADE", "PROF. & HOD"],
        ["2", "PROF. AJAY ACHARYA", "	A.PROF."],
        ["3", "PROF. MANISH BAHRANI", "	A.PROF."],
        ["4", "PROF. SHAILJA GUPTA", "	A.PROF."],
        ["5", "PROF. GEETIKA KHATRI", "	A.PROF."],
        ["6", "PROF. POOJA DUBEY", "	A.PROF."],
        ["7", "PROF. BRAJESH MISHRA", "	A.PROF."],
        ["8", "PROF. PRADEEP VISHWAKARMA", "	A.PROF."],
      ],
    };
  },
};
</script>

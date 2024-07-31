<template>
    <AppContainer>

      <Header title="Academics Achievements" />
  
      <section class="probootstrap-section" style="padding-top: 25px">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="probootstrap-flex">
                <div class="probootstrap-text probootstrap-animate">
  
                  <div class="panel panel-grey">
  
                    <div class="panel-body">
                      <p align="justify"><strong>PRAKASH GAHARWAR MEMORIAL GOLD MEDAL</strong> Shri Prakash Singh
                        Gaharwar,
                        son of Shri V.B. Singh Gaharwar, a student of B.E., E&amp;TC 2000-2001 batch, expired on 25th
                        October 2001 and is fondly remembered by students and staff of the college. Shri V.B. Singh
                        Gaharwar
                        has instituted <b>GOLD MEDALS</b> in the memory of his son which were awarded to the students
                        obtaining First position in varios branches of B.E.</p>
                      <h4 align="center">WINNERS of the PRAKASH GAURAWAR GOLD MEDAL</h4>
                      <p align="center">(Awarded by His Excellency Shri T.N. Chaturvedi, Governor of Karnatak)</p>
                      &nbsp;&nbsp;
  
                      <table class="table table-bordered">
                        <tbody>
                          <tr>
                            <td width="10%" align="center"><strong>Year</strong></td>
                            <td width="25%" align="center"><strong>Computer Science &amp; Engg.</strong></td>
                            <td width="30%" align="center"><strong>Electronics &amp; Communication Engg.</strong></td>
                            <td width="25%" align="center"><strong>Mechanical Engineering</strong></td>
                          </tr>
                          <tr v-for="(item, index) in items" :key="index">
                            <tr v-for="value in item" :key="value">{ value }</tr>
                          </tr>

                        </tbody>
                      </table>
  
  
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
            items: [                          [
                            "2001" ,
                            "Shruti Jain",
                            "Sachin Kumar",
                            "Pradeep Shrivastava"
        ],
                          [
                            "2002",
                            "Sucharita Chakravarty",
                            "Parmjeet Singh Pasrija",
                            "Amit Kumar"
        ],
                          [
                            "2003",
                            "Preeti Shukla",
                            "Pooja Kulshreshtha",
                            "Ayan Bose"
        ],
                          [
                            "2004",
                            "Deepali Chourasia",
                            "Swati Purohit",
                            "Harshita Rusia"
        ],
                          [
                            "2005",
                            "Preeti Pandey",
                            "Anurag Jain",
                            "Rohit Suri"
        ],
                          [
                            "2006",
                            "Navdeep Wadhawa",
                            "Natasha Shrivastava",
                            "Shaswat Mitra"
        ],
                          [
                            "2007",
                            "Dew Ghosh",
                            "Ekta Gaur",
                            "Debottam Biswas"
        ],
                          [
                            "2008",
                            "Aditi Jain",
                            "Shrikant Dhikarla",
                            "Vikash Gugliani"
        ],
                          [
                            "2009",
                            "Pooja Somya",
                            "Hina Mahajan",
                            "Sudeep Sarkar"
        ],
                          [
                            "2010",
                            "Komal Anandani",
                            "Charan Singh Jhans ",
                            "Anurag Singh"
        ],
                          [
                            "2011",
                            "Parul Gupta",
                            "Harshit Payas",
                            "Kumar Gaurav Singh"
        ],
                          [
                            "2012",
                            "Priya Ghosh",
                            "Sachin Mehra",
                            "Sandeep Kesri"
                        ],
  ]
        }
    },
}
</script>
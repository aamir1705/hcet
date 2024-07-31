<template>
  <div>
    <section class="probootstrap-section probootstrap-section-colored">
      <div class="container">
        <div class="row">
          <div class="col-md-12 text-left section-heading probootstrap-animate">
            <h1 class="mb0">Programmes Offered - 2023</h1>
          </div>
        </div>
      </div>
    </section>



    <section class="probootstrap-section probootstrap-section-sm">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="row probootstrap-gutter0">

              <div class="col-md-7 col-md-push-1  probootstrap-animate" id="probootstrap-content">
                <h2>Get In Touch</h2>
                <p>Get the details you want from us, regarding admission</p>
                <form id="myForm" action="https://sheetdb.io/api/v1/1zagekwftlm8s" method="POST"
                  class="probootstrap-form">
                  <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" class="form-control" id="name" name="data[name]">
                  </div>
                  <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" class="form-control" id="email" name="data[email]">
                  </div>
                  <div class="form-group">
                    <label for="subject">Contact NO</label>
                    <input type="text" class="form-control" id="subject" name="data[contact no]">
                  </div>

                  <div class="form-group">
                    <label for="subject">City</label>
                    <input type="text" class="form-control" id="subject" name="data[city]">
                  </div>

                  <div class="form-group">
                    <label for="branch">Branch Preference:</label>
                    <br />
                    <select name="data[branch]" id="branch">
                      <option value="BTECH - Computer Science">BTECH - Computer Science</option>
                      <option value="BTECH - Information Technology">BTECH - Information Technology</option>
                      <option value="BTECH - Civil Engineering">BTECH - Civil Engineering</option>
                      <option value="BTECH - Electronics &amp; Communication Engineering">BTECH - Electronics &amp;
                        Communication Engineering</option>
                      <option value="BTECH - Electrical &amp; Electronics Engineering">BTECH - Electrical &amp;
                        Electronics Engineering</option>
                      <option value="BTECH - Civil Engineering">BTECH - Civil Engineering</option>
                      <option value="BTECH - Mechanical Engineering">BTECH - Mechanical Engineering</option>

                    </select>

                  </div>

                  <div class="form-group">
                    <button id="click-me" onclick="alert('Form submitted Successfully')" type="submit"
                      class="btn btn-primary btn-lg">Submit</button>
                  </div>
                </form>
              </div>

            </div>

          </div>
        </div>
      </div>
    </section>

    <section class="flexslider">
      <ul class="slides">

        <li style="background-image: url(img/couns1.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                    Counselling</h1>

                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/couns2.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                  </h1>

                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/couns3.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                  </h1>

                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/couns4.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                  </h1>

                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/couns5.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                  </h1>

                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/couns6.jpg)" class="overlay">
          <div class="container">
            <div class="row" slider-wrapper>
              <div class="col-md-8 col-md-offset-2">
                <div class="probootstrap-slider-text text-center">
                  <h1 style="font-size: 70px; font-display: block; font-weight: 400; margin: 10px; color: cornsilk">
                  </h1>

                </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </section>
  </div>
</template>

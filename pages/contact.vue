<template>
  <AppContainer>
    <Header title="Contact Us" />

    <section class="probootstrap-section probootstrap-section-sm">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="row probootstrap-gutter0">
              <div class="col-md-4" id="probootstrap-sidebar">
                <div
                  class="probootstrap-sidebar-inner probootstrap-overlap probootstrap-animate"
                >
                  <h3>Pages</h3>
                  <ul class="probootstrap-side-menu">
                    <li><a href="/">Home</a></li>
                    <li><a href="courses.html">Courses</a></li>
                    <li><a href="teachers.html">Faculty</a></li>

                    <li><a href="about.html">About Us</a></li>
                    <li class="active"><a>Contact Us</a></li>
                  </ul>
                </div>
              </div>
              <div class="flex flex-col gap-10">
                <h2>Get In Touch</h2>
                <p>Contact us using the form below.</p>
                <form  action="#" method="post" class="flex flex-col gap-10">
                  <div>
                    <label for="name">Full Name</label>
                    <input
                      type="text"
                      class="bg-white border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
                      id="name"
                      name="name"
                    />
                  </div>
                  <div>
                    <label for="email">Email</label>
                    <input
                      type="email"
                      class="bg-white border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
                      id="email"
                      name="email"
                    />
                  </div>
                  <div>
                    <label for="subject">Subject</label>
                    <input
                      type="text"
                      class="border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
                      id="subject"
                      name="subject"
                    />
                  </div>
                  <div>
                    <label for="message">Message</label>
                    <textarea
                      cols="30"
                      rows="10"
                      class="bg-white border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
                      id="message"
                      name="message"
                    ></textarea>
                  </div>
                  <div>
                    <button type="submit" class="bg-[#49D292] border-[#49D292] py-4 px-12 text-white rounded-full ">
                      Send Message
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <section class="flexslider">
              <ul class="slides">
                <li>
                  <div class="item">
                    <iframe
                      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3668.1881730856235!2d79.99478101535573!3d23.16333126686425!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x7a8002ac2a17d69!2sHitkarini%20College%20of%20Engineering%20and%20Technology!5e0!3m2!1sen!2sin!4v1614106959661!5m2!1sen!2sin"
                      width="1000"
                      height="500"
                      allowfullscreen=""
                      loading="lazy"
                      style="overflow: hidden; position: inherit; border: 0"
                    ></iframe>
                  </div>
                </li>
              </ul>
            </section>
          </div>
        </div>
      </div>
    </section>
  </AppContainer>
</template>

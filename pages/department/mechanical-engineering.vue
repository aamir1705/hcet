<template>
  <AppContainer>
    <Header title="Department of Mechanical Engineering" />
    <Department>
      <section>
        <img alt="" src="/img/manish.png" />
        <p><strong>Prof. M.K. Chowdhary</strong></p>
        <p><strong>Head</strong></p>
      </section>
      <section>
        <p class="text-justify">
          In developing its undergraduate laboratories, the HCET's Department of
          Mechanical Engineering has considered the direction in which it thinks
          the mechanical engineering profession is headed over the next few
          decades. Computing and information technologies are radically changing
          how mechanical engineering is practiced. In many industries, these
          technologies have almost entirely replaced paper-based methods for
          design and analysis. Advances in networking, software and processing
          power are on the verge of allowing any engineer to have access to
          advanced computer-aided design (CAD) and analysis software, web-based
          communications, information data bases and numerically controlled
          prototyping processes all seamlessly linked and accessible from a
          single desktop machine.
        </p>

        <p class="text-justify">
          This transformation is changing how products are produced and tested.
          Mass customization is one manufacturing trend being made possible by
          these technologies. If design and automated manufacturing methods are
          linked, design changes can be quickly made and converted into
          finished, custom-designed products.
        </p>

        <p class="text-justify">
          The fundamentals of mechanical engineering have not changed, but
          revolutionary changes are occurring in how fundamentals are applied by
          practicing engineers. The key skill set now in demand for graduating
          mechanical engineers is comfort in combining the use of computational
          tools, hands-on intuition and engineering fundamentals. In fact,
          physical intuition gained from laboratory experiences is perhaps even
          more critical now than in the past because practicing engineers are
          expected to make significant design and analysis decisions before any
          product testing occurs. Our goal in developing our undergraduate
          laboratories is to prepare HCET's mechanical engineering students to
          not only meet this demand of the evolving mechanical engineering
          workplace, but to also be positioned to act as leaders in its
          transformation.
        </p>
      </section>
    </Department>
    <H3Light>
      Laboratories available for students of Mechanical Engineering:
    </H3Light>

    <ul class="list-disc">
      <li><span style="font-size: 16px">CAD/CAM</span></li>
      <li>
        <span style="font-size: 16px">Refrigeration &amp; Airconditioning</span>
      </li>
      <li><span style="font-size: 16px">Fluid Mechanics</span></li>
      <li><span style="font-size: 16px">Heat &amp; Mass Transfer</span></li>
      <li><span style="font-size: 16px">Automobile</span></li>
      <li><span style="font-size: 16px">Turbo Machinery</span></li>
      <li>
        <span style="font-size: 16px">Vibration &amp; Noise Control</span>
      </li>
      <li><span style="font-size: 16px">Simulation &amp; Modeling</span></li>
      <li><span style="font-size: 16px">KOM/DOM</span></li>
    </ul>
    <Table :table_row_names="table_rows" :data_sets="data" />

    <H3Light>Major Project Presentation</H3Light>
    <section class="flexslider">
      <ul class="slides">
        <li style="background-image: url(img/me2.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li style="background-image: url(img/me.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/me1.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>
        <li style="background-image: url(img/me2.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li style="background-image: url(img/AKT_0756.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li style="background-image: url(img/AKT_0755.JPG)" class="overlay">
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
                  ></h1>
                </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </section>

    <H3Light>Details of Labs:</H3Light>

    <table style="width: 537pt; border-collapse: collapse; border: none">
      <tbody>
        <tr>
          <td
            style="
              width: 40.75pt;
              border: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <strong
                ><span style="font-family: 'Arial', sans-serif"
                  >S.NO.</span
                ></strong
              >
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-image: initial;
              border-left: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <strong
                ><span style="font-family: 'Arial', sans-serif"
                  >SEMESTER</span
                ></strong
              >
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-image: initial;
              border-left: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <strong
                ><span style="font-family: 'Arial', sans-serif"
                  >LAB NAME</span
                ></strong
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-image: initial;
              border-left: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <strong
                ><span style="font-family: 'Arial', sans-serif"
                  >MAJOR FACILITY</span
                ></strong
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="6"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">1</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VIII</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Refrigeration &amp; Air-conditioning</span
              >
            </p>
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">&nbsp;</span>
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Air conditioning trainer.</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cooling Tower</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >ICE Plant Trainer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Domestic Refrigerator Trainer(VCRC Test Ring)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Vapour Absorption refrigeration trainer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermoelectric refrigeration tutor</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">2</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VIII</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Computer Integrated Manufacturing</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >PLC Trainer, Robotic Arm</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">3</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VIII</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Advance M/c Design</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Parkinson Gear Cutting Tester</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="22"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">4</span>
            </p>
          </td>
          <td
            rowspan="22"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VII</span>
            </p>
          </td>
          <td
            rowspan="22"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Automobile Engineering</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Electric equipments demo. Board</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Carburetor in cut section</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <ol start="1" style="margin-bottom: 0cm; margin-top: 0cm" type="a">
              <li
                style="
                  margin-top: 0cm;
                  margin-right: 0cm;
                  margin-bottom: 0cm;
                  margin-left: 0cm;
                  line-height: normal;
                  font-size: 15px;
                  font-family: 'Calibri', sans-serif;
                  text-align: center;
                "
              >
                <span style="font-family: 'Arial', sans-serif"
                  >S.U Carburetor</span
                >
              </li>
            </ol>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >b. Solex Carburetor</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Fuel pump</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >a. &nbsp; &nbsp; Mechanical type</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >b. Electrical type</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Differential gear assembly</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Const. mesh gear box</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Complete chassis of Jeep</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Steering Mechanism (Rack &amp; Pinion)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Steering Mechanism (Worm &amp; Sector Type)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Working Model of clutch system</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Hydraulic Brake System</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Suspension System of Fiat car</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Fuel injection system (Six cylinder)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Working Model of ignition system (Four cylinder)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Working Model of fuel supply system (Four cylinder)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Paddle Pump</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Rexene Cover</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Gear Box (Synchronies Type)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cut Section Model of Wankle Engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">5</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VII</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >OR and chain supply management</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >TORA Software</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">6</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VII</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Vibration Lab</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Vibration Test rig capable of performing 12 different
                experiments on vibration analysis.</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="18"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">7</span>
            </p>
          </td>
          <td
            rowspan="18"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            rowspan="18"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat and Mass Transfer Lab</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermal Conductivity of liquid</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermal Conductivity of insulating powder</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermal conductivity of Gourded hot plate</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat transfer in Natural Convection</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat transfer in &nbsp;Forced convection</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat transfer in Pin-Fin Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat transfer from lagged pipe</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Heat pipe demonstrator</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Emmissivity Measurement Appararus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Composite Wall apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Steafan Boltzman Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Critical Heat Flux Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Parallel Flow/CounterFlow Heat Exchanger</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Drop &amp; Film Condensation Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Critical Heat Flux apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Shell &amp; Tube Heat Exchanger</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Regenerative Heat Exchanger</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Plate type Heat Exchanger</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">8</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Metal Cutting &amp; CNC</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Lathe,Milling,Drilling,Shaping,Gear Tester etc.</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="6"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">9</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Turbo mechanics</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Francis Turbine Test Rig</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Pelton Wheel Test Rig</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Air Blower Test Rig</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Impact of Jet apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Kaplan Turbine Test Rig</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Air Compressor Test Rig</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="5"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">10</span>
            </p>
          </td>
          <td
            rowspan="5"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            rowspan="5"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Internal Combustion Engine</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Four cylinder Four stroke Petrol enging</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single Cylinder Four Stroke Diesel Engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cut Section Model of IC Engine(Petrol &amp;Diesel)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single cylinder two stroke petrol engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Exhaust gas analyzer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="12"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">11</span>
            </p>
          </td>
          <td
            rowspan="12"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            rowspan="12"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Computer Aided Engineering</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">NY-Nastron</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >(WindowsNT/2000/XP SGI IRIX,HP UX,</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Sub Solaris,IBM AIX Vol1 of 1)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Fe-Map,NX-Nastron</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Basic,Non Linear Nastron</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Hyper works</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Solid Edge</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Artisan</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Simulation</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Mech Design</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Ketia</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Ansis</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="5"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">12</span>
            </p>
          </td>
          <td
            rowspan="5"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">VI</span>
            </p>
          </td>
          <td
            rowspan="5"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Dynamics of machines</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Whirling of Shaft Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cam analysis &nbsp; &nbsp; &nbsp;apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Static and Dynamic Balancing Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Motorized Gyroscope</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              height: 16.15pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal Governor Apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="6"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">13</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">V/IV</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Fluid Mechanics</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Apparatus for determination of losses in pipe line</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Discharge of Notches and Weirs</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Venturimeter, Orifice meter, Frictional Losses in pipes</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Bernoulli&rsquo;s theorem</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Calibration of Rota meter</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Determination of Orifice and Mouthpiece</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="6"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">14</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">IV</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Theory of machines</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Four bar mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Slider crank mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Differential gear mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Gear train mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal gyroscope</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cam analysis apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="3"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">15</span>
            </p>
          </td>
          <td
            rowspan="3"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">IV</span>
            </p>
          </td>
          <td
            rowspan="3"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermal Engineering.&amp; gas dynamics</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Steam power plant</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Reciprocating air compressor</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Centrifugal air compressor</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="39"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">16</span>
            </p>
          </td>
          <td
            rowspan="39"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">IV/III</span>
            </p>
          </td>
          <td
            rowspan="39"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Machine Drawing &amp; Design</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Crank &amp; Connecting rod model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Kinematic pairs</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Internally Expanding Brake</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Shafting Journal Bearing</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Knuckle Joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Cotter Joint</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Gibb &amp; Cotter Joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Tie Rod Joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Socket &amp; Spigot Joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Eccentric Model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Expansion Steam Trap</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Hooks Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Flexible Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Box or Muff Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Flanged Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Split Muff Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Claw Clutch</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Feed Check Valve</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Plate Clutch</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Fusible plug</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Locking Bolt</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Rivets (04 Types)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Riveted Joints ( Three types)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Lever Safety Valve</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Spring Loaded Safety Valve</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Water Gauge</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Stop Valve (Hopkins type)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Crank &amp; Connecting rod model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Hooks coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Foundation bolt set</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Foundation bolt set of four</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Key set of five</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cross head model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Standard bolt</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Bolts of four type</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Combined high steam &amp; low water</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Uniflow steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Float steam trap</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Computer P-4 &amp; softwres like Solid Edge &amp; Auto Cad for
                Drawing</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="28"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">17</span>
            </p>
          </td>
          <td
            rowspan="28"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">III</span>
            </p>
          </td>
          <td
            rowspan="28"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Kinematics of Machines</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Slide crank mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >a. Reciprocating Engine Mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >b. Oscillating Cylinder Mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >c. Whit worth &nbsp;Mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Ellipse Tracer model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Watt&apos;s Mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Kinematic Pairs</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Oldham&apos;s Coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single Helical Gears</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single Stage Spiral gears</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Herringbone Gears</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Geneva Drive</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Peucelleaur Linkage Drive Model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cam &amp; follower set</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Sleeve &amp; cotter joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Governor Model (Four Types)</span
              >
            </p>
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">&nbsp;</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Band brake model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Band &amp; block brake</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Pantograph mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Green economizer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Conical friction clutch</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Slide crank mechanism</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single shoe brake</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Blow-off cock</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cam &amp; follower set</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Sleeve &amp; cotter joint</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal coupling</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="9"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">18</span>
            </p>
          </td>
          <td
            rowspan="9"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">III</span>
            </p>
          </td>
          <td
            rowspan="9"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermodynamics</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >D-Slide valve steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Piston valve steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Compound steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Uniflow steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cornish Boiler</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >D-Slide valve steam engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Gas turbine models</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Steam turbine models</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Turbo Jet engine model</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">19</span>
            </p>
          </td>
          <td
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">III</span>
            </p>
          </td>
          <td
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Production Processes</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Lathe, Milling, Shaping, Drilling machines etc.</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="4"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">20</span>
            </p>
          </td>
          <td
            rowspan="4"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">III</span>
            </p>
          </td>
          <td
            rowspan="4"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Strength mechanics of materials</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Impact testing m/c</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Hardness testing m/c</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Torsion testing m/c</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal testing m/c(FIE)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="11"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">21</span>
            </p>
          </td>
          <td
            rowspan="11"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">V/VI</span>
            </p>
          </td>
          <td
            rowspan="11"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Solar Energy</span>
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Precision Pyranometer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermoelectric Pyreheliometer(Long Tube)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Thermoelectric Pyreheliometer(Short Tube)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Shading Ring</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Sunshine Recorder</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Sunshine Recorder</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Cord for Sunshine Recorder</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >4-Channel Electronic Integrated Printer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Energy sun Tracking Device</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single Point Potentiometric Recorder</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Radiation Integrator</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="6"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">22</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">III/IV</span>
            </p>
          </td>
          <td
            rowspan="6"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Material Science</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Metzer-M make monocular inclined metallurgical</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >microscope magnification 100X to 675X</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Metzer-M make singledisc polisher variable speed</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Metzer-M make belt surface coupled with</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >0.5HP TFFC 220V</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Metzer-M make muffle furnace temp up to 900C</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="15"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">23</span>
            </p>
          </td>
          <td
            rowspan="15"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">I/II</span>
            </p>
          </td>
          <td
            rowspan="15"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Basic Mechanical Engineering</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of two stroke petrol engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of four stroke petrol engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of two stroke diesel engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of four stroke diesel engine</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Combined high steam &amp; low water</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Float steam trap</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Pulley Different type (4 no.) 1 Set</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Pulley drive singleV belt type</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Pulley drive doubleV belt &nbsp;2 speed</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Loose &amp; fast pulley drive flat belt</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Single spur gear</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Two stage spur gear</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Three stage spur gear</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of Locomotive boiler</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Model of Lancashire boiler</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="21"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">24</span>
            </p>
          </td>
          <td
            rowspan="21"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">I/II</span>
            </p>
          </td>
          <td
            rowspan="21"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Engineering</span>
            </p>
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Mechanics</span>
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Apparatus of Polygon of Forces</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Compound Screw jack</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Compound Wheel &amp; Axle</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Friction slide apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >M.I. of Flywheel apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Screw Jack</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Simple Jib Crane</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Triangle &amp; Parallelogram of Forces</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">apparatus</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Wheel &amp; differential axle</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Winch crane double purchase</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Worm &amp; worm wheel(double purchase)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Worm &amp; worm wheel(triple purchase)</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Roof truss apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Force apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Bending moment apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Centrifugal force apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Rope brake dynamometer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Prony brake dynamometer</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Universal force table</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Combined coil &nbsp;and belt force apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            rowspan="4"
            style="
              width: 40.75pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">25</span>
            </p>
          </td>
          <td
            rowspan="4"
            style="
              width: 71.35pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif">I/II</span>
            </p>
          </td>
          <td
            rowspan="4"
            style="
              width: 122.8pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Engineering Graphics</span
              >
            </p>
          </td>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Solid Edge version-20</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Models of Solids</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Projection of line apparatus</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 302.1pt;
              border-top: none;
              border-left: none;
              border-bottom: 1pt solid windowtext;
              border-right: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: top;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
                text-align: center;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >Models f intersection of surfaces</span
              >
            </p>
          </td>
        </tr>
      </tbody>
    </table>

    <H3Light>Important Lab Equipments:</H3Light>

    <ul class="list-disc">
      <li>
        <span style="font-family: 'Arial', sans-serif"
          >Vapour Absorption refrigeration trainer: To analyze performance of
          VARS at different pressure and temperatures using integrated
          software.</span
        >
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif"
          >Parkinson Gear Cutting Tester: To find out different gear cutting
          parameters using microscope.</span
        >
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif"
          >Pelton Wheel &amp; Francis Turbine test rigs.</span
        >
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif">Wind tunnel.</span>
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif"
          >Vibration Test rig capable of performing 12 different experiments on
          vibration analysis</span
        >
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif"
          >Lathe, Milling, Drilling, Shaping, Gear Tester etc.</span
        >
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif">Steam power plant</span>
      </li>
      <li>
        <span style="font-family: 'Arial', sans-serif">Soft wares like :</span>
      </li>
    </ul>
    <table
      style="
        width: 139.5pt;
        margin-left: 41.4pt;
        border-collapse: collapse;
        border: none;
      "
    >
      <tbody>
        <tr>
          <td
            style="
              width: 139.5pt;
              border: 1pt solid windowtext;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Hyper works</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 139.5pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Solid Edge</span>
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 139.5pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Artisan</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 139.5pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Simulation</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 139.5pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif"
                >IDEAS Mech Design</span
              >
            </p>
          </td>
        </tr>
        <tr>
          <td
            style="
              width: 139.5pt;
              border-right: 1pt solid windowtext;
              border-bottom: 1pt solid windowtext;
              border-left: 1pt solid windowtext;
              border-image: initial;
              border-top: none;
              padding: 0cm 5.4pt;
              vertical-align: bottom;
            "
          >
            <p
              style="
                margin-top: 0cm;
                margin-right: 0cm;
                margin-bottom: 0cm;
                margin-left: 0cm;
                line-height: normal;
                font-size: 15px;
                font-family: 'Calibri', sans-serif;
              "
            >
              <span style="font-family: 'Arial', sans-serif">Ketia</span>
            </p>
          </td>
        </tr>
      </tbody>
    </table>

    <br />

    <H3Light> Laboratories - Professor Incharge & Technical Staff: </H3Light>
    <Table :table_row_names="table_row_2" :data_sets="data_2"  />
    

    <section class="flexslider">
      <ul class="slides">
        <li
          style="background-image: url(img/MEDepartment1.jpg)"
          class="overlay"
        >
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
                    Refrigeration &amp; Air-Conditioning Lab
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li
          style="background-image: url(img/MEDepartment2.jpg)"
          class="overlay"
        >
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
                    Kinematics & Dynamics of Machine and Mechanism
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li
          style="background-image: url(img/MEDepartment3.jpg)"
          class="overlay"
        >
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
                    Thermal Engg. & Turbo Machinery
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li
          style="background-image: url(img/MEDepartment4.jpg)"
          class="overlay"
        >
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
                    Basic Mechanical Engg. Lab
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li
          style="background-image: url(img/MEDepartment5.jpg)"
          class="overlay"
        >
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
                    Vibration Lab
                  </h1>
                </div>
              </div>
            </div>
          </div>
        </li>

        <li
          style="background-image: url(img/MEDepartment6.jpg)"
          class="overlay"
        >
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
                    Heat &amp; Mass Transfer Lab
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
      table_rows: ["#", "Name", "Designatiom"],
      data: [
        ["1", "PROF. MANISH KUMAR CHOUDHARY", "PROF. & HOD"],
        ["2", "DR. ABHISHEK SONI", "	A.PROF."],
        ["3", "PROF. DEVANSHU PYASI	", "	A.PROF."],
        ["4", "PROF. VIVEK PATHAK", "	A.PROF."],
        ["5", "PROF. BIMLESH KUMARI", "	A.PROF."],
        ["6", "PROF. VIJAY PARASHAR", "	A.PROF."],
        ["7", "PROF. ASHWANI SHRIVASTAVA", "	A.PROF."],
        ["8", "PROF. YADRAM SINGH", "	A.PROF."],
        ["9", "PROF. PRAVEEN JHA", "	A.PROF."],
        ["10", "PROF. SANTOSH BEOHAR", "	A.PROF."],
        ["11", "PROF. RAKESH MEHRA", "	A.PROF."],
      ],
      table_rows_2: [
        "S.N.",
        "Name of Lab",
        "Sem",
        "In-Charge",
        "Supporting Staff",
      ],
      data_2: [
        [
          "1",
          "	Basic Mechanical Engg.",
          "I/II",
          "Prof. A.Soni",
          "Mr. Ajay Singh Thakur",
        ],
        [
          "2",
          "	Engg. Graphics Lab",
          "I/II",
          "Prof. M.K.Choudhary",
          "Mr. Nawab Khan",
        ],
        [
          "3",
          "Thermal Engg. & Turbo Machinery.",
          "VI",
          "Prof. M.K.Choudhary",
          "Mr. Nawab Khan",
        ],
        [
          "4",
          "Fluid Mechanics",
          "IV",
          "Prof. A.Soni",
          "Mr. Rakesh Mehra",
        ],
        [
          "5",
          "Kinematics & Dynamics of Machine and Mechanism",
          "IV",
          "Prof. Yashwant Vishwakarma",
          "Mr. Ajay Singh Thakur",
        ],
        [
          "6",
          "Simulation & Modeling CIM",
          "VIII",
          "Mr. A.Soni",
          "Mr. Rakesh Mehra",
        ],
        [
          "7",
          "Internal Combustion engine",
          "V",
          "Prof. Devanshu Pyasi",
          "Mr. Rakesh Mehra",
        ],
        [
          "8",
          "Automobile Engineering",
          "VIII",
          "	Prof. Yashwant Vishwakarma",
          "Mr. Rajeev Singh Thakur",
        ],
        [
          "9",
          "Heat & Mass Transfer",
          "VII",
          "Prof. Devanshu Pyasi",
          "Mr. Rajeev Thakur",
        ],
        [
          "10",
          "Refrigeration & Air-Conditioning",
          "VII",
          "	Prof. Devanshu Pyasi",
          "Mr. Rakesh Mehra",
        ],
        [
          "11",
          "Central Workshop",
          "I/II",
          "Prof. M.K.Choudhary",
          "All Instructor",
        ],
      ],
    };
  },
};
</script>

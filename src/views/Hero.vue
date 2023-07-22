<template>
  <section class="hero-section" id="hero">
    <div class="container">
      <div class="row position-relative" style="height: 700px">
        <div
          class="col-6 d-flex flex-column justify-content-evenly"
          style="height: 500px"
        >
          <div class="d-flex flex-column lh-sm">
            <div class="display-3 fw-bold" style="margin-bottom: -10px">
              Let's Build
            </div>
            <div class="d-flex fw-bold display-3" style="margin-bottom: -10px">
              Your
              <span
                style="
                  height: 4px;
                  width: 130px;
                  background-color: #ea6847;
                  align-self: center;
                  margin-left: 10px;
                  margin-top: 14px;
                "
              ></span>
            </div>
            <div class="display-3 fw-bold m-0">Dream house</div>
          </div>
          <div>
            <button
              type="button"
              class="btn btn-dark btn-lg rounded-pill me-2 px-4"
            >
              Find Property
            </button>
            <button
              type="button"
              class="btn border-2 shadow-sm btn-lg btn-light rounded-pill px-5"
            >
              Explore
            </button>
          </div>
          <div>
            <div class="d-flex justify-content-start">
              <div class="d-flex flex-column justify-content-center me-5">
                <p
                  class="display-6 align-self-center m-0"
                  style="color: #ea6847"
                >
                  43k+
                </p>
                <p class="align-self-center m-0 text-secondary">Regular</p>
                <p class="align-self-center m-0 text-secondary">Customers</p>
              </div>
              <div class="d-flex flex-column justify-content-center">
                <p
                  class="display-6 align-self-center m-0"
                  style="color: #ea6847"
                >
                  203K+
                </p>
                <p class="align-self-center m-0 text-secondary">Projects</p>
                <p class="align-self-center m-0 text-secondary">Completed</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-6 position-relative">
          <div class="position-absolute" style="z-index: 2">
            <img
              src="/Images/gallery.jpg"
              height="500px"
              width="400px"
              alt="image"
              class="position-absolute"
              style="
                transform: rotate(15deg);
                margin: 50px 0 0 50px;
                z-index: 2;
              "
            />
          </div>
          <div
            class="position-absolute"
            style="
              border: 2px;
              border-style: solid;
              border-color: #ea6847;
              height: 500px;
              width: 400px;
              transform: rotate(-30deg);
              top: 50px;
              right: 100px;
              z-index: 1;
            "
          ></div>
        </div>
        <div
          class="position-absolute border border-light shadow rounded bg-light align-self-center d-flex justify-content-evenly"
          style="height: 100px; bottom: 100px; width: 1200px; z-index: 3"
        >
          <div class="d-flex text-middle">
            <img
              src="/Images/map-pin-line.svg"
              alt=""
              height="30px"
              style="color: black"
              class="align-self-center m-3"
            />
            <div class="d-flex flex-column align-self-center">
              <p class="text-secondary m-0">
                location
                <span
                  ><img src="/Images/arrow-drop-down-line.png" alt="" />
                </span>
              </p>
              <h5 class="fw-semibold">Chicago, US</h5>
            </div>
          </div>
          <div class="d-flex text-middle">
            <img
              src="/Images/home-4-line.svg"
              alt=""
              height="30px"
              style="color: black"
              class="align-self-center m-3"
            />
            <div class="d-flex flex-column align-self-center">
              <p class="text-secondary m-0">
                Property Types
                <span
                  ><img src="/Images/arrow-drop-down-line.png" alt="" />
                </span>
              </p>
              <h5 class="fw-semibold">3 BHK Apartment</h5>
            </div>
          </div>
          <div class="d-flex text-middle">
            <img
              src="/Images/money-dollar-circle-line.svg"
              alt=""
              height="30px"
              style="color: black"
              class="align-self-center m-3"
            />
            <div class="d-flex flex-column align-self-center">
              <p class="text-secondary m-0">
                Price Range
                <span
                  ><img src="Images/arrow-drop-down-line.png" alt="" />
                </span>
              </p>
              <h5 class="fw-semibold">$30k - $120k</h5>
            </div>
          </div>
          <div class="d-flex text-middle align-self-center">
            <button
              type="button"
              class="btn btn-dark rounded-pill me-2"
              style="height: 55px"
            >
              <img
                src="/Images/search-line.svg"
                alt=""
                height="30px"
                width="80px"
                class="align-self-center bg-dark"
              />
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped></style>

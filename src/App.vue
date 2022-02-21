<template >
  <div class="container" style="position: relative; width: 100%">
    <div class="row">
      <div
        class="col-lg-2 col-md-2 col-12 p-2"
        style="background-color: rgba(0, 0, 255, 0.1)"
      >
        <LeftDashboard />
      </div>
      <div class="col-lg-7 col-md-7 col-12">
        <div class="px-5 pt-5">
          <div class="searchBar p-2">
            <i class="bi bi-search text-muted px-2"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-search"
                viewBox="0 0 16 16"
              >
                <path
                  d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
                /></svg
            ></i>

            <input type="text" id="searchInput" placeholder="Search ..." />
          </div>
          <div class="my-5">
            <h1>Hi, <span>Mickey</span><sup class="mb-3">23</sup></h1>
          </div>

          <div class="d-flex justify-content-around">
            <div class="card py-2 mr-2 rounded bitcoin">
              <div class="card-body">
                <h5 class="card-title pb-3">
                  <p class="float-start title">Bitcoin</p>
                  <div class="float-end">
                    <i class="bi bi-three-dots-vertical"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        fill="currentColor"
                        class="bi bi-three-dots-vertical"
                        viewBox="0 0 16 16"
                      >
                        <path
                          d="M9.5 13a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z"
                        /></svg
                    ></i>
                  </div>
                </h5>
                <br />
                <p class="card-text py-3 float-start">
                  <i class="bi bi-currency-bitcoin float-start"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="160"
                      height="90"
                      fill="currentColor"
                      class="bi bi-currency-bitcoin"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                      /></svg
                  ></i>
                </p>
                <p class="bigPrice">0.222222 BTC</p>
                <p class="smallPrice">0.222222455 BTC</p>
              </div>
            </div>
            <div class="card py-2 rounded daga">
              <div class="card-body">
                <h5 class="card-title pb-3">
                  <p class="float-start title">Bitcoin</p>
                  <div class="float-end">
                    <i class="bi bi-three-dots-vertical"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        fill="currentColor"
                        class="bi bi-three-dots-vertical"
                        viewBox="0 0 16 16"
                      >
                        <path
                          d="M9.5 13a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z"
                        /></svg
                    ></i>
                  </div>
                </h5>
                <br />
                <p class="card-text py-3 float-start">
                  <i class="bi bi-currency-bitcoin float-start"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="160"
                      height="90"
                      fill="currentColor"
                      class="bi bi-currency-bitcoin"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                      /></svg
                  ></i>
                </p>
                <p class="bigPrice">0.222222 BTC</p>
                <p class="smallPrice">0.222222455 BTC</p>
              </div>
            </div>
            <div class="card py-2 rounded eth">
              <div class="card-body">
                <h5 class="card-title pb-3">
                  <p class="float-start title">Bitcoin</p>
                  <div class="float-end">
                    <i class="bi bi-three-dots-vertical"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        fill="currentColor"
                        class="bi bi-three-dots-vertical"
                        viewBox="0 0 16 16"
                      >
                        <path
                          d="M9.5 13a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm0-5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0z"
                        /></svg
                    ></i>
                  </div>
                </h5>
                <br />
                <p class="card-text py-3 float-start">
                  <i class="bi bi-currency-bitcoin float-start"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="160"
                      height="90"
                      fill="currentColor"
                      class="bi bi-currency-bitcoin"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                      /></svg
                  ></i>
                </p>
                <p class="bigPrice">0.222222 BTC</p>
                <p class="smallPrice">0.222222455 BTC</p>
              </div>
            </div>
          </div>

          <div class="">
            <p class="paymentText mt-4 pt-4">Latest Activity</p>
            <p>Updated 12 minutes ago</p>
            <div class="float-end mb-5">
              <i
                class="bi bi-gear-fill mx-2"
                style="
                  background-color: rgba(0, 0, 255, 0.1);
                  padding: 10px;
                  border-radius: 10%;
                "
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-gear-fill"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M9.405 1.05c-.413-1.4-2.397-1.4-2.81 0l-.1.34a1.464 1.464 0 0 1-2.105.872l-.31-.17c-1.283-.698-2.686.705-1.987 1.987l.169.311c.446.82.023 1.841-.872 2.105l-.34.1c-1.4.413-1.4 2.397 0 2.81l.34.1a1.464 1.464 0 0 1 .872 2.105l-.17.31c-.698 1.283.705 2.686 1.987 1.987l.311-.169a1.464 1.464 0 0 1 2.105.872l.1.34c.413 1.4 2.397 1.4 2.81 0l.1-.34a1.464 1.464 0 0 1 2.105-.872l.31.17c1.283.698 2.686-.705 1.987-1.987l-.169-.311a1.464 1.464 0 0 1 .872-2.105l.34-.1c1.4-.413 1.4-2.397 0-2.81l-.34-.1a1.464 1.464 0 0 1-.872-2.105l.17-.31c.698-1.283-.705-2.686-1.987-1.987l-.311.169a1.464 1.464 0 0 1-2.105-.872l-.1-.34zM8 10.93a2.929 2.929 0 1 1 0-5.86 2.929 2.929 0 0 1 0 5.858z"
                  />
                </svg>
              </i>
              <a class="button" href="#popup1">
                <i
                  class="bi bi-plus-lg button"
                  href="#popup1"
                  style="
                    background-color: blue;
                    padding: 10px;
                    border-radius: 10%;
                  "
                  ><svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-plus-lg"
                    viewBox="0 0 16 16"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M8 2a.5.5 0 0 1 .5.5v5h5a.5.5 0 0 1 0 1h-5v5a.5.5 0 0 1-1 0v-5h-5a.5.5 0 0 1 0-1h5v-5A.5.5 0 0 1 8 2Z"
                    /></svg
                ></i>
              </a>
            </div>
          </div>
          <table class="table table-borderless mt-5">
            <tbody>
              <tr class="insurance d-flex align-items-center">
                <th scope="row">
                  <i class="bi bi-currency-bitcoin"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-currency-bitcoin"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                      /></svg
                  ></i>
                </th>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
              </tr>
              <tr class="electricity d-flex align-items-center mt-4">
                <th scope="row">
                  <i class="bi bi-currency-bitcoin"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-currency-bitcoin"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M5.5 13v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.5v1.25c0 .138.112.25.25.25h1a.25.25 0 0 0 .25-.25V13h.084c1.992 0 3.416-1.033 3.416-2.82 0-1.502-1.007-2.323-2.186-2.44v-.088c.97-.242 1.683-.974 1.683-2.19C11.997 3.93 10.847 3 9.092 3H9V1.75a.25.25 0 0 0-.25-.25h-1a.25.25 0 0 0-.25.25V3h-.573V1.75a.25.25 0 0 0-.25-.25H5.75a.25.25 0 0 0-.25.25V3l-1.998.011a.25.25 0 0 0-.25.25v.989c0 .137.11.25.248.25l.755-.005a.75.75 0 0 1 .745.75v5.505a.75.75 0 0 1-.75.75l-.748.011a.25.25 0 0 0-.25.25v1c0 .138.112.25.25.25L5.5 13zm1.427-8.513h1.719c.906 0 1.438.498 1.438 1.312 0 .871-.575 1.362-1.877 1.362h-1.28V4.487zm0 4.051h1.84c1.137 0 1.756.58 1.756 1.524 0 .953-.626 1.45-2.158 1.45H6.927V8.539z"
                      /></svg
                  ></i>
                </th>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
                <td>
                  <p class="larger-text">Insurance</p>
                  <br />
                  <p class="smaller-text">Property Coverage</p>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <div
        class="col-lg-3 col-md-3 col-12"
        style="background-color: rgba(0, 0, 255, 0.1)"
      >
        <RightDashboard />
      </div>
    </div>
  </div>
  <div id="popup1" class="overlay">
    <div class="popup">
      <h3 class="popupHeading py-2">
        Bill Payment
        <a class="close float-end" href="#">&times;</a>
      </h3>

      <div class="p-3">
        <form>
          <div class="mb-3">
            <label
              for="exampleInputEmail1"
              class="form-label"
              style="color: blue"
              >Service</label
            >
            <select
              name="pets"
              id="pet-select"
              class="form-control"
              required="true"
            >
              <option value="">Select</option>
              <option value="dog">Dog</option>
              <option value="cat">Cat</option>
              <option value="hamster">Hamster</option>
            </select>
          </div>
          <div class="mb-3">
            <label
              for="exampleInputEmail1"
              class="form-label"
              style="color: blue"
              >Wallet</label
            >
            <select
              name="pets"
              id="pet-select"
              class="form-control"
              required="true"
            >
              <option value="">Select</option>
              <option value="dog">Dog</option>
              <option value="cat">Cat</option>
              <option value="hamster">Hamster</option>
            </select>
          </div>
          <div class="mb-3">
            <label
              for="exampleInputPassword1"
              class="form-label"
              style="color: blue"
              >Amount</label
            >
            <input
              type="text"
              class="form-control"
              required="true"
              id="exampleInputPassword1"
            />
          </div>
          <div class="d-flex justify-content-between">
            <button class="btn btn-outline-danger p-2">Cancel</button>
            <button type="submit" class="btn btn-primary p-2">Pay</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import LeftDashboard from "./components/LeftDashboard.vue";
import RightDashboard from "./components/RightDashboard.vue";
// import MiddleDashboard from "./components/MiddleDashboard.vue";

export default {
  name: "App",
  components: {
    LeftDashboard,
    RightDashboard,
    // MiddleDashboard,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter&display=swap");
#app {
  font-family: "Inter", sans-serif;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  color: black;
}
body {
  width: 100%;
}
.searchBar {
  background-color: rgba(0, 0, 255, 0.1);
  border-radius: 60px;
}
.searchBar input {
  border: none;
  background-color: transparent;
  width: 70%;
}
sup {
  background-color: pink;
  padding: 2px;
  border-radius: 50%;
}
.paymentText {
  font-size: 28px;
  color: black;
  font-weight: bold;
}
.larger-text {
  font-weight: bold;
  font-size: 14px;
}
.smaller-text {
  font-size: 12px;
  color: gray;
  margin-top: -30%;
  font-weight: bold;
}
.insurance i {
  color: rgba(15, 10, 222, 1);
  background-color: rgba(15, 10, 222, 0.5);
  padding: 10px;
  border-radius: 10%;
}
.electricity i {
  color: rgba(255, 105, 180, 1);
  background-color: rgba(255, 105, 180, 0.5);
  padding: 10px;
  border-radius: 10%;
}
.title {
  font-weight: bold;
  font-size: 14px;
}
.bigPrice {
  font-weight: bold;
  font-size: 20px;
  color: blue;
}
.smallPrice {
  font-weight: bold;
  font-size: 15px;
  color: blue;
}
.bitcoin .card-text i {
  color: white;
}
.bitcoin {
  background-color: rgba(255, 105, 180, 0.2) !important;
}
.daga .card-text i {
  color: white;
}
.eth {
  background-color: rgba(135, 206, 250, 0.2) !important;
}
.eth .card-text i {
  color: white;
}
.daga {
  background-color: rgba(221, 160, 221, 0.2) !important;
}

.overlay {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.7);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
}
.overlay:target {
  visibility: visible;
  opacity: 1;
}

.popup {
  margin: 70px auto;
  background: #fff;
  border-radius: 5px;
  width: 20%;
  border-radius: 10px;
  position: relative;
  transition: all 5s ease-in-out;
}
.popup .close {
  transition: all 200ms;
  font-size: 30px;
  font-weight: bold;
  text-decoration: none;
  color: white;
}

.popup .content {
  max-height: 30%;
  overflow: auto;
}

@media screen and (max-width: 700px) {
  .box {
    width: 70%;
  }
  .popup {
    width: 70%;
  }
}
.button {
  color: White !important;
}
.popupHeading {
  color: white !important;
  font-weight: bold;
  background-color: blue;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  text-align: center;
}
</style>

<script>

  export default {
    name: 'Table',

  }
</script>

<template>
  <div class="container-fluid px-lg-5 px-sm-0 px-md-0 px-0">
    <div class="whole">
      <table class="">
        <tr>
          <div class="p-sm-2 p-lg-0">
            <th class="px-4 py-4">
              <img class="pe-1" src="../assets/images/checkbox.png">
              Company
              <i class="fa-solid fa-arrow-down"></i>
            </th>
          </div>
          <th>
            <div>
              License
            </div>
          </th>
          <th>
            <div class="d-none d-lg-block">
              Status
            </div>
          </th>
          <th>
            <div class="d-none d-lg-block">
             Users
            </div>
          </th>
          <th>
            <div class="d-none d-lg-block">
             About
            </div>
          </th>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/ticked.png">
              </div>
              <div>
                <img src="../assets/images/Catalog.png">
              </div>
              <div>
                <h6 class="m-0">Catalog</h6>
                <p class="p-0">catalogapp.io</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-1"></div>
            </div>
          </td>
          <td>
            <div class="text-center d-none d-lg-block customer">
              Customer
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell1.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Content curating app
              </p>
              <p class="about-down">
                Brings all your news into one place
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block pe-lg-1">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/ticked.png">
              </div>
              <div>
                <img src="../assets/images/circle.png">
              </div>
              <div>
                <h6 class="m-0">Circooles</h6>
                <p class="p-0">getcircooles.com</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-2"></div>
            </div>
          </td>
          <td>
            <div class="text-center churn d-none d-lg-block">
              Churned
            </div>
          </td>
          <td>
            <div  class="d-none d-lg-block">
              <img src="../assets/images/Cell2.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Design software
              </p>
              <p class="about-down">
                Super lightweight design app
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block pe-0">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/ticked.png">
              </div>
              <div>
                <img src="../assets/images/cmd.png">
              </div>
              <div>
                <h6 class="m-0">Command+R</h6>
                <p class="p-0">cmdr.ai</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-3"></div>
            </div>
          </td>
          <td>
            <div class="text-center customer d-none d-lg-block">
              Customer
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell3.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Data prediction
              </p>
              <p class="about-down">
                AI and machine learning data
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/plain.png">
              </div>
              <div>
                <img src="../assets/images/hour.png">
              </div>
              <div>
                <h6 class="m-0">Hourglass</h6>
                <p class="p-0">hourglass.app</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-4"></div>
            </div>
          </td>
          <td>
            <div class="text-center customer d-none d-lg-block">
              Customer
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell4.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Productivity app
              </p>
              <p class="about-down">
               <span class="fw-bold">T</span>ime management and productivity
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/plain.png">
              </div>
              <div>
                <img src="../assets/images/layers.png">
              </div>
              <div>
                <h6 class="m-0">Layers</h6>
                <p class="p-0">getlayers.io</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-5"></div>
            </div>
          </td>
          <td>
            <div class="text-center churn d-none d-lg-block">
              Churned
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell5.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Web app integrations
              </p>
              <p class="about-down">
                Connect web apps seamlessly
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/ticked.png">
              </div>
              <div>
                <img src="../assets/images/quotient.png">
              </div>
              <div>
                <h6 class="m-0">Quotient</h6>
                <p class="p-0">quotient.co</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-6"></div>
            </div>
          </td>
          <td>
            <div class="text-center customer d-none d-lg-block">
              Customer
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell6.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Sales CRM
              </p>
              <p class="about-down">
                Web-based sales doc management
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block"> 
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>
        <tr>
          <td class="px-4 py-3 px-lg-o py-lg-0">
            <div class="d-flex p-sm-2 p-lg-0">
              <div class="pe-1">
                <img src="../assets/images/ticked.png">
              </div>
              <div>
                <img src="../assets/images/sisy.png">
              </div>
              <div>
                <h6 class="m-0">Sisyphus</h6>
                <p class="p-0">sisyphus.com</p>
              </div>
            </div>
          </td>
          <td>
            <div class="line-1">
              <div class="inner-line-7"></div>
            </div>
          </td>
          <td>
            <div class="text-center customer d-none d-lg-block">
              Customer
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img src="../assets/images/Cell7.png">
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <p class="about-up m-0">
                Automation and workflow
              </p>
              <p class="about-down">
                <span class="fw-bold">T</span>ime tracking, invoicing and expenses
              </p>
            </div>
          </td>
          <td>
            <div class="d-none d-lg-block">
              <img class="icons me-lg-1" src="../assets/images/delete.png">
              <img class="icons" src="../assets/images/edit.png">
            </div>
          </td>
        </tr>    
      </table>
      <div class="d-flex px-2 py-2 justify-content-between">
        <div class="d-none d-lg-block">
          <button class="btn mx-1 px-3">Previous</button>
          <button class="btn mx-1 px-3">Next</button>
        </div>
        <div class="px-1 d-none d-lg-block">
          <p>Page 1 of 10</p>
        </div>
      </div>
    </div>
    <div class="my-4 px-4 d-lg-none d-sm-block d-flex justify-content-between">
      <i class="fa-solid fa-arrow-left about-down"></i>
      <p>Page 1 of 10</p>
      <i class="fa-solid fa-arrow-right about-down"></i>
    </div>
  </div>

</template>

<style scoped>

  .whole {
    border: 2px solid #EAECF0;
    border-radius: 8px;
    color: #667085;
    box-shadow: 0px 4px 8px -2px rgba(16, 24, 40, 0.1), 0px 2px 4px -2px rgba(16, 24, 40, 0.06);
    margin-bottom: 20px;
  }

  table {
    width: 100%;
  }

  tr:first-child {
    border-bottom: 2px solid #EAECF0;
  }

  tr:nth-child(even) {
    background: #F9FAFB;;
  }

  .line-1 {
    width: 95px;
    height: 8px;
    background: #F9F5FF;
    border-radius: 4px;
  }

  .inner-line-1 {
    width: 65%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-2 {
    width: 60%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-3 {
    width: 30%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-4 {
    width: 80%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-5 {
    width: 25%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-6 {
    width: 15%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .inner-line-7 {
    width: 40%;
    height: 100%;
    background: #7F56D9;
    border-radius: 4px;
  }

  .customer {
    background: #ECFDF3;
    border-radius: 16px;
    width: 100px;
    color: #027A48;
    font-weight: 600;
  }

  .churn {
    background: #F2F4F7;
    border-radius: 16px;
    width: 100px;
    color: #344054;
    font-weight: 600;
  }

  .about-up {
    color: #101828;
  }

  .about-down {
    color: #667085;
  }

  .icons {
    width: 15px;
    height: 16.7px;
    cursor: pointer;
  }
</style>
<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="back">
    <div class="container ">

      <div class="row">
        <div class="col text-center pt-5">
          <h5 class="fw-bold">WHAT ARE WE DOING</h5>
        </div>

      </div>

      <div class="row">
        <div class="col text-center pt-5">
          <h2 class="text-white fw-bold"><span class="bg-title-light rounded">Results</span> in Numbers</h2>
        </div>

      </div>

      <div class="row numbers">
        <div class="col-3 text-center ">
          <h3>
            128
          </h3>

          <p>
            Certifications
          </p>
        </div>

        <div class="col-3 text-center">
          <h3>
            230
          </h3>

          <p>
            Employees
          </p>
        </div>

        <div class="col-3 text-center">
          <h3>
            1517
          </h3>

          <p>
            Customers
          </p>
        </div>

        <div class="col-3 text-center ">
          <h3>
           94
          </h3>

          <p>
            Countries Served
          </p>
        </div>

      </div>

    </div>
  </div>

  <div class="second-section d-flex align-items-center  ">
    <div class="container ">
      <div class="row m-0 p-0 d-flex justify-content-between align-items-center">
      <div class="col-2  d-flex align-items-center">
        <img src="../assets/images/logo-4.png" class="ps-3" alt="">
      </div>

      <div class="col-2  d-flex align-items-center">
        <img src="../assets/images/logo-2.png"  alt="">
      </div>

      <div class="col-2  d-flex align-items-center">
        <img src="../assets/images/logo-3.png" alt="">
      </div>

      <div class="col-2  d-flex align-items-center">
        <img src="../assets/images/logo-1.png"  alt="">
      </div>

      <div class="col-2  d-flex align-items-center">
        <img src="../assets/images/logo-5.png" class="ps-5" alt="">
      </div>


      <div class="col-2 d-flex align-items-center">
        <img src="../assets/images/logo-4.png" alt="">
      </div>

    </div>
    </div>
    
  </div>
</template>

<style lang="scss" scoped>

.back {
  background-image: url("../assets/images/bg-7.jpg");
  height: 600px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: 100%;


 h2 {
  font-size: 60px;
 }

 h3 {
  font-size: 50px;
 }


  h5 {
    color: $secondary-green;
    font-size: 1rem;
  }

  .numbers {
    padding-top: 100px;


    h3 {
    color: $secondary-green;
    font-weight: bold;
    }


    p {
      color: white;
      font-size: 2rem;
    }
  }

  
}


.second-section {
  height: 300px;
  background-color: #111117;

   img {
    filter: invert(56%) sepia(6%) saturate(147%) hue-rotate(201deg) brightness(89%) contrast(84%);
   }
  
}

</style>

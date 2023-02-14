<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="back  position-relative ">
    
    
    <div class="row">
      <div class="col-6 company  ">



        <h5 class="fw-bold fs-6">
          ABOUT THE NETWORK
        </h5>

        <h2 class="fw-bold">
          The Company
        </h2>

        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum reiciendis, incidunt magnam rerum ea beatae veniam illo! Minus, autem omnis!
        </p>


        <div class="d-flex flex-wrap ">
          <div class="card mt-2 me-2 bg-transparent" style="width: 16rem;">
            <div class="card-body p-0 text-start ">
              <h4 class="card-title py-2">
                <i class="fa-solid fa-award pe-2"></i>Tradition</h4>
              
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              
            </div>
          </div>

          <div class="card mt-2 me-2 bg-transparent " style="width: 16rem;">
            <div class="card-body p-0 text-start ">
              <h4 class="card-title py-2">
                <i class="fa-solid fa-lock"></i>Security</h4>
              
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              
            </div>
          </div>


          <div class="card mt-2 me-2 bg-transparent " style="width: 16rem;">
            <div class="card-body p-0 text-start ">
              <h4 class="card-title py-2">
                <i class="fa-solid fa-pen-to-square"></i>Certificate</h4>
              
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              
            </div>
          </div>


          <div class="card mt-2 me-2 bg-transparent " style="width: 16rem;">
            <div class="card-body p-0 text-start ">
              <h4 class="card-title py-2">
                <i class="fa-solid fa-graduation-cap"></i>Expertise</h4>
              
              <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
              
            </div>
          </div>
        </div>


        <div class="py-5">
          <button class="full-btn me-4">GET IN TOUCH</button>
          <button class="outline-btn">READ MORE</button>
        </div>

      </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>

.back {
  height: 900px;
  width: 100%;
  background-image: url("../assets/images/about-4.jpg");
  background-position: right;
  background-repeat: no-repeat;
  background-size: 50%;
  background-color: #111117;
  
  
  
}

img {
  width: 200px;
 
  
  
  
  
}

.company {
  width: 50%;
  padding-left: 300px;
  padding-top: 200px;
}

h2 {
  color: white;
  font-size: 60px;
}

h5 {
  color: $secondary-green;
}
.card {
  color: white;

  i {
    color: $secondary-green;
    padding-right: 5px;
  }

  
}

p {
    color: $primary-grey;
  }


.outline-btn {
  background: transparent;
}
</style>


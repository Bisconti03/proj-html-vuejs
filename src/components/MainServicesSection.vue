<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="back  ">
    <div class="container">
    <div class="row">
      <div class="col">
        <h5 class="fs-6 fw-bold py-5 ">
          OUR BUSINESS AREAS
        </h5>
      </div>
    </div>

    <div class="row">
      <div class="col">
        <h2 class=" fw-bold pb-4">
          Excellenxce in <span class="bg-title rounded">Services</span> 
        </h2>
      </div>
    </div>

    <div class="row py-4 d-flex justify-content-between align-items-center">
      <div class="col-8">
        <p>
          We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of
          experienced and renowned professionals. These are some options that you can hire.
        </p>
      </div>

      <div class="col-2 ps-5">
        <button class="full-btn">SEE ALL</button>
      </div>
    </div>

    <div class="row gy-4 d-flex justify-content-between flex-wrap ">
      <div class="col-4 ">
        <div class="card  border-0" style="width: 25rem;">
          <div class="card-body ">
             <i class="fa-solid fa-arrow-right fs-2"></i>

            <img src="../assets/images/svg-1.svg" alt="">
            <h4 class="card-title fw-bold">Audit & Assurance</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>

      <div class="col-4">
        <div class="card border-0" style="width: 25rem;">
          <div class="card-body">
            <i class="fa-solid fa-arrow-right fs-2"></i>
            <img src="../assets/images/svg-2.svg" alt="">
            <h4 class="card-title fw-bold">Financial Advisory</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>

      <div class="col-4">
        <div class="card border-0" style="width: 25rem;">
          <div class="card-body">
            <i class="fa-solid fa-arrow-right fs-2"></i>
            <img src="../assets/images/svg-3.svg" alt="">
            <h4 class="card-title fw-bold">Analytics and M&A</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>



      <div class="col-4">
        <div class="card border-0" style="width: 25rem;">
          <div class="card-body ">
            <i class="fa-solid fa-arrow-right fs-2"></i>
            <img src="../assets/images/svg-4.svg" alt="">
            <h4 class="card-title fw-bold">Middle Marketing</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>


      <div class="col-4">
        <div class="card border-0" style="width: 25rem;">
          <div class="card-body">
            <i class="fa-solid fa-arrow-right fs-2"></i>
            <img src="../assets/images/svg-5.svg" alt="">
            <h4 class="card-title fw-bold">Legal Consulting</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>


      <div class="col-4">
        <div class="card border-0" style="width: 25rem;">
          <div class="card-body">
            <i class="fa-solid fa-arrow-right fs-2"></i>
            <img src="../assets/images/svg-6.svg" alt="">
            <h4 class="card-title fw-bold">Regulatory Disk</h4>
            
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

            
            
            
          </div>

        
        </div>

      
      </div>
    </div>

    
  </div>
  </div>
  
</template>

<style lang="scss" scoped>
.back {
  background-color: #eef4ed;
  padding: 100px 0;
}

h5 {
  color: $secondary-green;
}
h2 {
  font-size: 60px;
  color: #21333e;
}


.card {

  padding-left: 20px;

  &:hover {
    cursor: pointer;


    i {
      background-color: #7bd1d1;
    }
  }
  

  
  
  img {
    width: 45px;
    filter: invert(32%) sepia(93%) saturate(685%) hue-rotate(139deg) brightness(99%) contrast(96%);
    padding: 20px 0;
  }

  h4 {
    padding: 20px 0;
  }

  i {
    position: absolute;
    top: 20px;
    right: 20px;
    color: $primary-green ;
    filter: opacity(0.7);
    border-radius: 50%;
    padding: 13px;
    
  }

 
}


</style>


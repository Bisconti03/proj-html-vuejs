<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="container ">
    <div class="row">
      <div class="col text-center ">
        <h5 class="fs-6 pb-5 custom-color fw-bold">WE DO MORE FOR EVERYONE</h5>
      </div>
    </div>

    <div class="row">
      <div class="col text-center">
        <h2 class="fw-bold pb-4">Actions and <span class="bg-title rounded">Projects</span></h2>
      </div>
    </div>


    <div class="row py-3">
      <div class="col text-center ">
        <span>
          <a href="">ALL</a>
        </span>
        <span>
          <a href="">INSTITUTIONAL</a>
        </span>
        <span>
          <a href="">SOCIAL</a>
        </span>
        <span>
          <a href="">EVENTS</a>
        </span>
        <span>
          <a href="">INNOVATION</a>
        </span>
        <span>
          <a href="">ENVIROMENT</a>
        </span>
        <span>
          <a href="">TECHNOLOGY</a>
        </span>
      </div>
    </div>






    <div class="row ">
      <div class="col d-flex flex-wrap justify-content-around  ">

        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-1.jpg" class="card-img opacity-50" alt="...">

          <div class="card-img-overlay d-flex  justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center  ">

            
            
            <h5 class="card-title text-center my-5 ">Academic professional program in social media</h5>
           
          </div>

          <div class="card-img-overlay  d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide"><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>

        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-2.jpg" class="card-img opacity-50" alt="...">
          <div class="card-img-overlay d-flex   justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>

          
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            
            <h5 class="card-title text-center my-5 ">President's speech at the annual meeting</h5>
           
          </div>

          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide"><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>

        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-3.jpg" class="card-img opacity-50" alt="...">

          <div class="card-img-overlay d-flex   justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            
            <h5 class="card-title text-center my-5 ">International business trip in Shangai</h5>
           
          </div>

          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide "><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>


        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-4.jpg" class="card-img opacity-50" alt="...">

          <div class="card-img-overlay d-flex   justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            
            <h5 class="card-title text-center my-5 ">Technology workshop with education theme</h5>
           
          </div>

          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide"><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>


        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-5.jpg" class="card-img opacity-50" alt="...">

          <div class="card-img-overlay d-flex   justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            
            <h5 class="card-title text-center my-5">Donation of clothes and food to the partner NGO</h5>
           
          </div>

          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide"><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>


        <div class="card text-bg-dark d-flex  " >
          <img src="../assets/images/project-6.jpg" class="card-img opacity-50" alt="...">

          <div class="card-img-overlay d-flex   justify-content-end ">

            <i class="fa-solid fa-2x fa-arrow-right hide"></i>

            </div>
          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            
            <h5 class="card-title text-center my-5 ">Confraternization of the procurement team</h5>
           
          </div>

          <div class="card-img-overlay d-flex flex-column-reverse align-items-center ">
            <p class="card-text text-center hide "><small>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</small></p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  padding: 150px 0;
}


span {
  padding: 10px 15px;
}

h2 {
  font-size: 60px;
  color: #21333e;
  overflow: hidden;
}

.custom-color {
  color: $secondary-green ;
}
 
a {
  text-decoration: none;
  color: $primary-grey;
  padding: 10px 15px;

  &:hover {
    background-color: $light-green;
  }
}


.card {
  width: 22rem;
  margin-top: 60px;

  

  .hide {
    display: none;
  }

  

  h5 {
    font-weight: bold;
  }
}


.card:hover {

  cursor: pointer;
  .hide {
    display: block;
  }
}


</style>


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
        <header>
    <div class="container ">
        <div class="row py-3 d-flex justify-content-between">
            <div class="col-2 ">
                <img src="../assets/images/logo.PNG" alt="">
            </div>

            <div class="col-7  d-flex justify-content-between align-items-center">
                
                   <span>
                    <a href="">HOME</a>
                    </span>
                   <span>
                    <a href="">SERVICES</a>
                    </span>
                   <span>
                    <a href="">ABOUT</a>
                    </span>
                   <span>
                    <a href="">PROJECTS</a>
                   </span>
                   <span>
                    <a href="">RESULTS</a>
                    </span>
                    
                    
               

                <button class="full-btn">
                    GET IN TOUCH
                </button>
            </div>
        </div>
    </div>
  </header>

  <main class="position-relative">
    
    <div class="position-absolute centered-div top-50 start-50 translate-middle" >
        <div class="d-flex  flex-column align-items-center">
            <h1 class="fw-bold" >
                Ready <span class="bg-title rounded">Team</span> 
            </h1>

            <p >
                No Matter what your company needs, we will be ready to assist you in the best possible way.
            </p>

            <div>
                <button class="full-btn mx-2">GET IN TOUCH</button>
                <button class="outline-btn mx-2"> READ MORE</button>
            </div>
        </div>
            
        
    </div>
  </main>
    </div>
  
</template>

<style lang="scss" scoped>
.back {
    background-image: url("../assets/images/3257525.jpg");
    background-size: cover;
    
    
}

.h1 {
    font-size: 2.5em;
    color: #21333e;
    

    

    
}



.centered-div {
    width: 600px;
    
}

header {
    img {
        width: 150px;
    }

    span {
        color: $primary-blue;
        padding: 15px 10px;

        &:hover {
            background-color: $light-green;
        }
    }

    a {
        text-decoration: none;
        color: #21333e;

        
    }
}

main {
    height: 800px;
    background-image: url("../assets/images/bg-parallax.png");
    background-position: center;
    background-size: 200%;
    background-repeat: no-repeat;

    h1 {
        font-size: 80px;
    }
}

</style>


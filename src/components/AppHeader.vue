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
                
                   <span>HOME</span>
                   <span>SERVICES</span>
                   <span>ABOUT</span>
                   <span>PROJECTS</span>
                   <span>RESULTS</span>
                    
                    
               

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
            <h1 >
                Ready Team
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
    background-color: white;
    
    
}

.h1 {
    font-size: 2.5em;
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


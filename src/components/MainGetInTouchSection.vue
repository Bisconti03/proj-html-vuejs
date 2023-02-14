<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="container">
    <div class="row">

      <div class="col-6 p-4">
        <h5 class="fs-6">SEND A MESSAGE  </h5>

        <h2 class="fw-bold">Get in Touch</h2>

        <p>We will respond to your message as soon as possible</p>

        <div class="row">
          <div class="col-6">
            <div class="mb-3">
            
            <input type="name" class="form-control bg-custom" id="exampleFormControlInput1" placeholder="Name">
            </div>
          </div>

          <div class="col-6">
            <div class="mb-3">
            
            <input type="email" class="form-control bg-custom" id="exampleFormControlInput1" placeholder="Email">
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-6">
            <div class="mb-3">
            
            <input type="name" class="form-control bg-custom" id="exampleFormControlInput1" placeholder="Phone">
            </div>
          </div>

          <div class="col-6">
            <select class="form-select bg-custom" aria-label="More Info">
              <option class="fw-light" selected>More Info</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
          </select>
          </div>
        </div>


        <div class="row">
          <div class="col">
            <div class="form-floating">
              <textarea class="form-control bg-custom" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
              <label for="floatingTextarea2">Message</label>
            </div>
          </div>

          
        </div>


        <button class="full-btn my-3">SEND</button>
      </div>

      <div class="col-4 p-3">
        <h3 class="fw-bold">Example Inc.</h3>

        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>

        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>

        <ul>
          <li>
            <i class="fa-solid fa-phone"></i>
            <span>
              +1 (305) 1234-5678
            </span>
          </li>
          <li>
            <i class="fa-solid  fa-envelope"></i>
            <span>
              hello@example.com
            </span>
          </li>
          <li>
            <i class="fa-sharp fa-solid fa-location-dot special-icon"></i>
            <span>
              Main Avenue, 987
            </span>
          </li>
        </ul>

        <button class="outline-btn">VIEW MAP</button>
      </div>

      

    </div>

    
  </div>
</template>

<style lang="scss" scoped>

.container {

  padding: 150px 0;

}

h2 {
  font-size: 60px;
  color: #21333e;
}

h5 {
  color: $secondary-green;
}

h3 {
  color: #21333e;
  font-size: 30px;
}

p {
  color: grey;
}

.bg-custom {
  background-color: #ececec;
}

ul {
  padding-left: 0;

  li {
    padding: 10px 0;
    display: flex;
    align-items: center;

    i {
    color: $secondary-green;
    background-color: $light-green;
    
    border-radius: 50%;
    padding: 15px;
    
      }

      span {
        color: $secondary-green;
        padding-left: 15px;
      }
    
  }

  

  .special-icon {
    padding: 15px 17px;
  }
}


</style>


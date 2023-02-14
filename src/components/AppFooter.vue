<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <main>
    <div class="container">
      <div class="row main-row d-flex justify-content-between">
        <div class="col-3">
          <img src="../assets/images/logo.PNG" alt="">

          <p>
            A Functional HTML TEmplate for Corporate & business
          </p>

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
            <i class="fa-sharp fa-solid fa-location-dot "></i>
            <span>
              Main Avenue, 987
            </span>
          </li>
        </ul>

        <button class="outline-btn  text-white">GET IN TOUCH</button>
        </div>

        <div class="col-2  bg-custom rounded ps-4 pt-4 ">
          <h3 class="text-white">About</h3>
          <ul>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              The Company
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Institutional
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Social & Events
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Innovation
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Enviroment
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Technology
            </span>
            </a>
          </li>
        </ul>

        </div>

        <div class="col-2  bg-custom rounded ps-4 pt-4 ">
          <h3 class="text-white">Services</h3>
          <ul>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Audit & Assurance
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Financial Advisory
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Analytics M&A
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Middle Marketing
            </span></a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
             Legal Consulting
            </span></a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Regulatory Risk
            </span>
            </a>
          </li>
        </ul>
        </div>

        <div class="col-2 bg-custom rounded ps-4 pt-4 ">
          <h3 class="text-white">Support</h3>
          <ul>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Responsibility
            </span>
            </a>
            
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Terms of Use
            </span>
            </a>
            
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              About Cookies
            </span>
            </a>
            
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Privacy Policy
            </span>
            </a>
            
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
             Accessibility
            </span>
            </a>
          </li>
          <li>
            <a href="">
              <i class="fa-solid fa-angle-right"></i>
            <span>
              Information
            </span>
            </a>
            
          </li>
        </ul>
        </div>
      </div>
    </div>
  </main>

  <footer>
    <div class="container">
      <div class="row d-flex justify-content-between align-items-center ">
        <div class="col-5 py-4 ">
          <p class="">
            Enjoy the low price. We are tracking any intention of piracy.
          </p>
        </div>

        <div class="col-4 py-4">
          <p>
            &copy 2020 NEXGEN is proudly Powered by <a href="">Codings</a>
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>

main {
  background-color: #111117;
  color: $tertiary-grey;
  
  button {
    background-color: #0d0d11;

    &:hover {
      background-color: $secondary-green;
    }
  }
 .main-row {
  padding: 150px 0;
 }
  img {
    width: 50%;
    padding: 15px 0;
  }

  ul {
    padding-left: 0;

    li {
      padding: 5px 0;

      a {
        text-decoration: none;
        color: $tertiary-grey ;
      }
    }
  }

  .bg-custom {
    background-color: #19191f;
    
  }
}


footer {
  background-color: #0d0d11;
  color: $tertiary-grey;

  a {
    text-decoration: none;
    color: $primary-green;
  }

  p {
    margin-bottom: 0;
  }
}
</style>


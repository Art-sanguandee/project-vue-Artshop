<template>
<div id="nav" v-if="!isLoginPage">
<header class="p-3 text-bg-dark">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
          <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
        </a>

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <li><a href="/" class="nav-link px-2 text-secondary">Art Shop</a></li>
          <li><a href="/" class="nav-link px-2 text-white">Home</a></li>
          <li><a href="/product" class="nav-link px-2 text-white">Product</a></li>
          <li><a href="/contact" class="nav-link px-2 text-white">Contact</a></li>
          <li><a href="/addproduct" class="nav-link px-2 text-white">Add Prodcut</a></li>
          <li><a href="/register" class="nav-link px-2 text-white">Register</a></li>
          <li><a href="/grade" class="nav-link px-2 text-white">Grade</a></li>

        <!--
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Register
            </a>
            
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="/register">Register</a></li>
              <li><a class="dropdown-item" href="/login">Login</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="/logout">Logout</a></li>
            </ul>
          </li>  
           -->                                                                                 
        </ul>
       

        <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3" role="search">
          <input type="search" class="form-control form-control-dark text-bg-withe" placeholder="Search..." aria-label="Search">
        </form>

       <div class="text-end">
          <button type="button" class="btn btn-outline-light me-2"><a class="text-decoration-none" href="/login">Login</a></button>
          <button type="button" class="btn btn-warning"><a class="text-decoration-none" href="/sign-up">Sign-up</a></button>
        </div>
      </div>
    </div>
</header>
</div>
</template>

<script>
import { computed } from 'vue'
import { useRoute } from 'vue-router'

export default {
    name : 'Menu',

    setup() {
    const route = useRoute()

    // ตรวจสอบว่า route ปัจจุบัน 'Login' หรือไม่ 
    const isLoginPage = computed(() => route.name === 'login')

    return { isLoginPage }
    }

}
</script>

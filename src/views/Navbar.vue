<template>
  <div class="container" id="navbar">
    <header
      class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4"
    >
      <div class="col-md-3 mb-2 mb-md-0">
        <a
          href="/"
          class="d-inline-flex link-body-emphasis text-decoration-none"
        >
          <img
            src="/Images/logo.png"
            width="140px"
            height="60px"
            style="object-fit: cover"
          />
        </a>
      </div>

      <ul
        class="nav col-12 col-md-auto mb-2 justify-content-evenly flex-grow-1 fw-semibold"
      >
        <li>
          <a
            href="#"
            class="nav-link px-2 link-dark"
            style="margin-right: -100px"
            >Home</a
          >
        </li>
        <li>
          <a
            href="#"
            class="nav-link px-2 link-dark"
            style="margin-right: -100px"
            >Buy</a
          >
        </li>
        <li>
          <a
            href="#"
            class="nav-link px-2 link-dark"
            style="margin-right: -100px"
            >Sell</a
          >
        </li>
        <li><a href="#" class="nav-link px-2 link-dark">Contact Us</a></li>
      </ul>

      <div class="col-md-3 text-end">
        <button type="button" class="btn btn-dark rounded-pill me-2 px-4">
          Sign Up
        </button>
        <button type="button" class="btn shadow-sm btn-light rounded-pill px-4">
          Log in
        </button>
      </div>
    </header>
  </div>
</template>

<script setup>
import { onMounted } from "vue";

const { navbarElements } = defineProps({ navbarElements: Array });
</script>

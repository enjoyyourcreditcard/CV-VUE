<script setup lang="ts">
  import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
    <div class="p-4 p-md-5 mb-4 rounded text-bg-dark">
      <div class="col-md-6 px-0">
        <h1 class="display-4 fst-italic">JOY WIDI WIBOWO</h1>
        <p class="lead my-3">Software Engineering student in SMKS Taruna Bhakti, experienced with front end and back end
          development. Results-oriented and working collaboratively with team members to achieve goals.</p>
      </div>
    </div>

    <div class="row mb-2">
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary">Front End</strong>
            <h3 class="mb-0">EKiosk Wisata Depok</h3>
            <div class="mb-1 text-muted">August 2022</div>
            <p class="card-text mb-auto">Tourist information website and popular places in Depok using Laravel and
              Bootstrap.</p>
            <a href="https://github.com/enjoyyourcreditcard/apkTravel" class="stretched-link">Github page..</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <svg class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg" role="img"
              aria-label="Placeholder: Thumbnail" preserveAspectRatio="xMidYMid slice" focusable="false">
              <title>Placeholder</title>
              <rect width="100%" height="100%" fill="#55595c" /><text x="50%" y="50%" fill="#eceeef"
                dy=".3em">Thumbnail</text>
            </svg>

          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-success">Back End</strong>
            <h3 class="mb-0">RFID Inventory Management</h3>
            <div class="mb-1 text-muted">December 2021</div>
            <p class="mb-auto">Inventory management application using PHP and SmartCard.</p>
            <a href="https://github.com/enjoyyourcreditcard/Inventori-tap-tap" class="stretched-link">Github page..</a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <svg class="bd-placeholder-img" width="200" height="250" xmlns="http://www.w3.org/2000/svg" role="img"
              aria-label="Placeholder: Thumbnail" preserveAspectRatio="xMidYMid slice" focusable="false">
              <title>Placeholder</title>
              <rect width="100%" height="100%" fill="#55595c" /><text x="50%" y="50%" fill="#eceeef"
                dy=".3em">Thumbnail</text>
            </svg>

          </div>
        </div>
      </div>
    </div>
</template>
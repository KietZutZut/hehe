<!-- pages/benefits.vue -->
<template>
    <div class="container mt-4">
      <h1 class="mb-4">Lợi ích khi sử dụng Nuxt.js</h1>
      <ul class="list-group">
        <li class="list-group-item">Hỗ trợ SSR và CSR cho hiệu suất tối ưu.</li>
        <li class="list-group-item">Quản lý routing tự động thông qua hệ thống Pages.</li>
        <li class="list-group-item">Tích hợp dễ dàng với Vuex cho quản lý trạng thái.</li>
        <li class="list-group-item">Hỗ trợ SEO tốt hơn nhờ SSR.</li>
        <li class="list-group-item">Quản lý cấu hình đơn giản với các modules có sẵn.</li>
      </ul>
      <router-link to="/" class="btn btn-primary mt-3">Trở về trang chính</router-link>
      <router-link to="/about" class="btn btn-secondary mt-3 ml-2">Xem so sánh với Vue.js</router-link>
    </div>
  </template>
  
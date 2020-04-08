<template>
  <div class="theHeader">
    <div class="inside">
      <div class="theHeader__inside">
        <span class="theHeader__logo">Logo</span>
        <nav>
          <nuxt-link to="/">Home</nuxt-link>
          <nuxt-link to="/detail">Detail</nuxt-link>
        </nav>
      </div>
    </div>
  </div>
</template>

<style>
.theHeader {
  padding: 10px 20px;
  background: #f2f2f2;
}
.theHeader__inside {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 24px;
  color: inherit;
}
.theHeader__logo {
  text-transform: uppercase;
  font-weight: 500;
}
.theHeader a {
  color: inherit;
  text-decoration: none;
}
</style>

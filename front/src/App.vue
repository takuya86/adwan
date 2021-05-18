<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/test">Test</router-link> |
    <%= link_to "Login" %>
  </div>
  <router-view />
</template>

<style>
@import "./CSS/app.scss";
</style>

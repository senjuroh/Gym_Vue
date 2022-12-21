<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;500;700&family=Rubik+Spray+Paint&display=swap");
:root {
  --primary: #1a548d;
  --secondary: #05b2e2;
}
.head1 {
  font-family: "Rubik Spray Paint", cursive;
  color: var(--primary);
}
.head2 {
  color: var(--secondary);
  font-family: "Open Sans", sans-serif;
  font-weight: 400;
  font-size: 28px;
}
p {
  font-family: "Open Sans", sans-serif;
}
a {
  text-decoration: none;
  color: var(--secondary);
}
</style>

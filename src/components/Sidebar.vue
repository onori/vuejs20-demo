<template lang="jade">
  .sidebar
    .app-link
      p APP
    .sidebar-link
      i.zmdi.zmdi-home
      p.sidebar-link HOME
</template>

<style lang="postcss" scoped>
  .sidebar {
    width: 122px;
    height: 100%;
    background-color: #00ACC1;
    display: flex;
    flex-direction: column;
    text-align: center;
    color: #fff;

    &sidebar-link {
      height: 92px;
      background-color: #029AAD;
    }
  }
</style>

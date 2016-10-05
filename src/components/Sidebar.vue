<template lang="jade">
  .sidebar
    .sidebar-content
      .app-link
        p APP
      .sidebar-link
        i.material-icons home
        .sidebar-title HOME
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
  }
  .sidebar-content {
    justify-content: center;
    align-items: center;
    height: 100%;
  }
  .app-link {
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .sidebar-link {
    height: 92px;
    width: 100%;
    display: flex;
    align-content: center;
    justify-content: center;
    align-items: center;
  }
  .sidebar-title {
    display: flex;
    width: 100%;
  }
  .sidebar-link:hover {
    background-color: #029AAD;
  }
  .material-icons {
    font-size: 36px;
  }
</style>

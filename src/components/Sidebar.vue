<template lang="jade">
  .sidebar
    .sidebar-content
      .app-link
        img(src='./logo.svg')
      .sidebar-link
        i.material-icons home
        .sidebar-title ホーム
      .sidebar-link
        i.material-icons account_circle
        p.sidebar-title ユーザー
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
    height: 100%;
  }
  .app-link {
    height: 70px;
    display: flex;
    align-content: center;
    justify-content: center;
    align-items: center;
    background-color: #FFF;
  }
  .app-link img {
    width: 85%;
  }
  .sidebar-link {
    height: 92px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-content: center;
    justify-content: center;
    align-items: center;
  }
  .sidebar-title {
    display: block;
    width: 100%;
    display: flex;
    align-content: center;
    justify-content: center;
    align-items: center;
  }
  .sidebar-link:hover {
    background-color: #029AAD;
  }
  .material-icons {
    display: block;
    font-size: 36px;
  }
</style>

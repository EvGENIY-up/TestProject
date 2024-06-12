<script setup>
</script>

<template>
  <div class="header-block">
    <img src="/src/assets/Iconbackimg.svg" alt="Назад" class="back-img">
    <div class="header__logo">
      <img src="/src/assets/Logo.svg" alt="Логотип" class="logo-img">
      <p class="logo-title">Логотип</p>
    </div>
    <button class="catalog-btn">Каталог</button>
    <div class="search-block">
      <img src="/src/assets/Search.svg" alt="search" class="search" />
      <img  class="clear" src="/src/assets/Icondelete.svg" alt="Remove" />
      <input  type="text" placeholder="Поиск..." />
    </div>
    <div class="info-block">
      <p>Информация о компании</p>
      <p>Контакты</p>
      <p>Полезные ссылки</p>
    </div>
    <button class="find">Найти</button>
  </div>
  <hr class="line">
</template>

<style scoped lang="scss">
.header-block{
  display: flex;
  justify-content: space-around;
  margin: 0 10px;

  .back-img{
    @media (min-width: 1440px) {
      display: none;
    }
  }
  .header__logo{
    display: none;

    @media (min-width: 1440px) {
      display: flex;
      justify-content: center;
      width: 145px;
      height: 48px;
    }
    .logo-img{
      width: 24px;
      height: 24px;
      margin-top: 10px;
    }
    .logo-title{
      font-size: 16px;
      line-height: 25px;
      margin-left: 13px;
      margin-top: 10px;
    }
  }
  .catalog-btn{
    display: none;

    @media (min-width: 1440px) {
      display: block;
      font-size: 14px;
      font-weight: 500;
      line-height: 17px;
      background-color: white;
      padding: 15px 24px;
      border: solid #73AFF4 1px;
      border-radius: 8px;
    }
  }
  .info-block{
    display: none;

    @media (min-width: 1440px) {
      display: flex;
    }
    p{
      padding: 10px 10px;
      font-weight: 400;
      font-size: 14px;
      line-height: 20px;
    }
  }
}
.search-block {
  padding: 0 13px;
  position: relative;
  display: flex;

  .search {
    display: none;

    @media (min-width: 1440px) {
      display: block;
      width: 20px;
      height: 20px;
      position: absolute;
      left: 30px;
      top: 15px;
    }
  }

  .clear {
    position: absolute;
    right: 0;
    width: 20px;
    height: 20px;
    top: 10px;
    right: 20px;

    @media (min-width: 1440px) {
      display: none;
    }
  }

  input {
    border: 0;
    padding: 10px;
    font-size: 16px;
    width: 200px;
    outline: none;

    @media (min-width: 1440px) {
      width: 480px;
      border: solid #73AFF4 1px;
      border-radius: 10px;
      padding: 12px 48px;
    }
    @media (min-width: 1920px) {
      width: 1015px;
      border: solid #73AFF4 1px;
      border-radius: 10px;
      padding: 12px 48px;
    }
  }
}
.find{
  font-size: 16px;
  font-weight: 400;
  line-height: 14px;
  color: white;
  background-color: #7397F5;
  padding: 12px 16px;
  border: solid #7397F5;
  border-radius: 5px;
  cursor: pointer;

  @media (min-width: 1440px) {
    display: none;
  }
}
.line{
  background-color: #D5D5D5;
  color: #D5D5D5;
  border: none;
  margin-top: 6px;
  width: 300px;
  margin-left: 58px;
  height: 1px;
  margin-bottom: 6px;

  @media (min-width: 1440px) {
    display: none;
  }
}


</style>
<script setup>
</script>

<template>
  <div class="position">
    <div class="position__cover">
      <div class="cover__hit">
        <p class="hit__title">Хит продаж</p>
        <img src="/src/assets/Fire.svg" alt="Спрос" class="hit__img">
      </div>
      <img src="/src/assets/Box.svg" alt="Фотография товара" class="cover__img">
      <div class="cover__sale">25%</div>
    </div>
    <p class="position__name">Бренд</p>
    <p class="position__description">Полное название товара в несколько строк для вида с обрывом в конце</p>
    <div class="position__prices">
      <b class="price-new">5990 ₽</b>
      <p class="price-old">5990 ₽</p>
    </div>
    <button class="position_buy">Купить</button>
  </div>
</template>

<style scoped lang="scss">
.position{
  width: 165px;
  margin-top: 12px;


  @media (min-width: 1440px) {
    width: 213px;
    margin-left: 18px;
  }

  @media (min-width: 1920px) {
    width: 303px;
    margin-left: 18px;
  }
}
.position__cover{
  background-color: #F8F8FA;
  width: 165px;
  height: 200px;

  @media (min-width: 1440px) {
    width: 213px;
  }
  @media (min-width: 1920px) {
    width: 303px;
  }

  .cover__hit{
    display: inline-flex;
    justify-content: space-around;
    border: solid #F2F2F2 1px;
    border-radius: 4px;
    background-color: white;
    width: 112px;
    height: 32px;
    margin-left: 12px;
    margin-top: 12px;

    .hit__title{
      font-size: 14px;
      padding-left: 8px ;
      padding-top: 8px ;
      padding-bottom: 8px ;
      line-height: 16px;

    }
    .hit__img{
      width: 20px;
      height: 20px;
      margin-top: 6px;
      margin-right: 4px;
      padding: 2px;
    }
  }
  .cover__img{
    display: block;
    margin: auto;
    margin-top: 26px;
  }
  .cover__sale{
    width: 48px;
    height: 26px;
    background-color: #7397F5;
    color: white;
    font-size: 14px;
    font-weight: 700;
    line-height: 14px;
    border-radius: 4px;
    margin-top: 32px;
    margin-left: 12px;
    padding: 6px 10px;
  }
}
.position__name{
  margin-top: 12px;
  margin-bottom: 8px;
  font-size: 14px;
  line-height: 16px;
  color: #AAAAAA;
}
.position__description{
  font-size: 14px;
  line-height: 16px;
}
.position__prices{
  display: flex;
  margin: 12px 0;

  .price-new{
    line-height: 14px;
  }

  .price-old{
    margin-left: 8px;
    font-size: 12px;
    line-height: 14px;
    font-weight: 400;
    color: #AAAAAA;
    text-decoration: line-through;
  }
}
.position_buy{
  font-weight: 700;
  font-size: 14px;
  line-height: 14px;
  padding: 12px 16px;
  color: #7397F5;
  border: solid #7397F5 1px;
  border-radius: 4px;
  background-color: white;
  cursor: pointer;
  transition: border-color 0.25s;
  transition: color 0.25s;

  &:hover {
    border-color: #646cff;
    color: #646cff;
  }
  &:focus,
  &:focus-visible {
    outline: 4px auto -webkit-focus-ring-color;
  }
}
</style>

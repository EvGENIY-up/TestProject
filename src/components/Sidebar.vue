<script setup>

</script>

<template>
<div class="sidebar">
  <div class="category">
    <div class="category__section">
      <p class=" category-name">Название категории</p>
      <p class="category-amount">3</p>
    </div>
    <div class="category__section">
      <p class="li category-name ">Название категории</p>
      <p class="category-amount">3</p>
    </div>
    <div class="category__section">
      <p class="li category-name ">Название категории</p>
      <p class="category-amount">3</p>
    </div>
    <div class="category__section">
      <p class="li category-name ">Название категории</p>
      <p class="category-amount">3</p>
    </div>
  </div>
  <div class="price-block">
    <h3 class="price-title">Цена</h3>
    <div class="price-text">
      <div class="price-value">
        <p class="price-begin">от</p>
        <input  type="text" placeholder="5500 ₽" />
      </div>
      <hr class="price-line">
      <div class="price-value">
        <p class="price-begin">от</p>
        <input  type="text" placeholder="5500 ₽" />
      </div>
    </div>
  </div>
  <div class="brand-block">
    <div class="brand-section">
      <p class="section-title">Бренд</p>
      <p class="section-clear">Очистить</p>
    </div>
    <div class="brand-search">
      <img class="search-img" alt="Поиск" src="/src/assets/Iconsearch.svg">
      <input  type="text" placeholder="Поиск" />
    </div>
    <div class="brand-attributes">
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
    </div>
  </div>
  <div class="size-block">
    <h3 class="size-block-title">Размер</h3>
    <div class="size-attributes">
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
      <div class="attribute">
        <div class="check-attribute">
          <label class="container">Атрибут
            <input type="checkbox" checked="checked">
            <span class="checkmark"></span>
          </label>
        </div>
        <p class="attribute-amount">3</p>
      </div>
    </div>
  </div>
</div>
</template>

<style scoped lang="scss">
.sidebar{
  display: none;
  width: 280px;
  margin-top: 26px;

  @media (min-width: 1440px) {
    display: block;
  }

  .category__section{
    display: flex;
    justify-content: space-between;

    .category-name{
      font-size: 14px;
      line-height: 16px;
      padding: 8px 7px;
    }

    .category-amount{
      font-size: 12px;
      padding: 7px 35px;
      line-height: 14px;
      color: #AAAAAA;
    }
    .li{
      padding-left: 24px;
    }
  }
  .price-block{
    margin-top: 28px;

    .price-title{
      text-align: center ;
      font-size: 16px;
      line-height: 20px ;
    }
    .price-text{
      display: flex;
      justify-content: space-between;
      margin-top: 16px;

      .price-value {
        display: flex;
        border: 1px solid #D5D5D5;
        border-radius: 4px;
        padding: 0 13px;
        cursor: pointer;

        .price-begin {
          font-size: 12px;
          line-height: 14px;
          color: #AAAAAA;
          font-weight: 400;
          padding: 11px 0;
        }

        input {
          border: 0;
          padding: 10px 7px;
          font-size: 14px;
          line-height: 16px;
          max-width: 80px;
          outline: none;
          cursor: pointer;

        }
      }
      .price-line{
        background-color: #D5D5D5;
        border: none;
        width: 10px;
        z-index: 100;
        height: 1px;
        margin-top: 18px;
      }
    }
  }
  .brand-block{
    margin-top: 28px;
    margin-bottom: 16px;

    .brand-section{
      display: flex;
      justify-content: space-between;

      .section-title{
        font-size: 16px;
        line-height: 20px;
        font-weight: 700;
      }
      .section-clear{
        font-size: 12px;
        line-height: 23px;
        font-weight: 400;
        color: #AAAAAA;
        text-decoration: underline;
        cursor: pointer;
      }
    }
    .brand-search {
      border: 1px solid #D5D5D5;
      border-radius: 4px;
      padding: 0 13px;
      position: relative;
      margin-top: 16px;
      cursor: pointer;

      .search-img {
        position: absolute;
        width: 16px;
        height: 16px;
        top: 10px;
        right: 250px;
      }

      input {
        border: 0;
        padding: 10px;
        font-size: 14px;
        width: 200px;
        margin-left: 14px;
        line-height: 16px;
        color: #AAAAAA;
        outline: none;
        cursor: pointer;
      }
    }
    .brand-attributes{
      margin-top: 16px;
      height: 180px;
      overflow: auto;
      overflow-y: scroll;
      scrollbar-width: thin;
      scrollbar-color: #AAAAAA #FFFFFF;
      scrollbar-arrow-color: #FFFFFF;
      -ms-scrollbar-arrow-color: #FFFFFF;
      scrollbar-track-color: #FFFFFF;
      scrollbar-face-color: #FFFFFF;
      scrollbar-shadow-color: #FFFFFF;


      .attribute{
        display: flex;
        justify-content: space-between;

        .check-attribute{
          display: flex;
        }
        .attribute-amount{
          font-size: 12px;
          color: #AAAAAA;
          line-height: 18px;
          padding: 0 22px;
        }
      }
    }
  }
}
.size-block{
  margin-top: 5px;

  .size-block-title{
    text-align: center;
  }
  .size-attributes{
    margin-top: 16px;
    height: 180px;

    .attribute{
      display: flex;
      justify-content: space-between;

      .check-attribute{
        display: flex;
      }
      .attribute-amount{
        font-size: 12px;
        color: #AAAAAA;
        line-height: 18px;
        padding: 0 22px;
      }
    }
  }
}
.li{
  margin-left: 24px;
}
</style>
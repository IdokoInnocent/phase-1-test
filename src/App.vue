<template>
  <main class="main">
    <nav class="header">
      <h1 class="header__primary">Online Shopping</h1>
      <div class="header__cart">
        <span class="material-icons"> shopping_cart </span>
        <p>Cart <span class="header__cart--count">3</span></p>
      </div>
    </nav>

    <!-- products and cart section-->
    <section class="row">
      <div class="product-listing">
        <div class="row__icons">
          <span class="material-icons">apps</span>
          <span class="material-icons">view_list</span>
        </div>
        <div class="product-listing__row">
          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/20.jpg" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Nike Sport<span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">Unisex sport can</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/5.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Long Sleeve
                <span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">Men's office shirt</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/2.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Smart Watch
                <span class="product-availability product-availability--out"
                  >OUT OF STOCK</span
                >
              </h1>

              <p class="product-description">Smart watch for smart people</p>
              <p class="product-price">₹3,500</p>
              <a class="btn btn--out">ADD TO CART</a>
            </div>
          </div>
        </div>

        <!-- Second Row Product-->
        <div class="product-listing__row">
          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/10.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Gold Chain <span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">Women's Gold Chain</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/3.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Polo T-Shirt
                <span class="product-availability product-availability--out"
                  >OUT OF STOCK</span
                >
              </h1>

              <p class="product-description">White polo t-shirt for men</p>
              <p class="product-price">₹3,500</p>
              <a class="btn btn--out">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/6.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                bridal Gown
                <span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">White bridal gown</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>
        </div>

        <!-- Third Row Product -->
        <div class="product-listing__row">
          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/9.png" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Necklace <span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">Gold Necklace for women</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/17.jpg" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Leather Shoe
                <span class="product-availability product-availability--out"
                  >OUT OF STOCK</span
                >
              </h1>

              <p class="product-description">Pure leather Mocassin for men</p>
              <p class="product-price">₹3,500</p>
              <a class="btn btn--out">ADD TO CART</a>
            </div>
          </div>

          <div class="product-listing__card">
            <div class="img-container">
              <img class="img" src="/img/18.jpg" alt="Image" />
            </div>
            <div class="product-listing__details">
              <h1 class="product-name">
                Leather purse
                <span class="product-availability">IN STOCK</span>
              </h1>

              <p class="product-description">Simple female purse</p>
              <p class="product-price">₹3,500</p>
              <a class="btn">ADD TO CART</a>
            </div>
          </div>
        </div>
      </div>

      <!-- Cart Section -->
      <div class="cart">
        <h1 cart__heading>YOUR SHOPPING CART</h1>
        <div class="cart__row">
          <div class="cart__block">
            <h2 class="cart__product-name">Smart Watch</h2>
            <div>
              <p class="cart__product-price">
                ₹3,500 <button class="cart__delete">&times;</button>
              </p>
            </div>
          </div>
          <div class="line">&nbsp;</div>

          <div class="cart__block">
            <h2 class="cart__product-name">White T Shirt</h2>
            <div>
              <p class="cart__product-price">
                ₹3,500 <button class="cart__delete">&times;</button>
              </p>
            </div>
          </div>
          <div class="line">&nbsp;</div>

          <div class="cart__block">
            <h2 class="cart__product-name">Leather Shoe</h2>
            <div>
              <p class="cart__product-price">
                ₹3,500 <button class="cart__delete">&times;</button>
              </p>
            </div>
          </div>
          <div class="line">&nbsp;</div>

          <div class="cart__block">
            <p class="cart__total cart__product-name">Total</p>
            <p class="cart__total-value">₹10,500</p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "App",

  data() {
    return {};
  },
};
</script>

<style lang="scss">
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #66c57a;
  color: #fff;
  padding: 1.5rem;
  font-family: "Lato", sans-serif;

  &__primary {
    font-size: 1.8rem;
  }

  &__cart {
    display: flex;
    justify-content: space-between;
    // align-items: center;

    p {
      font-size: 1.6rem;
    }

    &--count {
      background: red;
      padding: 0.5rem 0.8rem;
      border-radius: 100rem;
      font-size: 1.2rem;
      font-weight: 600;
      // display: inline-block;
    }
  }
}

// row section
.row {
  display: flex;

  @media only screen and (max-width: 37.5em) {
    flex-direction: column;
  }

  &__icons {
    display: flex;
    justify-content: flex-end;
    position: relative;
    top: 1rem;
    right: 2.5rem;
  }

  .product-listing {
    flex-basis: 70%;
    background-color: #ddd;
    // height: 100vh;

    &__row {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 2rem 2rem;
      column-gap: 2rem;
      row-gap: 1rem;

      @media only screen and (max-width: 56.25em) {
        display: grid;
        grid-template-columns: repeat(2, 2fr);
        column-gap: 1rem;
      }

      @media only screen and (max-width: 37.5em) {
        display: flex;
        flex-direction: column;
      }
    }

    &__card {
      background: var(--white);
      width: 100%;
      border-radius: 1rem;
      box-shadow: 0 15px 20px rgba(0, 0, 0, 0.3);

      .img-container {
        // border-radius: 1rem;
        // background-color: black;

        img {
          object-fit: cover;
          width: 100%;
          display: block;
          border-top-right-radius: 1rem;
          border-top-left-radius: 1rem;
        }
      }
    }

    &__details {
      margin-left: 2rem;
      margin-top: 2rem;
      // padding-bottom: 2rem;
      height: 16rem;

      .product-name {
        font-size: 1.5rem;
      }

      .product-description {
        font-size: 1.3rem;
        font-weight: 600;
        font-style: italic;
        margin-top: 0.7rem;
      }

      .product-price {
        margin-top: 1.3rem;
        font-size: 1.5rem;
        font-weight: 600;
      }

      .product-availability {
        font-size: 1rem;
        font-weight: 600;
        padding: 0.4rem 1rem;
        border-radius: 1rem;
        background-color: rgba(255, 255, 0, 0.35);
        position: relative;
        left: 10rem;

        @media only screen and (max-width: 75em) {
          left: 3rem;
          padding: 0.3rem;
        }

        &--out {
          background: #ddd;
          padding: 0.4rem;
          position: relative;
          left: 8rem;

          @media only screen and (max-width: 56.25em) {
            padding: 0.2rem;
            left: 2rem;
          }
        }
      }
    }
  }

  .cart {
    flex-basis: 30%;
    background: var(--white);
    padding: 2rem;

    h1 {
      color: #333fff;
    }

    &__row {
      display: flex;
      flex-direction: column;
    }

    &__block {
      display: flex;
      align-items: center;
      gap: 10rem;
      padding-top: 1.4rem;

      @media only screen and (max-width: 56.25em) {
        gap: 3rem;
      }

      .cart__product-name {
        font-size: 1.5rem;
        font-weight: 600;
        color: #777;
      }

      .cart__total-value {
        font-size: 2rem;
        font-weight: 900;
        color: #333fff;
        position: relative;
        left: 5rem;

        @media only screen and (max-width: 56.25em) {
          left: 1rem;
        }

        @media only screen and (max-width: 56.25em) {
          left: 2rem;
        }
      }
      div {
        .cart__product-price {
          font-size: 1.5rem;
          font-weight: 600;
        }

        .cart__delete {
          display: inline-block;
          font-size: 1.6rem;
          // background: #777;
          position: relative;
          left: 1.6rem;
          cursor: pointer;
          outline: none;
          border: none;
          padding: 0.1rem 0.4rem;
        }
      }
    }
  }
}

.btn {
  font-size: 1.3rem;
  font-weight: 600;
  text-decoration: none;
  color: var(--white);
  background-color: var(--color-sec);
  padding: 1rem 5rem;
  border-radius: 3rem;
  text-align: center;
  position: relative;
  top: 4rem;
  left: 3rem;
  cursor: pointer;

  @media only screen and (max-width: 75em) {
    padding: 1rem 2rem;
    border-radius: 1.5rem;
    left: 1rem;
  }

  &--out {
    background: #777;
  }
}

.line {
  margin: 1rem 0;
  width: 75%;
  height: 1px;
  background-color: #e0e0e0;

  @media only screen and (max-width: 56.25em) {
    width: 80%;
  }

  @media only screen and (max-width: 37.5em) {
    width: 40%;
  }
}
</style>

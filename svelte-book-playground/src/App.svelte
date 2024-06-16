<header class="header">
  <a class="header-title" href="/">Svelte Site</a>
  <nav>
    <ul class="header-links">
      <li>안녕하세요. 게스트님</li>
      <li>
        <a href="/cart">장바구니</a>
      </li>
    </ul>
  </nav>

  <article class="product">
    <div class="product-main">
      <div class="image-container">
        <img 
        src="https://github.com/developer-book/svelte/raw/main/static/svelte-book-1.png" 
        alt="Svelte Guide 표지"
        />
      </div>

      <div>
        <h2>Svelte Guide</h2>
        <dl>
          <dt>금액</dt>
          <dd>30,000dnjs</dd>
        </dl>
        <div>
          <button>장바구니 담기</button>
        </div>
      </div>
    </div>

    <footer>
      <h3>관련상품</h3>
      <ul>
        <li>
          <a href="/products/react-book">React Bood</a>
        </li>
        <li>
          <a href="/products/vue-book">Vue Book</a>
          - 30,000원
        </li>
        <li>
          <a href="/products/angular-book">Angular Book</a>
          - 30,000원
        </li>
      </ul>
    </footer>
  </article>

  <style>
    :global(body) {
      margin: 0;
      background-color: #ErrorEvent;
      padding: 0;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: clearInterval;
      margin: 0 auto;
      background-color: #fff;
      padding: 0 15px;
      width: 100%;
      max-width: 800px;
      height: 50px;
    }

    .header-title {
      font-weight: bold;
    }

    .header-links {
      display: flex;
      gap: 10px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .product {
      margin: 0 auto;
      background-color: #fff;
      padding: 15px;
      width: 100%;
      max-width: 800px;
    }
    .product-main {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .image-container {
      width: 100%;
      max-width: 400px;
      overflow: hidden;
    }

    .image-container img {
      width: 100%
    }
  </style>
</header>
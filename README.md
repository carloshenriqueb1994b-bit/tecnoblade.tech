<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Tecnoblade tech — Os Melhores Eletrônicos do Mercado</title>
<meta name="description" content="Tecnoblade tech: smartphones, laptops, tablets e acessórios com preços imbatíveis." />
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.tecnoblade.tech' viewBox='0 0 64 64'%3E%3Cpath fill='%23ff3b30' d='M32 6l9 12h11l-8 10 8 10H41l-9 12-9-12H12l8-10-8-10h11z'/%3E%3C/svg%3E">
<style>
  :root{
    --bg:#0f172a; /* slate-900 */
    --bg-2:#111827; /* gray-900 */
    --card:#1f2937; /* gray-800 */
    --text:#e5e7eb; /* gray-200 */
    --muted:#9ca3af; /* gray-400 */
    --brand:#ef4444; /* red-500 */
    --brand-2:#f97316; /* orange-500 */
    --accent:#22c55e; /* green-500 */
    --shadow:0 10px 30px rgba(0,0,0,.35);
    --radius:18px;
  }
  *{box-sizing:border-box}
  html,body{margin:0;background:linear-gradient(180deg,var(--bg),#0b1222 70%);color:var(--text);font-family:Inter,system-ui,Segoe UI,Roboto,Arial,sans-serif}
  a{color:inherit;text-decoration:none}
  .container{max-width:1200px;margin:auto;padding:0 16px}
  /* Header */
  header{position:sticky;top:0;z-index:40;background:rgba(15,23,42,.85);backdrop-filter:blur(8px);border-bottom:1px solid rgba(255,255,255,.06)}
  .nav{display:flex;align-items:center;gap:18px;justify-content:space-between;padding:14px 0}
  .brand{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.3px}
  .brand .logo{width:34px;height:34px;border-radius:12px;background:linear-gradient(135deg,var(--brand),#ff7b54);display:grid;place-items:center;box-shadow:var(--shadow)}
  .nav-links{display:flex;gap:14px;flex-wrap:wrap}
  .nav-links a{opacity:.85;font-weight:600}
  .nav-right{display:flex;gap:10px;align-items:center}
  .btn{background:var(--brand);border:none;color:white;padding:10px 14px;border-radius:12px;font-weight:700;cursor:pointer;box-shadow:var(--shadow)}
  .btn.secondary{background:#374151}
  .icon-btn{background:#1f2937;border:1px solid rgba(255,255,255,.08);color:#fff;border-radius:12px;display:grid;place-items:center;width:40px;height:40px;cursor:pointer}
  .pill{border-radius:999px;padding:6px 10px;background:#1f2937;border:1px solid rgba(255,255,255,.08);display:flex;gap:8px;align-items:center}
  input[type="search"]{all:unset;min-width:220px;color:#fff}
  /* Hero */
  .hero{position:relative;overflow:hidden}
  .hero::before{
    content:"";position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1518779578993-ec3579fee39f?q=80&w=2100&auto=format&fit=crop') center/cover no-repeat;opacity:.18;filter:saturate(0) blur(1px)
  }
  .hero .wrap{display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center;padding:48px 0}
  .h1{font-size:clamp(28px,4vw,56px);line-height:1.05;margin:0 0 10px}
  .h1 span{color:var(--brand)}
  .lead{color:#d1d5db;opacity:.95;max-width:680px}
  .cta{display:flex;gap:12px;margin-top:18px;flex-wrap:wrap}
  .hero-card{background:linear-gradient(180deg,#1f2937,#111827);border:1px solid rgba(255,255,255,.06);border-radius:var(--radius);padding:18px;box-shadow:var(--shadow)}
  .hero-card img{width:100%;border-radius:14px}
  /* Sections */
  section{padding:28px 0}
  .section-title{font-size:26px;margin:0 0 8px}
  .section-sub{color:var(--muted);margin:0 0 18px}
  /* Category cards */
  .grid{display:grid;gap:18px}
  .grid.cols-3{grid-template-columns:repeat(3,minmax(0,1fr))}
  .grid.cols-4{grid-template-columns:repeat(4,minmax(0,1fr))}
  @media (max-width:960px){.grid.cols-3,.grid.cols-4{grid-template-columns:repeat(2,minmax(0,1fr))}.hero .wrap{grid-template-columns:1fr}}
  @media (max-width:600px){.grid.cols-3,.grid.cols-4{grid-template-columns:1fr}}
  .card{background:linear-gradient(180deg,#1f2937,#111827);border:1px solid rgba(255,255,255,.06);border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow)}
  .card-body{padding:14px}
  .category-thumb{height:160px;background:#0b1222 url('https://images.unsplash.com/photo-1609692814858-f7cd2f0afa9d?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat}
  /* Product */
  .product{position:relative;display:flex;flex-direction:column}
  .product .badge{position:absolute;top:10px;left:10px;background:var(--brand);color:#fff;font-weight:800;border-radius:999px;padding:6px 10px;font-size:12px}
  .product .badge.offer{background:var(--brand-2)}
  .product .badge.new{background:#a855f7}
  .product .fav{position:absolute;top:10px;right:10px}
  .product .thumb{background:#0b1222;height:210px;display:grid;place-items:center}
  .product .thumb img{max-height:170px;max-width:90%;object-fit:contain;filter:drop-shadow(0 10px 18px rgba(0,0,0,.5))}
  .brand-tag{color:#f3f4f6;font-weight:700;font-size:12px;opacity:.85}
  .title{font-weight:800;margin:6px 0}
  .rating{display:flex;gap:6px;align-items:center;color:#fde68a;font-size:13px}
  .price{margin-top:8px}
  .price .now{color:#fff;font-weight:900;font-size:20px}
  .price .old{color:#9ca3af;text-decoration:line-through;margin-left:8px;font-size:13px}
  .actions{display:flex;gap:10px;margin-top:12px}
  .small{font-size:12px;color:var(--muted)}
  /* Drawer Cart */
  .drawer{position:fixed;inset:0;pointer-events:none}
  .drawer.open{pointer-events:auto}
  .drawer .backdrop{position:absolute;inset:0;background:rgba(0,0,0,.55);opacity:0;transition:.2s}
  .drawer.open .backdrop{opacity:1}
  .drawer .panel{
    position:absolute;top:0;right:-420px;width:min(420px,95%);height:100%;background:#0b1222;border-left:1px solid rgba(255,255,255,.08);box-shadow:var(--shadow);transition:.25s;padding:16px;display:flex;flex-direction:column;gap:12px
  }
  .drawer.open .panel{right:0}
  .cart-item{display:grid;grid-template-columns:60px 1fr auto;gap:10px;align-items:center;padding:10px;border:1px solid rgba(255,255,255,.06);border-radius:14px;background:linear-gradient(180deg,#121a2b,#0c1526)}
  .qty{display:flex;align-items:center;gap:6px}
  .qty button{width:28px;height:28px;border-radius:8px;border:1px solid rgba(255,255,255,.08);background:#1f2937;color:#fff;cursor:pointer}
  .total{margin-top:auto;border-top:1px solid rgba(255,255,255,.08);padding-top:12px}
  .empty{color:#9ca3af;text-align:center;padding:30px}
  .link{color:#93c5fd;text-decoration:underline;cursor:pointer}
  footer{padding:36px 0;border-top:1px solid rgba(255,255,255,.06);color:#9ca3af;text-align:center}
</style>
</head>
<body>
<header>
  <div class="container nav">
    <a class="brand" href="#">
      <span class="logo">🗡️</span>
      <span>tecnoblade <span style="color:#ffb4a4">tech</span></span>
    </a>
    <nav class="nav-links">
      <a href="#produtos">Produtos</a>
      <a href="#categorias">Categorias</a>
      <a href="#ofertas">Ofertas</a>
      <a href="#contato">Contato</a>
    </nav>
    <div class="nav-right">
      <label class="pill" title="Buscar">
        🔎 <input id="search" type="search" placeholder="Buscar produtos…" />
      </label>
      <button id="btnCart" class="icon-btn" title="Carrinho 🛒">🛒<span id="cartCount" style="margin-left:6px;font-weight:700"></span></button>
    </div>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <div class="container wrap">
    <div>
      <h1 class="h1">Os <span>Melhores Eletrônicos</span> do Mercado</h1>
      <p class="lead">
        Descubra nossa seleção premium de smartphones, laptops, tablets e acessórios tecnológicos das melhores marcas com preços imbatíveis.
      </p>
      <div class="cta">
        <a href="#produtos" class="btn">Ver Produtos</a>
        <a href="#ofertas" class="btn secondary">Ofertas Especiais</a>
      </div>
    </div>
    <div class="hero-card">
      <img alt="Showroom" src="https://images.unsplash.com/photo-1510557880182-3d4d3cba35c1?q=80&w=1600&auto=format&fit=crop">
      <div class="small" style="margin-top:8px">Entrega para todo o Brasil • Garantia e Nota Fiscal</div>
    </div>
  </div>
</section>

<!-- CATEGORIAS -->
<section id="categorias">
  <div class="container">
    <h2 class="section-title">Nossas Categorias</h2>
    <p class="section-sub">Explore nossa ampla seleção de produtos organizados por categoria.</p>
    <div class="grid cols-3" id="categoryGrid">
      <!-- gerado via JS -->
    </div>
  </div>
</section>

<!-- VITRINE / FILTROS -->
<section class="container" id="produtos">
  <div style="display:flex;gap:12px;align-items:center;flex-wrap:wrap;margin-bottom:14px">
    <strong>Filtrar:</strong>
    <select id="filterCategory" class="pill">
      <option value="">Todas as categorias</option>
    </select>
    <select id="filterBrand" class="pill">
      <option value="">Todas as marcas</option>
    </select>
    <select id="sortBy" class="pill">
      <option value="featured">Ordenar: Destaque</option>
      <option value="price-asc">Menor preço</option>
      <option value="price-desc">Maior preço</option>
      <option value="rating">Melhor avaliação</option>
    </select>
    <span class="small">Dica: clique no ❤️ para favoritar.</span>
  </div>
  <div class="grid cols-3" id="productGrid"><!-- via JS --></div>
</section>

<!-- OFERTAS EM DESTAQUE -->
<section id="ofertas">
  <div class="container">
    <h2 class="section-title">Produtos em Destaque</h2>
    <p class="section-sub">Os mais vendidos e com melhores avaliações.</p>
    <div class="grid cols-4" id="featuredGrid"><!-- via JS --></div>
  </div>
</section>

<!-- CONTATO -->
<section id="contato">
  <div class="container card" style="padding:18px">
    <h3>Contato</h3>
    <div class="small">Dúvidas? Fale com a Tecnoblade tech pelo WhatsApp:
      <a class="link" href="https://wa.me/55+61+998807331" target="_blank" rel="noopener">clique aqui</a>.
      (edite o número acima para o seu)
    </div>
  </div>
</section>

<footer>
  © <span id="y"></span> Tecnoblade tech — Todos os direitos reservados.
</footer>

<!-- Drawer Carrinho -->
<div class="drawer" id="drawer">
  <div class="backdrop" id="backdrop"></div>
  <aside class="panel">
    <div style="display:flex;justify-content:space-between;align-items:center">
      <h3 style="margin:0">Seu Carrinho</h3>
      <button id="closeCart" class="icon-btn">✖️</button>
    </div>
    <div id="cartList"><div class="empty">Seu carrinho está vazio.</div></div>
    <div class="total">
      <div style="display:flex;justify-content:space-between">
        <span class="small">Subtotal</span>
        <strong id="subtotal">R$ 0,00</strong>
      </div>
      <div style="display:flex;gap:10px;margin-top:12px;flex-wrap:wrap">
        <button id="btnClear" class="btn secondary">Limpar</button>
        <button id="btnCheckout" class="btn">Finalizar Compra</button>
      </div>
      <div class="small" style="margin-top:8px">
        O checkout abre o WhatsApp com o resumo do pedido (você pode mudar depois para PIX ou cartão).
      </div>
    </div>
  </aside>
</div>

<script>
  // ====== DADOS ======
  const BRL = new Intl.NumberFormat('pt-BR',{style:'currency', currency:'BRL'});
  const products = [
    {
      id:'iphone15pm', name:'iPhone 15 Pro Max', brand:'Apple', category:'Smartphones',
      price:5000.99, oldPrice:9999.99, rating:4.9, ratingsCount:2847, badge:'Mais Vendido',
      img:'https://images.unsplash.com/photo-1695048133145-1c29a2b3d527?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'macbook-air-m3', name:'MacBook Air M3', brand:'Apple', category:'Laptops',
      price:10999.99, oldPrice:14999.99, rating:4.8, ratingsCount:1592, badge:'Oferta',
      img:'https://images.unsplash.com/photo-1517336714731-489689fd1ca8?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'s24u', name:'Samsung Galaxy S24 Ultra', brand:'Samsung', category:'Smartphones',
      price:7499.99, oldPrice:8299.99, rating:4.7, ratingsCount:3241, badge:'Novo',
      img:'https://images.unsplash.com/photo-1606904825809-00287b2a0f19?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'ipad-air', name:'iPad Air (M2)', brand:'Apple', category:'Tablets',
      price:4799.99, oldPrice:5299.99, rating:4.8, ratingsCount:1022, badge:'Oferta',
      img:'https://images.unsplash.com/photo-1542751110-97427bbecf20?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'lenovo-slim', name:'Lenovo Slim 7', brand:'Lenovo', category:'Laptops',
      price:5699.00, oldPrice:6199.90, rating:4.6, ratingsCount:811, badge:'',
      img:'https://images.unsplash.com/photo-1517336714731-489689fd1ca8?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'dell-xps13', name:'Dell XPS 13', brand:'Dell', category:'Laptops',
      price:7999.90, oldPrice:8999.90, rating:4.7, ratingsCount:1300, badge:'Mais Vendido',
      img:'https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'airpods-pro', name:'AirPods Pro (2ª Geração)', brand:'Apple', category:'Fones',
      price:1599.00, oldPrice:1999.00, rating:4.9, ratingsCount:5000, badge:'Oferta',
      img:'https://images.unsplash.com/photo-1585386959984-a4155223169f?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'sony-wh1000xm5', name:'Sony WH-1000XM5', brand:'Sony', category:'Fones',
      price:2399.00, oldPrice:2999.00, rating:4.8, ratingsCount:2100, badge:'',
      img:'https://images.unsplash.com/photo-1518441902110-477b6e0b1d9f?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'galaxy-tab-s9', name:'Samsung Galaxy Tab S9', brand:'Samsung', category:'Tablets',
      price:4999.90, oldPrice:5499.90, rating:4.6, ratingsCount:620, badge:'Novo',
      img:'https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?q=80&w=1200&auto=format&fit=crop'
    },
    {
      id:'xiaomi-13', name:'Xiaomi 13', brand:'Xiaomi', category:'Smartphones',
      price:3499.00, oldPrice:3799.00, rating:4.5, ratingsCount:980, badge:'',
      img:'https://images.unsplash.com/photo-1557180295-76eee20ae8aa?q=80&w=1200&auto=format&fit=crop'
    }
  ];

  const categories = [
    { key:'Smartphones', subtitle:'iPhone, Samsung, Xiaomi',
      img:'https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?q=80&w=1600&auto=format&fit=crop'},
    { key:'Laptops', subtitle:'MacBook, Dell, HP, Lenovo',
      img:'https://images.unsplash.com/photo-1517336714731-489689fd1ca8?q=80&w=1600&auto=format&fit=crop'},
    { key:'Tablets', subtitle:'iPad, Samsung Tab, Surface',
      img:'https://images.unsplash.com/photo-1542751110-97427bbecf20?q=80&w=1600&auto=format&fit=crop'},
    { key:'Fones', subtitle:'AirPods, Sony, JBL, Beats',
      img:'https://images.unsplash.com/photo-1585386959984-a4155223169f?q=80&w=1600&auto=format&fit=crop'}
  ];

  // ====== ESTADO ======
  const state = {
    search: '',
    filterCategory: '',
    filterBrand: '',
    sortBy: 'featured',
    favorites: new Set(JSON.parse(localStorage.getItem('favorites')||'[]')),
    cart: JSON.parse(localStorage.getItem('cart')||'[]') // [{id,qty}]
  };

  // ====== UTIL ======
  const $ = (sel, root=document)=>root.querySelector(sel);
  const $$ = (sel, root=document)=>Array.from(root.querySelectorAll(sel));
  const setCartCount = ()=>{ $('#cartCount').textContent = state.cart.reduce((a,i)=>a+i.qty,0)||'' };
  const save = ()=>{
    localStorage.setItem('favorites', JSON.stringify([...state.favorites]));
    localStorage.setItem('cart', JSON.stringify(state.cart));
    setCartCount();
  };
  const productById = id => products.find(p=>p.id===id);
  const addToCart = (id, qty=1)=>{
    const row = state.cart.find(i=>i.id===id);
    if(row){ row.qty += qty; } else { state.cart.push({id, qty}); }
    save(); renderCart();
  };
  const changeQty = (id, delta)=>{
    const idx = state.cart.findIndex(i=>i.id===id);
    if(idx>=0){
      state.cart[idx].qty += delta;
      if(state.cart[idx].qty<=0) state.cart.splice(idx,1);
      save(); renderCart();
    }
  };
  const clearCart = ()=>{ state.cart = []; save(); renderCart(); };

  // ====== RENDER ======
  function renderCategories(){
    const grid = $('#categoryGrid'); grid.innerHTML='';
    categories.forEach(c=>{
      const card = document.createElement('article'); card.className='card';
      card.innerHTML = `
        <div class="category-thumb" style="background-image:url('${c.img}')"></div>
        <div class="card-body">
          <div class="title">${c.key}</div>
          <div class="small">${c.subtitle}</div>
        </div>`;
      card.addEventListener('click', ()=>{
        $('#filterCategory').value = c.key;
        state.filterCategory = c.key;
        renderProducts();
        window.scrollTo({top: $('#produtos').offsetTop - 70, behavior:'smooth'});
      });
      grid.appendChild(card);
    });
  }

  function optionsFrom(arr, el){
    [...new Set(arr)].sort().forEach(v=>{
      const o = document.createElement('option'); o.value=v; o.textContent=v; el.appendChild(o);
    });
  }

  function starRow(score){
    const full = Math.round(score);
    return '⭐'.repeat(full)+'<span class="small" style="color:#fef3c7;margin-left:6px">'+score.toFixed(1)+'</span>';
  }

  function badgeClass(text){
    if(text==='Oferta') return 'badge offer';
    if(text==='Novo') return 'badge new';
    return 'badge';
  }

  function renderProducts(){
    const grid = $('#productGrid'); grid.innerHTML='';
    let list = products.slice();

    // search/filter/sort
    if(state.search){
      const q = state.search.toLowerCase();
      list = list.filter(p => (p.name+' '+p.brand+' '+p.category).toLowerCase().includes(q));
    }
    if(state.filterCategory) list = list.filter(p=>p.category===state.filterCategory);
    if(state.filterBrand) list = list.filter(p=>p.brand===state.filterBrand);
    if(state.sortBy==='price-asc') list.sort((a,b)=>a.price-b.price);
    if(state.sortBy==='price-desc') list.sort((a,b)=>b.price-a.price);
    if(state.sortBy==='rating') list.sort((a,b)=>b.rating-a.rating);

    list.forEach(p=>{
      const card = document.createElement('article'); card.className='card product';
      card.innerHTML = `
        ${p.badge?`<div class="${badgeClass(p.badge)}">${p.badge}</div>`:''}
        <button class="icon-btn fav" title="Favoritar">${state.favorites.has(p.id)?'❤️':'🤍'}</button>
        <div class="thumb"><img alt="${p.name}" src="${p.img}"></div>
        <div class="card-body">
          <div class="brand-tag">${p.brand}</div>
          <div class="title">${p.name}</div>
          <div class="rating">${starRow(p.rating)} <span class="small">(${p.ratingsCount})</span></div>
          <div class="price"><span class="now">${BRL.format(p.price)}</span>${p.oldPrice?`<span class="old">${BRL.format(p.oldPrice)}</span>`:''}</div>
          <div class="actions">
            <button class="btn">Comprar Agora</button>
            <button class="btn secondary">Adicionar</button>
          </div>
        </div>`;
      $('.fav', card).addEventListener('click', (e)=>{
        e.stopPropagation();
        if(state.favorites.has(p.id)) state.favorites.delete(p.id); else state.favorites.add(p.id);
        save(); renderProducts();
      });
      $('.actions .btn', card).addEventListener('click', ()=>{ addToCart(p.id,1); openCart(); });
      $$('.actions .btn', card)[1].addEventListener('click', ()=>addToCart(p.id,1));
      grid.appendChild(card);
    });

    // destaque (quatro primeiros ordenados por avaliação)
    const featured = products.slice().sort((a,b)=>b.rating-a.rating).slice(0,4);
    const fgrid = $('#featuredGrid'); fgrid.innerHTML='';
    featured.forEach(p=>{
      const card = document.createElement('article'); card.className='card product';
      card.innerHTML = `
        ${p.badge?`<div class="${badgeClass(p.badge)}">${p.badge}</div>`:''}
        <div class="thumb

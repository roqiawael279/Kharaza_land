/* أساسيات التصميم */ body { font-family: 'Cairo', sans-serif; margin: 0; padding: 0; background-color: #fffaf5; color: #333; }

header, footer { background-color: #f8c9dd; color: #5a004f; text-align: center; padding: 1rem; }

main { padding: 1rem; }

.products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; margin-top: 1rem; }

.product { background-color: #fff; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); padding: 1rem; text-align: center; }

.product img { max-width: 100%; height: auto; border-radius: 10px; }

button, a.button { background-color: #f88dbb; color: white; border: none; padding: 0.5rem 1rem; font-size: 1rem; border-radius: 8px; cursor: pointer; text-decoration: none; display: inline-block; margin-top: 0.5rem; }

button:hover, a.button:hover { background-color: #e570a4; }

.cart-item { display: flex; gap: 1rem; margin-bottom: 1rem; background-color: #fff; border-radius: 10px; padding: 1rem; align-items: center; }

.cart-item img { width: 80px; height: auto; border-radius: 8px; }

.cart-actions { display: flex; flex-direction: column; align-items: center; gap: 0.5rem; margin-top: 1rem; }

.hidden { display: none; }

/* ✅ Responsive Design */ @media (max-width: 600px) { header, footer { font-size: 0.9rem; padding: 0.8rem; }

.product { padding: 0.8rem; }

.product h3, .product p { font-size: 1rem; }

button, a.button { font-size: 0.9rem; padding: 0.4rem 0.8rem; }

.cart-item { flex-direction: column; align-items: flex-start; }

.cart-item img { width: 100%; }

.cart-actions { flex-direction: column; } }

/* دعم اتجاه RTL */ body[dir="rtl"] { direction: rtl; text-align: right; }

body[dir="ltr"] { direction: ltr; text-align: left; }

<link rel="icon" type="image/png" href="assets/favicon.png">
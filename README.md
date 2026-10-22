<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Взаимка — обмен цифровыми навыками</title>
<meta name="description" content="Бесплатная платформа взаимопомощи: обменивайтесь навыками (программирование, монтаж, дизайн, переводы, учёба) без денег.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@500;700&family=Manrope:wght@400;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#F4F3FB;--surface:#fff;--ink:#1B1838;--muted:#6A6786;--line:#E4E2F2;--win:#5B3DF5;--win-soft:#ECE8FF;--vol:#0B8F6E;--vol-soft:#DDF5EC;--on:#fff;--shadow:0 10px 30px rgba(40,30,110,.10);
--hf:'Unbounded','Manrope',system-ui,sans-serif;--bf:'Manrope',system-ui,-apple-system,'Segoe UI',Roboto,sans-serif;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:light}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#14122B;--surface:#1E1B3D;--ink:#F1F0FF;--muted:#A9A6C8;--line:#322E5C;--win:#9C86FF;--win-soft:#2B2560;--vol:#3DD6A8;--vol-soft:#12403A;--on:#14122B;--shadow:0 10px 30px rgba(0,0,0,.35);color-scheme:dark}}
:root[data-theme="dark"]{--bg:#14122B;--surface:#1E1B3D;--ink:#F1F0FF;--muted:#A9A6C8;--line:#322E5C;--win:#9C86FF;--win-soft:#2B2560;--vol:#3DD6A8;--vol-soft:#12403A;--on:#14122B;--shadow:0 10px 30px rgba(0,0,0,.35);color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.5 var(--bf);--ac:var(--win);--ac-soft:var(--win-soft);transition:background .3s}
body[data-mode="vol"]{--ac:var(--vol);--ac-soft:var(--vol-soft)}
button,input,textarea,select{font:inherit;color:inherit}
button{cursor:pointer}
:focus-visible{outline:3px solid var(--ac);outline-offset:2px}
.wrap{max-width:1040px;margin:0 auto;padding:0 20px}
.top{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:18px 0}
.brand{font:700 20px var(--hf);letter-spacing:-.02em;display:flex;align-items:center;gap:10px}
.logo{width:34px;height:34px;border-radius:12px;background:var(--ac);display:grid;place-items:center;color:var(--on);font-size:18px;transition:background .3s}
.btn{border:0;border-radius:14px;padding:11px 18px;font-weight:800;background:var(--ac);color:var(--on);transition:transform .15s,background .3s,opacity .2s}
.btn:hover{transform:translateY(-1px)}.btn:active{transform:scale(.97)}
.btn.ghost{background:var(--ac-soft);color:var(--ac)}
.btn.sm{padding:9px 14px;font-size:14px;width:100%}
.hero{padding:26px 0 22px;text-align:center}
.hero h1{font:700 clamp(28px,6vw,46px)/1.12 var(--hf);letter-spacing:-.03em;margin:0 auto 14px;max-width:16em}
.hero p{margin:0 auto;max-width:34em;color:var(--muted);font-size:17px}
.swap{display:inline-flex
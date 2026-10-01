<!DOCTYPE html>

<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Razas de perro</title>

<style>
:root {
  --bg: #0a3d91;
  --bg2: #082f70;
  --fg: #5dff9a;
  --fg2: #b8ffd3;
}

* {
  box-sizing: border-box;
}

html {
  scroll-padding-top: env(safe-area-inset-top, 0px);
}

body {
  margin: 0;
  background: var(--bg);
  color: var(--fg);
  font-family: "Trebuchet MS", "Segoe UI", Arial, sans-serif;
  line-height: 1.5;
}

header {
  padding: 12vh 6vw 8vh;
  max-width: 1100px;
  margin: 0 auto;
}

h1 {
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(3rem, 11vw, 8rem);
  line-height: .95;
  margin: 0 0 1.5rem;
  font-weight: 700;
  letter-spacing: -.02em;
}

header p {
  font-size: 1.2rem;
  max-width: 34rem;
  color: var(--fg2);
  margin: 0 0 2rem;
}

.btn {
  display: inline-block;
  background: var(--fg);
  color: var(--bg2);
  padding: .8rem 1.6rem;
  border-radius: 999px;
  font-weight: 700;
  text-decoration: none;
}

.btn:focus-visible,
a:focus-visible {
  outline: 3px solid #fff;
  outline-offset: 3px;
}

main {
  background: var(--bg2);
  padding: 8vh 6vw;
}

.wrap {
  max-width: 1100px;
  margin: 0 auto;
}

h2 {
  font-family: Georgia, serif;
  font-size: 2rem;
  margin: 0 0 2rem;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
  gap: 1rem;
}

li {
  border: 2px solid var(--fg);
  border-radius: 14px;
  padding: 1.1rem 1.2rem;
}

li b {
  display: block;
  font-size: 1.25rem;
}

li span {
  color: var(--fg2);
  font-size: .95rem;
}

footer {
  padding: 6vh 6vw;
  text-align: center;
  color: var(--fg2);
}
</style>

</head>

<body>

<header>
  <h1>Razas de perro</h1>

  <p>
    Una lista para conocer las razas más populares y elegir la que mejor encaja contigo.
  </p>

<a class="btn" href="#razas">Ver las razas</a>

</header>

<main id="razas">
  <div class="wrap">
    <h2>Elige tu compañero</h2>

```
<ul>
  <li><b>Labrador retriever</b><span>Amable, activo y fácil de educar.</span></li>
  <li><b>Pastor alemán</b><span>Leal, inteligente y protector.</span></li>
  <li><b>Golden retriever</b><span>Cariñoso y paciente con los niños.</span></li>
  <li><b>Bulldog francés</b><span>Pequeño, tranquilo y sociable.</span></li>
  <li><b>Beagle</b><span>Curioso, alegre y gran olfato.</span></li>
  <li><b>Caniche</b><span>Muy listo y de pelo poco alérgico.</span></li>
  <li><b>Border collie</b><span>Energía sin límites e inteligencia alta.</span></li>
  <li><b>Husky siberiano</b><span>Resistente, juguetón y amante del frío.</span></li>
  <li><b>Chihuahua</b><span>El más pequeño, con mucho carácter.</span></li>
  <li><b>Boxer</b><span>Fuerte, divertido y muy familiar.</span></li>
  <li><b>Dálmata</b><span>Elegante, deportista y reconocible.</span></li>
  <li><b>Podenco andaluz</b><span>Ágil, rápido y muy cazador.</span></li>
</ul>
```

  </div>
</main>

</body>
</html>

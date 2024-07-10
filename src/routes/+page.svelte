<script>
  import Catalonia from "../lib/catalonia.svelte";
  import Direccion from "../lib/direccion.svelte";
  import Ingles from "../lib/ingles.svelte";
  import Llengues from "../lib/llengues.svelte";
  import Projectes from "../lib/projectes.svelte";
  import Spain from "../lib/spain.svelte";
  import "../styles.css";
</script>

<section class="presentacion">
  <h1>Sóc Álex 👋</h1>

  <p>
    El millor desenvolupador web del multiverse. Programo: HTML, CSS, JavaScript i PHP.
    (Nivell principiant amb traumes ).
  </p>
</section>
<section class="llengues">
  <h2>
    <Llengues /> Llengues
  </h2>
  <div class="contenedor">
    <div>
      <Spain />
      <p>Castellano</p>
    </div>
    <div>
      <Catalonia />
      <p>Català</p>
    </div>
    <div>
      <Ingles />
      <p>English</p>
    </div>
  </div>
</section>

<section class="prj">
  <h2>
    <Projectes /> Projectes
  </h2>
  <article>
    <h3>Contador k'ho flipes</h3>
    <p>Projecte de contador fet amb HTML, CSS i JS.</p>
    <a target="_blank" href="https://contadorflipante.netlify.app/">
      <Direccion/>
    </a>
    <img src="/contadorimagen.webp" alt="" />
  </article>

  <article>
    <h3>Banderuki-game</h3>
    <p>Projecte de joc amb banderes amb HTML, CSS i JS.</p>
    <a target="_blank" href="https://banderas.pages.dev/">
      <Direccion/>
    </a>
    <img src="/banderuki-img.png" alt="" />
  </article> 

  <article>
    <h3>Ets neng?</h3>
    <p>Projecte per saber el teu percentatge de nen amb HTML, CSS i JS.</p>
    <a target="_blank" href="https://nen.pages.dev/">
      <Direccion/>
    </a>
    <img src="/nen-img.png" alt="" />
  </article>  
</section>

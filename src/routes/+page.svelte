<script>
  import Catalonia from "../lib/catalonia.svelte";
  import Ingles from "../lib/ingles.svelte";
  import Llengues from "../lib/llengues.svelte";
  import Projectes from "../lib/projectes.svelte";
  import Spain from "../lib/spain.svelte";
  import "../styles.css";
</script>

<section class="presentacion">
  <h1>Sóc Álex 👋</h1>

  <p>
    El millor desenvolupador web del multiverse. Full stack, de tot menys js
    (tinc traumes).
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
    <img src="/contadorimagen.webp" alt="" />
  </article>
</section>

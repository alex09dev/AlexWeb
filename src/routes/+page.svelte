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
  <h1>Sóc <presentacion-gradiente>Álex</presentacion-gradiente> 👋</h1>

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
  
  <article>
    <h3>Contador k'ho flipes</h3>
    <p>Projecte de contador fet amb HTML, CSS i JS.</p>
    <a target="_blank" href="https://contadorflipante.netlify.app/">
      <Direccion/>
    </a>
    <img src="/contadorimagen.webp" alt="" />
  </article>
</section>

<div class="github-mail">
  <a target="_blank" href="https://github.com/alex09dev"><svg xmlns="http://www.w3.org/2000/svg" width="40px" height="40px" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"></path></svg>alex09dev</a>

  <a target="_blank" href="mailto:alex365.dev@gmail.com"><svg xmlns="http://www.w3.org/2000/svg" viewBox="52 42 88 66" width="40px" height="40px">
    <path fill="#4285f4" d="M58 108h14V74L52 59v43c0 3.32 2.69 6 6 6"/>
    <path fill="#34a853" d="M120 108h14c3.32 0 6-2.69 6-6V59l-20 15"/>
    <path fill="#fbbc04" d="M120 48v26l20-15v-8c0-7.42-8.47-11.65-14.4-7.2"/>
    <path fill="#ea4335" d="M72 74V48l24 18 24-18v26L96 92"/>
    <path fill="#c5221f" d="M52 51v8l20 15V48l-5.6-4.2c-5.94-4.45-14.4-.22-14.4 7.2"/>
    </svg>alex365.dev@gmail.com</a>
</div>

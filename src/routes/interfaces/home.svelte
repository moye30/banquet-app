<script>
  import Header from "../../components/header.svelte";
  import ButtonNewMenu from "../../components/buttonNewMenu.svelte";
</script>

<Header />

<div class="BtnNM">
  <ButtonNewMenu />
</div>

<style>
  .BtnNM {
    display: flex; /* Activa flexbox */
    justify-content: center; /* Centra horizontalmente */
    align-items: center; /* Centra verticalmente */
    height: 100vh; /* Ocupa toda la altura de la pantalla */
    width: 100vw; /* Opcional: ocupa toda la anchura de la pantalla */
    background-color: #f9f9f9; /* Color de fondo opcional */
  }
</style>

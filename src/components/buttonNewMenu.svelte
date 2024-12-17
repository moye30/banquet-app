<script>
  import { goto } from "$app/navigation"; // Importa la función de navegación

  export let text = "Nuevo menú"; // Texto del botón

  // Función para navegar a la nueva interfaz
  function navigateToCreateMenu() {
    goto("src/routes/interfaces/createMenu"); // Redirige a la ruta correcta de "createMenu"
  }
</script>

<button class="button" on:click={navigateToCreateMenu}>
  {text}
</button>

<style>
  .button {
    background-color: #004885;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 0.5rem 1rem;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .button:hover {
    background-color: #3d6887;
  }

  .button:active {
    background-color: #6174a1;
  }
</style>

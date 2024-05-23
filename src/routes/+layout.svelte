<script>
    import "../app.css";
    import ViewTransition from "$lib/components/ViewTransition.svelte"
  </script>
  
  <svelte:head>
    <title>Usuck</title>
  </svelte:head>

  <div class=app>
    <ViewTransition />
    <main class="min-h-screen ">
        <slot />
    </main>
</div>
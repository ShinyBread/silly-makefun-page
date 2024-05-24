<script>
    import "../app.css";
    import ViewTransition from "$lib/components/ViewTransition.svelte"
  </script>
  
  <svelte:head>
    <title>Usuck</title>
  </svelte:head>

  <div class=app>
    <ViewTransition />
    <main class="min-h-screen bg-background border-8">
        <slot />
    </main>
</div>
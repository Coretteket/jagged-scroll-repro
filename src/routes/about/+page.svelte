<div>
  <h1>Welcome to About</h1>
  <p>Visit <a href="/">/index</a> to navigate.</p>
</div>

{#each Array(25) as _}
  <p>
    Donec suscipit orci leo, et auctor turpis tincidunt non. Proin fermentum aliquam magna sed
    placerat. Ut congue neque vel ante bibendum, vitae eleifend ex lacinia. Integer consectetur
    pellentesque quam, eu lacinia odio. Donec dictum pharetra nunc. Cras suscipit in felis a
    aliquam. Curabitur nec vehicula ipsum, ut iaculis nisl. Pellentesque habitant morbi tristique
    senectus et netus et malesuada fames ac turpis egestas. Nunc finibus est quis massa pharetra, ut
    venenatis justo lacinia. Duis rutrum velit quis arcu lobortis, ac tincidunt odio dapibus.
    Vestibulum varius quam non lorem lobortis viverra. Ut rhoncus sapien at dictum convallis.
  </p>
{/each}

<style>
  div {
    position: fixed;
    background: white;
  }

  div,
  p {
    width: 25rem;
  }
</style>

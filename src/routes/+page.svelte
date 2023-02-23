<div>
  <h1>Welcome to SvelteKit</h1>
  <p>Visit <a href="/about">/about</a> to navigate.</p>
</div>

{#each Array(25) as _}
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In fringilla dui in leo finibus luctus.
    Nunc porttitor posuere nisi, suscipit maximus dolor dignissim a. Praesent tristique odio justo,
    feugiat molestie tortor eleifend id. In euismod ligula ipsum, in auctor leo vulputate sit amet.
    Aenean dui nulla, suscipit quis condimentum quis, tristique vitae erat. Donec sed eleifend nibh,
    id eleifend libero. Integer et vulputate libero.
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

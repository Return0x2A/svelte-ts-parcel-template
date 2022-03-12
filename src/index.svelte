  <script lang="ts">
      const title: string = "svelte typescript template with parcel";
  </script>
  
  <style lang="scss">
    :global(body) {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    h1 {
      font: normal 24pt Lato, "Helvetica Neue", Arial, Helvetica, sans-serif;
      color: dimgray;
      cursor: default;
    }
  </style>
  
  <h1>{title}</h1>
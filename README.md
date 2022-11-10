# component svelte mapa mundial svg

Install:
```
npm i mapa-mundi
```

Exemple bàsic:
```svelte
<script>
    import { World, getRandomCountry } from 'mapa-mundi'
  
    function handleClick(event) {
      console.log(event.detail.country);
      console.log(getRandomCountry());
    }
</script>

<World on:countryClicked={handleClick} />
```


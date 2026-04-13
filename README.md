# string-similarity

Algoritmos de similaridade de strings: Levenshtein, Jaro-Winkler e coeficiente de Dice (bigrams).

## Instalação

```bash
npm install string-similarity
```

## Uso

```ts
import { levenshtein, jaroWinkler, dice } from "string-similarity";

levenshtein("kitten", "sitting"); // 3
jaroWinkler("martha", "marhta");   // 0.96...
dice("night", "nacht");            // 0.25
```

## API

- `levenshtein(a: string, b: string): number`
- `jaroWinkler(a: string, b: string): number`
- `dice(a: string, b: string): number`

## Licença

MIT

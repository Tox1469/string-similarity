[![CI](https://img.shields.io/github/actions/workflow/status/Tox1469/string-similarity/ci.yml?style=flat-square&label=ci)](https://github.com/Tox1469/string-similarity/actions)
[![License](https://img.shields.io/github/license/Tox1469/string-similarity?style=flat-square)](LICENSE)
[![Release](https://img.shields.io/github/v/release/Tox1469/string-similarity?style=flat-square)](https://github.com/Tox1469/string-similarity/releases)
[![Stars](https://img.shields.io/github/stars/Tox1469/string-similarity?style=flat-square)](https://github.com/Tox1469/string-similarity/stargazers)

---

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
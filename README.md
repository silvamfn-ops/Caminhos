# Caminhos do Sul — Aplicação Web de Moto-Turismo & Guia Cultural

Aplicação PWA (Progressive Web App) desenhada para planeamento de viagens de mota no computador (com importação de `.pptx` e `.kmz`/`.kml`) e utilização no iPhone ou Android durante a condução e visitas a pé.

## Estrutura do Repositório

* `index.html` — Aplicação completa (Interface Mobile/Mota + Planeador Desktop + Importadores).
* `manifest.json` — Configuração PWA para instalação no ecrã inicial do iPhone (Safari -> Partilhar -> Adicionar ao ecrã principal) e Android.
* `sw.js` — Service Worker para funcionamento **100% offline** em zonas de serra sem cobertura de rede.

## Como alojar no GitHub Pages (Gratuito)

1. Cria um novo repositório no GitHub (ex: `caminhos-do-sul`).
2. Carrega os ficheiros `index.html`, `manifest.json`, `sw.js` e `README.md` para a raiz do repositório.
3. Vai a **Settings** -> **Pages**.
4. Em **Source**, seleciona `Deploy from a branch`, escolhe a branch `main` e a pasta `/ (root)` e clica em **Save**.
5. Dentro de 1 minuto, o teu link ficará ativo (ex: `https://teu-utilizador.github.io/caminhos-do-sul/`).
6. Abre esse link no Safari do iPhone e toca em **Partilhar -> Adicionar ao ecrã principal** para instalares como aplicação nativa.

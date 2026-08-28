# Surto Selvagem — Fichas da Terra do Viço

Ficha interativa de Daggerheart para o grupo (Dáhlia, Baine, Azura, Lucius, 0N-N1, Nyra). Um único arquivo `index.html`, sem servidor.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `surto-selvagem`) e envie o `index.html` para a raiz.
2. Em **Settings → Pages**, escolha *Deploy from a branch* → `main` / `root`.
3. A ficha fica em `https://SEU-USUARIO.github.io/surto-selvagem/`.

## Como funciona
- Tudo salva sozinho no navegador de quem abre (localStorage), **uma chave por ficha**: editar, restaurar ou remover uma aba não afeta as outras. Cada jogador usa o próprio celular.
- **Baixar esta ficha (JSON)** / **Baixar todas** = backup; **Carregar JSON** aceita uma ficha ou várias e só substitui as de mesmo nome/id, sem apagar o resto.
- **Importar ficha PDF** lê os PDFs no formato “Surto Selvagem · ficha de mesa” (nome, atributos, limiares, armas, ancestralidade, habilidades, cartas, experiências) e substitui a aba existente ou cria uma nova. Usa o pdf.js via CDN, então precisa de internet na primeira abertura.
- Trilhas de PV, Fadiga, Armadura, Esperança e **Corrupção do Surto**; contadores de recursos (Dados de Oração, Matança, Entidades, marcadores Vampiro…).
- Dados de Dualidade com atributo, experiência, vantagem e modificador.
- Repouso curto/longo com os movimentos do livro.
- Cartas de domínio: mão × reserva, editar, e escolher no baralho completo (9 domínios básicos + Sangue e Pavor do The Void, níveis 1–10).
- Arma principal, secundária e **de reserva**, e armaduras dos patamares 1–4 (incluindo as especiais do patamar 2) com limiares sugeridos.
- Para atualizar as fichas oficiais, edite a constante `BASE` dentro do `index.html` e mude `VER` para forçar a atualização.

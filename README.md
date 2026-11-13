# Cupons & Indicações — Meu Locus

Página única (`index.html`), sem dependências, pronta pra GitHub Pages.
Estética V4 do Meu Locus: fundo roxo + padrão de ícones médicos (`padrao-lilas.png`), Playfair Display + Inter.

Hub de **cupons, descontos e links de indicação** de coisas que a Fernanda usa e
recomenda de verdade. Inclui aviso de transparência ("links de indicação · sem
custo extra pra você") para proteger a confiança da audiência.

## Conteúdo atual
- **Embaixadora:** Meta Analysis Academy
- **Recursos que eu criei:** Guia de gravação (`guia-gravacao.html`: mesa com 3 câmeras e luz, checklist profissional, cola de marcações faladas pra editar com IA)
- **Material de estudo (V4, mesmo fundo da página de links):** BLS em mapas, revisão e flashcards de SAVC, gasometria, sódio, Porta da UPA (com aviso de que não é orientação médica), flashcards e fluxogramas de GO/obstetrícia, flashcards de MFC e guia do R1 de Patologia. Sem dados pessoais, sem nomes de professores e sem casos copiados de aula.
- **Saúde & bem-estar:** Queima Diária (link de indicação: `quei.ma/c/143ghfa9dj457`)
- Rodapé: redes do Meu Locus + volta pra página de links principal

## Como adicionar um cupom/desconto novo
Copie um bloco `<li>...</li>` e troque:
- `href` → o link
- `.t` → nome
- `.s` → descrição curta
- (opcional) adicione `<span class="coupon">CÓDIGO</span>` dentro de `.txt` para
  mostrar o código do cupom num "chip" laranja tracejado. Link de embaixadora: `class="embaixadora"` no `<a>` + `<span class="tag">EMBAIXADORA</span>`.

Crie novas seções duplicando um `<p class="section-label">...</p>` + `<ul class="links">`.

## 🚀 Publicar / atualizar
Repo público `indicacoes`. Cada `git push` na `main` redeploya o GitHub Pages.
URL: `https://damatech00.github.io/indicacoes/`

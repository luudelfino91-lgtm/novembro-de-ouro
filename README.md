# Novembro de Ouro — guia do gestor

Jogo de tabuleiro da campanha, alimentado por uma planilha do Google. Você só edita a planilha. O jogo se atualiza sozinho.

## O que tem nesta pasta
- `index.html` — o jogo (um arquivo só).
- `avatares/` — fotos dos operadores (uma por pessoa).
- `assets/` — logos (Control Desk e, se quiser, Funchal).

## Rotina diária (2 minutos)
1. Abra a planilha e vá na aba **Lancamentos**.
2. Para cada operador, adicione uma linha: data, nome (escolha na lista), pagamento, acordo, meta (1 ou 0), localização, atrasos, monitoria.
3. Pronto. Quem estiver com o jogo aberto vê a mudança em até 2 a 3 minutos. Para ver na hora, abra o jogo com `#gestor` no final do endereço e clique em **Atualizar agora**. Essa tela também lista avisos, como nome de operador digitado errado.

## Antes de abrir para valer
- Aba **Config**: troque `exemplo` de `sim` para `nao` e apague as linhas de exemplo em Lancamentos.
- Aba **Operadores**: ajuste nomes, equipes e apelidos. O que aparece no jogo é o Apelido.
- Aba **Casas** e **Premios**: confira qual prêmio fica em cada casa. A distribuição que veio é de exemplo.
- Compartilhe a planilha como **Qualquer pessoa com o link: Leitor**. Sem isso o jogo não consegue ler. Quem tiver o link consegue ver nomes e resultados.

## Fotos dos operadores
1. Salve a foto na pasta `avatares/` (JPG ou PNG, rosto centralizado funciona melhor).
2. Na aba **Operadores**, coluna **Foto**, escreva o nome do arquivo (ex.: `mariana-palermo.jpg`).
3. Sem foto, o jogo mostra as iniciais na cor do operador. Dá para ter só alguns com foto.

## Logo do Control Desk
Salve o arquivo como `assets/logo-control-desk.png` (fundo transparente ou branco, altura de uns 120 px). Enquanto não existir, o topo mostra o texto "Control Desk". A logo da Funchal é opcional: `assets/logo-funchal.png`.

## Regra do prêmio e outros ajustes (aba Config)
- `modo`: `pouso` (prêmio só ao parar na casa no fim do dia) ou `passagem` (também ao passar por ela).
- `casasPorPonto`: quantas casas cada ponto avança.
- `dias`: duração da campanha. Os dias que faltam entram no simulador de metas de cada operador.

## Como publicar o jogo (GitHub Pages)
1. Crie um repositório e envie `index.html`, `avatares/` e `assets/`.
2. Em Settings, Pages, escolha a branch principal e a pasta raiz.
3. O endereço gerado é o link do jogo para os operadores. Para trocar uma foto ou logo, basta enviar o arquivo novo.

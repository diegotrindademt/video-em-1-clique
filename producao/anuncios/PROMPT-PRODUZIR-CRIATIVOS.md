# Pedido para produzir os 13 criativos (colar no Claude Code, na pasta C:\CURSO-EDICAO-IA)

Copie tudo abaixo da linha.

---

Leia `producao/anuncios/ROTEIROS-13-CRIATIVOS.md` inteiro, depois `CLAUDE.md`, `04-IDENTIDADE-DO-CURSO.md` e `kit/AGENTS.md`. Os roteiros já foram aprovados: não reescreva fala nem gancho. Produza os 13 vídeos seguindo o "Padrão técnico" do arquivo.

1. **Um modelo só para os 13:** crie `kit/studio/src/criativos/` com uma composição base (legenda palavra por palavra na área segura, cartões da identidade, cartão final, selo "Dramatização", rodapé de aviso, zoom em cada corte) e uma composição por criativo (`Criativo01` a `Criativo13`) que só troca dados: fala, cenas e textos. Nada de 3D do zero.
2. **Voz:** para cada criativo, gere a fala com `kit/tools/gerar-voz.py` (voz Orus). Rode `tirar-respiracoes.py` e corte toda pausa acima de 120 ms. Meta de 175 a 190 palavras por minuto. Transcreva palavra por palavra com o whisper para tirar os tempos.
3. **Mídias:** busque com `node kit/tools/buscar-imagens.mjs` vídeos verticais do Pexels e do Pixabay para cada cena. Antes de editar, me mostre uma folha de miniaturas por criativo. Nos criativos 11, 12 e 13, os personagens precisam parecer as mesmas pessoas em todas as cenas. Anote tudo em `CREDITOS.md`.
4. **Música e efeitos:** uma trilha por estilo (no máximo 4 trilhas para os 13, para economizar tempo de geração), 11 a 13 dB abaixo da voz, e efeitos no ponto certo. Áudio final em -14 LUFS.
5. **Ordem:** primeiro o **Criativo 13**, como piloto. Me mostre a folha de quadros-chave e a prévia em baixa. Só depois de eu aprovar o padrão, faça os outros 12 em sequência, sem me perguntar a cada um.
6. **Render:** `renders/criativos/C01-pizzaria-do-lado.mp4` e assim por diante, em 1080x1920. Confira com ffprobe (resolução, 30 fps, duração) e meça a loudness. Copie os 13 MP4 para `C:\Users\diego\Downloads\CRIATIVOS META - PARA VER\`.
7. **Pendências (não invente):** no Criativo 8, espere eu mandar a minha história e a gravação da minha voz, e use a minha voz no lugar da Orus. No Criativo 13, a frase "É a última vez que você vê esse preço" está confirmada. Não cite o número de aulas em nenhum criativo.

Regras: não use a vitrine v1 a v6, a mini VSL, os pôsteres nem as imagens da página de vendas. Não fale em garantia. Não publique nada. Não suba campanha no Meta antes de eu aprovar os vídeos.

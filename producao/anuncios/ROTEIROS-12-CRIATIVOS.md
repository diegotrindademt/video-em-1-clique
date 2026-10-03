# 12 criativos Meta: roteiros finais para produção

Curso Vídeo em 1 Clique · R$ 97 · checkout Cakto · página https://curso.videoviralai.com.br
Aprovado pelo Diego em 03/10/2026. O antigo criativo do fundador foi cancelado: o Diego não aparece em nenhum vídeo. Mudanças dele: sem garantia de 7 dias, fala sem respiração e acelerada, e 3 criativos novos (10, 11 e 12). Linha geral: **atacar a dor, e o remédio é o curso.**

Skills de base: `coreyhaines31/marketingskills@ad-creative` (formatos Meta S a F, sistema de gancho em 3 partes, regra da ponte, especificação de vídeo vertical) e `ig-reel` (26 fórmulas de gancho e `hookscore_pt.py`; a nota de cada gancho falado está entre parênteses).

## Padrão técnico (vale para os 12)

- 1080x1920, 30 fps, MP4 H.264. Exportar também 4:5 (1080x1350) para o feed.
- Tudo que é texto fica na área segura: x de 180 a 900, y de 220 a 1420.
- Legenda palavra por palavra, branca com contorno preto, sem caixa atrás. Os títulos usam a identidade do curso (Bahnschrift 900, ciano `#3fe0ff`, dourado `#ffcc3d`, cartões de vidro fosco), sempre **por cima de filmagem real**. Nada de fundo liso.
- Voz: `gerar-voz.py`, voz Orus, `gemini-3.1-flash-tts-preview`. Depois `tirar-respiracoes.py` e **cortar toda pausa acima de 120 ms**. Meta de ritmo: 175 a 190 palavras por minuto. Se ficar lento, acelerar a voz em 8 a 10% sem mudar o tom.
- Cortes de 0,5 a 1,5 s, com um pequeno zoom em cada corte. Nenhum plano parado por mais de 3 s.
- Trilha 11 a 13 dB abaixo da voz, efeitos sonoros (whoosh, clique, caixa registradora, notificação) e áudio final em -14 LUFS.
- Mídias: Pexels e Pixabay (`buscar-imagens.mjs`), anotadas em `CREDITOS.md`. Proibido usar a vitrine v1 a v6, a mini VSL, os pôsteres e as imagens da página.
- Telas do Claude recriadas, com o selo "tela ilustrativa". Os pedidos mostrados são os reais do Caderno de Prompts.
- Em todo criativo, aparece por escrito "Precisa do plano Claude Pro".
- Proibido: garantia de 7 dias, "melhor curso", "dinheiro fácil", "código", "terminal" e "programação".
- Criativos com personagem (4, 10, 11 e 12) levam no canto o selo "Dramatização". A personagem nunca é apresentada como aluna real.

## Tabela de diversidade

| # | Nome | Formato | Gancho | Ângulo | Avatar | Visual |
|---|---|---|---|---|---|---|
| 1 | Pizzaria do lado | Demonstração em tela dividida | Comparação com o vizinho | Dor | Negócio local | Mesa vista de cima e tela limpa |
| 2 | O atalho | VSL curta | Ninguém te conta (#3) | Curiosidade | Renda extra | Documental, azul-esverdeado e laranja |
| 3 | Mito do PC gamer | Mito x verdade | Permissão (#20) | Objeção (computador) | Canal sem rosto | Duotone de serigrafia |
| 4 | Conversa do salão | Conversa no celular | Amiga pergunta | Curiosidade | Negócio local | Celular sobre o salão |
| 5 | A hora perdida | Antes e depois | Contraste (#13) | Comparação | Social media | Tela dividida fria e quente |
| 6 | Pedido da padaria | Tutorial relâmpago | Copia isso (#9) | Dor | Negócio local | Comida em close, luz quente |
| 7 | Roteiros parados | Motion de colagem | Se você... (#10) | Dor | Canal sem rosto | Colagem com retícula |
| 8 | Quinta, 23h | Reação com corte seco | Situação específica | Dor | Social media | Noite no celular e tela clara |
| 9 | A conta inteira | Objeção de preço | A conta (#6) | Objeção (custo) | Canal sem rosto | Tipografia suíça sobre mesa |
| 10 | Pai e filho | História dramatizada | Confissão do pai | Desejo (renda para o filho) | Pai de adolescente | Cinema realista, luz de casa |
| 11 | Açaí parado | História dramatizada, antes e depois | Confissão da dona | Dor | Negócio local (açaí) | Cores tropicais, balcão real |
| 12 | Vídeo flopado | Comparação lado a lado | Pergunta direta + contraste | Dor (engajamento) | Influenciador | Tela dividida de Reels e contador |

---

## 1. Pizzaria do lado
**Gancho (0 a 3 s).** Imagem: em cima, uma pizzaria concorrente com o Reels rodando; embaixo, a sua com uma foto parada. Fala: "A pizzaria do lado posta Reels todo dia e a sua só posta foto." (58). Tela: "ELA POSTA VÍDEO. VOCÊ POSTA FOTO."

**Fala completa:**
> A pizzaria do lado posta Reels todo dia e a sua só posta foto. Editar vídeo come a sua noite inteira, e no fim ainda fica com cara de amador. Agora olha. Você escreve: crie um vídeo vertical de 30 segundos da minha pizzaria, com voz, legenda e música. E o Claude monta tudo. Quer mudar? Aos 8 segundos, deixe o preço maior. Pronto. No Vídeo em 1 Clique você aprende isso do zero, mesmo sem nunca ter editado. Precisa do Claude Pro. Toque em Saiba mais.

**Cenas:** 0 a 3 s, o gancho · 3 a 7 s, a pessoa cansada no notebook às 23h · 7 a 15 s, tela dividida com o pedido sendo digitado e o vídeo se montando · 15 a 19 s, o ajuste do preço · 19 a 24 s, o cartão final.

- **Texto principal:** "Um pedido em português e o Claude monta o Reels da sua pizzaria com voz, legenda e música. Usa o Claude Pro."
- **Título:** "Reels da pizzaria a partir de um pedido"
- **Descrição:** "Para quem nunca editou"

## 2. O atalho (VSL curta)
**Gancho.** Imagem: macro de um polegar rolando Reels de lojas. Fala: "Ninguém te conta que esses Reels de 30 segundos saem de um pedido escrito." (79). Tela: "VOZ, LEGENDA E MÚSICA".

**Fala completa:**
> Ninguém te conta que esses Reels de 30 segundos saem de um pedido escrito. Você passa horas no celular tentando editar, a legenda sai fora do tempo, o vídeo fica travado, e você desiste. Quem conhece o atalho só escreve um pedido. O atalho é o Claude, uma inteligência artificial. Você descreve o vídeo em português e ele monta roteiro, voz, legenda palavra por palavra, música e efeitos. Quer ajustar? Mais uma frase. Roda no notebook comum, Windows ou Mac. O Vídeo em 1 Clique mostra o passo a passo, do zero ao vídeo pronto, por 97 reais. Precisa do Claude Pro. Toque em Saiba mais e veja as aulas.

**Cenas:** problema (frustração no app de edição, cortes rápidos) · mecanismo (pedido virando vídeo, tipografia suíça) · prova (vídeo pronto rodando no notebook) · oferta (cartão R$ 97).

- **Texto principal:** "Esses Reels com legenda palavra por palavra saem de um pedido no Claude. Aulas curtas, do zero ao vídeo pronto."
- **Título:** "Aprenda a pedir o vídeo certo para a IA"
- **Descrição:** "Pagamento único de R$ 97"

## 3. Mito do PC gamer
**Gancho.** Imagem: um carimbo "MITO" batendo sobre um PC gamer cheio de luzes. Fala: "Você não precisa de placa de vídeo. Bastam 10 GB livres no notebook." (82). Tela: "PC GAMER PARA CANAL DARK?"

**Fala completa:**
> Você não precisa de placa de vídeo. Bastam 10 GB livres no notebook. Tem gente adiando o canal sem rosto há meses achando que precisa de um computador caro. Mito. Quem pensa o vídeo é o Claude, uma inteligência artificial. O seu notebook só monta o arquivo. Windows 10, 11 ou Mac. Outro mito: que você precisa saber editar. O Vídeo em 1 Clique foi feito para quem nunca editou nada. Você escreve o que quer e recebe o vídeo com voz, legenda e música. Precisa do Claude Pro. Toque em Saiba mais.

- **Texto principal:** "Notebook comum, Windows ou Mac, sem placa de vídeo. Você precisa de 10 GB livres e do plano Claude Pro."
- **Título:** "Canal sem rosto no notebook que você tem"
- **Descrição:** "Windows 10, 11 ou Mac"

## 4. Conversa do salão (sem locução, só as bolhas e os sons)
**Gancho.** Imagem: um celular na mão sobre o salão real desfocado. A primeira bolha traz o print do vídeo do salão e a mensagem "Ju, o vídeo do salão ficou lindo. Custou quanto?" (52).

**Bolhas** (0,3 a 0,8 s entre elas, com som de envio e de recebimento):
1. [print do vídeo] Ju, o vídeo do salão ficou lindo. Custou quanto?
2. nada kkk fui eu que fiz
3. vc?? vc nem edita
4. eu escrevi o que eu queria e a IA montou
5. voz, legenda, música, tudo
6. eu passava a noite no app e ficava feio
7. qual IA?
8. o Claude. aprendi no Vídeo em 1 Clique
9. me manda o link
10. [link] precisa do Claude Pro, tá?

Depois, o cartão final de 3 s.

- **Texto principal:** "Vídeo do salão com voz, legenda e música, a partir de um pedido escrito do seu jeito. Requer Claude Pro."
- **Título:** "Vídeo do seu salão com um pedido escrito"
- **Descrição:** "Pagamento único de R$ 97"

## 5. A hora perdida (antes e depois)
**Gancho.** Imagem: em cima, sem cor, uma linha do tempo lotada e um relógio acelerado; embaixo, colorido, um campo de texto. Fala: "Você ainda gasta 1 hora no app para editar 30 segundos?" (84). Tela: "1 HORA × 1 PEDIDO".

**Fala completa:**
> Você ainda gasta 1 hora no app para editar 30 segundos? Cortar, legendar palavra por palavra, caçar música, acertar o volume, e no fim o vídeo ainda fica com cara de amador. Do outro lado, você escreve o vídeo que quer e o Claude monta tudo isso. Quer mudar? Aos 8 segundos, deixe o preço maior. Ele mexe só ali. Essa hora volta para você. Aprenda no Vídeo em 1 Clique. Precisa do Claude Pro. Toque em Saiba mais.

- **Texto principal:** "Mudar o vídeo é escrever "aos 8 segundos, deixe o preço maior". O Claude mexe só ali. Requer Claude Pro."
- **Título:** "Ajuste o vídeo escrevendo uma frase"
- **Descrição:** "Uma frase muda o vídeo"

## 6. Pedido da padaria (tutorial relâmpago)
**Gancho.** Imagem: pães saindo do forno, vistos de cima, com o pedido sendo datilografado por cima. Fala: "Copia esse pedido de 3 linhas e troca só o nome da sua padaria." (72).

**Fala completa:**
> Copia esse pedido de 3 linhas e troca só o nome da sua padaria. Se você só posta foto da vitrine porque vídeo dá trabalho, faz assim. Linha um: o que é o vídeo. Linha dois: o tom e a música. Linha três: o que aparece no final, o preço e o endereço. Manda para o Claude e o vídeo volta pronto, com voz e legenda. Esse e todos os pedidos das aulas estão no Caderno de Prompts do Vídeo em 1 Clique. Precisa do Claude Pro. Toque em Saiba mais.

**Pedido na tela** (testar antes de publicar):
1. Vídeo vertical de 20 segundos da Padaria [Nome], com pão saindo do forno.
2. Tom acolhedor, voz grave e música leve.
3. No fim: pão francês R$ [X] o quilo e o endereço [Rua].

- **Texto principal:** "Troque o nome da padaria no pedido e receba o vídeo. Os pedidos das aulas vêm no Caderno de Prompts."
- **Título:** "Copie o pedido e receba o vídeo"
- **Descrição:** "Caderno de Prompts incluso"

## 7. Roteiros parados (motion de colagem)
**Gancho.** Imagem: uma pilha de roteiros (foto real em retícula) crescendo, com a etiqueta rasgada "10 ROTEIROS PARADOS". Fala: "Se seu canal sem rosto tem 10 roteiros parados, assiste isso." (80).

**Fala completa:**
> Se seu canal sem rosto tem 10 roteiros parados, assiste isso. O roteiro sai. A voz, a IA grava. O que trava é montar: imagem, legenda, música e corte, um vídeo por vez. E o canal fica parado. Com o Vídeo em 1 Clique, você cola o roteiro num pedido e o Claude devolve o vídeo com voz, legenda palavra por palavra e imagens de bancos gratuitos, no notebook que você já tem. Precisa do Claude Pro. Toque em Saiba mais e destrava esses 10 roteiros.

- **Texto principal:** "Seu roteiro vira vídeo com voz, legenda e imagens a partir de um pedido. Para canal sem rosto. Usa Claude Pro."
- **Título:** "Roteiro parado vira vídeo pronto"
- **Descrição:** "Aulas curtas e diretas"

## 8. Quinta, 23h (reação com corte seco)
**Gancho.** Imagem: uma pessoa no sofá à noite, com a luz do celular no rosto (Pexels). Fala: "São 23h, você deve 4 Reels ao cliente e ainda não editou nenhum." (88). Tela: "entrega na sexta".

**Fala completa:**
> São 23h, você deve 4 Reels ao cliente e ainda não editou nenhum. Cada vídeo leva uma hora, e a entrega é amanhã. Agora olha. Um pedido por Reels. O Claude monta voz, legenda e música. O cliente quer trocar o texto do final? Mais uma frase e pronto. O Vídeo em 1 Clique tem uma aula só de como revisar e entregar vídeos para clientes. Precisa do Claude Pro. Toque em Saiba mais e vai dormir.

**Cenas:** depois de 3 s, corte seco para a tela com 4 pedidos e 4 vídeos aparecendo em grade.

- **Texto principal:** "Você descreve cada Reels do cliente e o Claude monta. Tem aula de como revisar e entregar. Usa Claude Pro."
- **Título:** "Entregue os Reels dos seus clientes"
- **Descrição:** "Inclui aula de entrega"

## 9. A conta inteira
**Gancho.** Imagem: mãos colocando um recibo numa mesa de madeira, com os números aparecendo. Fala: "Seu vídeo com IA custa R$ 97 uma vez, mais o Claude Pro." (84).

**Fala completa:**
> Seu vídeo com IA custa R$ 97 uma vez, mais o Claude Pro. O curso Vídeo em 1 Clique: 97 reais, pagamento único. O Claude Pro: a partir de 92 reais por mês no plano anual, pago direto para a Anthropic. É ele que monta os vídeos. Imagens, músicas e voz: o curso mostra opções grátis. Computador: o notebook que você já tem. Essa é a conta inteira, sem editor cobrando todo mês. Toque em Saiba mais.

- **Texto principal:** "O curso custa R$ 97 uma vez. O Claude Pro sai a partir de R$ 92 por mês no anual. O resto tem opção grátis."
- **Título:** "Quanto custa fazer vídeo com IA"
- **Descrição:** "Tudo aberto antes de comprar"

---

## 10. Pai e filho (dramatização) · NOVO
**Personagens realistas:** um pai de uns 45 anos, de camisa simples, e um filho de 15. Primeira opção: filmagem do Pexels com o mesmo casal de atores em várias cenas. Se não houver, imagens geradas realistas com o mesmo rosto em todas as cenas, animadas com movimento sutil.

**Gancho.** Imagem: o pai na mesa da cozinha à noite, olhando o filho deitado no sofá com o celular. Fala (voz do pai): "Meu filho de 15 anos passava o dia inteiro no celular sem fazer nada." (72). Tela: "15 ANOS. O DIA TODO NO CELULAR."

**Fala completa:**
> Meu filho de 15 anos passava o dia inteiro no celular sem fazer nada. Eu queria que ele aprendesse alguma coisa que desse dinheiro de verdade. Aí eu achei um curso que ensina a fazer vídeo profissional só pedindo para a inteligência artificial. Ele fez as aulas num fim de semana. Começou com o vídeo da lanchonete da esquina. Depois veio a barbearia, a loja de roupa. Os pedidos chegam pelo direct do Instagram. Ele cobra 50 reais por vídeo e faz uns 5 por dia. Faz a conta: 250 reais por dia. Em 22 dias, 5.500 reais no mês. O celular que era passatempo virou trabalho. Vídeo em 1 Clique. Precisa do Claude Pro. Toque em Saiba mais.

**Cenas:**
- 0 a 3 s: o gancho.
- 3 a 8 s: o rosto preocupado do pai.
- 8 a 13 s: o pai no notebook achando o curso (tela ilustrativa).
- 13 a 22 s: o filho no notebook, com o vídeo da lanchonete se montando.
- 22 a 28 s: o direct do Instagram "quanto é o vídeo?" e a resposta "R$ 50".
- 28 a 36 s: a conta animada em dourado: R$ 50 × 5 = R$ 250 por dia → × 22 dias = **R$ 5.500/mês**, com som de caixa registradora.
- 36 a 42 s: pai e filho rindo juntos na mesa.
- 42 a 46 s: o cartão final.

**Rodapé fixo durante a conta:** "Dramatização. Exemplo de conta, não é promessa de ganho. O resultado depende de cada pessoa."

- **Texto principal:** "Ele aprendeu a fazer vídeo pedindo para a IA e começou a atender os comércios do bairro. Precisa do Claude Pro."
- **Título:** "Uma profissão para o seu filho"
- **Descrição:** "Dramatização ilustrativa"

**Versão B, de segurança** (mesmo vídeo, troca só de 28 a 36 s): sem a conta mensal. Fica "Primeiro cliente: a lanchonete. Depois, a barbearia. Ele mesmo define o preço." Subir a B se o Meta reprovar a A.

## 11. Açaí parado (dramatização) · NOVO
**Personagem realista:** uma dona de açaí de uns 35 anos, com avental, num balcão real e cores tropicais.

**Gancho.** Imagem: o balcão vazio, os potes cheios e ela olhando o celular, que não toca. Fala (voz dela): "Meu açaí passava 3 horas sem vender um copo e o celular nem tocava." (76). Tela: "3 HORAS SEM VENDER".

**Fala completa:**
> Meu açaí passava 3 horas sem vender um copo e o celular nem tocava. Eu postava foto do copo e ninguém via. Tentei editar vídeo no celular e ficou horrível. Aí eu descobri o Vídeo em 1 Clique. Eu escrevo o vídeo que eu quero e a inteligência artificial monta, com voz, legenda e música. Comecei a postar vídeo todo dia. O Instagram começou a encher de seguidor, o direct não parava, e os pedidos começaram a sair um atrás do outro. Hoje o motoboy não para. Precisa do Claude Pro. Toque em Saiba mais.

**Cenas:**
- 0 a 3 s: o gancho.
- 3 a 9 s: o post de foto com "0 curtidas" e a tentativa frustrada de editar.
- 9 a 15 s: ela digitando o pedido (tela ilustrativa).
- 15 a 22 s: o Reels do açaí pronto rodando, colorido e com legenda.
- 22 a 32 s: uma montagem acelerada com o contador de seguidores subindo, notificações em cascata, comandas saindo da impressora, açaí sendo montado e o motoboy saindo, em cortes de 0,5 s.
- 32 a 38 s: ela sorrindo atrás do balcão cheio.
- 38 a 42 s: o cartão final.

**Rodapé:** "Dramatização. Resultados variam."

- **Texto principal:** "Seu açaí posta foto e ninguém vê? Aprenda a fazer vídeo com voz, legenda e música pedindo para a IA. Usa Claude Pro."
- **Título:** "Vídeo que faz o açaí aparecer"
- **Descrição:** "Para negócio local"

## 12. Vídeo flopado (influenciador) · NOVO
**Personagem realista:** um criador de uns 25 anos, gravando com o celular no quarto e luz de ring light.

**Gancho.** Imagem: tela dividida. À esquerda, o vídeo cru dele, sem corte, com o contador parado em "200 visualizações". À direita, o mesmo vídeo editado, com legenda karaokê, zoom nos cortes e efeitos. Fala: "Seu vídeo flopou de novo com 200 visualizações? Olha o mesmo vídeo editado." (52).

**Fala completa:**
> Seu vídeo flopou de novo com 200 visualizações? Olha o mesmo vídeo editado. Mesma ideia, mesma pessoa. De um lado, sem edição. Do outro, legenda palavra por palavra, cortes, zoom, música e efeito, feito com um pedido para o Claude. Não é que o seu conteúdo seja ruim. A sua edição que não é profissional. Você está tendo a chance de editar como profissional por 97 reais. É a última vez que você vê esse preço. Vídeo em 1 Clique. Precisa do Claude Pro. Toque em Saiba mais.

**Cenas:**
- 0 a 6 s: a tela dividida.
- 6 a 18 s: o lado editado toma a tela, com o contador de visualizações subindo, corações, notificações de seguidores e comentários.
- 18 a 26 s: frase na tela, em duas linhas, a segunda em dourado: "NÃO É QUE SEU CONTEÚDO SEJA RUIM. / SUA EDIÇÃO QUE NÃO É PROFISSIONAL."
- 26 a 34 s: "R$ 97" em dourado e "ÚLTIMA VEZ NESSE PREÇO".
- 34 a 38 s: o cartão final.

**Rodapé:** "Dramatização. Números ilustrativos."

**Confirmado pelo Diego em 03/10/2026:** R$ 97 é o preço de entrada enquanto a conta de anúncios esquenta, e ele vai subir. A frase "É a última vez que você vê esse preço" está liberada. Quando o preço subir, pausar este criativo.

- **Texto principal:** "Seu conteúdo é bom, a edição que segura. Aprenda a editar como profissional pedindo para a IA, por R$ 97. Usa Claude Pro."
- **Título:** "Edite como profissional por R$ 97"
- **Descrição:** "Preço de entrada"

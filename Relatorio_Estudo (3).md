# Relatório do Teste de Usabilidade — SkillSwap

**Disciplina:** Interação Humano-Computador
**Professora:** Joana Gabriela R. de Souza
**Integrantes:** [DAVI, JOSUE E LUIZ FERNANDO BATISTA]
**Data do teste:** 18 de maio de 2026

---

## Sobre o protótipo

A gente desenvolveu um protótipo em papel pra uma plataforma chamada SkillSwap, que é basicamente uma rede social pra trocar habilidades sem envolver dinheiro. A ideia é que cada pessoa ensina alguma coisa que sabe — pode ser idioma, instrumento, programação, culinária, o que for e em troca aprende outra coisa com alguém. Pra equilibrar essas trocas, o sistema usa créditos colaborativos, que funcionam meio como uma moeda interna baseada em tempo.

O protótipo cobre o que a gente entende ser o fluxo principal de uso: o usuário entra na home e vê um feed de publicações de outras pessoas oferecendo habilidades, pode buscar por uma habilidade específica ou filtrar por tags, encontra alguém interessante e se conecta. Depois de conectado, dá pra abrir o chat e conversar, e a partir daí marcar uma sessão na tela de agendamento, escolhendo dia, horário, duração e se vai ser online ou presencial. O usuário também pode criar a própria publicação a qualquer momento, oferecendo o que sabe.

No total foram desenhadas as seguintes telas em papel: homepage com feed, tela de conexões, chat (lista e conversa), agendamento de sessões, modal de criar publicação e perfil de usuário.

## Tarefas que a gente testou

Pra avaliar se o protótipo funcionava na prática, montamos quatro tarefas que cobrem as ações mais importantes da plataforma. A primeira foi criar uma publicação — a gente pediu pro usuário se imaginar oferecendo aulas de violão em troca de aulas de inglês. A segunda foi encontrar alguém que ensina programação e se conectar com a pessoa, pra testar o caminho de descoberta e a função de conexão. A terceira foi mandar uma mensagem pra esse contato, separando o "conectar" do "conversar" pra ver se essa distinção fazia sentido. E a quarta foi agendar uma sessão online, pra ver se o formulário de agendamento era claro.

A gente também fez quatro perguntas no final, sobre a experiência geral, se a proposta da plataforma ficou clara, qual foi a parte mais confusa e se o usuário usaria o app na vida real.

## Como foi o teste

O usuário que participou foi a Beatriz, aluna do quarto período de Engenharia de Produção (PUC MINAS), de outra turma da faculdade. Antes de começar, a gente explicou que não era ela que tava sendo testada, era o protótipo, e pediu pra ela pensar em voz alta enquanto usava. Um integrante do grupo ficou como moderador, outro como "computador" (trocando as folhas do protótipo conforme ela tocava nas telas) e o terceiro ficou observando e anotando tudo. O teste não foi gravado, pois ela não queria, mas durou aproximadamente uns 15 minutos.

Vale comentar que a Beatriz nunca tinha usado uma plataforma de troca de habilidades, então a primeira impressão dela foi bem útil pra ver o que confunde alguém que chega sem contexto nenhum.

## O que rolou em cada tarefa

**Tarefa 1 — Criar publicação.** A Beatriz demorou mais ou menos uns 30 segundos só procurando onde clicar pra criar a publicação. Chegou a tocar no ícone de busca primeiro, achando que era ali, depois passou o dedo no menu inferior antes de achar o botão. Quando o modal abriu, ela preencheu título e descrição sem problema, mas travou no campo de habilidade e fez uma pergunta importante, falou literalmente "espera, mas eu coloco a que eu ensino ou a que eu quero aprender?" (No caso era o que você vai ensinar!!). Acabou colocando violão (a que ela ensina) e foi em frente. Pulou o upload de vídeo. Quando voltou pra home depois de publicar, ela ficou olhando o feed, Concluiu, mas com hesitação.

**Tarefa 2 — Encontrar e conectar.** Essa foi a mais tranquila de todas. Ela foi direto no botão dos personagens no topo, digitou, olhou as tags e clicou na primeira que combinava. Apareceram os perfis, ela escolheu um, leu rapidinho e clicou em conectar. Levou menos de dois minutos. Mas no fim, depois de conectar, ela ficou olhando pra tela e falou "tá, e agora?". A gente percebeu que ela esperava alguma coisa acontecer ali, tipo um chat abrir.

**Tarefa 3 — Enviar mensagem.** Depois da tarefa 2, ela já tava meio na pista de que precisava ir em outro lugar e voltou pro home. Olhou o menu, achou o ícone de chat e foi. Comentou enquanto fazia isso: "imaginei que ia abrir direto quando conectei, ou ter pelo menos a opção". Achou a conversa com a Maria fácil, escreveu "oi maria, tudo bem? vi que você ensina programação, tenho interesse em trocar conhecimento" e mandou. Tranquilo.

**Tarefa 4 — Agendar sessão.** Ela achou a tela de agendamento rapidão, pelo menu. Olhou as próximas sessões e as aulas disponíveis, e ela acabou clicando em "agendar". No formulário, ela entrou colocou as informações e foi bem rapido até. Preencheu o resto sem problema e confirmou.

## Principais problemas que apareceram

Olhando pra tudo que rolou, três coisas se destacaram bastante.

A mais clara foi a ambiguidade do campo "habilidade". Ele aparece tanto na criação de publicação quanto no agendamento, e em nenhum dos dois lugares fica explícito se a pessoa tá falando da habilidade que oferece ou da que procura. A Beatriz travou nesse campo duas vezes diferentes, e numa delas chegou a inverter o critério em relação à primeira vez ou seja, o mesmo campo, com o mesmo nome, ela interpretou de jeitos opostos em momentos diferentes.

A segunda coisa foi a separação entre conectar e conversar. O fluxo atual exige que o usuário conecte numa tela e, depois, vá manualmente até o chat pra falar com a pessoa. Mas a expectativa natural dela e provavelmente da maioria das pessoas que usam apps de mensagem hoje era que conectar já abrisse a conversa. Ela falou isso espontaneamente duas vezes, o que indica que não foi um erro pontual, foi um modelo mental diferente do que o protótipo entrega.

A terceira foi mais sutil: o sistema de créditos colaborativos, que é uma das ideias centrais da plataforma, basicamente não apareceu na experiência dela. Em nenhuma tela ela viu quantos créditos tinha (mas estava presente na HOME PAGE, no TOPO), quanto custaria a sessão que tava marcando. Quando a gente perguntou no final se ela entendeu o sistema, ela falou que "lembrava de ter ouvido falar quando vocês explicaram no começo, mas não vi isso no app". Mas um ponto é verdade, esquecemos de colocar o quanto custava para agendar com cada pessoa (OFICINA).

## O que dá pra melhorar

A correção mais imediata é desdobrar o campo único de "habilidade" em dois campos separados, com rótulos bem explícitos: "habilidade que você oferece" e "habilidade que você procura". Isso resolveria a confusão tanto na publicação quanto no agendamento, e ainda deixaria a base de dados mais rica pra fazer matches automáticos no futuro. É a mudança que mais retorno daria com o menor esforço.

Sobre conectar e conversar, a sugestão seria unir as duas ações ou pelo menos colocar um botão grande de "enviar mensagem" logo depois que a conexão é confirmada. Outra opção, mais radical, seria eliminar o passo de "conectar" como uma coisa separada e deixar que qualquer um inicie uma conversa direto pelo perfil. O custo disso é que o conceito de "conexão" deixa de existir, mas talvez ele não tenha tanto valor assim, a Beatriz não comentou nada sobre achar útil ter essa lista separada.

Pra resolver o problema dos creditos, acho que deixar mais visiviel, mesmo estando no topo do home, com uma cor diferente. Quando o usuário entrar pela primeira vez, ter uma explicação rápida (uns três cards, no máximo) sobre como funcionam. E na hora de agendar uma sessão, deixar claro quanto vai custar e quanto a pessoa tem.

## O que o usuário achou no geral

Quando perguntamos a impressão geral, a nota foi 4 de 5. Justificou dizendo que a ideia é "muito boa, sinceramente faria sentido pra mim", mas que em algumas horas ela ficou perdida e isso atrapalhou a experiência. Sobre a proposta da plataforma, ela falou que a parte de trocar habilidades ficou clara, mas a parte dos créditos não, e não viu isso aparecer em lugar nenhum durante o uso. A parte mais confusa, segundo ela, foi o campo de habilidade (ela citou diretamente, sem a gente puxar) e a separação entre conectar e mandar mensagem. Quando perguntamos se usaria na vida real, ela disse que sim, que tem vontade de aprender violão e poderia ensinar inglês ou redação, mas que precisaria entender melhor como os créditos funcionam antes de usar pra valer.

## Pra fechar

No geral, a gente saiu do teste com a sensação de que o protótipo cumpre o fluxo principal, mas tem alguns pontos de fricção que precisariam ser resolvidos antes de uma versão de verdade ir pro ar. O teste foi útil principalmente pra mostrar coisas que pareciam óbvias pra gente porque a gente desenhou o app — tipo a diferença entre conectar e conversar, ou o fato de que "habilidade" pode significar duas coisas opostas dependendo da tela — mas que pra alguém vendo pela primeira vez não eram nada óbvias. Esse é o tipo de aprendizado que dificilmente apareceria sem botar o protótipo na mão de alguém de fora.

Pra uma próxima iteração, a gente repensaria os campos ambíguos, juntaria conectar e conversar e daria muito mais espaço pros créditos no fluxo, porque hoje eles são invisíveis. Também valeria testar com mais gente uma usuária só dá pistas fortes, mas não cobre todos os perfis que provavelmente vão usar a plataforma. Em especial, seria interessante testar com alguém com mais familiaridade em redes sociais e ver se as mesmas dúvidas aparecem.


**Anexos entregues:** vídeo da interação, roteiro do teste e este relatório.

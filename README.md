# English em Jogo

Quiz de Inglês do 6º ano. 46 questões em 11 tópicos.

**Prova (questões 21 a 25, Sistemática 3)**, 4 questões cada:

1. Present Continuous (forma negativa, ação no momento da fala)
2. Leitura de infográfico
3. Genitive case ('s e s')
4. Ideia principal do texto
5. Simple Present (rotina, hábito e verdade universal)

**Unit 8 · How are medicines produced?** (*Futures: project book, year 6*, Troika/Amais Educação, 2023, p. 52–61):

6. Video: What are medicines and drugs? (campanha antitabagismo, vício, drogas × remédios), 4 questões
7. Reading: What are medicines? (synthetic, natureza, fungos, bactérias, labs), 4 questões
8. Reading: Types of medicines (pills, drops, topical, antibiotics, over-the-counter), 4 questões
9. After you read + Culture (ideias principais, cuidado com OTC, medicina alternativa), 4 questões
10. Language: giving advice (should/shouldn't) × giving a suggestion (Why don't you...?), 5 questões
11. Listening: entrevista com médico sobre automedicação (verdadeiro/falso do livro), 5 questões. O áudio foi recriado com a voz do navegador; a transcrição aparece depois da resposta.

- Tela inicial em formato de **trilha de missões**: botão "Jogar agora" (1 questão por tópico), um mundo por bloco de conteúdo (Prova, Unit 8) e uma parada por tópico
- Estrelas por tópico (1 ⭐ a partir de 50%, 2 a partir de 75%, 3 com 100%), contadas quando o aluno faz a missão completa do tópico; aviso de "revisar" quando a última tentativa teve erro
- Sequência de dias seguidos (🔥) e total de estrelas no topo. Tudo fica salvo só no navegador do aluno (localStorage), sem servidor e sem dados pessoais
- Em "Mais opções": modos Rápido (1 por tópico), Estudo (15 variadas) ou Completo (todas as 46)
- Atalhos de conteúdo: Tudo, só Prova (21–25) ou só Unit 8
- Explicação em português a cada resposta
- Resultado por tópico e treino só dos tópicos com erro
- Botão para copiar o resultado e compartilhar

## Deploy

Site estático, sem build. Na Vercel: importe o repositório, Framework Preset **Other**, e faça o deploy. Cada push na `main` atualiza o site.

## Nova unidade

Acrescente os tópicos em `TOPICS`, o grupo em `GROUPS` e um item em `WORLDS` (nome, subtítulo, ícone e tópicos). A trilha ganha um novo mundo automaticamente.

## Editar questões

As questões ficam no array `Q` dentro de `index.html`. Em cada item, a primeira opção de `o` é a correta (as alternativas são embaralhadas na tela). Textos de apoio vão em `<span class="txt">...</span>` no início do enunciado. Questões de listening usam o campo `a` com as falas (`[["Doctor","..."],...]`).

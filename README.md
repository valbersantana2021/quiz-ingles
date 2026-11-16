# English em Jogo

Quiz de Inglês do 6º ano. 44 questões em 11 tópicos.

**Prova (questões 21 a 25, Sistemática 3)**, 4 questões cada:

1. Present Continuous (forma negativa, ação no momento da fala)
2. Leitura de infográfico
3. Genitive case ('s e s')
4. Ideia principal do texto
5. Simple Present (rotina, hábito e verdade universal)

**Unit 8 · What are medicines and drugs?** (temas de *Futures: project book, year 6*, Troika/Amais Educação, 2023; questões autorais), 4 questões cada:

6. What are medicines? (pharmacist, prescription, os sentidos de "drug")
7. Types of medicines (syrup, tablet, capsule, ointment, inhaler)
8. Understanding how medicines can affect the body (side effects, dose, expiry date)
9. Text · After you read (texto "Medicines: friends or enemies?")
10. Language (should / shouldn't, imperativo, once/twice/three times a day)
11. Listening (áudio gerado pela voz do navegador em inglês, com transcrição depois da resposta)

- Modos: Rápido (1 por tópico), Estudo (15 variadas) ou Completo (todas as 44)
- Atalhos de conteúdo: Tudo, só Prova (21–25) ou só Unit 8
- Explicação em português a cada resposta
- Resultado por tópico e treino só dos tópicos com erro
- Botão para copiar o resultado e compartilhar

## Deploy

Site estático, sem build. Na Vercel: importe o repositório, Framework Preset **Other**, e faça o deploy. Cada push na `main` atualiza o site.

## Editar questões

As questões ficam no array `Q` dentro de `index.html`. Em cada item, a primeira opção de `o` é a correta (as alternativas são embaralhadas na tela). Textos de apoio vão em `<span class="txt">...</span>` no início do enunciado. Questões de listening usam o campo `a` com as falas (`[["Doctor","..."],...]`).

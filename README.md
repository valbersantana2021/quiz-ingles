# English em Jogo

Quiz de Inglês do 6º ano, no modelo das questões 21 a 25 da prova (Sistemática 3). 5 tópicos, 4 questões cada:

1. Present Continuous (forma negativa, ação no momento da fala)
2. Leitura de infográfico
3. Genitive case ('s e s')
4. Ideia principal do texto
5. Simple Present (rotina, hábito e verdade universal)

- Modos: Rápido (1 por tópico), Estudo (10 variadas) ou Completo (todas as 20)
- Explicação em português a cada resposta
- Resultado por tópico e treino só dos tópicos com erro
- Botão para copiar o resultado e compartilhar

## Deploy

Site estático, sem build. Na Vercel: importe o repositório, Framework Preset **Other**, e faça o deploy. Cada push na `main` atualiza o site.

## Editar questões

As questões ficam no array `Q` dentro de `index.html`. Em cada item, a primeira opção de `o` é a correta (as alternativas são embaralhadas na tela). Textos de apoio vão em `<span class="txt">...</span>` no início do enunciado.

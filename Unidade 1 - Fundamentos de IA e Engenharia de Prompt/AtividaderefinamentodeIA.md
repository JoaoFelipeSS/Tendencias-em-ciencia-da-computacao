## Problema escolhido
 Comparação das linguagens javascript e typescript.
### Contexto
Será um aprendizado para iniciantes em programação.
### Problema
Sanar dúvida sobre as linguagens e suas diferenças.
### Objetivo
Um estudo simples e direto para começar os estudos referentes a essas linguagens.
___________________________________________________________________________________
## Prompt 1 - Versão inicial

### Prompt
Atue como professor de Ciência da Computação. Faça uma comparação entre Javascript e typescript para iniciantes em programação. Apresente: 1. Definições das linguagens; 2. como elas funcionam; 3. três exemplos de comparações; Utilize linguagem simples e limite a resposta a aproximadamente 500 palavras.

### Resultado
JavaScript x TypeScript

1. Definição das linguagens

JavaScript (JS) é uma linguagem de programação muito utilizada para criar páginas web interativas. Com ela, é possível fazer menus, formulários, animações, sistemas e aplicações completas. É uma linguagem dinamicamente tipada, ou seja, o tipo de uma variável pode mudar durante a execução do programa.

TypeScript (TS) é uma linguagem desenvolvida pela Microsoft que estende o JavaScript, adicionando recursos como tipagem estática. Todo código JavaScript válido pode ser utilizado em TypeScript, mas o TypeScript oferece ferramentas adicionais para ajudar o programador a encontrar erros antes da execução.

2. Como elas funcionam

O JavaScript pode ser executado diretamente pelos navegadores, como Chrome, Edge e Firefox. O navegador possui um mecanismo que interpreta e executa o código JavaScript. Ele também pode ser executado fora do navegador utilizando ambientes como o Node.js.

O TypeScript, por outro lado, não é executado diretamente pelo navegador. Primeiro, o código TypeScript precisa ser convertido (transpilado) para JavaScript. Depois disso, o JavaScript gerado pode ser executado normalmente pelo navegador ou por outro ambiente compatível.

A principal diferença é que o TypeScript permite declarar os tipos das variáveis, ajudando a identificar problemas durante o desenvolvimento.

3. Três exemplos de comparação

Exemplo 1 – Declaração de variável

JavaScript:

let idade = 20;
idade = "vinte";

No JavaScript, isso é permitido porque a variável pode mudar de tipo.

TypeScript:

let idade: number = 20;
idade = "vinte"; // Erro

No TypeScript, o programa identifica que "vinte" não é um número.

Exemplo 2 – Funções

JavaScript:

function soma(a, b) {
    return a + b;
}

TypeScript:

function soma(a: number, b: number): number {
    return a + b;
}

No TypeScript, fica explícito que os parâmetros devem ser números e que a função retorna um número.

Exemplo 3 – Facilidade para iniciantes

JavaScript possui uma sintaxe mais simples para começar e pode ser executado diretamente no navegador.

TypeScript possui alguns conceitos adicionais, como tipos, interfaces e generics, que podem exigir um pouco mais de aprendizado. Em compensação, esses recursos ajudam a organizar projetos maiores e encontrar erros antecipadamente.

Conclusão: para quem está começando, JavaScript pode ser mais simples para aprender os fundamentos da programação. Depois, aprender TypeScript pode ser uma boa evolução, principalmente para trabalhar em projetos maiores.

### Primeira impressão
- O que funcionou?
  A explicação ficou simples e clara, o direcionamento de estudo ficou interessante.
- O que faltou?
  por ter limitado a quantidade de palavras a explicação ficou muito resumida.
- O que ficou genérico?
  a explicação em si ficou generica pelo limite de palavras. 
- O que poderia ser melhor?
  a comparação ficou muita simples deixando a desejar.
___________________________________________________________________________________
## Prompt 2 - Primeiro refinamento

### Alterações realizadas
- Papel: professor de Ciência da Computação especializado nas linguagens javascript e typescript.
- Contexto: Os estudantes estão no primeiro semestre e ainda não tem nenhuma experiência com nenhuma linguagem.
- Objetivo: Fazer com que consigam compreender as diferenças, qualidades e deficiências.
- Público: Estudantes Universitarios iniciantes em programação (primeiro semestre).
- Formato: (Organize a resposta utilizando subtítulos e uma tabela para a comparação.)
- Restrições: máximo de 500 palavra e explicar qualquer termo técnico utilizado
- Critérios: Ao final da explicação, um estudante iniciante deverá conseguir explicar o conceito utilizando suas próprias palavras.

### Prompt
Atue como professor de Ciência da Computação
especializado nas linguagens javascript e typescript.

CONTEXTO:
Os estudantes estão no primeiro semestre e ainda
não tem nenhuma experiência com nenhuma linguagem.

OBJETIVO:
Fazer com que consigam compreender as diferenças, qualidades e deficiências.

TAREFA:
Explique o conceito apresentando:
1. definição em linguagem simples;
2. analogia com uma situação profissional;
3. funcionamento geral;
4. três exemplos universitário;
5. três exemplos profissionais;

FORMATO:
Organize a resposta utilizando subtítulos e uma
tabela para a comparação.

RESTRIÇÕES:
- máximo de 500 palavras;
- explicar qualquer termo técnico utilizado.

CRITÉRIO DE QUALIDADE:
Ao final da explicação, um estudante iniciante deverá
conseguir explicar o conceito utilizando suas próprias palavras.

Finalize apresentando duas perguntas para verificar
a compreensão do estudante.

### Resultado
JavaScript e TypeScript

1. Definição em linguagem simples

JavaScript (JS) é uma linguagem de programação usada para criar páginas, sistemas e aplicações interativas. É bastante utilizada na web e pode ser executada diretamente pelo navegador.

TypeScript (TS) é uma linguagem baseada no JavaScript que adiciona **tipagem**, ou seja, permite informar qual tipo de informação uma variável deve armazenar, como texto, número ou verdadeiro/falso. Isso ajuda a encontrar erros durante o desenvolvimento.

2. Analogia profissional

Imagine uma empresa desenvolvendo um sistema para cadastrar funcionários.

Com **JavaScript**, o programador tem mais liberdade para inserir informações, mas alguns erros podem aparecer somente quando o sistema estiver funcionando.

Com **TypeScript**, é como ter uma conferência antes de o sistema funcionar. O código verifica se as informações estão sendo utilizadas nos formatos esperados, reduzindo determinados tipos de erros.

3. Funcionamento geral

O **JavaScript** pode ser executado diretamente pelo navegador. O navegador possui um **motor**, que é o componente responsável por interpretar e executar o código.

O **TypeScript** precisa passar por um processo chamado **transpilação**, que significa converter o código TypeScript para JavaScript. Depois disso, o JavaScript pode ser executado normalmente.

4. Exemplos universitários

1. Sistema de notas:
JavaScript pode receber e calcular notas dos alunos. TypeScript permite indicar que as notas devem ser números, evitando determinados erros.

2. Cadastro de alunos:
Um programa pode armazenar nome, idade e matrícula. No TypeScript, podemos definir os tipos dessas informações, tornando o código mais organizado.

3. Projeto em grupo:
Em um trabalho com vários estudantes, o TypeScript pode ajudar a identificar erros no código antes da execução, facilitando a colaboração.

5. Exemplos profissionais

1. Loja virtual:
JavaScript pode controlar carrinho, produtos e interações da página. TypeScript ajuda a organizar grandes quantidades de informações.

2. Sistema bancário:
TypeScript pode ajudar a garantir que informações como valores, contas e usuários sejam utilizadas nos formatos esperados.

3. Aplicativos corporativos:
Em sistemas desenvolvidos por equipes grandes, o TypeScript facilita a manutenção do código, ou seja, realizar correções e alterações posteriormente.

6. Comparação

| Característica      | JavaScript                   | TypeScript                        |
| ------------------- | ---------------------------- | --------------------------------- |
| Aprendizado inicial | Mais simples                 | Um pouco mais complexo            |
| Tipagem             | Dinâmica                     | Estática                          |
| Execução            | Direta                       | Convertido para JavaScript        |
| Detecção de erros   | Durante ou antes da execução | Muitos erros são detectados antes |
| Projetos grandes    | Pode exigir mais organização | Facilita a organização            |
| Principal vantagem  | Simplicidade e flexibilidade | Segurança e organização           |

Tipagem dinâmica significa que uma variável pode receber diferentes tipos de informação. **Tipagem estática** significa que o tipo da informação é definido e verificado durante o desenvolvimento.

Conclusão

De forma simples: **JavaScript é mais direto e flexível para começar**, enquanto **TypeScript adiciona ferramentas para tornar o código mais organizado e reduzir erros**, principalmente em projetos maiores. TypeScript não substitui o JavaScript: ele é baseado nele.

Para verificar a compreensão

1. Qual é a principal diferença entre JavaScript e TypeScript?
2. Por que o TypeScript pode ser vantajoso em um projeto profissional desenvolvido por várias pessoas?
_______________________________________________________________________________________________
| Critério                 | Prompt 1                     | Prompt 2                          |
| -------------------      | ---------------------------- | ----------------------------------|
| Clareza                  |             sim              |             sim                   |
| Precisão                 |             sim              |                                   |
| Relevância               |           pouca              |                                   |
| Organização              |           pouca              |                                   |
| Adequação ao público     |             sim              |                                   |
| Atendimento ao objetivo  |             sim              |                                   |
| Utilidade prática        |           pouca              |                                   |

<div align="center">

# Tendências em Ciência da Computação

### Inteligência Artificial | Engenharia de Prompt | Low-Code | Agentes de IA

Atividades e projetos da disciplina **Tendências em Ciência da Computação** (Profa. Kadidja Valéria, UDF): da engenharia de prompt a um agente de IA com ética aplicada.

![IA](https://img.shields.io/badge/Inteligência_Artificial-6A1B9A)
![Prompt Engineering](https://img.shields.io/badge/Engenharia_de_Prompt-1565C0)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Botpress](https://img.shields.io/badge/Botpress-low--code-00A3FF)
![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey)

</div>

---

## Destaque: Assistente Acadêmico da UDF

Projeto da **Unidade 4**: um agente de IA que tira dúvidas acadêmicas dos estudantes (rematrícula, estágio, TCC, dependências e faltas), construído do zero em **4 camadas** (perceber, compreender, decidir e executar). O projeto leva em conta privacidade desde o projeto (LGPD), mitigação de viés e interpretabilidade.

- Roda direto no navegador, sem instalação, servidor ou chave de API
- Todas as respostas têm o botão **"Por que recebi esta resposta?"**
- Bateria automatizada com **50 casos de teste em 7 grupos**: **50 de 50 aprovados**
- Evolução do chatbot low-code feito no Botpress na Unidade 3

**[Ver o projeto completo](Unidade%204%20-%20Aplicações%20e%20Limitações/)**

---

## Conteúdo

| Unidade | Tema | O que tem lá |
|---|---|---|
| [1 · Fundamentos de IA e Engenharia de Prompt](Unidade%201%20-%20Fundamentos%20de%20IA%20e%20Engenharia%20de%20Prompt/) | IA no dia a dia e engenharia de prompt | IA em apps reais, prompts para uma calculadora de IRRF, refinamento de prompts e reflexão |
| [2 · Programação Assistida e Automação com IA](Unidade%202%20-%20Programação%20Assistida%20e%20Automação%20com%20IA/) | Programação com assistentes de IA | Em construção |
| [3 · Low Code / No Code](Unidade%203%20-%20Low%20Code%20No%20Code/) | Plataformas low-code | Chatbot Acadêmico no Botpress, com base de conhecimento e reflexão crítica |
| [4 · Aplicações e Limitações](Unidade%204%20-%20Aplicações%20e%20Limitações/) | Agentes de IA e ética aplicada | Agente próprio em JavaScript, testes automatizados, design conversacional e análise ética |

---

## Estrutura do repositório

```
.
├── Unidade 1 - Fundamentos de IA e Engenharia de Prompt/
├── Unidade 2 - Programação Assistida e Automação com IA/
├── Unidade 3 - Low Code No Code/
├── Unidade 4 - Aplicações e Limitações/
│   ├── agente/                  # agente.js, base-conhecimento.js, index.html, testes.js
│   ├── bateria-de-testes.md
│   └── design-conversacional.csv
├── PLANO_DE_AULA_5W.md          # plano de aula da disciplina (modelo 5W)
└── LICENSE
```

---

## Como executar o agente (Unidade 4)

```bash
git clone https://github.com/JoaoFelipeSS/Tendencias-em-ciencia-da-computacao.git
cd "Tendencias-em-ciencia-da-computacao/Unidade 4 - Aplicações e Limitações/agente"
node testes.js          # roda a bateria de testes
```

Para conversar com o agente, abra `agente/index.html` no navegador.

---

## Equipe

| Estudante | Papel no projeto da Unidade 4 |
|---|---|
| **João Felipe Soares Silva** | Modelagem: temas, intenções e regras de decisão |
| João Vítor Miranda de Moraes | Implementação |
| Luis Fernando Figueiredo Frizzo | Testes e curadoria |

[![GitHub](https://img.shields.io/badge/GitHub-JoaoFelipeSS-181717?logo=github)](https://github.com/JoaoFelipeSS)

## Licença

Distribuído sob a licença [CC0 1.0 Universal](LICENSE).

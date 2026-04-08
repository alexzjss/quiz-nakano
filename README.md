# 🎯 DESAFIO NAKANO

Uma homenagem interativa ao **Prof. Fábio Nakano** da EACH-USP, criada para ser apresentada durante a aula. O quiz mistura perguntas sobre a carreira do professor com perguntas de **linguagem C** para a turma — tudo em um arquivo HTML único, sem dependências externas.

---

## 🚀 Como usar

Basta abrir o arquivo `index.html` diretamente no navegador. Nenhuma instalação, servidor ou framework é necessário.

```bash
# Clone o repositório
git clone https://github.com/alexzjss/quiz-nakano.git

# Abra o arquivo no navegador
open index.html   # macOS
xdg-open index.html   # Linux
start index.html  # Windows
```

---

## 🎮 Fluxo do Quiz

1. **Tela de Introdução** – apresenta o desafio e convida o professor e a turma a participar.
2. **10 Perguntas** – alternando entre dois tipos:
   - 🎒 **Para a Sala** – perguntas de linguagem C (operadores, funções, loops, keywords).
   - 👨‍🏫 **Para o Professor** – curiosidades sobre a vida e carreira do Prof. Nakano.
3. **Tela Final** – o professor deve listar o máximo de alunos que conseguir lembrar, com efeitos visuais que ficam progressivamente mais caóticos conforme mais nomes são digitados.

---

## 📚 Perguntas

| # | Tipo | Tema |
|---|------|------|
| 1 | 🎒 Sala | O que `printf` faz em C? |
| 2 | 👨‍🏫 Professor | Graduação do Prof. Nakano |
| 3 | 🎒 Sala | Operador módulo `%` em C |
| 4 | 👨‍🏫 Professor | Tema do doutorado |
| 5 | 🎒 Sala | Lógica de rotina matinal (questão-piada) |
| 6 | 👨‍🏫 Professor | Empresa onde trabalhou antes de ser professor |
| 7 | 🎒 Sala | Keyword `const` em C |
| 8 | 👨‍🏫 Professor | Idiomas que o professor fala |
| 9 | 🎒 Sala | Loop `do...while` em C |
| 10 | 👨‍🏫 Professor | Prêmio recebido em 2003 no IME-USP |

Cada resposta correta vale **10 pontos**. Ao responder, uma explicação é exibida.

---

## ✨ Efeitos Visuais

- **Partículas** animadas em canvas no fundo
- **Emojis flutuantes** subindo pela tela
- **Feedback animado** (✅ CORRETO! / ❌ ERROU!) com pop e shake
- **Confete** ao acertar e ao terminar o quiz
- **Temas de cor** diferentes para cada pergunta (purple, green, blue, orange, pink, dark)
- **Modo caos** na tela final: quanto mais nomes de alunos digitados, mais confetes, estrelas e shake de tela

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|-----------|-----|
| HTML5 / CSS3 | Estrutura e estilo (tudo inline no `index.html`) |
| JavaScript (Vanilla) | Lógica do quiz, animações, efeitos |
| Canvas API | Partículas animadas no fundo |
| Google Fonts | Bangers, Fredoka One, Nunito, Press Start 2P |

---

## 📁 Estrutura

```
quiz-nakano/
├── index.html   # Aplicação completa (HTML + CSS + JS em um único arquivo)
├── LICENSE
└── README.md
```

---

## 📜 Licença

Veja o arquivo [LICENSE](LICENSE).

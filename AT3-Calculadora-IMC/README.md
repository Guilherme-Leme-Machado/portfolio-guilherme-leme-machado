# ⚖️ Calculadora de IMC

## 📝 Descrição do Projeto
Este projeto consiste em uma calculadora de **Índice de Massa Corporal
(IMC)** para adultos, desenvolvida com HTML5 e **JavaScript**. O usuário
informa a altura e o peso, e a página calcula o IMC pela fórmula
`peso / (altura × altura)` e exibe o valor com duas casas decimais junto
da classificação correspondente.

Desenvolvido como parte das disciplinas de **Desenvolvimento Front-End
Para Web (2026.2)**, a atividade introduz o uso de JavaScript no
navegador: leitura de campos, estruturas condicionais e atualização do
conteúdo da página.

A classificação segue as faixas de IMC abaixo:

| IMC | Classificação |
| :--- | :--- |
| Abaixo de 18,5 | Baixo Peso |
| 18,5 a 24,9 | Peso Normal |
| 25 a 29,9 | Sobrepeso |
| 30 a 34,9 | Obesidade Grau I |
| 35 a 39,9 | Obesidade Grau II |
| 40 ou mais | Obesidade Mórbida |

A calculadora aceita a altura em metros (ex: `1.75`) ou em centímetros
(ex: `175`), convertendo automaticamente, e avisa quando algum campo
está vazio.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** HTML5 e JavaScript
* **Ferramentas:** Git, GitHub e VSCode

## 📊 Resultados e Aprendizados
O projeto resultou em uma calculadora funcional, em um único arquivo
(`atividade-peso.html`).

* **Manipulação do DOM:** Aprendi a ler valores com
  `document.getElementById` e a exibir o resultado na página com
  `innerHTML`.
* **Eventos:** Utilizei o evento `onclick` para disparar o cálculo ao
  clicar no botão.
* **Estruturas Condicionais:** Implementei a cadeia de
  `if / else if / else` para classificar o IMC.
* **Tratamento de Entrada:** Tratei a altura informada em centímetros e
  o caso de campos vazios para evitar resultados inválidos.

---
[Voltar ao início](https://github.com/Guilherme-Leme-Machado/portfolio-guilherme-leme-machado)

# 🧠 O Colaborador Invisível — Front-End Copilotado com IA

## 📝 Descrição do Projeto
Este projeto consiste em uma aplicação web sobre o **impacto da IA e da
comunicação fluida na saúde mental da Geração Z** no ambiente de
trabalho. A página principal reúne um artigo com gráficos e perguntas
frequentes, e três ferramentas interativas ajudam o usuário a refletir
sobre seus próprios hábitos digitais.

Desenvolvido como parte das disciplinas de **Desenvolvimento Front-End
Para Web (2026.2)**, o projeto foi construído em parceria com IA
generativa, e todas as falhas do código gerado foram auditadas e
corrigidas manualmente (veja o `AUDITORIA_IA.md`).

* **Início (`index.html`):** artigo com sumário lateral, quatro gráficos
  (linhas e pizza) feitos com Chart.js e acordeão de perguntas e
  respostas.
* **Gerador de Protocolo de Desconexão
  (`gerador_de_desconexao.html`):** o usuário define horário limite,
  regime de dias, meta diária sem telas e hábitos de desconexão, e
  exporta o plano de bem-estar em PDF.
* **Simulador de Sobrecarga Cognitiva (`simulador_cognitivo.html`):**
  com base em horas de trabalho, pausas, uso de IA e fatores de estresse,
  gera uma pontuação de sobrecarga com recomendações personalizadas.
* **Teste de Autopercepção Socioemocional
  (`teste_autopercepcao.html`):** questionário com barra de progresso,
  cálculo dinâmico do score e feedback imediato por perfil.

Todas as páginas contam com alternância entre **modo claro e escuro**,
lembrada pelo navegador.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** HTML5, CSS3 e JavaScript
* **Bibliotecas:** Bootstrap 5.3 e Chart.js
* **Ferramentas:** Git, GitHub e VSCode
* **Modelo de IA:** Google Gemini 3 Flash

## 📊 Resultados e Aprendizados
O projeto resultou em um conjunto de quatro páginas integradas, com
estilos e scripts separados em arquivos próprios (`css/` e `js/`).

* **Separação de Responsabilidades:** Mantive um script por página e uma
  folha de estilos única, em vez de código embutido no HTML.
* **Modais Dinâmicos:** Corrigi o disparo indevido do modal, isolando-o
  no clique do botão e separando a função de atualização da função que
  trata o evento.
* **Dark Mode Completo:** Sobrescrevi classes nativas do Bootstrap
  (`.text-dark`, `.bg-light`, `.alert-info`) para evitar texto
  ilegível no tema escuro e persisti a escolha com `localStorage`.
* **Exportação em PDF:** Usei `@media print` para imprimir somente o
  cartão com o plano ou o resultado, ocultando navegação e formulários.
* **Validação:** Bloqueei o botão do teste socioemocional até que todas
  as perguntas fossem respondidas, evitando resultados parciais.
* **Visualização de Dados:** Representei dados por geração em gráficos
  de linhas e de pizza com Chart.js.

## 🧠 Declaração de Uso Ético da IA
Este projeto utilizou inteligência artificial (Google Gemini 3 Flash)
estritamente como ferramenta de suporte tecnológico para a geração
inicial das páginas, scripts e estilos a partir de prompts
documentados. Todo o código gerado foi revisado, testado e compreendido
por mim, garantindo a minha responsabilidade integral sobre a autoria
final, integridade e funcionamento da aplicação. Os prompts utilizados,
as falhas encontradas e as correções feitas estão registrados no
[Relatório de Auditoria de IA](./AUDITORIA_IA.md).

## 💻 Deploy do projeto
[Clique para acessar](https://guilherme-leme-machado.github.io/site_copilotado_com_IA)

---
[Voltar ao início](https://github.com/Guilherme-Leme-Machado/portfolio-guilherme-leme-machado)

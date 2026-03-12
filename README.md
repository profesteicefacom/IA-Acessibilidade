# IA-Acessibilidade
Protocolo de engenharia de prompt para a adaptação de materiais didáticos de Computação para estudantes com deficiência visual. Baseado nas normas ISO 9241-171 e NBR ISO 24495-1. Submissão WEI 2026

# Design Instrucional Acessível com IAGen em Computação

Este repositório contém o protocolo de engenharia de prompt e os registos (*logs*) de interação utilizados na investigação intitulada **"IA Generativa no Suporte ao Design de Atividades de Computação Acessíveis"**, submetida ao **WEI 2026 (Workshop sobre Educação em Computação - SBC)**.

O objetivo deste projeto é fornecer uma metodologia sistematizada para que docentes possam utilizar modelos de linguagem (LLMs) na adaptação de materiais didáticos para estudantes com deficiência visual, garantindo rigor técnico e acessibilidade normativa.

## 🚀 Reprodutibilidade e Ciência Aberta

Para garantir que esta investigação seja aplicável em diversos contextos educativos, todos os testes foram realizados utilizando a **versão gratuita do ChatGPT**. Esta escolha metodológica visa democratizar o acesso às técnicas de adaptação, permitindo que professores sem acesso a licenças pagas possam replicar os resultados.

## 🧠 Procedimento de Prompting Estruturado

A interação com o modelo seguiu um protocolo rigoroso fundamentado na convergência de três marcos da literatura de engenharia de prompt:

1.  **Atribuição de Persona (Reynolds & McDonell, 2021):** O modelo é instruído a operar como um especialista híbrido em Engenharia de Software, Design de Interação (IHC) e Educação Inclusiva.
2.  **Padrão de Restrições (White et al., 2023):** Injeção direta das normas **ISO 9241-171** e **ABNT NBR ISO 24495-1** como regras de design, proibindo referências espaciais e garantindo a preservação da agência do estudante.
3.  **Raciocínio em Cadeia (Wei et al., 2022):** Utilização de *Chain-of-Thought* (CoT) para obrigar o modelo a descrever a lógica da transposição semântica antes de gerar o recurso final.

## 📂 Estrutura do Repositório

* `/prompts`: Contém o template mestre utilizado para a geração das atividades.
* `/logs`: Transcrições completas das interações (Prompts e Respostas), permitindo auditar o raciocínio da IA.
* `/outputs`: Artefatos gerados, incluindo códigos PlantUML, tabelas linearizadas e roteiros de computação tangível.

## 🛠️ Como Replicar

1.  Aceda ao [ChatGPT](https://chat.openai.com/) (Versão gratuita).
2.  Copie o template de prompt localizado em `/prompts/Template_Mestre.md`.
3.  Preencha os campos `[CENÁRIO]` e `[BARREIRA]` com os dados da sua atividade.
4.  Analise a "Cadeia de Raciocínio" gerada pela IA antes de validar o recurso didático final.

## 📄 Licença

Este repositório está licenciado sob a licença **Creative Commons Attribution 4.0 International (CC-BY 4.0)**. Pode partilhar e adaptar os conteúdos, desde que atribua o devido crédito à investigação original.

## ✍️ Citação

Caso este protocolo seja útil para o seu trabalho, utilize a seguinte citação:

```bibtex
#em breve
```
---
*Investigação focada na promoção da justiça digital e na autonomia de estudantes cegos no ensino de computação.*

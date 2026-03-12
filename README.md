# Design Instrucional Acessível com IAGen em Computação

Este repositório hospeda o protocolo de engenharia de prompt e os registros (*logs*) de interação da pesquisa intitulada **"IA Generativa no Suporte ao Design de Atividades de Computação Acessíveis"**.

O projeto estabelece um procedimento sistematizado para auxiliar docentes na adaptação de materiais didáticos de computação para estudantes com deficiência visual. O foco central é a remoção de barreiras de percepção física através da transposição semântica, assegurando o rigor técnico e a autonomia pedagógica.

## 🚀 Reprodutibilidade e Ciência Aberta

Alinhado aos princípios de justiça digital, este estudo utiliza exclusivamente a **versão gratuita do ChatGPT**. Esta decisão metodológica garante que as estratégias de adaptação sejam replicáveis por docentes em diversos contextos institucionais, independentemente de acesso a licenças pagas, promovendo a democratização de ferramentas de inclusão.



## 🧠 Protocolo de Prompting Estruturado

A interação com o modelo de linguagem não ocorre de forma trivial; ela segue um protocolo fundamentado em três pilares da literatura científica para garantir resultados consistentes e tecnicamente válidos:

1. **Programação por Personas (Reynolds & McDonell, 2021):** O modelo é configurado para simular um especialista híbrido em Engenharia de Software, IHC e Educação Inclusiva. Isso delimita o vocabulário técnico e a sensibilidade pedagógica da IA.
2. **Padrão de Restrições (White et al., 2023):** Injeção das normas **ISO 9241-171** e **ABNT NBR ISO 24495-1** como regras de design. O protocolo proíbe referências espaciais e exige equivalência semântica, impedindo que a acessibilidade seja meramente superficial.
3. **Estímulo ao Raciocínio (Wei et al., 2022):** Aplicação de *Chain-of-Thought* (Cadeia de Pensamento), onde a IA deve descrever sua lógica de adaptação e conformidade normativa antes de gerar o artefato final.



## 📋 Conformidade Normativa

Diferente de adaptações genéricas, este protocolo operacionaliza cláusulas específicas de normas internacionais e nacionais:

* **ISO 9241-171 (Acessibilidade de Software):** Foco em Independência Sensorial e Navegação Hierárquica. A saída é estruturada para ser eficiente no escaneamento por leitores de tela (NVDA/JAWS), transformando elementos visuais em relações lógicas.
* **ABNT NBR ISO 24495-1 (Linguagem Simples):** Foco na redução da sobrecarga cognitiva auditiva. As respostas são otimizadas para serem concisas, diretas e fáceis de localizar auditivamente.

## 📂 Estrutura do Repositório

* `/prompts`: Arquivos com o procedimento de configuração (Pre-prompt) e o template de execução.
* `/logs`: Transcrições brutas das sessões, permitindo a auditoria das cadeias de raciocínio da IA.
* `/outputs`: Resultados da transposição (ex: códigos PlantUML, tabelas linearizadas e roteiros tangíveis).

## 🛠️ Como Replicar

1.  Consulte o arquivo `/prompts/Protocolo_Estruturado.md`.
2.  Inicie uma sessão na versão gratuita do ChatGPT e envie o **Comando de Configuração**.
3.  Após a confirmação da persona, utilize o **Template de Execução** inserindo os dados do seu cenário específico (ex: um diagrama ou fragmento de código).
4.  Valide se a "Cadeia de Pensamento" da IA respeitou as restrições de agência (não resolver o exercício para o aluno).

## 📄 Licença

Este repositório está sob a licença **Creative Commons Attribution 4.0 International (CC-BY 4.0)**. O uso, compartilhamento e adaptação são livres, desde que atribuído o crédito à investigação original.

## ✍️ Citação

```bibtex
#EM BREVE
```

---
*Investigação focada na promoção da autonomia e justiça digital para estudantes cegos no ensino de computação.*

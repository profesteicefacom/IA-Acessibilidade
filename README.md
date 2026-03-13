# Design Instrucional Acessível com IAGen em Computação

Este repositório hospeda o protocolo de engenharia de prompt e os registros (*logs*) de interação da pesquisa intitulada **"IA Generativa no Suporte ao Design de Atividades de Computação Acessíveis"**.

O projeto estabelece um procedimento sistematizado para auxiliar docentes na identificação de barreiras de acessibilidade e na proposição de estratégias pedagógicas para estudantes com deficiência visual. O objetivo central é transformar a IA em uma assistente de design instrucional, garantindo que a tecnologia atue na remoção de barreiras de percepção sem comprometer o desafio cognitivo ou a agência do estudante no ensino de tecnologia.

## 🚀 Reprodutibilidade e Ciência Aberta

Alinhado aos princípios de justiça digital e acessibilidade econômica, este estudo utiliza exclusivamente a **versão gratuita do ChatGPT**. Esta decisão garante que o protocolo seja replicável por docentes em diversos contextos institucionais, independentemente do acesso a licenças pagas, promovendo a democratização de ferramentas de inclusão síncrona.

## 🧠 Protocolo de Prompting Estruturado

A interação com o modelo de linguagem segue um rigoroso desenho experimental fundamentado em três marcos da literatura de engenharia de prompt, visando resultados tecnicamente válidos e pedagogicamente úteis:

1. **Padrão de Persona (Reynolds & McDonell, 2021; White et al., 2023):** O modelo é ancorado no papel de um especialista em acessibilidade no ensino de computação. Isso localiza a tarefa no domínio do design pedagógico inclusivo, orientando a geração de recomendações tecnicamente precisas.
2. **Padrão de Restrições (White et al., 2023):** Injeção de marcos normativos como regras de design rígidas. O protocolo utiliza diretrizes de acessibilidade e linguagem simples para mitigar dependências sensoriais e ambiguidades linguísticas.
3. **Raciocínio em Cadeia (Wei et al., 2022):** Aplicação de *Chain-of-Thought* (Cadeia de Pensamento) para a decomposição de problemas complexos. Exige-se que o modelo realize uma análise intermediária das barreiras e seus impactos antes de propor a adaptação final.

## 📋 Conformidade Normativa

Diferente de abordagens genéricas, este protocolo operacionaliza cláusulas técnicas de marcos nacionais e internacionais:

* **ISO/IEC 25010 & ISO 9241-171:** Foco na qualidade, equivalência semântica e independência sensorial na interação com tecnologias assistivas.
* **ABNT NBR ISO 24495-1 (Linguagem Simples):** Redução da sobrecarga cognitiva auditiva através de clareza informativa e concisão textual.
* **WCAG & ABNT NBR 17225:** Alinhamento com os princípios universais de perceptibilidade e operabilidade digital.

## 📂 Estrutura do Repositório

* `/prompts`: Contém o **Template Mestre** estruturado para apoio ao design instrucional.
* `/logs`: Transcrições brutas das sessões, evidenciando as etapas de análise de barreiras e recomendações.
* `/outputs`: Estratégias de adaptação geradas (ex: roteiros de computação tangível, códigos PlantUML e estruturas lineares).

## 🛠️ Como Replicar

1.  Acesse o arquivo `/prompts/Template_Mestre.md`.
2.  Inicie uma sessão na versão gratuita do ChatGPT e envie o comando seguindo a estrutura de **Papel da IA** e **Referencial Normativo**.
3.  Insira os dados da sua atividade (Tipo de recurso, Dinâmica e Objetivo Pedagógico).
4.  Analise a **Cadeia de Raciocínio** gerada pela IA para validar se as recomendações preservam a agência do estudante e a integridade do conteúdo técnico antes de aplicar a atividade.

## 📄 Licença

Este repositório está sob a licença **Creative Commons Attribution 4.0 International (CC-BY 4.0)**. O uso, compartilhamento e adaptação são livres, desde que atribuído o crédito à investigação original.

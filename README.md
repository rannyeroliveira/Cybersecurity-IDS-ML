# Intrusion Detection System (IDS)
![Uma ilustração de machine learning para detecção de intrusões](images/ids_img.png)
## 1. Descrição do Projeto
Este é um projeto de Machine Learning de ponta a ponta que visa construir um Sistema de Detecção de Intrusões (IDS) para identificar e classificar tráfego de rede malicioso. Utilizando um framework de Machine Learning para classificação, o projeto se concentra em diferenciar pacotes de dados normais de pacotes que representam ataques cibernéticos.

A metodologia de desenvolvimento seguiu os princípios de CRISP-DM, garantindo que todas as fases de um projeto de ciência de dados fossem abordadas. O projeto foi modularizado, com pipelines de automação para o treinamento e a predição, tudo desenvolvido com boas práticas como o uso de ambiente virtual, tratamento de exceções, logging e documentação detalhada.

## 2. Tecnologias e Ferramentas
 Python (Pandas, Scikit-learn, Matplotlib, Seaborn, Git, GitHub)

 Jupyter Notebook

 Visual Studio Code

 Metodologia CRISP-DM

## 3. Problema de Negócio e Objetivos do Projeto
- ### 3.1 Qual é o Problema de Negócio?
Equipes de segurança cibernética frequentemente enfrentam a difícil tarefa de monitorar grandes volumes de tráfego de rede para identificar possíveis ataques. A detecção manual é inviável, e sistemas baseados em regras fixas podem falhar ao identificar novas ameaças. O problema reside em ter uma ferramenta que possa, de forma autônoma e precisa, sinalizar atividades suspeitas para que as equipes de segurança possam agir proativamente.

- ### 3.2 Qual é o Contexto?
Para maximizar a segurança e a eficiência da equipe, o objetivo é maximizar o Recall (minimizando Falsos Negativos) e manter os Falsos Positivos em um nível gerenciável. Um alto número de falsos positivos pode causar "fadiga de alerta" na equipe de segurança, o que é um risco real.

 - ### 3.3 Quais são os Objetivos do Projeto?
Identificar os padrões de tráfego associados a ataques cibernéticos.

Construir um modelo de classificação (Random Forest) capaz de prever com alta precisão a ocorrência de um ataque.

Oferecer uma análise detalhada dos fatores que mais contribuem para a detecção de ataques, fornecendo insights para aprimorar as regras de segurança existentes.

- ### 3.4 Quais são os Benefícios do Projeto?
- Redução de Custos: Automatiza a detecção, reduzindo a necessidade de monitoramento manual intensivo.

- Melhora na Postura de Segurança: Aumenta a capacidade de detectar e responder a ameaças em tempo hábil.

- Análise de Dados: Fornece insights sobre os tipos de ataques mais comuns e suas características, permitindo uma melhor defesa.

- Proteção de Ativos: Minimiza a exposição a riscos cibernéticos, protegendo a integridade da rede e dos dados.

## 4. Pipeline da Solução (CRISP-DM)
 O projeto foi desenvolvido seguindo a metodologia CRISP-DM, um framework robusto para projetos de mineração de dados. Cada fase foi abordada com o objetivo de garantir a qualidade e a relevância da solução.

1. Compreensão do Negócio: Entendimento do problema de segurança cibernética e definição dos objetivos (alto Recall, baixo Falsos Positivos).

2. Compreensão dos Dados: Coleta do dataset UNSW-NB15, análise da estrutura, identificação de desbalanceamento e exploração dos padrões.

3. Preparação dos Dados: Limpeza, tratamento de valores ausentes, codificação de variáveis categóricas (One-Hot Encoding) e balanceamento da variável-alvo (SMOTE).

4. Modelagem: Treinamento do modelo Random Forest Classifier com otimização de parâmetros.

5. Avaliação: Avaliação do modelo usando métricas de segurança (Recall, F1-Score) e análise da Matriz de Confusão para entender os erros de classificação.

6. Implantação: Documentação do processo e dos resultados, com a proposta de um plano para integração do modelo em um ambiente de monitoramento.

## 5. Principais Insights e Conclusão
# Implementando sua Primeira Stack com AWS CloudFormation

Repositório dedicado à documentação do projeto prático do bootcamp da DIO sobre Infraestrutura como Código (IaC) utilizando **AWS CloudFormation**.

---

## 🎯 Objetivo do Projeto
Compreender e aplicar os conceitos fundamentais de Infraestrutura como Código (IaC) na AWS, automatizando a criação e gestão de recursos de nuvem através de modelos (*templates*) declarativos em formato JSON ou YAML.

---

## 🛠️ Conceitos e Componentes Explorados

* **Infraestrutura como Código (IaC):** Prática de gerir e aprovisionar recursos computacionais através de ficheiros de definição legíveis por máquinas, garantindo consistência, repetibilidade e rastreabilidade.
* **AWS CloudFormation:** Serviço gerido que permite criar e modelar recursos da AWS com base em templates, gerindo o ciclo de vida completo da infraestrutura (criação, atualizações e eliminação segura através de *Stacks*).
* **Estrutura de um Template CloudFormation:**
  * `AWSTemplateFormatVersion`: Versão do modelo.
  * `Description`: Descrição clara da stack.
  * `Parameters`: Valores passados em tempo de execução para personalizar o template.
  * `Resources`: Seção obrigatória onde se definem os componentes de infraestrutura criados (ex: instâncias EC2, buckets S3, redes VPC).
  * `Outputs`: Dados de retorno exibidos após a criação bem-sucedida da stack.

---

## 💡 Principais Vantagens Identificadas
1. **Automação e Consistência:** Eliminação de configuração manual propensa a erros na consola da AWS.
2. **Controlo de Versões:** Os templates podem ser versionados em sistemas como o Git, permitindo auditorias e reversões de alterações com facilidade.
3. **Gestão de Dependências:** O CloudFormation calcula automaticamente a ordem correta para criar ou destruir recursos interligados.

---

## 🚀 Conclusão
O projeto permitiu consolidar competências essenciais de engenharia de cloud e IaC, automatizando o aprovisionamento de ambientes de forma segura e padronizada.

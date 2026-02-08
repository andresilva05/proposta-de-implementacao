# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 10/02/2026  
**Empresa:** Abstergo Industries  
**Responsável:** André Silva  

---

## Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **Abstergo Industries**, realizado por **André Silva**.

O objetivo do projeto foi elencar **três serviços da Amazon Web Services (AWS)** com foco na **redução imediata de custos operacionais**, substituindo parte da infraestrutura local e melhorando a escalabilidade e a eficiência dos sistemas da empresa.

A adoção da computação em nuvem permite que a empresa pague apenas pelos recursos utilizados, reduzindo gastos com manutenção de servidores físicos, energia elétrica e suporte técnico.

---

## Descrição do Projeto

O projeto de implementação de serviços foi dividido em **três etapas**, cada uma com seus objetivos específicos, conforme descrito a seguir:

---

### Etapa 1

- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)  
- **Foco da ferramenta:** Hospedagem de servidores virtuais  
- **Descrição do caso de uso:**  
A empresa utilizava servidores físicos locais para hospedar seu site institucional e uma API interna, o que gerava custos elevados com manutenção e infraestrutura.  
Com a implementação do Amazon EC2, esses servidores foram migrados para a nuvem, permitindo pagamento apenas pelo tempo de uso, maior flexibilidade e redução imediata de custos operacionais.

---

### Etapa 2

- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)  
- **Foco da ferramenta:** Armazenamento de arquivos e dados estáticos  
- **Descrição do caso de uso:**  
Arquivos como imagens, documentos e backups eram armazenados diretamente nos servidores, aumentando custos de disco e manutenção.  
O Amazon S3 passou a ser utilizado para armazenar esses arquivos, reduzindo o uso de disco nos servidores EC2, diminuindo custos e garantindo alta durabilidade e disponibilidade dos dados.

---

### Etapa 3

- **Nome da ferramenta:** Amazon RDS (Relational Database Service)  
- **Foco da ferramenta:** Banco de dados relacional gerenciado  
- **Descrição do caso de uso:**  
A empresa mantinha um banco de dados local que exigia administração manual e backups frequentes.  
Com o Amazon RDS, foi possível automatizar backups, reduzir custos com administração e aumentar a confiabilidade do banco de dados utilizado para cadastro de usuários, login e registro de pedidos.

---

## Conclusão

A implementação dos serviços **Amazon EC2**, **Amazon S3** e **Amazon RDS** na empresa *Abstergo Industries* tem como resultado esperado a **redução de custos operacionais**, maior escalabilidade dos sistemas e diminuição do esforço de manutenção da infraestrutura.

Essas melhorias contribuem para o aumento da eficiência e produtividade da empresa, além de preparar o ambiente para crescimento futuro. Recomenda-se a continuidade da utilização dos serviços AWS e a avaliação de novas soluções em nuvem que possam otimizar ainda mais os processos internos.

---

**Assinatura do Responsável pelo Projeto:**  

**André Silva**

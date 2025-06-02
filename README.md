# Relatório de Implementação de Serviços AWS

**Data:** 02/06/2025 <br>
**Empresa:**  Abstergo Industries <br>
**Responsável:** Gabriela Silva

## Introdução
Este relatório apresenta a proposta e o andamento da implementação de serviços em nuvem da AWS na empresa **Abstergo Industries**, com o objetivo de transformar a infraestrutura tecnológica da empresa para um modelo *cloud*, visando a **redução de custos operacionais**, maior **escalabilidade** e **eficiência** na operação do clube de distribuição farmacêutico. A empresa busca se posicionar como uma **revendedora confiável para outras farmácias**, oferecendo agilidade e segurança na gestão de estoque e distribuição.

## Descrição do Projeto 
A implementação envolve a adoção de **três principais serviços AWS** que suportarão a transformação digital da empresa: computação, armazenamento e automação de processos. O foco principal é garantir **alta disponibilidade**, **otimização de custos** e **resiliência**, alinhados com a estratégia de crescimento da FarmaDistribuidora.

---

## Etapa 1  
### Nome da ferramenta: **Amazon EC2 (Elastic Compute Cloud)**  
**Foco da ferramenta:** Computação escalável sob demanda  
**Descrição do caso de uso:**  
A AWS EC2 será usada para hospedar os sistemas de gestão de estoque, pedidos e controle de distribuição. A capacidade de **Auto Scaling** permite ajustar a infraestrutura conforme a demanda, reduzindo custos com servidores ociosos. Além disso, o uso de **instâncias Spot e Reserved Instances** trará redução adicional de custos com computação.

---

## Etapa 2  
### Nome da ferramenta: **Amazon S3 (Simple Storage Service)**  
**Foco da ferramenta:** Armazenamento escalável e seguro  
**Descrição do caso de uso:**  
O Amazon S3 será utilizado para armazenar dados históricos de vendas, relatórios, pedidos e arquivos de clientes. A solução garante **alta durabilidade e segurança**, além de permitir uso de políticas de ciclo de vida para migração automática de arquivos antigos para classes de menor custo, como **S3 Glacier**, economizando recursos de armazenamento.

---

## Etapa 3  
### Nome da ferramenta: **AWS Lambda**  
**Foco da ferramenta:** Computação serverless para automação e integração  
**Descrição do caso de uso:**  
A AWS Lambda será empregada para **automatizar integrações** entre os sistemas internos e parceiros (como farmácias e distribuidores), bem como para processar eventos em tempo real. A abordagem **serverless** reduz significativamente os custos de infraestrutura e facilita atualizações e manutenções com maior agilidade e menor dependência de servidores fixos.

---

## Conclusão

Com a adoção dos serviços **Amazon EC2**, **S3** e **Lambda**, a Abstergo Industries obterá uma infraestrutura moderna, econômica e escalável. A empresa estará mais preparada para lidar com o aumento da demanda e com as exigências do mercado B2B farmacêutico. Além da **redução de custos operacionais**, haverá ganhos significativos em **eficiência, agilidade e segurança** da informação.


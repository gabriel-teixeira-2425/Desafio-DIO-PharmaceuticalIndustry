# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
**Data:** 07/07/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Gabriel Levi dos Santos Teixeira 

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gabriel Levi dos Santos Teixeira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:** 
- **Nome da Ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de objetos na nuvem
- **Descrição de caso de uso:** A distribuidora farmacêutica gera diariamente notas fiscais, relatórios e documentos que atualmente são armazenados em servidores locais. Com o Amazon S3, esses arquivos são armazenados na nuvem com alta durabilidade (11 noves) e segurança. Documentos antigos (acima de 90 dias) podem ser movidos automaticamente para a classe S3 Glacier, que é até 70% mais barata. A empresa paga apenas pelo espaço utilizado, eliminando custos com manutenção de servidores locais e equipe de infraestrutura.

**Etapa 2:** 
- **Nome da Ferramenta:** AWS Lambda
- **Foco da ferramenta:** Computação serverless
- **Descrição de caso de uso:** A distribuidora possui processos automatizados que rodam em horários específicos, como validação de estoque, envio de notificações de pedidos e integração com sistemas de fornecedores. Com o AWS Lambda, esses processos são executados sob demanda, sem necessidade de servidor dedicado. A empresa paga apenas pelo tempo de execução (em milissegundos), o que representa uma redução significativa em comparação com manter servidores ligados 24/7 para tarefas que rodam poucas vezes ao dia.

**Etapa 3:** 
- **Nome da Ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de dados relacional gerenciado
- **Descrição de caso de uso:** O banco de dados da distribuidora (clientes, produtos, pedidos, estoque) é atualmente mantido em servidor local, exigindo equipe dedicada para backups, atualizações e manutenção. Com o Amazon RDS, a AWS gerencia automaticamente patches de segurança, backups diários e snapshots. A empresa reduz custos com equipe de DBA interna e infraestrutura física, além de ganhar alta disponibilidade com a opção Multi-AZ, que garante continuidade em caso de falhas.

## Conclusão
A implementação das ferramentas Amazon S3, AWS Lambda e Amazon RDS na empresa Abstergo Industries tem como esperado redução imediata de custos operacionais, eliminação de servidores locais, otimização de processos automatizados e redução da dependência de equipe de infraestrutura, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
- Documentação AWS S3
- Documentação AWS Lambda
- Documentação AWS RDS
- Planilha de estimativa de custos

**Assinatura do Responsável pelo Projeto:**
Gabriel Levi dos Santos Teixeira


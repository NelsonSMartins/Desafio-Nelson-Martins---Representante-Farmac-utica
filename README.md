# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 03/01/2026
Empresa: Abstergo Industries (Setor Farmacêutico)
Responsável: Nelson Martins

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Nelson Martins. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimizar a infraestrutura da distribuidora.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, focando em migrar processos pesados para a nuvem de forma inteligente e econômica. As etapas são:

Etapa 1: 
- **Amazon EC2 (Instâncias Spot)**
- **Foco:** Máquinas Virtuais
- **Descrição de caso de uso:** Para o processamento de grandes lotes de notas fiscais e relatórios de distribuição que ocorrem em horários específicos, utilizaremos instâncias Spot. Como essas instâncias aproveitam a capacidade ociosa da AWS, conseguimos uma economia de até 90% no custo das máquinas virtuais em comparação ao modelo tradicional, reduzindo o gasto fixo com servidores.

Etapa 2: 
- **Amazon RDS (Relational Database Service)**
- **Foco:** Serviço de Bancos de Dados
- **Descrição de caso de uso:** Gerenciar um banco de dados de estoque de medicamentos em servidores locais é caro e arriscado. Ao usar o RDS, ganhamos em automação de backups e atualizações. O principal ganho é a redução de custos com pessoal técnico para manutenção e a garantia de que o banco de dados estará sempre disponível, evitando paradas na operação que geram prejuízo.

Etapa 3: 
- **AWS Instance Scheduler**
- **Foco:** Gestão de Máquinas Virtuais
- **Descrição de caso de uso:** Muitos servidores da parte administrativa da distribuidora não precisam ficar ligados durante a madrugada ou fins de semana. Com essa ferramenta, programamos o desligamento automático das máquinas fora do horário comercial. Isso reduz o custo de faturamento dessas máquinas em quase 60%, pagando apenas pelo tempo que a equipe está realmente trabalhando.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução drástica no desperdício de recursos computacionais e maior segurança no armazenamento de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Tabela de horários de desligamento (Instance Scheduler)
- Relatório de previsão de gastos mensal (AWS Pricing Calculator)
- Guia de boas práticas para gerenciamento de banco de dados

Assinatura do Responsável pelo Projeto:

Nelson Martins

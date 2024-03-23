# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/03/2024

Empresa: Abstergo Industries 

Responsável: Tiago Santana Ferreira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Tiago Santana Ferreira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 (Elastic Compute Cloud) 
- Tem como principal objetivo fornecer servidores virtuais escaláveis e configuráveis na nuvem. 
  Com o EC2, os usuários podem provisionar e gerenciar instâncias de servidores em uma variedade de tipos de computação, desde instâncias com recursos computacionais otimizados até instâncias com 
  foco em memória ou armazenamento.

- Vamos considerar um cenário em que a Abstergo Industries não tenha capital para custear um Data Center, que seria um custo monetário muito elevado no momento,tanto para construir, manter e fazer upgrades. Dessa forma,utilizando o Amazon EC2, a farmacêutica elimina a necessidade de investir em servidores físicos e infraestrutura. 
Em vez disso, ela paga apenas pelos recursos de computação que realmente utiliza, o que pode resultar em economia de custos significativa a longo prazo.

Etapa 2: 
- Amazon EC2 Auto Scaling

- Conforme o EC2 mencionado na etapa anterior, temos também esta ferramenta, que permite automatizar o dimensionamento de instâncias EC2, garantindo que você tenha a quantidade certa de capacidade computacional disponível para lidar com a demanda variável de tráfego e carga de trabalho em seus aplicativos.

- Analizando um cenário em que a farmacêutica está se preparando para um período de alta demanda devido a uma grande campanha promocional de um produto que vai lançar. 
Durante a promoção, espera-se um aumento significativo no tráfego do site, com picos de acessos que podem sobrecarregar a infraestrutura existente, comprometendo a experiência do cliente.
O Amazon EC2 Auto Scaling garante que a farmacêutica possa atender à demanda do cliente sem interrupções, mantendo uma alta disponibilidade do site.
Pois quanto mais acesso o site tiver mais instâncias do EC2 poderão ser criadas, e quando passar o período de pico reduzirá as instâncias, agindo de uma forma flexível de uso de recursos e consequentemente custos.

Etapa 3: 
- Amazon Aurora 
- É um serviço de banco de dados relacional da Amazon Web Services (AWS) projetado para oferecer alta performance, disponibilidade e durabilidade para cargas de trabalho críticas. 
   Ele é compatível com as engines MySQL e PostgreSQL e é especialmente conhecido por sua eficiência e escalabilidade.

- A farmacêutica Abstergo pode se beneficiar significativamente ao utilizar este serviço para suas necessidades de banco de dados. 
 Podendo armazenar dados críticos, como informações de clientes, inventário de produtos, histórico de pedidos e transações financeiras. 
 Com a alta disponibilidade e durabilidade do Amazon Aurora, a empresa pode confiar em seus dados para garantir uma operação suave e confiável de sua distribuidora online.
 Tendo por sua vez, um processamento de alta performance em suas transações e pedidos e consultas de clientes de forma rápida.
 Garantindo uma experiência de forma ágil e sem interrupções para os clientes, mesmo em dia de tráfego. 
 Durante períodos de alta demanda, como promoções sazonais ou lançamento de novos produtos, as indústrias Abstergo podem confiar na escalabilidade automática para lidar com o aumento do tráfego e 
 volume de dados. 
 Isso garante que o site da farmacêutica permaneça responsivo e acessível, independentemente das condições de pico.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos de imediato, médio e a longo prazo, pois leva em consideração o pagamento do serviço somente pelo o que for usado, tenho em vista a alta perfomace sobre as tecnologias de última geração que foram implementadas pela a Amazon Web Services (AWS), o que aumentará a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Referências:

https://docs.aws.amazon.com/ec2/

https://aws.amazon.com/pt/autoscaling/

https://aws.amazon.com/pt/rds/aurora/

Assinatura do Responsável pelo Projeto:

Tiago Santana Ferreira

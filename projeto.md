<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *AFRODBEAUTY*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Amanda Roberta Borges de Araújo|Gerente de Projeto|amanda.araujo@estudante.ifro.edu.br|
|Bruna Larissa Pinheiro Felix|Designer de interface com o usuário|bruna.pinheiro@estudante.ifro.edu.br|
|Andressa Alypio de Jesus|Analista de teste|andressaalypiodejesus@gmail.com|
|Anna Clara Oliveira dos Santos|Designer de banco de dados|annaclaraoliv16@gmail.com|
# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | AfrodBeauty |
| GERENTE DO PROJETO | Amanda Roberta Borges de Araújo |
| PRINCIPAL OBJETIVO | Atender as demandas dos clientes e vender produtos de beleza. |
| BENEFÍCIOS ESPERADOS |* Dar maior visibilidade para empresas;<br/>* *Proporcionar um site seguro para compras;<br/>* |
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](AFRODBEAUTY System) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, gerente e demais stakeholders deste projeto. O propósito deste documento é apresentar as funções e serviços que o nosso site apresenta e deve apresentar, bem como restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do site para um auxílio durante as etapas de desenvolvimento. O documento especifica todos os requisitos funcionais e não funcionais do site.

## CONCEPÇÃO DO SISTEMA

Pretendemos usar os seguintes métodos para possamos alcançar os nossos propósitos: 
• Enquetes: 
  Para que possamos saber qual é o interesse do público, o que eles mais gostam ou o que eles não gostam 
• Pesquisa de levantamento:
Utilizaremos para saber o que podemos melhorar e o que o público deseja.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* Feedback: retorno de resultados;
* Stakeholder: integrantes da equipe.

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste na criação de uma empresa/site criado e administrado por mulheres. Este visa vender produtos em parcerias com terceiros.

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Fazer pesquisas para entender se os métodos funcionam e, obter feedback dos clientes

* Realizar novas pesquisas de tendências que estão surgindo diariamente para deixar sempre atualizado o site. 

* Fazer treinamentos com os integrantes da equipe para o melhor desempenho de cada um para que, assim, possam desenvolver novidades para o site e apresentar um pouco sobre o mundo da beleza afim de facilitar o desenvolvimento dos integrantes.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Comprador:**|Realiza as compras no sistema|
|**Empresa:**|Empresas das quais estão cadastradas devem ter acesso para verificar seus produtos e as vendas realizadas|
|**Administrador:**|Responsável pela aprovação das compras e resolução de problemas dos mesmos|
|**SAC:**|O Serviço de Atendimento ao Consumidor deve estar habilitado para sanar as dúvidas dos clientes diretamente com um adm do sistema|
|**Técnico em Informática:**|Responsável pela programação e manutenção do sistema|
|**Transportadora:**|Responsável pelo transporte dos produtos|


## Abrangência e sistemas similares

### Abrangência:

O sistema consiste na implementação de uma empresa/site criado e administrado por mulheres. Este visa vender produtos de beleza em parcerias com terceiros, seja eles de grandes ou pequenas marcas. O sistema possui muitas funcionalidades e ferramentas destinadas as empresas e aos clientes.


Dentre as ferramentas para as empresas podemos citar:

* **Cadastro Empresarial:** as empresas poderão realizar um cadastro onde irão participar de uma avaliação para por fim fazer parte do site;

* **Cadastro dos produtos:** caso a empresa seja aprovada para fazer parte do site, estas deverão poder realizar cadastro dos produtos que desejam vender;

* **Relatar vendas:** as empresas podem ter acesso a todas as vendas que foram realizadas e a todos os clientes que compraram;

Dentre as ferramentas para o cliente podemos citar: 

* **Cadastro do cliente:** o cliente deve poder realizar o cadastro caso seja novo no site;

* **Logon:** caso o usuário já possua cadastro no site eles poderão realizar o logon;

* **Realizar pré-seleção dos produtos:** os clientes poderão simular um carrinho de compras, com os produtos desejados para que também possam saber o valor da compra;
 
* **Cadastrar endereço de compra:** o cliente poderá cadastrar o endereço onde será entregue sua compra;

* **Processar pagamento:** o cliente poderá escolher a forma de pagamento, seja ela pelo boleto, cartão de crédito ou gerar QrCode;
 
* **Reembolsar produtos:** o cliente poderá solicitar o reembolso caso haja problemas com o produto em até 7 dias úteis;

* **Contatar o SAC:** o cliente poderá contatar o serviço de atendimento ao consumidor caso haja problemas ou dúvidas;


### Sistemas similares:

Criado em 2023 por Amanda Borges, Andressa Alypio, Anna Clara e Bruna Pinheiro em Rondônia, Brasil. É um site destinado a compra e venda de produtos de beleza e auto-cuidado, com preços acessíveis, fácil acesso e boa segurança. Com devolução gratuita e garantida caso o produto não seja o esperado pelo consumidor, além do diferencial que é o acesso do SAC digital podendo ser acessado com poucos cliques e contando apenas com uma pequena taxa fixa de entrega.

No cenário internacional e nacional encontram-se três sistemas que se destacam:

**Shein:** Site/App fundado em 2008 por Chris Xu em Nanquim, na China, é destinado a vendas de produtos variados com preços acessíveis e fornecedores do mundo inteiro, além de contar com sua própria marca de produção. 

**Shopee:** Site/App fundado em 2015 por Forrest Li em Singapura, na China, é destinado a vendas de produtos variados com preços acessíveis e fornecedores do mundo inteiro, porém as avaliações não são muito boas, além das taxas de envio com valores absurdos. 

**Amazon:** Site/App fundado em 1994 por Jeff Bezos, nos EUA, é uma empresa multinacional de tecnologia que contam com venda de produtos variados.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um aparelho com as seguintes configurações mínimas para que possam ter melhor desempenho do site:

* Internet com mais de 100mb 
* Navegador: Chorme e Opera (Desktop); Samsung Internet(Telefone/Celular)
* Windows 10 ou posterior
* Linux Ubuntu 18.04+ de 64 bits, Debian 10+, openSUSE 15.2+ ou Fedora Linux 32+
* Mac macOS High Sierra 10.13 ou mais recentes
* Processador Intel Pentium 4 ou posterior

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os clientes e empresas usuárias desse sistema possuem bastante experiência com aplicações desse tipo bem como a equipe de desenvolvimento. No entanto ainda se faz necessário um treinamento para a equipe, pois apesar de estarem acostumados com aplicações, essa em específico é novidade. O nosso sistema é de porte médio, com um nível médipo de complexidade devido às suas constantes atualizações e ao seu funcionamento em sim. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Após a análise realizada, foi chegada a conclusão de que o projeto tem um ótimo custo-benefício, pois como o sistemas vende produtos de empresas parceiras, não possui um custo alto para sua criação e implantação. Assim como possui um bom custo-benefício para os clientes, pois como é apenas um sistema, não tem custos físicos, conseguindo deixar os preços mais em conta do que em lojas fisícas.

## Viabilidade Organizacional

Do ponto de vista da equipe, o projeto é de baixo risco. A equipe num geral demonstra muito interesse e ânimo com a implantação do projeto. É esperado que a implantação do projeto seja aprovada visando a concorrência entre os sistemas, gerando mais variedade de sites deste tipo para os usuários.


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento
A metodologia adotada para o desenvolvimento do sistema foi o SCRUM, pois a equipe é pequena e o método SCRUM é o ideal para isso, já que possui uma maior facilidade de comunicação e se caso houver problemas serão resolvidos de forma mais eficiente, graças as sprints, também cabe relevar a boa convivência em equipe que os membros podem ter.

[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Cadastrar as empresas | O sistema deve possibilitar o cadastro das empresas parceiras para a venda dos seus produtos, tendo como requisitos de cadastro: nome_fantasia; cnpj; email; telefone |
|RF-002 | Cadastrar os produtos | O sistema deve possibilitar que as empresas cadastradas façam o cadastro dos seus respectivos produtos que serão vendidos, tendo como requisitos de cadastro: cód_produto; quant_produto; tipo_produt; desc_produto; valor_produt|
|RF-003 | Cadastrar o cliente | O sistema deve possibilitar o cadastro dos clientes, tendo como requisitos: nome; dat_nascimento; sexo; email; telefone; cpf; endereço|
|RF-004 | Realizar pré-seleção de produtos | O sistema deve possibilitar que o cliente selecione o que deseja comprar além de simular o valor final da compra|
|RF-005 | Escolher forma de pagamento | O sistema deve possibilitar que o cliente escolha a forma com a qual deseja realizar o pagamento|
|RF-006 | Cadastrar o cartão de crédito | O sistema deve possibilitar que o cliente cadastre o cartão de crédito que irá usar no pagamento|
|RF-007 | Gerar código de barra | O sistema deve gerar um código de barras, caso o usuário escolha boleto como forma de pagamento|
|RF-008 | Gerar QRCode | O sistema deve gerar um QRCode caso o cliente escolha pagar com pix|
|RF-009 | Cadastrar endereço de entrega | O sistema deve possibilitar que o cliente cadastre o endereço de entrega do produto comprado|
|RF-010 | Cadastrar transportadora | O sistema deve possibilitar que transportadoras façam o cadastro para poderem trabalhar juntamente com a empresa. Nome; cpf; cnpj; telefone; endereço.|
|RF-011 | Rastrear compras | O sistema deve possibilitar que as transportadoras disponibilizem a opção de rastrear a compra feita|
|RF-012 | Avaliar as compras | O sistema deve possibilitar que o cliente possa avaliar as compras feitas, com adição de fotos e etc.|
|RF-013 | Contatar o centro logístico | O sistema deve possibilitar que o cliente entre em contato com o centro logístico do site, para tirar dúvidas e afins|
|RF-014 | Pesquisar produtos | O sistema deve possibilitar que o cliente pesquise pelos produtos que deseja|
|RF-015 | Escolher Transportadora | O sistema deve possibilitar que o cliente selecione a transportadora desejada|
|RF-016 | Filtrar produtos | O sisterma de ser capaz de possibilitar a divisão de itens por categorias para que o cliente possa filtrar de acordo com seus desejos|
|RF-017 | Favoritar produtos | O sistema deve possibilitar a função de salvar produtos que o cliente selecione|
|RF-018 | Relatar vendas | O sistema deve possibilitar que as empresas que fazem parte do site, consigam ter um feedback das vendas feitas seja mensal, semanal e/ou anualmente|
|RF-019 | Vizualizar estoque de produtos | O sistema deve possibilitar a vizualização do estoque dos produtos|
|RF-020 | Reembolsar produtos | O sistema deve possibilitar que, caso o cliente tenha algum problema com a compra, possa pedir reembolso para a empresa|
|RF-021 | Cancelar produtos | O sistema deve permitir que o cliente possa cancelar a compra dos produtos|
|RNF-022 |Autenticar |Permite que o usuário coloque um email extra para caso perca o acesso do pincipal |
|RNF-023 |Escolher idiomas |Permite que o usuário escolha o idioma desejado para utilizar o sistema |

## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Logon |O usuário deve efetuar logon para realizar as operações do sistema |
|RNF-002 |Manutenção |O sistema deve ser fácil de manter e atualizar |
|RNF-003 |Tutorial de uso |O usuário deve ter a opção de um tutorial explicativo de como usar o sistema |
|RNF-004 |Áudio descrição |Possui a função de ativar áudio no sistema possibilitando que pessoas com deficiência visual e analfabetas possam usar com mais facilidade |
|RNF-005 |Libras |Possui a função de ativar um tradudor de libras permitindo que pessoas com deficiência auditiva usem o sistema com mais facilidade |
|RNF-006 |Atuação |O sistema deve ser capaz de lidar com vários usuários ao mesmo tempo sem travar ou ter erros em seu funcionamento |
|RNF-007 |Compatibilidade de navegadores |O sistema deve possuir uma variedade de navegadores compatíveis |
|RNF-008 |Interface simples |O sistema deve possuir uma interface intuitiva e de fácil utilização |
|RNF-009 |Disponibilidade de sistema |O sistema deve estar disponível para uso 24 horas por dia durante os 7 dias da semana, mas poderá ficar fora do ar caso ocorra alguma falha até que ela seja resolvida |
|RNF-010 |Conformidade |O sistema deve cumprir todas as leis e regulamentos aplicáveis (como não vazar informações pessoais) |
|RNF-011 |Configurar idiomas |Permite que o usuário escolha o idioma desejado para utilizar o sistema |

[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2023 por estudantes](https://www.figma.com/file/9Ojc2qDtJA0nDTYhS7BITO/Untitled?type=design&node-id=0%3A1&t=3JCGg8KzUmas9r3Q-1)
![Imagem do Protótipo](/img/afrodbeauty4.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso

<img src='/img/aaaaaaaaa.png' alt='logo da empresa' width='20000px' heidth='20000px'/>

## Descrição / Especificação dos Casos de Uso

### UC-01 - Realizar pré-seleção de produtos

|UC-01 - Realizar pré-seleção de produtos|           
|:---|
|**Descrição/Objetivo:** Permite a pré-seleção dos produtos|
|**Atores: Comprador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** O produto ficará salvo na aba carrinho de compras|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O comprador seleciona o produto desejado|
|2. O comprador clica no botão adicionar ao carrinho|
|3. O comprador seleciona a variação do produto e a quantidade|
|4. O produto fica salvo no carrinho de compras|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Produto em falta** |
|1. Uma mensagem será apresentada para o comprador, informando que o produto está indisponível no momento |
|**A2: Variação não selecionada** |
|1. Uma mensagem será inserida para o comprador, informando que não foi escolhida a variação|
|2. A tela será direcionada novamente para a escolha da variação|


## Matriz de Rastreabilidade


| REQUISITO |UC-Cadastrar os produtos|UC-Vizualizar estoque de produtos|UC-Pesquisar produtos|UC-Cadatrar o cliente|UC-Contatar o centro logístico|UC-Favoritar produtos|UC-Reembolsar produtos|UC-Relatar vendas|UC-Cadastrar as empresas|UC-Cancelar produtos|UC-Realizar pré-seleção de produtos|UC-Filtrar produtos|UC-Autenticar|UC-Escolher idiomas do sistema|UC-Gerar QRCode|UC-Gerar códigos de barras|UC-Cadastrar o cartão de crédito|UC-Escolher forma de pagamentos|UC-Cadastrar endereço de entrega|UC-Cadastrar transportadora|UC-Avaliar as compras|UC-Escolher transportadora|UC-Rastrear compras|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001| | | | | | | | |X| | | | | | | | | | | | | | |
|RF-002|X| | | | | | | | | | | | | | | | | | | | | | |
|RF-003| | | |X| | | | | | | | | | | | | | | | | | | |
|RF-004| | | | | | | | | | |X| | | | | | | | | | | | |
|RF-005| | | | | | | | | | | | | | | | | |X| | | | | |
|RF-006| | | | | | | | | | | | | | | | |X| | | | | | |
|RF-007| | | | | | | | | | | | | | | |X| | | | | | | |
|RF-008| | | | | | | | | | | | | | |X| | | | | | | | |
|RF-009| | | | | | | | | | | | | | | | | | |X| | | | |
|RF-010| | | | | | | | | | | | | | | | | | | |X| | | |
|RF-011| | | | | | | | | | | | | | | | | | | | | | |X|
|RF-012| | | | | | | | | | | | | | | | | | | | |X| | |
|RF-013| | | | |X| | | | | | | | | | | | | | | | | | |
|RF-014| | |X| | | | | | | | | | | | | | | | | | | | |
|RF-015| | | | | | | | | | | | | | | | | | | | | |X| |
|RF-016| | | | | | | | | | | |X| | | | | | | | | | | |
|RF-017| | | | | |X| | | | | | | | | | | | | | | | | |
|RF-018| | | | | | | |X| | | | | | | | | | | | | | | |
|RF-019| |X| | | | | | | | | | | | | | | | | | | | | |
|RF-020| | | | | | |X| | | | | | | | | | | | | | | | |
|RF-021| | | | | | | | | |X| | | | | | | | | | | | | |
|RF-022| | | | | | | | | | | | |X| | | | | | | | | | |
|RF-023| | | | | | | | | | | | | |X| | | | | | | | | |

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

<img src='/img/aaa.png' alt='logo da empresa'>

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

<img src='/img/Selecionar produtos.png' alt='diagrama de sequencia selecionar produto'>

<img src='/img/CadastrarEmpresa.png' alt='diagrama de sequencia cadastrar empresa'>

<img src='/img/cadastrarCartao.png' alt='diagrama de sequencia cadastrar cartão'>

<img src='/img/Grupo.png' alt='diagrama de sequencia cadastrar cliente'>

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)

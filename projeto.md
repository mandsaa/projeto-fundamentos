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
|**Vendedor:**|Empresas das quais estão cadastradas devem ter acesso para verificar seus produtos e as vendas realizadas|
|**Administrador:**|Responsável pela aprovação das compras e resolução de problemas dos mesmos|
|**SAC:**|O Serviço de Atendimento ao Consumidor deve estar habilitado para sanar as dúvidas dos clientes diretamente com um adm do sistema|

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
Os colaboradores da empresa contratante possuem bastante experiência com aplicações desta natureza, os analistas também estão familiarizados com esta área de aplicação comercial, porém o sistema utiliza uma tecnologia nova, com a qual os analistas e programadores não estão familiarizados. No que se refere ao tamanho do sistema, trata-se de um projeto de médio porte, com baixo nível de complexidade, que não será integrado a outros sistemas, limitando-se a atender a demanda da escola no que se refere à EaD, que, atualmente possui 1.000 alunos matriculados. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício, e, mesmo com estimativas conservadoras do retorno sobre o investimento e dos benefícios totais, este projeto é viável economicamente. Após a implantação, espera-se uma melhoria na qualidade dos serviços prestados e aumento da capacidade de vagas da unidade escolar.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto apresenta baixo risco. Os diretores e coordenadores da instituição demonstram forte interesse no projeto. Espera-se que os professores e alunos aprovem a implantação do sistema, visto que atualmente a escola não possui uma ferramenta específica para o controle das informações, o que está provocando enormes transtornos para a instituição.


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento


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
|RF-005 | Processar pagamentos | O sistema deve possibilitar que o cliente escolha a forma com a qual deseja realizar o pagamento|
|RF-006 | Cadastrar o cartão de crédito | O sistema deve possibilitar que o cliente cadastre o cartão de crédito que irá usar no pagamento|
|RF-007 | Gerar código de barra | O sistema deve gerar um código de barras, caso o usuário escolha boleto como forma de pagamento|
|RF-008 | Gerar QRCode | O sistema deve gerar um QRCode caso o cliente escolha pagar com pix|
|RF-009 | Cadastrar endereço de entrega | O sistema deve possibilitar que o cliente cadastre o endereço de entrega do produto comprado|
|RF-010 | Cadastrar transportadora | O sistema deve possibilitar que transportadoras façam o cadastro para poderem trabalhar juntamente com a empresa|
|RF-011 | Rastrear compras | O sistema deve possibilitar que as transportadoras disponibilizem a opção de rastrear a compra feita|
|RF-012 | Avaliar as compras | O sistema deve possibilitar que o cliente possa avaliar as compras feitas, com adição de fotos e etc.|
|RF-013 | Contatar o centro logístico | O sistema deve possibilitar que o cliente entre em contato com o centro logístico so site, para tirar dúvidas e afins|
|RF-014 | Pesquisar produtos | O sistema deve possibilitar que o cliente pesquise pelos produtos que deseja|
|RF-015 | Escolher Transportadora | O sistema deve possibilitar que o cliente selecione a transportadora desejada|
|RF-016 | Filtrar produtos | O sisterma de ser capaz de possibilitar a divisão de itens por categorias para que o cliente possa filtrar de acordo com seus desejos|
|RF-017 | Favoritar produtos | O sistema deve possibilitar a função de salvar produtos que o cliente selecione|
|RF-018 | Relatar vendas | O sistema deve possibilitar que as empresas que fazem parte do site, consigam ter um feedback das vendas feitas seja mensal, semanal e/ou anualmente|
|RF-019 | Vizualizar estoque de produtos | O sistema deve possibilitar a vizualização do estoque dos produtos|
|RF-020 | Reembolsar produtos | O sistema deve possibilitar que, caso o cliente tenha algum problema com a compra, possa pedir reembolso para a empresa|
|RF-021 | Cancelar produtos | O sistema deve permitir que o cliente possa cancelar a compra dos produtos|
|RNF-022 |Autenticação |Permite que o usuário coloque um email extra para caso perca o acesso do pincipal |
|RNF-023 |Configuração de idiomas |Permite que o usuário escolha o idioma desejado para utilizar o sistema |

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

[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2023 por estudantes](https://www.figma.com/file/9Ojc2qDtJA0nDTYhS7BITO/Untitled?type=design&node-id=0%3A1&t=3JCGg8KzUmas9r3Q-1)
![Imagem do Protótipo](/img/afrodbeauty4.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)

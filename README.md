# Analisando empresas da cidade do Recife

A análise dos dados das empresas ativas pode revelar informações sobre o atual cenário econômico da cidade, os setores que estão prosperando e as áreas onde essas empresas estão concentradas. Por outro lado, a análise das empresas inativas pode lançar luz sobre os desafios enfrentados pelas empresas e os setores que podem estar em declínio.

Nesta análise, irei explorar dois conjuntos de dados - um contendo informações sobre as empresas ativas e outro sobre as empresas inativas. Ao comparar e contrastar esses dois conjuntos de dados, podemos obter insights valiosos sobre o ambiente empresarial na cidade do Recife.

<center><img alt="Colaboratory logo" width="50%" src="https://raw.githubusercontent.com/ViniciusRaony/analisando-dados-empresas-recife/main/images/img_introducao.jpg"></center>

Através desta análise, espero contribuir para uma melhor compreensão do panorama empresarial na cidade do Recife.

**Neste *notebook*, irei analisar os dados referentes às empresas ativas e inativas da cidade do Recife, e ver quais insights podem ser extraídos a partir desses dados brutos.**

## Obtenção dos Dados

Todos os dados usados aqui foram obtidos a partir do site da Prefeitura do Recife, que consta [neste meu link](http://dados.recife.pe.gov.br/dataset/empresas-da-cidade-do-recife). 

Vale ressaltar que as informações sensíveis estão devidamente anonimizadas nos arquivos fornecidos.

## Análise Exploratória dos Dados - Informações

- O tratamento de dados foi realizado em Python e consta no arquivo .ipynb desse repositório;
- O dashboard será elaborado em Python ou Power Bi (TODO)

**Dicionário das variáveis**

* `cnpj` - Cadastro Nacional de Pessoas Jurídicas
* `cod_empresa` - Código da Empresa critptografado
* `razao_social` - Razão Social da Empresa
* `nome_fantasia` - Nome fantasia da Empresa
* `cod_logradouro` - Identifica as Vias de Circulação do espaço urbano do Recife
* `nome_logradouro` - Identifica as vias de Circulação
* `num_logradouro` - Número do Logradouro
* `cod_bairro` - Código do Bairro na base de empresas
* `nome_bairro` - Bairro da cidade do Recife
* `situacao_empresa` - Situação da empresa
* `data_inicio` - Data inicio da empresa
* `data_encerramento` - Data encerramento da empresa
* `cod_grupo` - Grupo ao qual pertence a atividade principal da empresa
* `nome_grupo` - Nome do grupo ao qual pertence a atividade principal da empresa
* `cnae` - Código Nacional de Atividade Econômica
* `desc_atividade` - Descrição da Atividade Econômica
* `atividade_principal` - É a principal atividade desempenhada pela empresa?
* `atividade_vig_sanitaria` - É a principal atividade da empresa que exige vigilância sanitária do município?
* `atividade_predominante` - É a principal atividade da empresa que é prestadora de serviço?
* `incomodo` - Atividade Potencialmente Geradora de Incômodo?
* `latitude` - coordenada da latitude da empresa
* `longitude` - coordenada da longitude da empresa

## TODO ##
Dashboard

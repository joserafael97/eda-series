# EDA de dados de temperatura e chuvas em um lugar


Análise exploratória dos registros de temperaturas máximas e mínimas e níveis de chuvas dos municípios de Campina Grande e João Pessoa durante o período de 01/01/1988 até os dias atuais. Os dados originais vem do Banco de Dados Meteorológicos para Ensino e Pesquisa [Banco de Dados Meteorológicos para Ensino e Pesquisa](http://www.inmet.gov.br/projetos/rede/pesquisa/)
 (BDMEP) que tem como objetivo apoiar as atividades de ensino e pesquisa e outras aplicações em meteorologia, hidrologia, recursos hídricos, saúde pública, meio ambiente, etc. 
 
Para obtenção dos dados utilizados é necessário a criação de uma conta em [http://www.inmet.gov.br/projetos/rede/pesquisa/cad_senha.php](http://www.inmet.gov.br/projetos/rede/pesquisa/cad_senha.php)

No BDMEP estão acessíveis os dados diários a partir de 1961 das estações para as quais se disponha, em forma digital, de pelo menos 80% dos dados que foram registrados naquele período. Os dados históricos referentes a períodos anteriores a 1961 ainda não estão em forma digital e, portanto, estão indisponíveis no BDMEP.

Em qualquer trabalho derivado deste, por favor cite a fonte original. 

## Dependências

Para instalação da depedência inmetr é necessário realizar o procedimento com a ferramenta devtools (anteriormente instalada), como é mostrado abaixo.
```
deps = c("tidyverse", "lubridate", " skimr","devtools")
install.packages(deps)
devtools::install_github('lhmet/inmetr')

```

## Organização

* `code` - Scripts para ingerir e transformar os dados brutos, e funções fatoradas de relatórios
* `data` - Dados depois de obtidos, organizados e transformados a partir da fonte original
* `reports` - Notebooks com análises


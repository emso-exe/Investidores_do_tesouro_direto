# 🔎 Análise de Investidores do Tesouro Direto 💰

Neste projeto serão analisados os dados de investidores (pessoas físicas) do tesouro direto que aderiram ao programa a partir de seu lançamento em janeiro de 2002. A análise será baseada em dados no formato CSV, acessíveis no portal de [Dados Abertos](https://www.tesourotransparente.gov.br/ckan/dataset) disponibilizados pelo [Tesouro Nacional Transparente](https://www.tesourotransparente.gov.br/).

O Tesouro Direto é um programa do Tesouro Nacional, desenvolvido em parceria com a B3 (antiga BM&F Bovespa), que permite a venda de títulos públicos federais diretamente para pessoas físicas via internet. O objetivo principal do programa é captar recursos para financiar a dívida pública, ao mesmo tempo em que oferece uma forma acessível de investimento, com valores mínimos baixos e liquidez diária.

## 🚨 Contexto do problema

Com o crescente interesse em investimentos, especialmente em tempos de volatilidade de mercado, o Tesouro Direto tem se tornado uma opção popular entre investidores de diferentes perfis. No entanto, compreender as características demográficas, regionais e comportamentais dos investidores é fundamental para otimizar estratégias de captação e retenção de investidores.

## 💼 Demanda do negócio

- Perfil demográfico dos investidores
- Padrões regionais de investimento
- Comportamento de Operação
- Impacto da profissão e idade
- Correlação entre situação da conta e perfil

## 📃 Compreensão dos dados

Os dados disponíveis incluem um arquivo em formato _CSV_ e um arquivo _PDF_ com o dicionário de dados. Para o projeto de análise de dados serão utilizados as informações dos investidores do período de 2002 a 2023. Esses dados foram extraídos do portal de [Dados Abertos](https://www.tesourotransparente.gov.br/ckan/dataset) disponibilizados pelo [Tesouro Nacional Transparente](https://www.tesourotransparente.gov.br/) sob o título "Investidores do Tesouro Direto". O conjunto de dados inclui informações detalhadas sobre os investidores cadastrados no programa, como data de adesão, profissão, cidade de residência, entre outros. Também há um indicador se o investidor está ou não ativo e outro que sinaliza se o investidor realizou operações nos últimos 12 meses. Cada investidor é identificado por um código único. Caso o investidor tenha cadastro em mais de uma instituição financeira, cada registro adicional é representado por uma nova linha, mantendo o mesmo código de investidor.

## 📓 Dicionário de dados

| Variáveis | Descrição | Domínios |
|------------------------------|------------------------------|------------------------------|
| Codigo do Investidor | Código identificador do investidor. | |
| Data de Adesao | Data de adesão ao programa Tesouro Direto.<br>A data “1900” é atribuída para as pessoas jurídicas cadastradas no Programa. | Calendário |
| Estado Civil | <br>Valor “Não se aplica” é atribuído para as instituições de caridade aptas a receber doações. | Solteiro(a), Desquitado(a), Viúvo(a), Divorciado(a), Casado(a) com brasileiro(a) nato(a), Casado(a) com brasileiro(a) naturalizado(a), Casado(a) com estrangeiro(a), União estável, Separado judic., Não se aplica; |
| Genero | <br>Valor “Não se aplica” é atribuído para as instituições de caridade aptas a receber doações. | M (Masculino), F (Feminino) ou N (Não se aplica) |
| Profissao | <br>Valor “Não se aplica” é atribuído para as instituições de caridade aptas a receber doações. | |
| Idade | <br>Registros com o valor “00*” apresentam erro no cadastro. | |
| UF do Investidor |  | |
| Cidade do Investidor |  | |
| Pais do Investidor |  | |
| Situacao da Conta |  | A (Ativo), D (Desativado). |
| Operou 12 Meses |  | S (Sim), N (Não). |

> fonte: [Investidores do Tesouro Direto - Metadados](https://www.tesourotransparente.gov.br/ckan/dataset/investidores-do-tesouro-direto/resource/9243a43c-31cd-4984-8129-55768fb780f5)

## 💻 Tecnologias

- Python
    - Biblioteca GC
    - Biblioteca Pandas
    - Biblioteca Matplotlib
    - Biblioteca Seaborn
    - Biblioteca Numpy
    - Biblioteca Warnings
    - Biblioteca Tabulate
    - Biblioteca Statistics
- Power BI

## 💳 Créditos

- [Estênio Mariano](https://github.com/emso-exe)

## 🔖 Licença

Licença MIT (MIT). Por favor leia o [arquivo da licença](LICENSE.md) para mais informações.
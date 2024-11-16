# Revisão Sistemática da Literatura (RSL) - Etapas e Resultados

Este repositório contém os dados e informações relacionados à revisão sistemática da literatura realizada como parte de uma dissertação. A revisão sistemática foi conduzida com base em critérios de inclusão e exclusão rigorosamente definidos para identificar artigos relevantes que utilizam dados de telefonia, especificamente **CDR (Call Detail Records)**, para a criação de uma base de caminhos e de origem-destino, aplicável a serviços de cidades inteligentes.

## Resumo
- Inicialmente, **189 artigos** foram identificados.
- Após uma triagem inicial, **96 artigos** foram excluídos por não atenderem aos critérios estabelecidos (como uso de tecnologias alternativas, por exemplo, GPS, Bluetooth ou Wi-Fi).
- Após a primeira triagem, **86 artigos** foram considerados relevantes para responder às perguntas de pesquisa.
- Após a terceira revisão, com a leitura integral dos artigos e a aplicação rigorosa dos critérios de inclusão e exclusão, a lista final foi consolidada, resultando em **72 artigos selecionados**.

---

## Estrutura do Repositório

### 1. Inicial - 189 Artigos
Nesta seção, estão listados os **189 artigos iniciais** recuperados com base nas estratégias de busca. Esses dados estão organizados em um arquivo **Excel** que contém:
- Título dos artigos
- Base de dados
- Autores
- Ano de publicação
- Critérios preliminares de inclusão/exclusão

> Arquivo disponível:[189artigos.xlsx](https://github.com/user-attachments/files/17787041/189artigos.xlsx)
.)

---

### 2. Artigos Excluídos - 96 Artigos
Após a triagem inicial, **96 artigos** foram excluídos por não atenderem aos critérios de inclusão. Os principais motivos de exclusão incluem:
- Uso de tecnologias diferentes de CDR, como GPS, Bluetooth ou Wi-Fi.
- Estudos não relacionados ao contexto de cidades inteligentes.

Os dados dessa exclusão estão documentados com os seguintes campos:
- Título dos artigos
- Base de dados
- Razão da exclusão

> Arquivo disponível: [ [96excluidosartigos.xlsx](https://github.com/user-attachments/files/17787044/96excluidosartigos.xlsx)


---

### 3. Filtragem - 86 Artigos
Após a aplicação dos **critérios de inclusão e exclusão**, **86 artigos** foram selecionados para análise detalhada. Os dados desta etapa incluem:
- Títulos e resumos dos artigos selecionados
- Base de dados e autores
- Relevância para as perguntas de pesquisa

> Arquivo disponível: [86_Artigos_Selecionados.xlsx]([86artigos.xlsx](https://github.com/user-attachments/files/17787048/86artigos.xlsx)
)

---

### 4. Lista Final - 72 Artigos
Na etapa final, com a leitura integral dos artigos e a aplicação rigorosa dos critérios, foram selecionados **72 artigos**. Esses artigos são considerados os mais relevantes para a pesquisa e estão documentados com os seguintes campos:
- Título completo
- Detalhes metodológicos
- Relevância para a construção de matrizes de origem-destino para serviços de cidades inteligentes

> Arquivo disponível: [72_Artigos_Selecionados.xlsx](./caminho/para/o/arquivo)

---

## Eixos da ISO 37122
A ISO 37122 foi utilizada para determinar os eixos nos quais os artigos analisados na RSL foram enquadrados. Abaixo, apresentamos a imagem ilustrando esses eixos:

<img width="608" alt="image" src="https://github.com/user-attachments/assets/0aaec2bc-ee57-41b3-975a-ff04d9e0939d">


Esses eixos incluem categorias como:
- Planejamento Urbano
- Transporte
- Telecomunicação
- Saúde
- Meio Ambiente
- Entre outros.

A categorização dos artigos baseou-se na relevância de cada estudo em relação aos indicadores definidos por essa norma.

---

## Queries Utilizadas nas Bases de Busca
As buscas foram realizadas em bases eletrônicas utilizando as seguintes strings de pesquisa:

```plaintext
(((“call detail record” OR “call detail records” OR “call details records” OR “calls details records”) 
AND (“smart city” OR “smart cities” OR “smart finance” OR “smart grid” OR “smart health” OR 
“smart housing” OR “smart logistics” OR “smart mobility” OR “smart payment” OR “smart tourism” 
OR “smart environment”))).

Web of science 

ALL=(("call detail record" OR "call detail records" OR "call details records" OR "calls details records" ) AND ("smart city" OR "smart cities" OR "smart finance" OR "smart grid" OR "smart health" OR "smart housing" OR "smart logistics" OR "smart mobility" OR "smart payment" OR "smart tourism" OR "smart environment"))

ACM


ALL=(("call detail record" OR "call detail records" OR "call details records" OR "calls details records" ) AND ("smart city" OR "smart cities" OR "smart finance" OR "smart grid" OR "smart health" OR "smart housing" OR "smart logistics" OR "smart mobility" OR "smart payment" OR "smart tourism" OR "smart environment"))

IEEE

((("call detail record" OR "call detail records" OR "call details records" OR "calls details records" ) AND ("smart city" OR "smart cities" OR "smart finance" OR "smart grid" OR "smart health" OR "smart housing" OR "smart logistics" OR "smart mobility" OR "smart payment" OR "smart tourism" OR "smart environment")))



SCOPUS


(("call detail record" OR "call detail records" OR "call details records" OR "calls details records" ) AND ("smart city" OR "smart cities" OR "smart finance" OR "smart grid" OR "smart health" OR "smart housing" OR "smart logistics" OR "smart mobility" OR "smart payment" OR "smart tourism" OR "smart environment")) AND ( LIMIT-TO ( PUBYEAR,2022) OR LIMIT-TO ( PUBYEAR,2021) OR LIMIT-TO ( PUBYEAR,2020) OR LIMIT-TO ( PUBYEAR,2019) )


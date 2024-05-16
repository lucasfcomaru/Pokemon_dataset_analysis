<img src="Imagens/banner-pokemon-dataset.png"/>

<p align="center">
  <img src="https://img.shields.io/github/repo-size/lucasfcomaru/Pokemon_dataset_analysis?style=for-the-badge" alt="Repo size" title="Repo size"/>
  <img src="https://img.shields.io/github/languages/count/lucasfcomaru/Pokemon_dataset_analysis?style=for-the-badge" alt="Language count" title="Language count"/>
  <img src="https://img.shields.io/github/forks/lucasfcomaru/Pokemon_dataset_analysis?style=for-the-badge" alt="Forks" title="Forks"/>
  <img src="https://img.shields.io/bitbucket/issues/lucasfcomaru/Pokemon_dataset_analysis?style=for-the-badge" alt="Open issues" title="Open issues"/>
  <img src="https://img.shields.io/bitbucket/pr-raw/lucasfcomaru/Pokemon_dataset_analysis?style=for-the-badge" alt="Open pull requests count" title="Open pull requests"/>
</p>

# Projeto de Análise de Dados de Pokémon utilizando Pandas
## Descrição do Projeto
### Objetivo
<p align="left">
  O objetivo deste projeto é explorar, limpar, analisar e visualizar dados de uma base de dados de Pokémon utilizando a biblioteca Pandas do Python. Através desta análise, pretendemos descobrir padrões, tendências e insights sobre as características dos Pokémon e algumas correlações. Este projeto será dividido em várias etapas, incluindo a preparação dos dados, análise exploratória, visualização e interpretação dos resultados.
</p>
<p align="left">
  O projeto tem caráter experimental e visa a prática do conhecimento.
</p>

## Ferramentas utilizadas
<ul>
  <li><b>Python:</b> Linguagem de programação principal.</li>
  <li><b>Pandas:</b> Biblioteca para manipulação e análise de dados.</li>
  <li><b>Matplotlib/Seaborn:</b> Bibliotecas para visualização de dados.</li>
  <li><b>Jupyter Notebook:</b> Ambiente interativo para desenvolvimento e apresentação do projeto</li>
</ul>

## Etapas do projeto
### Coleta e preparação dos dados
<ul>
  <li>Importação da base de dados de Pokémon (base de dados encontra-se dentro da pasta /Original.</li>
  <li>Limpeza dos dados: exclusão de colunas que não serão utlizadas. </li>
  <li>Estruturação dos dados para facilitar a análise:</li>
    <ul>
      <li>Tradução de todos valores para a língua portuguesa.</li>
      <li>Alteração de valores "0" e "1" para "False" e "True" na coluna "lendários.</li>
      <li>Criação das colunas "total atr" e "md atr" que são a soma e a média dos atributos respectivamente.</li>
    </ul>
  <li>Análise Exploratória dos Dados (EDA)</li>
</ul>

### Criação e visualização de Gráficos
<ul>
  <li>Histogramas para analisar a quantidade de pokémons por tipo.</li>
  <li>Gráficos de dispersão para analisar relações entre variáveis.</li>
  <li>Gráficos de barras para análises com tipos de pokemons e atributos (por exemplo, tipos de Pokémon mais forte).</li>
  <li>Interpretação dos Resultados.</li>
</ul>

<details>
  <summary><b>Gráficos</b> ⤵️</summary>
    <img src="Imagens/tipo_media_atributos.png" width="460" alt="Tipo de pokémon por média de atributos" title="Tipo de pokémon por média de atributos"/>
    <img src="Imagens/qtd_pokemon_tipo.png" width="460" alt="Quantidade de pokémons por tipo" title="Quantidade de pokémons por tipo"/>
    <img src="Imagens/ataque_defesa_tipo.png" width="460" alt="Ataque e defesa por tipo de pokémon" title="Ataque e defesa por tipo de pokémon"/>
    <img src="Imagens/relacao_peso_altura.png" width="460" alt="Relação entre peso e altura dos pokémons" title="Relação entre peso e altura dos pokémons"/>
    <img src="Imagens/relacao_atributos_captura.png" width="460" alt="Relação entre atributos e taxa de captura" title="Relação entre atributos e taxa de captura"/>
</details>

### Resumo das descobertas mais importantes

### Conclusão
<!--
Etapas do Projeto
Estatísticas descritivas: médias, medianas, distribuições e desvios padrão.
Análise de correlação entre diferentes variáveis (por exemplo, relação entre tipos de Pokémon e suas estatísticas de batalha).
Identificação de padrões e tendências gerais.
Visualização dos Dados

Discussão dos principais achados da análise exploratória e das visualizações.
Insights sobre a distribuição e características dos Pokémon.
Identificação de padrões interessantes, como quais tipos de Pokémon têm melhores estatísticas em geral.
Conclusões e Próximos Passos

Resumo das descobertas mais importantes.
Sugestões para análises futuras ou possíveis extensões do projeto, como a inclusão de novos dados (por exemplo, habilidades especiais ou dados de batalhas reais).
Exemplo de Análises Específicas
Distribuição de Tipos de Pokémon: Analisar quantos Pokémon existem de cada tipo e como esses tipos estão distribuídos.
Comparação de Estatísticas Base: Comparar as estatísticas base (HP, Ataque, Defesa, Velocidade, etc.) entre diferentes tipos de Pokémon.
Evolução dos Pokémon: Estudar como as estatísticas mudam quando os Pokémon evoluem.
Conclusão
Este projeto de análise de dados de Pokémon com Pandas permitirá uma compreensão profunda dos dados relacionados a essas criaturas icônicas, proporcionando insights valiosos tanto para fãs quanto para pesquisadores interessados em dados de jogos e suas aplicações. Utilizando as poderosas ferramentas de Pandas e outras bibliotecas Python, este projeto exemplifica como técnicas de análise de dados podem ser aplicadas a um conjunto de dados interessante e divertido.
-->

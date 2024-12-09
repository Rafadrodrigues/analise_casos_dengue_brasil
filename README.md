# Análise das notificação casos de dengue no Brasil

O vírus da dengue é transmitido pela picada da fêmea do Aedes aegypti, um mosquito que costuma picar durante o dia (no início da manhã ou no final da tarde) e se multiplica em locais onde tem água parada. Ele vive dentro das casas e ao redor de residências, 
é nesse tipo de lugar que o mosquito encontra condições ideais para se proliferar como em quintais e calçadas, por isso os cuidados precisam ser contínuos.

A base de dados utilizada no retirada na plataforma da **Kaggle** por Jadson Rafael por meio dessas informações busco realizar uma análise explanatória e colaborar na compreensão do quanto dessa doença que vem afetando grande parte da população brasileira.. 

Acesse a base de dados no link abaixo.
### [DENGUE CASE NOTIFICATION 2024-BR](https://www.kaggle.com/datasets/jadsonrafael/notificao-de-casos-de-dengue-2024-br)

A Kaggle é uma plataforma para aprendizado de ciência de dados. É também uma comunidade, a maior da internet, para assuntos relacionados com Data Science.
Hoje, contém mais de 536 mil membros ativos, com novas entradas todos os dias. O Kaggle se destaca por ser uma comunidade, mas também por apresentar competições premiadas, o que profissionaliza um pouco as práticas no site.
Em geral, apresenta tutoriais, competições, rankings, cursos, dicas, fóruns, datasets e muito mais. É um grande site com uma variedade de informações para quem precisa mergulhar de cabeça nesse mundo.

# Configurando o ambiente

Instalando um ambiente virtual

    pip install virtualenv

Criando seu ambiente virtual

    python3 -m venv venv

Ativando seu ambiente virtual

    source venv/bin/activate

Você pode desativá-lo executando:

    deactivate

Instalando todas as dependências

    pip install -r requirements.txt

Após essas etapas, você pode executar seu projeto usando o seguinte comando:

    jupyter lab

ou usando seu IDE favorito.

 # Observações realizadas 

Realizar análises é fundamental para compreender a dinâmica do surto, identificar padrões e nos aproximamos de possível solução. 

- Os municípios mais afetados foram os de **Minas Gerais**, com Belo Horizonte apresentando o **maior número de notificações** no estado.
- A região **Sudeste** registrou o **maior número de notificações**, destacando-se significativamente em relação às demais regiões do país.
- As **mulheres** foram mais afetadas, representando **54,5%** das notificações.
- O surto de casos atingiu seu pico em 22 de janeiro de 2024, com um total de **16.477 notificações em um único dia**.

Dentre essas notificações, foram realizadas análises adicionais presentes no arquivo main. 


 # Gráficos obtidos

Análise de notificações nas regiões do Brasil.
<div align="center">
<img src="https://github.com/Rafadrodrigues/analise_casos_dengue_brasil/assets/104935995/f2f523eb-d096-44e6-bb8b-c1f78fa2f21d"/ width="700px">
</div>

Análise de notificações nas municípios do Brasil.

  Esse gráfico representa as maiores notificações de caso de dengue por município. Estão listados os 10 maiores. Um fato, que os municípios presentes
  mais da maioria são da região sudeste.
<div align="center">
<img src="https://github.com/Rafadrodrigues/analise_casos_dengue_brasil/assets/104935995/164d29d6-797a-457e-894f-6ae178a74be4"/ width="700px">
</div>

Distribuição das notificações por gênero.

Por meio deste gráfico, identificamos que as mulheres são as mais infectadas. As mulheres representam mais de 50% das notificações.
<div align="center">
<img src="https://github.com/Rafadrodrigues/analise_casos_dengue_brasil/assets/104935995/feea20d8-7c83-406b-902a-4a47e1d0fa99"/ width="700px">
</div>

Crescimento nas notificações.

Por este gráfico observamos o crescimento das notificações de dengue, desde o seu primeiro dia, seu pico de notificações e sua baixa.
<div align="center">
<img src="https://github.com/Rafadrodrigues/analise_casos_dengue_brasil/assets/104935995/c2d9aaf0-3128-42e6-a326-01c91262fdf0"/ width="700px">
</div>

# Dashboard

Você também pode ter uma visualização uma versão gráfica desse projeto utilizando **Power Bi**, para visualizar acesse o link abaixo:

### [Dashboard casos de dengue](https://github.com/Rafadrodrigues/Dashboard_casos_de_dengue)


# Campus Explorer

Oferecer ao usuário uma forma mais interativa de se localizar pelos campus da UFPel, iniciando a implentação pelo campus Anglo.

Equipe:

- Gabriel Leite Bessa

- Yago Martins Pinto

## Funcionamento

O usuário poderá se deslocar em um mapa 3D possuindo nesse mapa ainda o nome de cada sala e alguns outros detalhes que possam ser interessantes, como saídas de emergência. Ao clicar no nome de uma sala especifica o usuário poderá consultar mais informações sobre aquela sala, como por exemplo, qual a lotação da sala, disponibilidade de projetores, etc, além de dados sobre os horário e aulas naquela sala.

Além de se deslocar pelo campus, o usuário poderá pesquisar por uma sala ou por uma disciplina em uma barra de pesquisa na tela.

## Tecnologias

- Javascript

- ThreeJs

- Blender

- GSLSLoader

## Componentes

- Tela: irá conter o modelo em 3d, uma barra para pesquisa e uma bussola para a orientação do usuário.

- Modelo: é obrigado a ter: pontos de referência para o usuário poder se localizar, as salas e locais de saída.

- Dados: irão conter as salas e uma pequena descrição a seu respeito.

## Esquema dos dados

Forma de armazenar os dados: os dados serão armazenados em um ou mais arquivos JSON, devendo se definir o esquema de organização dos dados.

## Pendências

- Realizar a modelagem por andar ou por de todo o campus? (Questões de desempenho)
# Descrição das funcionalidades #
## Introdução ##
Este documento visa apontar, brevemente, as funcionalidades que o sistema deverá ser capaz de fazer, bem como seus respectivos formulários.

## Detalhes ##
### Cadastros ###
  * Cadastro de Usuário;
  * Cadastro de cerveja: O usuário poderá cadastrar suas receitas;
  * Cadastro de estilos e suas características (apenas por adms);
  * Cadastro de insumos: o usuário poderá cadastrar um insumo que será aprovado pelos administradores. Os insumos correspondem a:
    * Lúpulos
    * Maltes/fermentáveis
    * Fermentos;
    * Agregados (temperos e etc)

### Cálculos ###
  * O sistema deverá ser capaz de fazer os cálculos de:
    * OG;
    * FG;
    * ABV;
    * ABW;
    * IBU;
    * SRM / EBC;
### Formulário de cadastro da cerveja ###
> O formulário de cadastro deve conter os seguintes campos (auto-preenchidos ou não):
  * Cabeçalho:
    * Usuário;
    * Estilo;
    * Tipo de receita (só grãos, só extrato e meio-a-meio);
  * Data;
    * Adicionar Maltes:
  * porcentagem do total de grãos;
  * Peso;
  * Nome do malte;
  * L°;
  * PPG;
    * Qtdade de litros;
    * Lúpulos:
  * Tipo do uso (fervura ou dryHop);
  * Tempo de fervura;
  * Peso;
  * Nome;
  * Forma (Flor, Pellet, plug);
  * Ácidos alpha;
    * Fermento:
  * Nome do fermento;
    * Agregados:
  * Tipo de uso (Fermentação, fervura, brassagem);
  * Tempo;
  * Peso/Quantidade;
  * Nome do agregado;
    * Notas gerais (Campo descritivo para o detalhamento dos insumos);
### Formulário de processo ###
    * Brassagem:
      * temperatura;
      * tempo;
    * Fermentação:
      * Cada item da lista:
      * Tipo (primaria, secundaria, primming);
      * Temperatura;
      * Tempo;
    * Notas gerais (Campo descritivo para o detalhamento do processo);
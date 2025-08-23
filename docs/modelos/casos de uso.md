# Modelo de Caso de Uso

* [Identificação de casos de uso de negócio por ator (cumprir metas do usuário)](#atores)
* [Descrição dos os casos de uso de forma resumida](#descrição-dos-casos-de-uso)
* [Descrição de 1 caso de uso crítico/mais importante do sistema de forma completa](#caso-de-uso-crítico)


## Atores

* Usuário: cidadão que utiliza o aplicativo para descartar resíduos corretamente.
* Administrador: responsável por manter o banco de dados atualizado (novos materiais, pontos de coleta, dicas).


## Casos de Uso por Ator

|Usuário|Administrador|
|-------|-------|
|Buscar material pelo nome|Cadastrar novo material no sistema|
|Consultar destino correto do resíduo|Atualizar informações de descarte|
|Ver lista de dicas rápidas de reciclagem|Cadastrar pontos de coleta|
|Localizar pontos de coleta próximos||

## Descrição dos Casos de uso 
* 1\. Buscar material: usuário digita o nome do material e o sistema retorna a categoria e forma de descarte.
* 2\. Consultar destino correto: usuário seleciona material e visualiza instruções detalhadas de descarte.
* 3\. Ver dicas rápidas: usuário acessa lista de orientações práticas sobre reciclagem.
* 4\. Localizar pontos de coleta: usuário consulta locais próximos para descartar determinado resíduo.

* 5\. Cadastrar material (admin): administrador insere novo material no banco de dados.
* 6\. Atualizar informações (admin): administrador edita dados de descarte existentes.
* 7\. Cadastrar ponto de coleta (admin): administrador registra local de descarte disponível.


## Caso de Uso Crítico

### Caso de Uso: Buscar material pelo nome

\- Ator principal: Usuário

\- Pré-condições: O aplicativo deve estar instalado e funcionando; banco de dados deve estar carregado.

\- Fluxo principal:

* 1\. Usuário abre o aplicativo.
* 2\. Usuário digita o nome do material (ex: “garrafa PET”).
* 3\. O sistema pesquisa no banco de dados.
* 4\. O sistema retorna: “Plástico, reciclável. Deve ser limpo e descartado em coleta seletiva.”

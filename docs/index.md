<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
# Sistema de Guia de Reciclagem e Descarte
</center></font>


**Conteúdo**

- [Autores](#autores)
- [Cenário de negócio](#cenário-de-negócio)
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)


# Autores

* Dayô Araujo
* Enzo Viana


# Cenário de negócio


## Descrição do Projeto

O ReciclaAqui é um aplicativo que classifica tipos de resíduos (reciclável, eletrônico, orgânico, etc.) 
e orienta o usuário sobre a forma correta de descarte. Além disso, oferece dicas rápidas de reciclagem e 
localiza pontos de coleta próximos.


## Problema ou oportunidade percebida

Muitas pessoas ainda descartam resíduos de forma incorreta, seja por falta de informação 
ou de acesso a pontos de coleta. Isso gera impactos ambientais, como poluição e acúmulo de 
lixo em locais inadequados.


## Razão para esta demanda

Um aplicativo que auxilie no descarte correto pode contribuir para a conscientização ambiental, 
reduzir danos ao meio ambiente e ainda ajudar municípios e empresas de coleta seletiva a organizarem 
melhor os processos.


## Clientes, usuários e demais impactados com o produto

* Usuários finais: cidadãos que desejam descartar resíduos de forma correta e consciente, tornando o processo de reciclagem mais prático.
* Clientes indiretos: prefeituras, órgãos ambientais, ONGs de sustentabilidade e cooperativas de reciclagem.
* Envolvidos/impactados: empresas de coleta seletiva, meio ambiente e sociedade em geral, que ganham com a redução da poluição e maior conscientização ambiental.


## Principais critérios de qualidade para o produto

* Usabilidade: interface intuitiva, acessivel e fácil de navegar, adequada para todos os perfis de usuário.
* Confiabilidade: informações precisas e atualizadas sobre tipos de resíduos e formas de descarte.
* Desempenho: respostas rápidas nas pesquisas e consultas dentro do aplicativo.
* Portabilidade: compatível com diferentes dispositivos e sistemas operacionais.
* Manutenibilidade: banco de dados flexível e facilmente atualizável
* Amplitude de materiais: o sistema deve conter um banco de dados abrangente com diversos tipos de resíduos recicláveis.

# Diagrama de Casos de Uso

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

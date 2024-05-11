# ChatBoT para abertura de chamados de TI
Criação de um ChatBot a ser adicionado a pagina do site da instituição em que trabalho para receber as reclamações dos usuarios referentes aos problemas de TI e auxiliar na abertura de chamados, ja classificando o chamado na categoria correta.

As categorias e o modo da IA responder forem ensinados com as tecnicas de Engenharia de Prompt utilizando o parametro de SYSTEM INSTRUCTIONS

o Proximo passo seria fazer a integração com o sistema de chamados, no nosso caso o GLPI, para que fosse possivel abrir o chamado por meio de API com o chamado que o ChatBot ja Categorizou

Não sou a area de desenvolvimento, então essa parte eu passo para nossa equipe de desenvolvedores, mas creio que nao seria complicado, ja que eles poderiam pedir ao chat que trouxesse as informaçoes do chamado, receber a resposta em JSON e tratar em outro codigo, para ficar no modelo que a API do GLPI necessita.

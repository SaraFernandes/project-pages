---
layout:     notebook
title:      Padrão arquitetural MVC
author:     Sara Fernandes
tags: 		  Postagens
subtitle:   Como funciona
category:  project1

notebookfilename: intro
visualworkflow: true
---

Em 1979, Trygve Reenskaug surgiu com uma nova arquitetura para o desenvolvimento de aplicações interativas. Em seu design, as aplicações foram divididas em três tipos de componentes: *models*, *views* e *controllers* - MVC.

De acordo com Truel em [12], o MVC  ́e compreendido como um padrão arquitetural que pode ser utilizado para representar e entender a comunicação existente entre os componentes de uma aplicação, seja para web, desktop ou dispositivos móveis. Esse padrão define claramente a separação de responsabilidades e a comunicação entre os componentes de uma aplicação.

![Description](http://sarafernandes.github.io/img/mvc.png)

O diagrama da figura acima ilustra como cada um dos componentes do padrão MVC interagem uns com os outros para atender a uma solicitação do usuário.

A camada de visualização *(View)* é responsável pela interface com o usuário e controla as entradas e saídas gráficas e textuais. O modelo *(Model)* controla o comportamento e os dados do domínio da aplicação respondendo as solicitações e instruções para mudar seu estado, além de conter as regras de negócio. O controle *(Controller)* controla as solicitações do usuário repassando as mesmas para o modelo ou para a visualização adequadamente. Essa divisão em camadas tem o objetivo de aumentar a flexibilidade e a reuso do códico.

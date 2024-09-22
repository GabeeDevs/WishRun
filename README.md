# Documentação do Software WishRun

## Analise de Hardware e Software

**Nome do Projeto**: WishRun 

**Versão**: 1.0.0

**Data**: 26/08/2024

**Autor(es)**: Gabriel Costa Ramos       **RA:** 62778   **Turma:** ADC 4NB

**Descrição**: O WishRun é um site que consiste em reconhecer programas ou até mesmo hardwares que possam ser compatíveis com o computador do usuário. Ele possui um banco de dados para administrar informações sobre jogos e outros softwares. O site tem uma aba para verificar a compatibilidade do PC do usuario e verifica se é compativel com a peça selecionada ou jogo desejado, caso não seja compatível, ele sugere peças para deixar o PC compatível com o software desejado.

---

## Índice

1. [Introdução](#introdução)
2. [Objetivos](#objetivos)
3. [Requisitos Funcionais](#requisitos-funcionais)
4. [Requisitos Não Funcionais](#requisitos-não-funcionais)
5. [Regras de Negócio](#regras-de-negócio)
6. [Requisitos de Usuário](#requisitos-de-usuário)
7. [Requisitos de Sistema](#requisitos-de-sistema)
8. [Tecnologias Utilizadas](#tecnologias-utilizadas)
10. [Uso](#uso)
13. [Contato](#contato)

---

## Introdução

O WishRun surge da necessidade de ajudar os usuários a encontrar jogos e softwares compatíveis com seus computadores, evitando frustrações e gastos desnecessários com upgrades. Com um banco de dados abrangente e uma interface intuitiva, o programa facilitará a vida dos usuários na busca por compatibilidade.

## Objetivos

- Criar um banco de dados com informações detalhadas sobre jogos e softwares, incluindo requisitos de hardware.
- Desenvolver um sistema de verificação de compatibilidade rápido e preciso.
- Oferecer sugestões de peças para upgrades, caso o PC não atenda aos requisitos mínimos.
- Fornecer uma experiência agradável e útil aos usuários.

## Requisitos Funcionais

1. **Cadastro de Jogos e Softwares**: O sistema deve permitir o cadastro de jogos e softwares, incluindo informações como nome, versão, requisitos mínimos de hardware e data de lançamento.
2. **Verificação de Compatibilidade**: O sistema deve permitir que o usuário informe as espeicficações do seu computador e receba um resultado sobre a compatibilidade com os jogos e softwares cadastrados.
3. **Sugestão de Upgrades**: Caso o computador do usuário não atenda aos requisitos mínimos de um jogo ou software, o sistema deve sugerir peças para upgrades, como processador, memória RAM, placa de vídeo e disco rígido.
4. **Pesquisa e Filtros**: O sistema deve permitir que os usuários pesquisem por jogos e softwares específicos, além de filtrar os resultados por requisitos de hardware, data de lançamento e compatibilidade.
5. **Notificações de Lançamentos e Atualizações**: O sistema deve enviar notificações aos usuários sobre novos lançamentos de jogos e softwares, bem como atualizações que possam afetar a compatibilidade.

## Requisitos Não Funcionais

1. **Usabilidade**: A interface do sistema deve ser intuitiva e fácil de usar, permitindo que usuários de todas as idades e níveis de experiência possam navegar e utilizar todas as funcionalidades sem problema algum.
2. **Escalabilidade**: O sistema deve ser escalável para suportar um grande número de jogos, softwares e usuários cadastrados, sem perda de desempenho.
3. **Disponibilidade**: O sistema deve estar disponível 99,9% do tempo, garantindo que os usuários possam acessá-lo sempre que necessário.
4. **Confiabilidade**: O sistema deve garantir que as informações fornecidas sobre compatibilidade e sugestões de upgrades sejam precisas e confiáveis, minimizando erros e inconsistências.

## Regras de Negócio

1. **RN001**: Apenas usuários cadastrados poderão sugerir novos jogos e softwares para serem adicionados ao banco de dados.
2. **RN002**: O sistema deve ser capaz de identificar e atualizar automaticamente as informações sobre novos lançamentos e atualizações de jogos e softwares.

## Requisitos de Usuário

1. **RU001**: O usuário deve ser capaz de criar uma conta e fazer login no sistema.
2. **RU002**: O usuário deve poder informar as especificações do seu computador, incluindo processador, memória RAM, placa de vídeo e disco rígido.
3. **RU003**: O usuário deve poder pesquisar por jogos e softwares específicos e filtrar os resultados por requisitos de hardware, data de lançamento e compatibilidade.
4. **RU004**: O usuário deve poder receber notificações sobre novos lançamentos e atualizações de jogos e softwares.

## Requisitos de Sistema

1. **RS001**: O sistema deve utilizar um banco de dados relacional para armazenar informações sobre jogos, softwares e usuários.
2. **RS002**: O sistema deve ser compatível com os principais navegadores web e dispositivos móveis.
3. **RS003**: O sistema deve ter um mecanismo de busca eficiente para permitir pesquisas rápidas e precisas.
4. **RS004**: O sistema deve ter um sistema de notificações eficaz para enviar atualizações aos usuários.

## Tecnologias Utilizadas

- Linguagem de Programação: JavaScript
- Banco de Dados: MySQL
- Biblioteca de Visualização: D3.js


## Uso

1. Acesse o site do WishRun em seu navegador.
2. Informe as especificações do seu computador.
3. Pesquise por jogos e softwares ou use os filtros para encontrar o que você precisa.
4. Verifique a compatibilidade e, se necessário, receba sugestões de upgrades.
5. Caso deseje realizar Review o usuario terá que se cadastrar no site

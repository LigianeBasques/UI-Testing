# UI-Testing # 
 
## 👀Visão Geral👀 ##
Esse desafio foi proposto pela empresa **BeTalent**, o objetivo é avaliar conhecimentos e habilidades em teste de software. Testar  plataforma de e-commerce Sauce Demo (https://www.saucedemo.com).

# 💡Plano de testes- Sauce Demo💡 #
O plano de testes para a plataforma de e-commerce Sauce Demo detalha: os objetivos, o escopo, a abordagem e os recursos necessários para validar as funcionalidades do sistema, garantindo que a experiência dos usuários seja funcional e acessível.

___
<p><b>Código da Demanda</b>: 001<p/>
<p><b>Nome do Projeto</b>: Sauce Demo <p/>
<p><b>Autor(a) da Documentação</b>: Ligiane Basques<p/>
<p><b>Contato</b>: ligianealzie25@gmail.com<p/>
<p><b>Data Início</b>: 21/11/2024 <b>Data Fim</b>: 22/11/2024 <p/>
  
___

### Histórico de Versões ###

| Data | Nr Versão | Autor(a) | Descrição |
|----------|----------|----------|----------|
| 21/11/2024  | 1.0  | Ligiane Basques| Versão inicial do documento |
|  |   |  |  |
|  |  |  |  |

### 1-Visão Geral do Projeto ### 

A Sauce Demo é uma aplicação web fictícia de e-commerce. Ela simula cenários reais de loja virtual, como login, navegação, carrinho e checkout.

### 2- Declaração de Escopo ### 
| O escopo de teste cobre | O escopo de teste não cobre|
|----------|----------|
| Login com diferentes tipos de usuários disponíveis     | Teste Unitários serão executados pela equipe de desenvolvimento |
|Ordenação e filtragem de produtos  | Testes que fogem do escopo da demanda  |
| Remoção de itens do carrinho    |  |
|Navegação entre páginas   |   |
|Logout  |   |

### 3- Cronograma ### 

![Cronograma](https://imgur.com/tqaKZaC.png)

### 4- Abordagem de testes ### 
**4.1 Tipos de testes**

![Tipos de Testes](https://imgur.com/G8p6MFg.png)

### 5 - Estratégias de testes ### 
<li> Os testes serão realizados com foco em cobertura funcional das telas 
e navegabilidade, validando se todas as interfaces e páginas 
interagem  </li>
<li>A abordagem será funcional e de usabilidade, com base no mapa de cobertura gerado 
na análise do processo de testes, validando a implementação e fluxo 
das interfaces descritas no documento. </li>
<li>As evidências dos testes serão coletadas por meio de imagens e 
armazenadas no Google Drive conforme os cenários de teste 
executados.</li>
<li>Cada falha ou defeito encontrado será registrado com uma captura de 
tela associada ao defeito identificado.</li>
<li> Os defeitos  serão classificados de acordo com as prioridades e severidades definidas no 
plano de testes. </li>

### 6- Relatório de Defeitos ### 
O relatório de defeitos será compartilhado com todos os envolvidos em 
formato Excel e também ficará disponível o link no GitHub 

### 7- Gerencimanento de Defeitos ###
**7.1 Prioridade**

![Prioridade](https://imgur.com/YY71mqz.png)


**7.2 Severidade**

![Seceridade](https://imgur.com/OWnN6DY.png)


### 8- Recursos (Hardware/Software) ### 
| Hardware  | Software |
|----------|----------|
| Dispositivos Desktop   | Windows 10  para desktops.  |


# 📝Mapa de cobertura📝 #
Foi elaborado o mapa de cobertura para plataforma de e-commerce Sauce Demo, o qual representa a abrangência do testes que serão realizados no projeto. 

## Planilha com mapa de cobertura ##

<li> <a href="https://docs.google.com/spreadsheets/d/1ZiphIcookPwWGA1dLhf9TdA0ykQh3b3dJ4S_1XGLxdU/edit?usp=sharing" rel=nofollow>MAPA DE COBERTURA</a><//li>

# ⚠️Mapa de risco⚠️ #
Foi elaborado o mapa de risco para plataforma de e-commerce Sauce Demo, o qual avalia e prioriza riscos e suas probabilidades e impactos. Seu objetivo é facilitar a tomada de decisões e direcionar ações corretivas para áreas críticas.

## Planilha com mapa de risco ##
 
<li> <a href="https://docs.google.com/spreadsheets/d/1-2bA3fBWhi5dH2-OyNnykfpRDMCkjNby4eYjS09m8A8/edit?usp=sharing" rel=nofollow>MAPA DE RISCO</a><//li>

# 🏷️Roteiro de testes🏷️ #
Foi elaborado o roteiro de testes, nesse roteiro é detalhado: os cenários, casos de testes, os passos, ações, dados de entrada, condições de teste, resultados esperados e pré-requisitos necessários para executar testes  do sistema.

## Planilha com roteiro de testes ##
<li> <a href="https://docs.google.com/spreadsheets/d/1vGz83cxkfXRLcjjJrLvunO-IOrx_BmCfLZbAnggcCys/edit?usp=sharing" rel=nofollow>ROTEIRO DE TESTES</a><//li>

## 🐞BUGS encontrados🐞 ##
## Planilha com relatório de bugs ##
**Através do relatório de bugs, você pode usar os filtros para gerenciar a quantidade, status, severidade e prioridade dos bugs. Foi aplicado nessa planilha filtros**
<li> <a href="https://docs.google.com/spreadsheets/d/1DTmUYXzHShtqkni2SNJEd_hmfyJNmcDSLR02wjHlxC4/edit?usp=drive_link" rel=nofollow>RELATÓRIO DE BUGS</a><//li>


## 🚀Sugestões de melhorias de UX/UI (ME)🚀 ## 
| ID | Melhorias |
| ------------- | ------------- |
| ME-01 | Melhorar a experiência de login: Adicione uma dica (placeholder) nos campos de usuário e senha, informando valores de exemplo para facilitar a experiência do usuário
| ME-02 | Página de erro personalizada: poderia crie mensagens de erro mais informativas e amigáveis (ex:"Usuário ou senha inválidos. Tente novamente").
| ME-03 | Confirmação de ações: no processo de compras exiba mensagens claras de confirmação (ex: "Produto adicionado ao carrinho com sucesso!").
| ME-04 | Poderia ter uma campo de pesquisa para os produtos e organizados por categoria.
| ME-05 | Poderia ter um botão de favoritar produtos
| ME-06 | Poderia ter um campo para feedbacks do usuário que compraram produtos, ex: campo para adicionar as estrelas e relatar a experiência com aquele produto
| ME-07 | Poderia ter campos para escolha de tipos de pagamento: cartão, boleto ou pix
| ME-08 | Texto alternativo: Adicionar descrições precisas a imagens e ícones.
| ME-09 | Tipografia e botões uniformes: fontes consistentes para garantir tamanhos de botão uniformes para evitar distrações visuais.
| ME-10 | Paleta de cores: Atualizar o esquema de cores para torná-lo mais moderno e engajador. Considerando os tons mais suaves para melhorar a experiência visual.
| ME-11 | Poderia colocar um campo para que o usuário selecionasse o tipo de envio, ex: sedex, PAC 
| ME-12 | Poderia colocar um campo para que o usuário cancelasse um pedido após realizar o processo de compra


## 💻Testes de responsividade💻 ##
<li>Ferramenta utilizada para o teste: <b>Responsive Viewe extensão do google chrome</b></li>
<li>Navegador: <b>Google chrome: versão 131.0.6778.71</b> </li>
<li>Sistema operacional: <b>Windows 10 desktop</b></li>
<li>Sistema operacional mobile: <b>Android 15</b> </li>
<li>Resolução mobile: <b>393x852</b> </li>
<li>Aparelho mobile: <b>Samsung A14</b> </li>
<li>Tablet: <b>Galaxy Tab S7 </b> </li>
<li>Resolução Tablet: <b>526 x 842 </b> </li>

## Mobile ##

| ![Imagem 1](https://imgur.com/Y82zKL9.png/150) | ![Imagem 2](https://imgur.com/Y4CFuyY.gif/150) | ![Imagem 3](https://imgur.com/yNWQcuY.gif/150) | ![Imagem 4](https://imgur.com/OLQdmpa.gif/150) |
|---------------------------------------------|---------------------------------------------|---------------------------------------------|---------------------------------------------|
| Tela de Login                    | Tela de produtos                    | Tela de checkout                      | Tela de finalização da compra                     |


## Tablet ##

| ![Imagem 1](https://imgur.com/bMqqS6T.gif/150) |
|---------------------------------------------|
| Fluxo de compra completo                       |



# Escola DNC

Este projeto é uma página da web para promover um curso gratuito de Introdução à Tecnologia da DNC School. A página apresenta informações sobre o curso, um vídeo explicativo, depoimentos de alunos e um formulário de inscrição.

## Estrutura do Projeto

O projeto é composto por dois arquivos principais:

1. **HTML**: Define a estrutura da página.
2. **CSS**: Estiliza a página para uma melhor apresentação.
3. **JavaScript**: Implementa a lógica de interação, como a rolagem dos depoimentos.

## Funcionalidades

### 1. Menu Superior
- O menu superior contém o logotipo da escola e um título que convida os usuários a se inscreverem no curso.

### 2. Informações do Curso
- A seção informacional apresenta três ícones com informações sobre o curso:
  - Certificado de conclusão
  - Duração do curso (4 horas de conteúdo)
  - Aulas online gravadas

### 3. Seção de Vídeo
- Um vídeo do YouTube é incorporado, apresentando a escola e o curso.
- Abaixo do vídeo, há um título e uma descrição que explicam o que os alunos aprenderão.

### 4. Carrossel de Depoimentos
- Um carrossel apresenta depoimentos de alunos. Os usuários podem navegar entre os depoimentos usando setas para a esquerda e para a direita.

### 5. Formulário de Inscrição
- Um formulário permite que os usuários se inscrevam no curso, coletando informações como nome, e-mail e telefone.
- O formulário é enviado para uma API externa para processamento.

## Estrutura HTML

A estrutura HTML é organizada da seguinte forma:

- **Menu Superior**: Contém o logotipo e informações sobre o curso.
- **Menu Informacional**: Apresenta ícones e descrições sobre o curso.
- **Seção do Vídeo**: Incorpora um vídeo do YouTube e informações adicionais.
- **Seção Carrossel**: Exibe depoimentos de alunos.
- **Seção de Formulário**: Um formulário para inscrição no curso.

## Estilo CSS

O CSS aplicado ao projeto proporciona uma aparência moderna e responsiva. Algumas características incluem:

- **Fonte**: Utiliza a fonte "Inter" para uma leitura clara.
- **Cores**: O fundo e os elementos são estilizados com cores que contrastam bem, como azul e cinza claro.
- **Botões**: Os botões têm um efeito de hover que melhora a interatividade.

## Lógica JavaScript

A lógica do projeto é implementada em um arquivo JavaScript separado. As principais funções incluem:

- **rolarParaDireita**: Exibe o depoimento de Bruna e oculta o de Leonardo.
- **rolarParaEsquerda**: Exibe o depoimento de Leonardo e oculta o de Bruna.

## Como Usar

1. Abra o arquivo HTML em um navegador.
2. Navegue pelas seções para conhecer o curso.
3. Assista ao vídeo para entender melhor o que é oferecido.
4. Use as setas no carrossel para ver os depoimentos dos alunos.
5. Preencha o formulário para se inscrever no curso.

## Conclusão

Esta página da web é uma aplicação simples, mas eficaz, que demonstra como apresentar informações de forma clara e interativa. É uma boa base para quem deseja aprender mais sobre desenvolvimento web e design de interfaces.
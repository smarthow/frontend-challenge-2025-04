# 🧪 Desafio Técnico – Desenvolvedor Front-end

## Visão geral

Este desafio consiste em construir uma aplicação front-end que consome a [Random User API](https://randomuser.me/) para exibir uma lista de usuários em **formato de tabela paginada**, com **busca por nome** e uma **página de perfil individual** para cada usuário. O objetivo é avaliar suas habilidades com Next.js 14, React Query, TypeScript e Tailwind CSS.

> ⚠️ **É importante que o seu repo esteja público, caso contrário não iremos conseguir avaliar sua resposta**

---

## Contexto
O desafio será implementar uma listagem de usuários, que ao clicar em um usuário abre o perfil do mesmo. Será um bônus favoritar o usuário e listar o usuários favoritados.

> Obs: As imagens a seguir são ilustrativas, e podem ou não ser seguidas. Sinta-se à vontade para usar sua criatividade.

### Listagem de Usuários
![image](https://github.com/user-attachments/assets/9dbb1f8f-5466-43fb-8486-83e47adf97f7)

### Perfil de Usuário
![image](https://github.com/user-attachments/assets/3d5b6c14-9c27-4c58-9e67-733e4c99f6d1)


---

## Requisitos

### Tecnologias obrigatórias

- Next.js 14.x (App Router)
- TypeScript
- Tailwind CSS
- React Query (TanStack Query)
- Axios

### Funcionalidades obrigatórias

- Listagem paginada de usuários:
  - Colunas: Foto, Nome completo, Email, País, Data de nascimento (`dd/mm/yyyy`)
  - Paginação com Dropdown para selecionar 5 ou 10 itens por página
- Campo de busca por nome
- Página de perfil individual para cada usuário com as seguintes informações:
  - Imagem
  - Nome completo
  - Email
  - Localização (cidade, estado, país)
  - Telefone
  - Data de nascimento + idade
  - Mostrar quantos dias se passaram desde o último aniversário do usuário
    - Ex. 1: "5 days"
    - Ex. 2: "3 months"

---

## Diferenciais (bônus)
Estes itens não são obrigatórios, mas contarão como ponto positivo:
- Internacionalização
- Testes
- Deploy na Vercel
- Página de "Favoritos", onde os usuários salvos em localStorage aparecem mesmo após nova chamada à API

---

## Critérios de Avaliação
Além dos requisitos levantados acima, iremos considerar os seguintes critérios durante a avaliação do desafio:
- Gerenciamento de estado
- Componentização
- Responsividade
- Preocupação com usabilidade
- Preocupação com acessibilidade
- Padrões de código
- Padrão de commits

---

O desafio acima foi construído para propósitos de avaliação apenas. Já possuimos funcionalidades similares na nossa plataforma.

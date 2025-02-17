
# Blog

Um projeto de blog moderno e responsivo desenvolvido com React e Firebase. Este aplicativo permite a visualização, navegação e leitura de posts, utilizando o Firebase para gerenciamento de dados (como Firestore para armazenar os posts, Firebase Authentication para autenticação de usuários, etc.)


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env

VITE_FIREBASE_API_KEY=`your_firebase_api_key`

VITE_FIREBASE_AUTH_DOMAIN=`your_firebase_auth_domain`

VITE_FIREBASE_PROJECT_ID=`your_firebase_project_id`

VITE_FIREBASE_STORAGE_BUCKET=`your_firebase_storage_bucket`

VITE_FIREBASE_MESSAGING_SENDER_ID=`your_firebase_messaging_sender_id`

VITE_FIREBASE_APP_ID=`your_firebase_app_id`



## Funcionalidades

- **Criação de Posts:** Usuários autenticados podem criar novos posts e publicá-los no blog.
- **Modificação de Posts:** Permite a edição de posts já publicados, garantindo que o conteúdo possa ser atualizado facilmente.
- **Exclusão de Posts:** Usuários autenticados podem excluir posts que não são mais relevantes.
- **Listagem de Posts:** Exibe uma lista de posts publicados, permitindo que os usuários naveguem facilmente pelo conteúdo.
- **Visualização Detalhada:** Cada post possui uma página dedicada para a leitura completa, com detalhes e informações adicionais.
- **Autenticação com Firebase:** Implementa login e cadastro de usuários utilizando o Firebase Authentication, garantindo acesso seguro às funcionalidades restritas.
- **Gerenciamento de Dados em Tempo Real:** Utiliza o Firebase Firestore para armazenamento e recuperação dos posts, permitindo atualizações em tempo real.
- **Responsividade:** Design adaptado para dispositivos móveis e desktops, proporcionando uma ótima experiência de uso em qualquer tela.
- **Integração com Variáveis de Ambiente:** Configuração simplificada do projeto através de variáveis de ambiente, facilitando a personalização e segurança das chaves de API.


**Front-end:**
- React: Biblioteca para construção de interfaces interativas
- React Router DOM: Gerenciamento de rotas para navegação
  
**Back-end:**
- Firebase: Plataforma completa para backend, utilizada para várias funções
  - Firestore: Banco de dados NoSQL em tempo real
  - Authentication: Sistema de autenticação para segurança de usuários

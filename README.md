Navigation Between Screens - Navegação entre Telas com Jetpack Compose

Este projeto foi desenvolvido como forma de prática para entender melhor como funciona a navegação em aplicativos Android utilizando Jetpack Compose e a biblioteca Navigation Compose.

Descrição

A aplicação simula um fluxo básico de uso, parecido com o que encontramos em muitos aplicativos. O usuário começa na tela de login, acessa um menu principal e, a partir dalí, pode navegar para outras áreas, como "Perfil" e "Pedidos", podendo voltar ao menu sempre que quiser.

A proposta do projeto é focada no aprendizado da navegação dentro do Compose, explorando o uso de componentes como NavController e NavHost, além da definição de rotas e da transição entre diferentes telas.

Fluxo de navegação

Login - Menu - Pedidos / Perfil

O fluxo se inicia na tela de login, segue para o menu principal e permite a navegação entre as demais telas. Ao escolher a opção de sair, o usuário retorna para a tela inicial.

Tecnologias utilizadas

Kotlin — linguagem base do projeto
Jetpack Compose — utilizado para construção da interface
Navigation Compose — utilizado para controle de navegação
Material 3 — utilizado para os componentes visuais
Android SDK 36 / mínimo SDK 24 (Android 7.0 ou superior)

Aprendizados

Implementação de navegação utilizando NavHost e rememberNavController
Definição de rotas com composable
Uso do navController.navigate para troca de telas
Uso do popBackStack para retorno na navegação
Compartilhamento do NavController entre telas
Organização do projeto separando as telas em diferentes arquivos

Estrutura do projeto

app/src/main/java/gustavobifon/com/github/navigation/

MainActivity.kt
screens/
LoginScreen.kt
MenuScreen.kt
PedidosScreen.kt
PerfilScreen.kt

Como executar

Fazer o clone do repositório
Abrir no Android Studio
Aguardar o carregamento das dependências
Executar em um dispositivo ou emulador com Android 7.0 ou superior

Gustavo Bifon — projeto desenvolvido para fins de prática e aprendizado

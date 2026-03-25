# Navigation Compose - Checkpoint 1

## Descrição do Projeto

Este projeto é uma continuação do que foi desenvolvido na atividade anterior, aplicando conceitos de navegação entre telas utilizando **Jetpack Compose Navigation**, com foco na passagem de parâmetros entre telas.

O projeto demonstra domínio técnico e entendimento do código existente, expandindo-o de forma consistente e documentada a cada commit.

---

## Objetivo

Complementar o projeto implementando as seguintes evoluções:

1. Passagem de parâmetros obrigatórios na tela de Perfil
2. Passagem de parâmetros opcionais na tela de Pedidos
3. Inserção de valor em parâmetro opcional
4. Passagem de múltiplos parâmetros entre telas

---

## Histórico de Commits

### Primeiro Commit — Passagem de parâmetros obrigatórios na tela de Perfil
A tela de perfil deixou de ser estática e passou a receber o nome como parâmetro, permitindo exibir um perfil personalizado. A navegação do menu foi atualizada para já passar o nome ao abrir essa tela, e a rota foi configurada para aceitar esse dado, usando um valor padrão caso nenhum nome seja enviado.

### Segundo Commit — Passagem de parâmetros opcionais na tela de Pedidos
A tela de pedidos passou a receber o cliente como parâmetro e exibi-lo na tela. Foi adicionado um import necessário para lidar com argumentos na rota, e a rota de pedidos foi configurada para aceitar o cliente com um valor padrão caso ele não seja informado. A chamada da tela de perfil também foi reorganizada.

### Terceiro Commit — Inserção de valor em parâmetro opcional
A navegação do menu foi atualizada para abrir a tela de pedidos já passando um cliente específico.

### Quarto Commit — Passagem de múltiplos parâmetros entre telas
A tela de perfil passou a receber também a idade como parâmetro, e o texto foi atualizado para exibir essa informação junto ao nome. A navegação do menu foi ajustada para passar tanto o nome quanto a idade. Foi adicionado um import para suporte a tipos nos argumentos, a chamada da tela de pedidos foi reorganizada, e a rota do perfil foi reconfigurada para receber os dois dados, definindo nome como texto e idade como número.

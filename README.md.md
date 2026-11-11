# Projeto: Gerenciador de Tarefas CLI

## Nome da aplicação
Mini Sistema CRUD com Java - Gerenciador de Tarefas

## Descrição das funcionalidades
Esta aplicação é um sistema de linha de comandos (CLI) que permite gerir tarefas do dia a dia em memória (sem banco de dados). O sistema contempla as seguintes funcionalidades de CRUD básico:
- **Criar (Create):** Inserção de novas tarefas exigindo um título obrigatório (validação básica).
- **Ler (Read):** Listagem de todas as tarefas inseridas, mostrando o seu estado (Pendente/Concluída).
- **Atualizar (Update):** Permite alterar o estado de uma tarefa (marcar como concluída) ou editar o seu título e descrição originais.
- **Eliminar (Delete):** Remove uma tarefa da lista através do seu ID.

O sistema utiliza os pilares de Programação Orientada a Objetos, com encapsulamento e herança (a classe `Tarefa` herda da classe base `Item`).

## Como executar o projeto (passo a passo simples)

1. Certifique-se de que tem o Java Development Kit (JDK) instalado no seu computador.
2. Crie uma pasta para o projeto e, dentro dela, crie a estrutura de pastas correspondente aos pacotes:
   - `src/modelo/`
   - `src/principal/`
3. Guarde os ficheiros `Item.java` e `Tarefa.java` na pasta `modelo`.
4. Guarde o ficheiro `Main.java` na pasta `principal`.
5. Abra o terminal (linha de comandos) e navegue até à pasta raiz `src`.
6. Compile todo o código executando o seguinte comando:
   `javac modelo/*.java principal/Main.java`
7. Execute o programa principal com o comando:
   `java principal.Main`
8. O menu principal irá aparecer no ecrã. Siga as instruções e navegue introduzindo os números das opções. Digite `0` para finalizar o programa.
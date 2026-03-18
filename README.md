# TarefasApp - s4Aula2

Este é um projeto simples de lista de tarefas (To-Do List) desenvolvido como parte da disciplina de Desenvolvimento Android. O aplicativo demonstra o uso de componentes fundamentais do Android, como `RecyclerView`, `Intents` para comunicação entre atividades e o padrão `Adapter`.

## 🚀 Funcionalidades

*   **Visualização de Tarefas:** Exibe uma lista de tarefas pré-definidas e adicionadas pelo usuário.
*   **Adição de Tarefas:** Permite ao usuário inserir novas tarefas através de uma tela dedicada.
*   **Comunicação entre Activities:** Utiliza `ActivityResultLauncher` para retornar a nova tarefa da tela de cadastro para a tela principal.
*   **Interface Moderna:** Uso de `Material Design` e `FloatingActionButton`.

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Java
*   **Arquitetura:** MVC (Model-View-Controller) simplificado.
*   **Componentes de UI:**
    *   `RecyclerView` para listagem eficiente.
    *   `FloatingActionButton` para ação principal.
    *   `ConstraintLayout` e `LinearLayout` para design responsivo.
*   **API Level:**
    *   `minSdk`: 26
    *   `targetSdk`: 36

## 📂 Estrutura do Projeto

*   `MainActivity.java`: Tela principal que gerencia a lista e o RecyclerView.
*   `AddTaskActivity.java`: Tela para entrada de texto da nova tarefa.
*   `TaskAdapter.java`: Gerencia a vinculação dos dados das tarefas com a interface visual.
*   `res/layout/`: Contém os arquivos XML de definição da interface de usuário.

## ⚙️ Como executar

1.  Clone este repositório.
2.  Abra o projeto no **Android Studio**.
3.  Sincronize o Gradle.
4.  Execute em um emulador ou dispositivo físico com Android Oreo (API 26) ou superior.

---
Desenvolvido para fins de aprendizado prático em Android.
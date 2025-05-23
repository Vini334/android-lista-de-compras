Lista de Compras – App Android em Kotlin
Este projeto foi desenvolvido como uma forma de praticar conceitos importantes do desenvolvimento Android. A proposta é um aplicativo simples e funcional para gerenciar listas de compras, algo bastante útil no dia a dia.

O app foi criado em Kotlin, seguindo a arquitetura MVVM (Model-View-ViewModel), e utiliza componentes modernos do Android Jetpack, como ViewModel e LiveData. Para armazenar os dados de forma local, foi utilizado SQLite. A interface é construída com RecyclerView, garantindo uma experiência visual fluida e organizada.

Funcionalidades
Adicionar, editar e excluir itens da lista de compras

Armazenamento local com persistência de dados mesmo após fechar o app

Interface responsiva com uso de RecyclerView

Organização baseada em MVVM, facilitando manutenção e escalabilidade

Atualizações em tempo real usando LiveData

Tecnologias Utilizadas
Kotlin – linguagem principal utilizada no projeto

Android Jetpack – uso de ViewModel, LiveData e outros recursos modernos

SQLite – banco de dados local para persistência dos dados

RecyclerView – para exibir listas de forma eficiente

Gradle – ferramenta de build e gerenciamento de dependências

Conceitos Aplicados
Durante o desenvolvimento, foram aplicados os seguintes conceitos:

Programação orientada a objetos (POO) com Kotlin

Separação de responsabilidades através da arquitetura MVVM

Gerenciamento de ciclo de vida com ViewModel e LiveData

Implementação de CRUD com SQLite

Atualização automática da interface com LiveData

Organização modular da interface com RecyclerView e Adapters

Gerenciamento do projeto com Gradle

Testes
O projeto conta com testes unitários simples que garantem o funcionamento das principais funcionalidades relacionadas à manipulação dos dados. Os testes podem ser executados no Android Studio em um emulador ou dispositivo físico.

Considerações Finais
Este projeto serve como uma base sólida para outros aplicativos que demandam armazenamento local e gerenciamento de listas. O uso de boas práticas e tecnologias modernas ajuda a tornar o projeto mais organizado e fácil de evoluir. É uma boa referência tanto para estudos quanto para futuras melhorias ou adaptações.


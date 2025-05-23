🛒 Lista de Compras – App Android em Kotlin
Este projeto foi feito como uma forma de praticar e aplicar alguns conceitos importantes do desenvolvimento Android. A ideia foi criar um aplicativo simples, mas funcional, para gerenciar listas de compras — algo que todo mundo acaba precisando em algum momento.

O app foi todo desenvolvido em Kotlin e segue o padrão MVVM, usando recursos modernos do Android Jetpack como o ViewModel e LiveData. Para salvar os dados localmente, optei por usar SQLite, o que garante que as informações não se percam quando o app for fechado. A interface é feita com RecyclerView, garantindo uma navegação fluida e organizada.

📋 O que o app faz
Permite adicionar, editar e excluir itens da lista de compras

Os dados são salvos localmente, mesmo se o app for fechado

A interface é limpa e intuitiva, usando RecyclerView

A arquitetura MVVM organiza o código e facilita a manutenção

As alterações aparecem em tempo real, graças ao uso de LiveData

🧰 Tecnologias e ferramentas usadas
Kotlin – linguagem principal

Android Jetpack – com foco em ViewModel e LiveData

SQLite – para armazenar os dados de forma local

RecyclerView – para mostrar os itens da lista

Gradle – para gerenciamento de dependências e build

📚 Conceitos por trás do app
Durante o desenvolvimento, busquei aplicar conceitos importantes como:

Programação orientada a objetos (POO) com Kotlin

MVVM, separando bem as responsabilidades entre tela e lógica

Uso correto do ciclo de vida dos componentes

Operações de banco de dados usando SQLite com uma abordagem mais limpa

Interface que se atualiza automaticamente com LiveData

Organização do projeto com Gradle

Componentização usando RecyclerView com Adapters personalizados

🧪 Testes
Incluí alguns testes unitários para garantir que as funcionalidades principais, como salvar ou editar um item, funcionam como esperado. Eles podem ser rodados direto pelo Android Studio, tanto no emulador quanto em um dispositivo real.

📌 Considerações finais
Esse app pode servir como ponto de partida para projetos maiores ou como um exemplo de como combinar arquitetura limpa com recursos modernos do Android. É uma boa base para quem está estudando ou pretende evoluir para apps mais completos.

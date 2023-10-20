# Meu Projeto iPhone Simulador

Este projeto simula as funcionalidades básicas de um iPhone, focando em três principais componentes:
Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## Diagrama UML

O diagrama UML a seguir descreve a estrutura geral e os relacionamentos entre as diferentes partes do projeto.

```plantuml
                                +------------------+
                                |     iPhone       |
                                +------------------+
                                |                  |
                                +------------------+
                                | +main()          |
                                +---------+--------+
                                          |
             +----------------------------+----------------------------+
             |                            |                            |
    +------------------+        +--------------------+       +--------------------+
    | ReprodutorMusical|        | AparelhoTelefonico |       | NavegadorInternet  |
    +------------------+        +--------------------+       +--------------------+
    |                  |        |                    |       |                    |
    +------------------+        +--------------------+       +--------------------+
    | +tocar()         |        | +ligar()           |       | +exibirPagina()    |
    | +pausar()        |        | +atender()         |       | +adicionarNovaAba()|
    | +selecionarMusica|        | +iniciarCorrerioVoz|       | +atualizarPagina() |
    +------------------+        +--------------------+       +--------------------+
```
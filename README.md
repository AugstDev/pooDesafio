# Desafio DIO

```mermaid
classDiagram

    class iphone{
        
    }

    class reprodutorMusical{
        +tocar()
        +pausar()
        +selecionarMusica(String musica)

    }

    class navegadorInternet{
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }
    class aparelhoEletronico{
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    iphone --> reprodutorMusical
    iphone --> navegadorInternet
    iphone --> aparelhoEletronico
```

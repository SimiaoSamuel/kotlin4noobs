Nesse tutorial você vai escrever o seu primeiro código em kotlin, o famoso hello world!

A forma mais simples de se escrever algo no console com o kotlin é através do método println(), que além de printar algo irá pular uma linha.

Mas antes você precisa criar um método main para poder rodar o seu programa kotlin, existem duas formas de se criar um main

```kotlin
fun main() {
    println("Hello world!")
}
```

A diferença da segunda versão é que nela você consegue passar argumentos quando estiver rodando sua aplicação no console e pegar esses argumentos no seu método

Ainda não Abordamos o assunto mas basicamente o método main está esperando um array do tipo string, que pode estar vázio ou não dependendo se você passou algum argumento na hora que rodou a sua aplicação, e dentro desse método o array está na variavel de nome "args", você pode usar essa variável para verificar o contéudo dentro desse array e etc. 

```kotlin
fun main(args: Array<String>) {
    println("Hello world!")
}
```

Você também pode usar o método print() a diferença dele para o println() é que ele não vai pular uma linha

```kotlin
fun main(args: Array<String>) {
    print("Hello ")
    print("World!")
}
```

É isso, espero que você tenha entendido como escrever o seu primeiro Hello World em Kotlin, qualquer duvida você pode abrir uma issue.

Ex01 - Escreva Hello World! no console pulando um linha entre as duas palavras.

Resultado esperado: 
```kotlin
Hello
World
```
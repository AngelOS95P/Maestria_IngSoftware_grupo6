# Diagramas Klondike
Universidad Politecnica Salesiana  



> - [aperezm1@est.ups.edu.ec](mailto:aperezm1@est.ups.edu.ec)
>
>- [bpinos@est.ups.edu.ec](mailto:bpinos@est.ups.edu.ec)
>
>- [ptorresp1@est.ups.edu.ec](mailto:ptorresp1@est.ups.edu.ec)


---

## index

* [Domain Model](#domain-model)  
    * [Vocabulary](#vocabulary)
    * [Estado Inicial](#estado-inicial)  
    * [Estado movimiento de carta](#estado-movimiento-de-carta)
    * [Diagra de actividades](#diagra-de-actividades)


- [Modelo de vistas de caso de uso](#modelo-de-vistas-de-caso-de-uso)
    * [Diagrama de actores y casos de uso](#diagrama-de-actores-y-casos-de-uso)  
    * [Diagrama relacion de casos de uso](#diagrama-relacion-de-casos-de-uso)
    * [Casos de Uso](#casos-de-uso)
        * [CU Shuffle](#cu-shuffle)
        * [CU DealPile](#cu-dealpile)
        * [CU DealStock](#cu-dealstock)
        * [CU MoveCard](#cu-movecard)
        * [CU MovePile](#cu-movepile)
        * [CU ResetDeck](#cu-resetdeck)

* [Diagramas de analisis](#diagramas-de-analisis)
    * [Arquitectura MVC paquetes](#arquitectura-mvc-paquetes)
    * [Diagramas de Analisis de cada caso de uso](#diagramas-de-analisis-de-cada-caso-de-uso)
        * [DA CU Shuffle](#da-cu-shuffle)
        * [DA CU DealPile](#da-cu-dealpile)
        * [DA CU DealStock](#da-cu-dealstock)
        * [DA CU MoveCard](#da-cu-movecard)
        * [DA CU MovePile](#da-cu-movepile)
        * [DA CU ResetDeck](#da-cu-resetdeck)

- [Diagramas de Diseño](#diagramas-de-diseño)
    * [Diagrama de Hardware](#diagrama-de-hardware)



---

## Domain Model  

[WIKI](https://en.wikipedia.org/wiki/Klondike_(solitaire))


![Klondike](./docs/images/solitario.png)  



### Vocabulary

![Vocabulario](./docs/diagramas/modeloDominio/01_Class%20Diagram.svg)  
  


### Estado Inicial
  
![Estado_inicial](./docs/diagramas/modeloDominio/02_initialState.svg)  

### Estado movimiento de carta 

* Diferentes situacion para una carte que se quiera mover

![Estado_final](./docs/diagramas/modeloDominio/03_Diagrama%20de%20estados.svg)  


### Diagra de actividades

![Diagra de actividades](./out/1%20Modelo%20de%20Dominio/04_Diagrama%20de%20actividades/Actividades.svg)  




---


## Modelo de vistas de caso de uso

### Diagrama de actores y casos de uso
![Actores y casos de uso](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20actores%20y%20casos%20de%20uso/ActorsDiagram.svg)
### Diagrama relacion de casos de uso
![Relacion de casos de uso](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20relacion%20de%20Casos%20de%20Uso/StateDiagram.svg)

### Casos de Uso

#### CU Shuffle
![CU Shuffle](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20Shuffle/shuffleUseCaseSpecification.svg)
#### CU DealPile
![CU DealPile](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20DealPile/CUDealPile.svg)
#### CU DealStock
![CU DealStock](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20DealStock/CUDealStock.svg)
#### CU MoveCard
![CU MoveCard](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20Uso%20MoveCard/UseCaseMoveCard.svg)
#### CU MovePile
![CU MovePile](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20MovePile/UseCaseMovePile.svg)
#### CU ResetDeck
![CU ResetDeck](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20ResetDeck/resetDeckUseCaseSpecification.svg)

---


## Diagramas de analisis  
### Arquitectura MVC paquetes

![Diagra de arquitectura MVC](./out/3%20Diagramas%20de%20Analisis/arquitectura_paquetes_mvc/ArquitecturaMVC.svg)  

### Diagramas de Analisis de cada caso de uso

#### DA CU Shuffle
![CU Shuffle](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20Shuffle/ShuffleContextDiagram.svg)
#### DA CU DealPile
![CU DealPile](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20DealPile/ContextDiagram.svg)
#### DA CU DealStock
![CU DealStock](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20DealStock/ContextDiagram.svg)
#### DA CU MoveCard
![CU MoveCard](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20MoveCard/ContextDiagram.svg)
#### DA CU MovePile
![CU MovePile](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20MovePile/MovePileContextDiagram.svg)
#### DA CU ResetDeck
![CU ResetDeck](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20ResetDeck/ResetDeckContextDiagram.svg)


---

## Diagramas de Diseño

### Diagrama de Hardware
![Diagrma de Hardware](./out/4%20Diagramas%20de%20Dise%C3%B1o/Diagrama%20de%20Hardware/Diagrama%20de%20Hardware.svg)
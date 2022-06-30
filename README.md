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
    * [Initial State](#initial-state)
    * [Final State](#final-state)  
    * [Card's Life Cycle](#card's-life-cycle)
    * [Activity Diagram](#activity-diagram)
     * [Detail Activity Diagram](#detail-activity-diagram)


- [Use Case Views](#use-case-views)
    * [Actors and Use Cases Diagram](#actors-and-use-cases-diagram)  
    * [Use Case Relationship Diagram](#se-case-relationship-diagram)
    * [Casos de Uso](#casos-de-uso)
        * [CU Login](#cu-loguin)
        * [CU StartGame](#cu-startgame)
        * [CU DealToWaste](#cu-dealtowaste)
        * [CU PileToPileMove](#cu-piletopilemove)
        * [CU PiletoFoundationMove](#cu-piletofoundationmove)
        * [CU FoundationtoPileMove](#cu-foundationtopilemove)
        * [CU WastetoPileMove](#cu-wastetopilemove)
        * [CU WastetoFoundationMove](#cu-wastetofoundationmove)
        * [CU WastetoStockMove](#cu-wastetostockmove)
        * [CU Undo](#cu-undo)
        * [CU Redo](#cu-redo)
        * [CU RestartGame](#cu-restartgame)

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

![Vocabulario](./out/1%20Modelo%20de%20Dominio/01_Diagrama%20de%20clases/Class%20Diagram.svg)  
  

### Initial State
![Estado_inicial](./out/1%20Modelo%20de%20Dominio/02_Diagrama%20de%20objetos%20estado%20inicial/ObjectDiagramInitialState.svg)  
  
### Final State
![Estado_final](./out/1%20Modelo%20de%20Dominio/02_Diagrama%20de%20objetos%20estado%20final/ObjectDiagramFinalState.svg)


### Card's Life Cycle

* Diferentes situacion para una carta que se quiera mover

![Card's Life Cycle](./out/1%20Modelo%20de%20Dominio/03_Diagrama%20de%20estados/StateDiagram.svg)  



### Activity Diagram

![Diagra de actividades](./out/1%20Modelo%20de%20Dominio/04_Diagrama%20de%20actividades/ActivitiesDiagram.svg)

### Detail Activity Diagram

![Diagra de actividades detallado](./out/1%20Modelo%20de%20Dominio/05_Diagrama%20de%20actividades%20detallado/DetailActivityDiagram.svg)



---


## Use Case Views

### Actors and Use Cases Diagram
![Actores y casos de uso](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20actores%20y%20casos%20de%20uso/ActorsDiagram.svg)

### Use Case Relationship Diagram
![Relacion de casos de uso](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20relacion%20de%20Casos%20de%20Uso/UseCaseContextDiagram.svg)



### Casos de Uso

#### CU StartGame
![CU Shuffle](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20Shuffle/shuffleUseCaseSpecification.svg)


#### CU PiletoFoundationMove
![CU FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20PileToFoundationMove/UCPileToPileMove.svg)

#### CU FoundationtoPileMove
![CU FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20FoundationToPileMove/UCFoundationtoPileMove.svg)

#### CU WastetoPileMove
![CU FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToPileMove/UseCaseWasteToPileMove.svg)

#### CU WastetoFoundationMove
![CU WastetoFoundationMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToFoundationMove/UseCaseWasteToFoundationMove.svg)

#### CU WastetoStockMove
![CU WastetoStackMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToStock/UseCaseWasteToPileMove.svg)





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
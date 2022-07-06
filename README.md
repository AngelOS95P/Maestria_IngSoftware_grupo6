# Klondike Diagrams 
Universidad Politecnica Salesiana  


> Authors:
> - Angel Perez  - [aperezm1@est.ups.edu.ec](mailto:aperezm1@est.ups.edu.ec)
>
>- Blanca Pinos - [bpinos@est.ups.edu.ec](mailto:bpinos@est.ups.edu.ec)
>
>- Pablo Torres - [ptorresp1@est.ups.edu.ec](mailto:ptorresp1@est.ups.edu.ec)



---
## Práctica Agil

Product Backlog y tres gestiones de Srping, esta en el archivo en la siguiente ruta "Agil/Scrum.slxs" en este mismo repositorio.

* [Scrum](./Agil/SCRUM.xlsx)

## Index RUP

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
    * [Use Cases](#use-cases)
        * [UC Login](#uc-loguin)
        * [UC DealToWaste](#uc-dealtowaste)
        * [UC PileToPileMove](#uc-piletopilemove)
        * [UC PileToFoundationMove](#uc-piletofoundationmove)
        * [UC FoundationToPileMove](#uc-foundationtopilemove)
        * [UC WasteToPileMove](#uc-wastetopilemove)
        * [UC WasteToFoundationMove](#uc-wastetofoundationmove)
        * [UC WasteToStockMove](#uc-wastetostockmove)
        * [UC Undo](#uc-undo)
        * [UC Redo](#uc-redo)
        * [UC RestartGame](#uc-restartgame)

      

* [Analysis Views](#analysis-views)
    * [Analysis architecture](#analysis-architecture)
    * [Use Case Analysis](#use-case-analysis)
        * [AD UC Loguin](#ad-uc-loguin)
        * [AD UC Undo](#ad-uc-undo)
        * [AD UC WasteToPileMove](#ad-uc-wastetopilemove)
       



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



### Use Cases

#### UC Loguin

![CU Undo](./out/)


#### UC DealToWaste
![UC DealToWaste](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20DealToWaste/UCDealStock.svg)

#### UC PileToPileMove
![UC PileToPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20PileToPileMove/UCPileToPileMove.svg)

#### UC PileToFoundationMove
![UC FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20PileToFoundationMove/UCPileToPileMove.svg)

#### UC FoundationToPileMove
![UC FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20FoundationToPileMove/UCFoundationtoPileMove.svg)

#### UC WasteToPileMove
![UC FoundationtoPileMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToPileMove/UCWasteToPileMove.svg)

#### UC WasteToFoundationMove
![UC WastetoFoundationMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToFoundationMove/UCWasteToFoundationMove.svg)

#### UC WastetoStockMove
![UC WastetoStackMove](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20WasteToStock/UCWasteToStockMove.svg)


#### UC Undo
![UC Undo](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20Undo/UCUndo.svg)


#### UC Redo
![CU Redo](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20Redo/UCRedo.svg)

#### UC RestartGame
![CU Undo](./out/2%20Modelo%20de%20vistas%20de%20caso%20de%20uso/Diagrama%20de%20caso%20de%20uso%20-%20RestartGame/DetailActivityDiagram.svg)


---


## Analysis Views 
### Analysis architecture

![Diagra de arquitectura MVC](./out/3%20Diagramas%20de%20Analisis/arquitectura_paquetes_mvc/ArquitecturaMVC.svg) 

![Models Class](./out/3%20Diagramas%20de%20Analisis/arquitectura_paqutes_m/ArquitecturaMVC.svg)
![Views Class](./out/3%20Diagramas%20de%20Analisis/arquitectura_paquetes_v/ArquitecturaMVC.svg) 
![Controllers Class](./out/3%20Diagramas%20de%20Analisis/arquitectura_paquetes_c/ArquitecturaMVC.svg) 

### Use Case Analysis

#### AD UC Loguin
![CU Shuffle](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20Login/ContextDiagramLogin.svg)
#### AD UC Undo
![CU DealPile](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20Undo/ContextDiagramUndo.svg)
#### AD UC WasteToPileMove
![CU DealStock](./out/3%20Diagramas%20de%20Analisis/Diagrama%20de%20contexto%20-%20WastToPileMove/ContextDiagramUseCaseWasteToPileMove.svg)
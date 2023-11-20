Assignment sheet number: Assignment 3: Boolean Algebra   
Assignment number: 3.1, 3.2 und 3.3   
Name: Janis Wuga  
Matrikelnummer: 12313444   
Date: 20.11.2023   
My own production  
  
# AAssignment 3.1 - Truth tables:   
## Punkt 1:  
### AND:
| x | y | xy |
|---|:-:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |  

### OR:  
| x | y | xy |
|---|:-:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |    
  
 ### XOR:  
| x | y | xy |
|---|:-:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |  

### NAND:   
| x | y | xy |
|---|:-:|---:|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 | 

 ### NOR:  
| x | y | xy |
|---|:-:|---:|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |  
  
## Punkt 2:  
Gesammte Gleichung:  a ∧ (b ∨ a) ∨ b ∧ c = (a ∧ b) ∨ (b ∧ c)  
Linke Seite: a ∧ (b ∨ a) ∨ b ∧ c  
#### a ∧ (b ∨ a) = (a ∧ b) ∨ (a ∧ a)   

| a | b | c | a ∧ (b ∨ a) | (a ∧ b) ∨ (a ∧ a) |
|--|:-:|--:|:-----------------------:|:--------------------:|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 | 1 |
| 1 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 1 | 1 |

#### (a ∧ b) ∨ (a ∧ a) = (a ∧ b) ∨ a  

| a | b | c | (a ∧ b) ∨ (a ∧ a) | (a ∧ b) ∨ a  |
|---|:-:|--:|:-----------------------:|:--------------------:|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 | 1 |
| 1 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 1 | 1 | 

Linke Seite: (a ∧ b) ∨ a ∨ (b ∧ c)   
#### Zusammenfassung: (a ∧ b) ∨ a ∨ (b ∧ c) ≠ (a ∧ b) ∨ (b ∧ c)

| a | b | c | (a ∧ b) ∨ a ∨ (b ∧ c) | (a ∧ b) ∨ (b ∧ c) |
|---|:-:|--:|:-----------------------:|:--------------------:|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 1 | 1 |  

# Assignment 3.2 - Boolean Algebra:  
## 1.  

| a | b | c | d | 𝑎 ∧ 𝑏 𝑋𝑂𝑅 (𝑐 ∨ 𝑑) |  𝑎 ∧ −𝑏 ∧ (𝑐 ∨ −𝑑) |  (𝑎 ∧ 𝑏 𝑁𝐴𝑁𝐷 𝑐 ∧ −𝑑)|
|-|-|-|-|:-:|:-:|:-:|
| 1 | 1 | 0 | 1 | 0 | 0 | 1 |
| 1 | 0 | 1 | 1 | 1 | 1 | 1 |
| 1 | 0 | 1 | 0 | 1 | 1 | 1 |  

## 2.  

#### ¬𝑎 ∧ (𝑎 ∨ 𝑏) ∨ (𝑏 ∨ 𝑎 ∧ 𝑎) ∧ (𝑎 ∨ ¬𝑏)  
* ¬𝑎 ∧ (𝑎 ∨ 𝑏) = (¬𝑎 ∧ a) v (¬𝑎 ∨ 𝑏)  
 (¬𝑎 ∧ a) = 0   

(¬𝑎 ∨ 𝑏) ∨ (𝑏 ∨ 𝑎 ∧ 𝑎) ∧ (𝑎 ∨ ¬𝑏)  
* (𝑏 ∨ 𝑎 ∧ 𝑎) = (𝑏 ∨ 𝑎)  

(¬𝑎 ∨ 𝑏) ∨ (𝑏 ∨ 𝑎) ∧ (𝑎 ∨ ¬𝑏)
* (𝑏 ∨ 𝑎) ∧ (𝑎 ∨ ¬𝑏) = (b ∧ a) v (b ∧ ¬b) v (a ∧ a) v (a ∧ ¬𝑏)  
(b ∧ ¬b) = 0  
(a ∧ a)= a  

(¬𝑎 ∨ 𝑏) ∨ (b ∧ a) v a v (a ∧ ¬𝑏)  
* a v (a ∧ ¬𝑏) = a  
(b ∧ a) v a = a  
(¬𝑎 ∨ 𝑏) v a = (¬𝑎 v a) v (𝑎 ∨ 𝑏)  
(¬𝑎 v a) = 0
##### a v b  
#### (𝑎 ∨ 𝑐) ∧ (𝑎 ∧ 𝑑 ∨ 𝑎 ∧ ¬𝑑) ∨ 𝑎 ∧ 𝑐 ∨ c  
* (𝑎 ∧ 𝑑 ∨ 𝑎 ∧ ¬𝑑) = (𝑎 ∨ 𝑎) ∧ (¬𝑑 v a) ∧ (𝑑 v a) ∧ (¬𝑑 v d)  
(𝑎 ∨ 𝑎) = a  
(¬𝑑 v d)= 0  
𝑎 ∧ (¬𝑑 v a) ∧ (𝑑 v a)  
𝑎 ∧ (¬𝑑 v a) = a  
a ∧ (𝑑 v a)  
a ∧ (𝑑 v a) = a  

(𝑎 ∨ 𝑐) ∧ a ∨ 𝑎 ∧ 𝑐 ∨ c
* (𝑎 ∨ 𝑐) ∧ a = a  

a ∨ 𝑎 ∧ 𝑐 ∨ c
* a ∨ 𝑎 ∧ 𝑐 = a

##### a v c
#### ¬(¬𝑎 ∨ (𝑏 ∧ 𝑐)) ∨ (𝑐 ∧ (𝑏 ∨ 𝑐))  
* ¬(¬𝑎 ∨ (𝑏 ∧ 𝑐)) = (𝑎 ∧ (¬𝑏 ∨ ¬𝑐))  

(𝑎 ∧ (¬𝑏 ∨ ¬𝑐)) ∨ (𝑐 ∧ (𝑏 ∨ 𝑐)) 
* (𝑐 ∧ (𝑏 ∨ 𝑐)) = c  

𝑎 ∧ (¬𝑏 ∨ ¬𝑐) ∨ c
* 𝑎 ∧ (¬𝑏 ∨ ¬𝑐) = (𝑎 ∧ ¬𝑏) v (𝑎 ∧ ¬𝑐)  

(𝑎 ∧ ¬𝑏) v (𝑎 ∧ ¬𝑐) v c
* (𝑎 ∧ ¬𝑏) v (𝑎 ∧ ¬𝑐) = (𝑎 v ¬𝑏) ∧ (𝑎 v ¬𝑐) ∧ (¬𝑏 v ¬𝑐) ∧ (𝑎 v a)  
(𝑎 v a) = a  
(𝑎 v ¬𝑏) ∧ a = a  
(𝑎 v ¬𝑐) ∧ a = a  

𝑎 ∧ (¬𝑏 v ¬𝑐) v c
* (¬𝑏 v ¬𝑐) v c = (c v ¬𝑐) v (¬𝑏 v 𝑐)  
(c v ¬𝑐) = 1  

##### c v a ∧ ¬𝑏
# Assignment 3.3 - Properties of Boolean Algebra  
Das erste zeigt, dass (a v a = a) ist.  
Das zweite zeigt das gleiche wie das erste, nur dieses Mal auch, dass ein ¬ vor einer Gleichung wie (𝑎 ∨ 𝑎) ∨ (𝑏 ∨ 𝑏) die ∨ und ∧ vertauscht und ein ¬ zu jedem (a, b, c...) hinzufügt oder, wenn schon ein ¬ da war, entfernt.  
Das dritte zeigt das gleiche wie beim zweiten, nur dass dieses Mal noch einmal am Schluss umgeformt wird, da dieses Mal (𝑎 ∨ 𝑏) ∨ (𝑎 ∨ 𝑏) ist und nicht (𝑎 ∨ 𝑎) ∨ (𝑏 ∨ 𝑏).  
Das vierte ist wie das dritte, nur dass dieses Mal auch noch die Regel (𝑎 ∨ ¬𝑎) = 0 angewandt wird.  
Das fünfte verwendet das gleiche wie das dritte, nur dass dieses Mal gezeigt wird, dass, das Gegenteil von 0 in dem Fall 1 ist bzw. das Gegenteil von Wahr falsch ist.  
### Was diese alle gemeinsam haben ist das sie alle ein oder mehrere Beispiele von der Boolean Algebra beinhalten.
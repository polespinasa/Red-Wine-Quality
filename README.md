# Practica Kaggle APC UAB 2022-23

### Nom: Pol Espinasa Vilarrasa  
### Dataset: [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
![Wine](extres/wine.jpg)


## Introducció
La base de dades seleccionada tracta sobre la qualitat d'una variant de vins portuguesos, els "Vinho Verde".  
En aquest notebook es realitzara un anàlisi del dataset i es compraran els difrents atributs del cada vi, per així poder entendre quins d'aquests atributs afecten més a la qualitat del producte.  
La base de dades conté un seguit d'atributs, com el Ph del vi, àcids, sucres, sals, d'entre altres. Posteriorment es mostrarán i es tractaràn tots els atributs.
L'objectiu serà predir la qualitat dels vins segons la resta d'atributs.  

Nota: Alguns valors de accuracy poden variar dels que es veuen al notebook. Això és degut a que s'ha executat més d'un cop després de crear aquest resum.
## Models probats

Per realitzar aquesta predicció s'utilitzen quatre models diferetns:  
- Support Vector Classification
- K-Nearest Neighbour
- Decision Tree
- Random Forest


### Resultats normals: 

|     Model     | Accuracy |
| -- | -- |
|      SVC      |  0.719   |
|      KNN      |  0.672   |
| Decision Tree |  0.659   |
| Random Forest |  0.766   |

### Resultats amb cerca d'hiperparàmetres:

|     Model     | Accuracy |
| -- | -- |
|      SVC      |  0.728   |
|      KNN      |  0.704   |
| Decision Tree |  0.713   |
| Random Forest |  0.785   |

## Com utilitzar el codi

Per utilitzar el codi fa falta descarregar del github el dataset (amb la carpeta que el conté inclosa) i la llibreta de Jupiter.  
Posteriorment s'han de descarregar totes les llibreries necesaries: ```pip install -r requirements.txt```  
Obrir el notebook i executar totes les celes.

## Conclusions
La predició ha donat com a millor resultat un casi 80% d'accuracy. Estic segur que podria haver sigut millor usant altres paràmetres o altres models. Tot i això els resultats son prou bons i com es pot veure a les matrius de confusió els errors que té són per una unitat i no fa errors amb valors molt allunyats.

## License
This project is under the GPL-3.0 License - see the [LICENSE](LICENSE) for more details

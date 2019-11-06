# Les keywords :
* NoSQL (Not Only SQL)
* SQL
* ACID
* BASE
* Replication
* Chunk
* Rack
* Switch
* NameNode
* DataNode
* Upsizing
* Scalabilité
* matrice multicritere
* Shard(ing) (maître / esclave)
* Moteur de recherche "Lucene"

### Base de donnée :
* Stockage orienté clé/valeur
* Stockage orienté Ligne / colonne
* Stockage orienté document
* Stockage orienté graphe (position)

### Theoreme de CAP :
* Consistency (Cohérence) : Une donnée n'a qu'un seul état visible quel que soit le nombre de réplicas
* Availability (Disponibilité) : Tant que le système tourne (distribué ou non), la donnée doit être disponible
* Partition Tolerance (Distribution) : Quel que soit le nombre de serveurs, toute requête doit fournir un résultat correct
= rendre la data disponible selon au moin 2proprietes.
* (3 propriete : coherent, disponibilité, distribution)

***
### SQL :
* Faire des jointures entre les tables de la base de données
* Faire des requêtes complexes avec un langage de haut niveau sans se préoccuper des couches basses
* Gérer l'intégrité des données de manière infaillible

### ACID :
 * Atomicité : Une transaction s’effectue entièrement ou pas du tout
 * Cohérence : Le contenu d’une base doit être cohérent au début et à la fin d’une transaction
 * Isolation : Les modifications d’une transaction ne sont visibles/modifiables que quand celle-ci a été validée
 * Durabilité : Une fois la transaction validée, l’état de la base est permanent (non affecté par les pannes ou autre)

### BASE :
* Basically Avaible
* Soft state
* Eventually consistent
***

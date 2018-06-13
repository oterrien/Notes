# Atomicity

Cette propriété garantit qu'une succession de traitements (une transaction) est vue, depuis le système, comme un seul.  
Soit la transaction est faite en totalité, soit pas du toute.  
Il n'y a pas d'état intermédiaire du système.  

# Coherency

Cette propriété garantit que chaque transaction laisse le système dans un état valide, et ce qu'elle ait réussi ou échoué.

# Isolation

Cette propriété garantit que les transactions sont indépendantes les unes des autres.  

# Durability

En cas de validation d'une transaction en succès, l'état obtenu est persistent. 

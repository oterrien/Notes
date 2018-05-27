# **Single-responsibility Principle**
Une classe, une fonction ou une méthode doit avoir une et une seule responsabilité

# **Open-closed Principle**
Une classe doit être ouverte à l'extension, mais fermée à la modification
* l'idée est qu'une fois qu'une classe a été approuvée via des revues de code, des tests unitaires et d'autres procédures de qualification, elle ne doit plus être modifiée mais seulement étendue.

# **Liskov substitution principle**
Une instance de type T doit pouvoir être remplacée par une instance de type T’, tel que T’ sous-type de T, sans que cela ne modifie la cohérence du programme.
* contravariance des arguments de méthode dans T’ (une fonction de transformation « f » sera contravariant si, quand A étend B, alors f(B) étends f(A))
* covariance du type de retour dans T’ (une fonction de transformation « f » sera covariante si, quand A étend B, alors f(A) étends f(B))
* aucune nouvelle exception ne doit être générée par les méthodes de T’, sauf si celles-ci sont elles-mêmes des sous-types des exceptions levées par la méthode du supertype.

# **Interface segregation principle**
Préférer plusieurs interfaces spécifiques pour chaque client plutôt qu'une seule interface générale.
* l’idée est de ne pas obliger un client à implémenter des méthodes dont il n’aurait pas besoin.

# **Dependency Inversion principle**
Il faut dépendre des abstractions, pas des implémentations

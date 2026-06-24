# Maintenant compris:

### Search.php
- Si & Sinon
``` php
// Compris, $results = $submitted si search_employees est valide, sinon $results = array() 
$results = $submitted ? search_employees($dept_no, $name, $age_min, $age_max) : array();
```

- Symbole fleche (Retour)
``` php
    &larr (<-)
```

- Equivalent ECHO
``` php
    // Facon 1 (Basic)
    <? echo $emp['first_name'] ?>

    // Facon 2
    <?= $emp['first_name'] ?>
```

### Stats.php

- Reduire un nombre en entier
#### Etat par defaut
``` php
    <td><?= $row['salaire_moyen'] ?> €</td> // => 57317.5736 €
``` 

#### Reduiser
``` php
    <td><?= number_format($row['salaire_moyen'], 0, ',', ' ') ?> €</td> // => 57 318 €
```

# Pas encore compris:

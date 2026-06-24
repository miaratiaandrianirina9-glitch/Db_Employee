# Maintenant Compris
- l'opérateur `===`
````
````
# Pas encore Compris
- l'opérateur `??`
  ````php
      $line['manager_name'] ?? '—'
  ````
  ````php
      $first_name = $existing['first_name'] ?? '';
  ````
- ce code
  ````php
      $manager = $current_dept ? get_current_manager($current_dept['dept_no']) : null;
  ````
  ````php
      $current ? $current['dept_name'] . ' (depuis le ' . $current['from_date'] . ')' : 'aucun' 
  ````
  - `urlencode`
  ````php
      urlencode($emp_no)
  ````
- `htmlspecialchars`
  ````php
     htmlspecialchars($error)
  ````
  ````html php
      <input type="hidden" name="mode" value="<?= $editing ? 'edit' : 'add' ?>">
  ````
# Fonctions utilisées que je ne connais pas
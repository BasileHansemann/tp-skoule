#Table teacher :
|--|--|--|--|
|Champ|Type|Specificités|Description|
|id|int|unsigned Increment automatique|identifiant de la liste|
|firstname|varchar 64|NOT NULL|prenom du teacher|
|lastname|varchar 64|NOT NULL|nom du teacher|
|job|varchar 64|NOT NULL|spécialité(s) du teacher|

#Table student :
|--|--|--|--|
|id|int|unsigned Increment automatique|identifiant de la liste|
|firstname|varchar 64|NOT NULL|prenom du student|
|lastname|varchar 64|NOT NULL|nom du student|
|teacher_id|int||clé étrangère liant le student au teacher|
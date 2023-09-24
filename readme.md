# Projet développement CSC4101

| Nomenclature | Domaine fonctionnel |
| :----------: | :-----------------: |
| Objet        | Artwork             |
| Inventaire   | Collection          | 
| Gallerie     | Exposition          | 


### `Artwork` properties 

| Property name | Type     | Constraints | Commentary |
| :-----------: | :------: | :---------: | :--------: |
| Name          | `string` | notnull     |            |
| Artist        | `string` | notnull     |            |
| Date          | `int`    | notnull     |            |

### `Collection` properties

| Property name | Type     | Constraints | Commentary |
| :-----------: | :------: | :---------: | :--------: |
| Name          | `string` | notnull     |            |
| Location      | `string` | notnull     |            |

### `Exposition` properties

| Property name | Type     | Constraints | Commentary |
| :-----------: | :------: | :---------: | :--------: |
| Name          | `string` | notnull     |            |
| Location      | `string` | notnull     |            |
| Duration      | `int`    | notnull     |            |


### Associations

- Collection(`1`)-(`0..n`)Artwork
- Exposition(`1..n`)-(`0..n`)Collection
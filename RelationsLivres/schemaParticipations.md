### Creer table
CREATE TABLE participant_anthologie (
    auteur VARCHAR(100) NOT NULL,
    nom_anthologie VARCHAR(100) NOT NULL
);
### Trouver les auteurs associé a une colonne de la table
SELECT auteur FROM participant_anthologie WHERE nom_anthologie  = 'Maisons Hantées'; 
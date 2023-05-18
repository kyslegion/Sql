### Creer table
CREATE TABLE auteur (
    auteur VARCHAR(100) NOT NULL,
    nom_livre VARCHAR(100) NOT NULL
);
### Trouver les auteurs associé a une colonne de la table
SELECT auteur FROM participant_anthologie WHERE nom_anthologie  = 'Maisons Hantées'; 
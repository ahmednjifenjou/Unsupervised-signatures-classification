# Unsupervised-signatures-classification

Ce projet académique, réalisé de zéro, dans le cadre d'un cours de CLustering a pour but d'étudier deux(02) méthodes de Classification non supervisée: K-means, Ascencion Hiérarchique 

# Contexte

On dispose ici d'une base de données  constituée de 2500 signatures(100 personnes ayant chacune 25 signatures) acquises par un dispositif numérique - coordonnées des points touchés par un stylet sur un écran - comme le montre les fichiers dans le dossier "Base de données" ou on a pris les coordonnées d'une signature par individu(représentation dans le notebook)

# Objectifs 

A partir de cette base de données on veut créer des groupes de personnes en étudiant la complexité de leur signature. Cette complexité ici correspond à l'entropie différentielle d'une densité de mélange Gaussienne ayant K = 4, 8, ou 24 paramètres(voir les fichiers de complexités correspondants)

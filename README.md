# Projet Base de Données - Transactions Immobilières

## 🎯 Objectif
Construire une base de données normalisée (3NF) à partir de fichiers CSV publics sur les transactions immobilières, afin de permettre des analyses comme :
1. Nombre total d’appartements vendus au 1er semestre 2020.
2. Le nombre de ventes d’appartement par région pour le 1er semestre2020.
3. Proportion des ventes d’appartements par le nombre de pièces.
4. Liste des 10 départements où le prix du mètre carré est le plus élevé.
5. Prix moyen du mètre carré d’une maison en Île-de-France.
6. Liste des 10 appartements les plus chers avec la région et le nombrede mètres carrés.
7. Taux d’évolution du nombre de ventes entre le premier et le secondtrimestre de 2020.
8. Le classement des régions par rapport au prix au mètre carré desappartement de plus de 4 pièces.
9. Liste des communes ayant eu au moins 50 ventes au 1er trimestre
10. Différence en pourcentage du prix au mètre carré entre unappartement de 2 pièces et un appartement de 3 pièces.
11. Les moyennes de valeurs foncières pour le top 3 des communes desdépartements 6, 13, 33, 59 et 69.
12. Les 20 communes avec le plus de transactions pour 1000 habitantspour les communes qui dépassent les 10 000 habitants.

## 📂 Structure
- **data/** : fichiers CSV sources
- **sql/** : scripts SQL de création, insertion et requêtes
- **docs/** : documentation (dictionnaire de données, schéma relationnel, présentation)

## ⚙️ Technologies
- **SQLite** (SGBD léger)
- **Python** (optionnel pour l'import automatisé)
- **SQL** (création et manipulation des données)

## ✅ Conformité RGPD
- Données publiques (Etalab, cadastre, DVF).
- Anonymisation respectée (pas de données personnelles sensibles).
- Sauvegardes et sécurité assurées localement.

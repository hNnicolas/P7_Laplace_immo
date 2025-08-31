# Projet Base de Données - Transactions Immobilières

## 🎯 Objectif
Construire une base de données normalisée (3NF) à partir de fichiers CSV publics sur les transactions immobilières, afin de permettre des analyses comme :
- Les 20 communes avec le plus de transactions pour 1000 habitants (>10 000 hab).
- La répartition des ventes par région.
- Les valeurs foncières moyennes par commune.

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

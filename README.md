# BelcoTech – Programmation en CAPL (CANalyzer / CANoe)

Bienvenue dans ce guide complet illustrant la **programmation événementielle CAPL** pour les systèmes embarqués basés sur le **bus CAN**.  
Ce projet propose un script détaillé avec des commentaires pédagogiques pour comprendre, tester et simuler des échanges sur un réseau CAN via **Vector CANalyzer** ou **CANoe**.

---

## 🎯 Objectifs du Guide

- Illustrer les fondamentaux de la programmation CAPL
- Implémenter l’envoi, la réception, le traitement et le diagnostic de messages CAN
- Simuler un système embarqué automobile avec gestion des erreurs, timers, fichiers logs, etc.
- Faciliter la prise en main de CAPL pour le prototypage ou la validation

---

## 🧰 Fonctionnalités principales

- ✅ Envoi cyclique de messages moteur (RPM) et de vitesse
- ✅ Gestion intelligente des **timers** (500 ms, 1 s, 5 s)
- ✅ Réception et traitement des trames CAN (vérification, extraction, affichage)
- ✅ **Logging** dans des fichiers `.log` (messages et erreurs)
- ✅ Calcul de moyennes et suivi de statistiques
- ✅ Interactions clavier (debug, test, reset, statistiques)
- ✅ Gestion des erreurs CAN : trames erronées, bus off, surcharge
- ✅ Diagnostic périodique automatique

---

## 📂 Arborescence du projet

```bash
BelcoTech-Programmation-en-CAPL/
│
├── capl_scripting_examples/     # Contient le script CAPL principal
│   └── guide_complet.capl       # Script complet avec commentaires
│
├── README.md                    # Ce fichier d'explication

# Application de Gestion de Copropriété - La Résidence du Parc

Une application web pour la gestion des lots et le calcul des quotes-parts de travaux d'une copropriété.

## 🏢 Fonctionnalités

### Pour tous les utilisateurs
- **Liste des lots** : Consultation de tous les lots avec filtrage et tri
- **Calcul de quotes-parts** : Calcul automatique des montants de travaux par copropriétaire

### Pour l'administrateur
- **Import CSV** : Chargement sécurisé des données (mot de passe requis)
- **Gestion des données** : Mise à jour du fichier de lots

## 🔧 Utilisation

### Configuration initiale (Administrateur)
1. Accédez à la page "Administration"
2. Saisissez le mot de passe administrateur
3. Importez votre fichier CSV avec les colonnes :
   - N° cop, Copropriétaire, Type, Description, N° lot
   - Escalier, Etage, N° plan
   - Clé 1 : charges générales, Clé 3 : ascenceurs

### Utilisation quotidienne
1. **Liste des lots** : Consultez, filtrez et triez les lots
2. **Calcul QP** : Sélectionnez un copropriétaire, saisissez le montant des travaux et la clé de répartition

## 📊 Format du fichier CSV

Le fichier CSV doit être au format suivant (séparateur : point-virgule) :

```csv
N° cop;Copropriétaire;Type;Description;N° lot;Escalier;Etage;N° plan;Clé 1 : charges générales;Clé 3 : ascenceurs
1;Dupont Jean;Appartement;T3;15;A;2;101;125;90
2;Martin Sophie;Appartement;T2;22;B;1;102;90;60
```

## 🚀 Déploiement

Cette application est déployée sur Vercel et accessible à l'adresse : [URL_DE_VOTRE_APP]

## 🛠️ Technologies utilisées

- HTML5 / CSS3 / JavaScript ES6
- PapaParse pour le traitement des fichiers CSV
- Design responsive avec la police Aptos

## 📝 Licence

Application développée pour La Résidence du Parc.
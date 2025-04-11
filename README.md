# Recipes API

## Intro
Το παρακάτω **API** δημιουργήθηκε στα πλαίσια του ΠΜΣ Μηχανική Λογισμικού για Διαδικτυακές & Φορητές Εφαρμογές για τους σκοπούς του Project και την εργασία το Flutter.

Διατίθεται στην διεύθυνση https://recipesapi.digitalsystems.gr/v1/api/ και μπορεί να χρησιμοποιηθεί στο Flutter εύκολα με την βιβλιοθήκη της PocketBase εδώ: https://pub.dev/packages/pocketbase
Καθώς το API βασίζεται στο Pocketbase (https://pocketbase.io/docs/) πρέπει να κοιτάξετε το documentation εδώ https://pocketbase.io/docs/api-records/ για επιπλέον πεδία που μπορούν να συμπληρωθούν και δίνουν επιπλέον δυνατότητες όπως ταξινόμηση βάση κάποιου πεδίου/ων ή δυνατότητα φιλτραρίσματος ή ακόμα και relation expansion (να επιστρέφει αυτούσια και τις σχέσεις με ξένο κλειδί για παράδειγμα όλα τα βήματα μιας συνταγής αντί για μόνο τα id τους).

Για το upload/view των αρχείων εικόνων στις συνταγές και των βημάτων τους πάλι μπορείτε να δείτε το σχετικό documentation εδώ: https://pocketbase.io/docs/files-handling/
Τέλος για οποιαδήποτε απορία που έχετε στείλτε μήνυμα email / viber.

## Postman Docs
Μπορείτε να συμβουλευτείτε επίσης και το [Postman collection αρχείο](Recipes%20API.postman_collection.json) για γρήγορο έλεγχο των endpoint πριν (και κατά) την κατασκευή του frontend!

## Local replication
Υπάρχει επίσης και η επιλογή την τοπικής δημιουργίας ενός διπλότυπου της βάσης δεδομένων στο αρχείο [pb_schema](pb_schema.json) όπου κάποιος που γνωρίζει μπορεί να το κάνει εισαγωγή από το διαχειριστικό περιβάλλον του PocketBase.

*Read more information about PocketBase [here.](https://pocketbase.io/)*
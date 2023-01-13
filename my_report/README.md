# Lesson: Digital & Serious Games

### First and Last Name: Fylaktos Aggelos
### University Registration Number: dpsd18128
### GitHub Personal Profile: https://github.com/AggelosFyl
### Digital & Serious Games Personal Repository: https://aggelosfyl.github.io/Role-Playing-Game/

# Introduction

Στα πλαίσια του μαθήματος "Ψηφιακά παιχνίδια και παιγνιώδης μάθηση" δημιουργείται το παρακάτω παιχνίδι το οποίο είναι είδος Role Playing , δηλαδή αποτελείται από έναν Main χαρακτήρα και έναν εχθρό.

# Summary
 Γενικά σκοπός είναι να υπάρχει ο βασικός χαρακτήρας knight και να περιπλανιέται στον χώρο αντιμετωπίζοντας τον εχθρό ο οποίος μπορεί και αφαιρεί ζωή από τον προωταγωνιστή. Ακόμη θα υπάρχουν και collectibles τα οποία αντίστοιχα αυξάνουν την ζωή.


# 1st Deliverable

Για την δημιουργία του παρακάτω περιβάλλοντος χρησιμοποιήσα της προτεινόμενες οδηγίες από το tutorial της Rubys στο github σε συνδιασμό με ορισμένα βιντεο στο youtube.Πιο συγκεκριμένα άλλαξα τον χαρακτήρα τησ ruby με ένα δικό μου και επίσης χρησιμοποίησα διαφορετικά tileset για την δημιουργία του map.Για την ρύθμιση των κινήσεων του χαρακτηρα μου ακολούθησα αυστηρά το τουτοριαλ της Rubys. 
![image](https://user-images.githubusercontent.com/116358622/201469607-322a7ac8-825c-4c54-912a-c50027468cb2.png)



# 2nd Deliverable
Για την δημιουργία του 2ου παραδοτέου ακολουθήθηκαν οι οδηγίες του tutorial της Rubys όπως και στο πρώτο παραδοτέο. Ο πρωταγωνιστής κινείται στον χώρο δεξιά και αριστερά καθώς έχει και έναν "idle" movement όταν παραμένει στάσιμος. Στον εχθρό προστέθηκε κίνηση καθώς και δυνατότητα αφαίρεσης ζωή από τον πρωταγωνιστή. Προστέθηκε damage zone με ίδιες δυνατότητες όπως ο εχθρός . Ακόμη κατά την διάρκεια του παιχνιδιού υπάρχει κάμερα που ακολουθεί τον πρωταγωνιστή κατά την διάρκεια του παιχνιδιού όπου και άν κινείται.

# 3rd Deliverable 
Ακολούθησα τισ οδηγίες που μου δώσατε στο δευτερο παραδοτέο οπότε και πρόσθεσα ένα τοίχο γύρο απο την πίστα ώστε ο χαρακτήρας να μην μπορει να βγεί απο την πίστα και ακόμη άλλαξα και τα sprite  και έβαλα δικά μου αντί αυτών του tutorial .
![image](https://user-images.githubusercontent.com/116358622/212307601-90d01f53-4d56-4cf4-a575-a8640536512b.png)

Για την δημιουργία του καπνού ακολούθησα πίστα το tutorial προσθέτοντας καπνούς στο robot (εχθρό) οι οποίοι εμφανίζονται σε τυχαία σχήματα και εξαφανίζονται σε τυχαίο ύψος ώστε να δίνει ένα ρεαλιστικό ύφος.![image](https://user-images.githubusercontent.com/116358622/212299577-72660042-e198-4029-b761-666554c73b53.png)

Για την δημιουργία του health bar  ακολούθησα το tutorial  σε συνδιασμό με κάποια βίντεο που βρήκα στο youtube και έφτιαξα μία μπάρα ζωής που έχει 4 επίπεδα και όταν ο χαρακτήρας δέχεται ζημία μειώνεται κατά ένα.![image](https://user-images.githubusercontent.com/116358622/212306159-94622b0f-1703-40fc-8189-967b531a99f3.png)

Στην συνέχεια για να φτιάξω το portal και να κάνει teleport ο χαρακτηρας απο ένα σημείο τηw πίστας σε ένα άλλο, χρησιμοποιήσα το tutorial της ruby και κάποια βίντεο στο youtube όπου και έβαλα δύο κυκλικές επιφάνειες ώς portals που μπορεί να πάει ο χαρακτήρας και πατώντας ο παίκτης το γράμμα "e" να γίνεται μεταφορα του χαρακήρα στις δύο αυτές επιφάνειες.
![image](https://user-images.githubusercontent.com/116358622/212306338-87f76a6a-4118-4fc1-b9b1-1cf6420bac83.png)

Για να προσθέσω ηχητικά εφέ στους χαρακτήρες μου είτε σε αυτους που χειρίζεται ο παίκτης είτε σε αυτούς που χρησιμοποιούν UI για να λειτουργούν ακολούθησα το tutorial της ruby σε συνδιασμό με κάποια tutorial στο youtube .Έπίσης πρόσθεσα ένα τραγούδι να παίζει καθόλι την διάρκεια του παιχνιδιού το οποίο το βρήκα στο διαδύκτιο.Τέλος για την δημιουργία ενός μενού όπου ο παίκτησ μπορεί να επιλέξει ανάμεσα σε δύο πίστες, ένα κουμπί options που του δίνεται η δυνατότητα να  μπορει να αυξομειώσει τον ήχο και ένα κουμπί που το όνόμασα QUIT όπου με αυτο τερματίζεται η λειτουργία του παιχνιδιού.Επίσης μέσα στις πίστες που μπορεί να επιλέξει ο χρήστης πρόσθεσα και ένα κουμπί που όταν το πατάει επιστρέφει στο menu για να μην χρειάζεται να κλείσει το παιχνίδι και να το ξανα ανοίξει για να επιλέξει την άλλη πίστα.

![image](https://user-images.githubusercontent.com/116358622/212306676-05c69037-d20d-4f90-96a7-e843e49fa1ce.png)

![image](https://user-images.githubusercontent.com/116358622/212306735-2b1866ec-4846-47db-b40d-98a97bf64f50.png)



# Conclusions
Αφότου ολοκλήρωσα το παιχνίδι κατάλαβα ότι η δημιουργία ένος παιχνιδιού σε μία πλατφόρμα όπως το unity μπορεί να γίνει αρκετά απαιτητική για κάποιον αρχάριο και να τον αποθαρύνει ,αλλά όσο πιο πολύ χρόνο αφιώρωνεις πιστεύω γίνεται και πιο εύκολο καθώς μαθαίνεις τον τρόπο λειτουργίας του unity και το κυριότερο μαθαίνεις την λογική που πρεπεί να σκέφτεσαι και την σειρά που πρέπει να κάνεις τις πράξεις σου ώστε να έρθει το επιθημιτό αποτέλεσμα .Όσο αφορά το συγκεκριμένο παιχνίδι και την δική μου εμπειρία με το tutorial πιστεύω ότι η διαδικασία ήταν πολύ ευχάριστη και σου έδινε την επιθυμία να το εξελίξεις και να το κάνεις όσο καλύτερο γίνεται,ακόμη και στα σημεία που κολλούσα για ώρες όταν εν τέλει έλυνα το πρόβλημα και προχωρούσα ένιωθα πολύ χαρούμενος που δεν τα παράτησα και συνέχισα να επιμένω να ψάχνω λύσεις όπου μπορούσα .Ένα πράγμα που θέλω να τονίσω είναι ότι ο κώδικασ ήταν λιγάκι παραπάνο απαιτητικόσ απο ότι μπορούσα να διαχειριστώ για τον λόγο ότι δεν γνωρίζω αρκετά καλά την γλώσσα προγραμματισμού ώστε να καταλαβαίνω 100% το τι έγραφα και τι αποτέλεσμα υα έχει αυτο στο παιχνίδι .Εν κατακλείδι η διαδικασία μου άρεσε και θα ήθελα στο κοντινό μέλλον να του δώσω χρόνο και ενέργεια ώστε να το εξελίξω και να μπορέσω να δημιουργήσω κάτι μεγαλύτερο και πιο ενδιαφερον για τους παίκτες με σκοπό να γίνω ανταγωνιστικός στην αγορά φαίρνοντας ένα αξιοπρεπές αποτέλεσμα!

# Sources
https://assetstore.unity.com/packages/2d/characters/hero-knight-pixel-art-165188
https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
https://www.clipartmax.com/download/m2H7N4b1m2A0G6G6_spikes-spikes-pixel-art/#
https://youtu.be/qKlCT5vRuIU
https://www.google.com/search?q=bomb+pixel+art+png&tbm=isch&ved=2ahUKEwjuuMv--ML8AhUDvkwKHR7wBlUQ2-cCegQIABAA&oq=bomb+pixel+art&gs_lcp=CgNpbWcQARgBMgQIIxAnMgcIABCABBATMgcIABCABBATMgcIABCABBATMggIABAHEB4QEzIICAAQBxAeEBMyCAgAEAcQHhATMggIABAHEB4QEzIICAAQBxAeEBMyCAgAEAcQHhATUABYAGDoCWgAcAB4AIABXIgBXJIBATGYAQCqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=hnfAY-7dKYP8sgKe4JuoBQ&bih=723&biw=1482&client=opera&hs=Llm&hl=el#imgrc=UEd3SKWSSEPL3M
https://www.google.com/search?q=bomb+pixel+art+png&tbm=isch&ved=2ahUKEwjuuMv--ML8AhUDvkwKHR7wBlUQ2-cCegQIABAA&oq=bomb+pixel+art&gs_lcp=CgNpbWcQARgBMgQIIxAnMgcIABCABBATMgcIABCABBATMgcIABCABBATMggIABAHEB4QEzIICAAQBxAeEBMyCAgAEAcQHhATMggIABAHEB4QEzIICAAQBxAeEBMyCAgAEAcQHhATUABYAGDoCWgAcAB4AIABXIgBXJIBATGYAQCqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=hnfAY-7dKYP8sgKe4JuoBQ&bih=723&biw=1482&client=opera&hs=Llm&hl=el#imgrc=UEd3SKWSSEPL3M

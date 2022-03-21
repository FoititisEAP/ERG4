
# ΓΡΑΠΤΗ ΕΡΓΑΣΙΑ 4

![ΕΑΠ](/images/eap_logo.png)
### ΕΛΛΗΝΙΚΟ ΑΝΟΙΚΤΟ ΠΑΝΕΠΙΣΤΗΜΙΟ, ΣΧΟΛΗ ΘΕΤΙΚΩΝ ΕΠΙΣΤΗΜΩΝ ΚΑΙ ΤΕΧΝΟΛΟΓΙΑΣ

### ΠΡΟΓΡΑΜΜΑ ΣΠΟΥΔΩΝ ΣΔΥ: «ΣΧΕΔΙΑΣΗ ΚΑΙ ΑΝΑΠΤΥΞΗ ΣΥΣΤΗΜΑΤΩΝ ΔΙΑΧΥΤΟΥ ΥΠΟΛΟΓΙΣΜΟΥ»

ΘΕΜΑΤΙΚΗ ΕΝΟΤΗΤΑ: ΣΔΥ60
ΑΚΑΔΗΜΑΪΚΟ ΕΤΟΣ: 2021-2022

## ΣΤΟΙΧΕΙA ΠΟΥ ΣΥΜΠΛΗΡΩΝΕΙ Ο ΦΟΙΤΗΤΗΣ / Η ΦΟΙΤΗΤΡΙΑ

Πατήστε το κουμπί της επεξεργασίας και συμπληρώστε τα παρακάτω στοιχεία:

Αποθετήριο: https://github.com/FoititisEAP/ERG4

Username και password στην πλατφόρμα Thingsboard (μόνο σε περίπτωση που επιλέξετε να εργαστείτε με την cloud έκδοση):

ΑΜ:150661

Όνομα-Επώνυμο: ΣΤΥΛΙΑΝΟΣ ΘΩΜΑΣ

Υπεύθυνη Δήλωση Φοιτητή: Βεβαιώνω ότι είμαι συγγραφέας αυτής της εργασίας και ότι κάθε βοήθεια την οποία είχα για την προετοιμασία αυτής της εργασίας, είναι πλήρως αναγνωρισμένη και αναφέρεται είτε στο σημείο «Σχόλια προς καθηγητή» είτε μέσα στην εργασία. Επίσης, έχω αναφέρει τυχόν πηγές από τις οποίες έκανα χρήση δεδομένων, ιδεών ή στοιχείων, είτε αυτά αναφέρονται ακριβώς είτε παραφρασμένα. Επίσης, βεβαιώνω ότι η εργασία αυτή προετοιμάστηκε από εμένα προσωπικά ειδικά για τη συγκεκριμένη Θεματική Ενότητα.

-[x] Συμφωνώ και αποδέχομαι την ανωτέρω δήλωση

-[] Δε συμφωνώ και δεν αποδέχομαι την ανωτέρω δήλωση (στην περίπτωση αυτή, ο Κ-Σ έχει δικαίωμα να μην αξιολογήσει την εργασία του φοιτητή)

## ΣΤΟΙΧΕΙΑ ΕΚΠΑΙΔΕΥΤΙΚΟΥ ΕΝΔΙΑΦΕΡΟΝΤΟΣ

### Σκοπός ΓΕ

Με την επιτυχή ολοκλήρωση αυτής της εργασίας, θα έχετε:

Α) Πρακτική εμπειρία ανάλυσης και σχεδίασης της διάδρασης με συσκευές χρήστη, 
Β) Πρακτική επαφή με λογισμικό δημιουργίας πρωτοτύπων χαμηλής πιστότητας, 
Γ) Εξοικείωση με εργαλεία εγκατάστασης και διαχείρισης περιβάλλοντος ΙοΤ (Internet of Things) .

### Μέθοδος και παραδοτέα

Κάθε εργασία περιέχει ερωτήματα που αφορούν την αναζήτηση βιβλιογραφίας (άρθρα, links, βίντεο). Στόχος είναι να αναπτύξετε τις απαντήσεις σας ως μια κριτική σύνθεση, να επιλέξετε τα καταλληλότερα άρθρα, να συνθέσετε συλλογισμούς από αυτά και να παραθέσετε τη δική σας προοπτική. Σημαντική είναι η κριτική σύνθεση κατ' αντιδιαστολή της απλής παράθεσης εναλλακτικών λύσεων-προτάσεων από διαφορετικές πηγές, κάτι που σημαίνει στη βαθμολόγηση δίδεται έμφαση στην ποιότητα της σύνθεσης και όχι στην ποσότητα των βιβλιογραφικών αναφορών.

Ο τρόπος εργασίας είναι ίδιος για όλα τα θέματα προγραμματισμού. Αρχικά, γίνεται εγκατάσταση του εργαλείου ανάπτυξης ή/και κάποιας βιβλιοθήκης. Στη συνέχεια, γίνεται εκτέλεση κάποιου απλού παραδείγματος από αυτά που είναι διαθέσιμα είτε στο περιβάλλον ανάπτυξης, ή/και στην αντίστοιχη βιβλιοθήκη, ή σε κάποια υπηρεσία διαμοιρασμού κώδικα (π.χ., github, stackoverflow) ώστε να είναι σίγουρο ότι όλα δουλεύουν. Στις περισσότερες περιπτώσεις, το ζητούμενο είναι μια μικρή μετατροπή του κώδικα του παραδείγματος ώστε να εξυπηρετεί άλλο σκοπό. Φυσικά, θα πρέπει να δώσετε αναφορά στην πηγή και να τεκμηριώσετε μόνο τις δικές σας αλλαγές.

*Παραδοτέα:* Για κάθε ερώτημα που ζητάει οθόνες από εφαρμογές ή απαιτεί εκτέλεση κώδικα, η απάντηση θα πρέπει να περιλαμβάνει μία ή περισσότερες ενδεικτικές οθόνες (screenshots) στις οποίες θα φαίνεται τόσο το περιβάλλον ανάπτυξης με τον κώδικα καθώς και το αποτέλεσμα της εκτέλεσης. Η αναφορά δεν περιέχει κώδικα αλλά περιέχει τις ενδεικτικές οθόνες, τις οποίες καλό είναι να έχετε αποθηκεύσει σε εξωτερική υπηρεσία αποθήκευσης αρχείων (π.χ., imgur, dropbox) και να βεβαιωθείτε ότι δεν είναι πολύ μεγάλες (π.χ., 100KB για κάθε εικόνα-οθόνη είναι συνήθως αρκετά). Ο πηγαίος κώδικας θα πρέπει να βρίσκεται σε ξεχωριστά δημόσια αποθετήρια, τα οποία μπορούν να είναι φορκ-αντίγραφο από κάποιο παράδειγμα που βρήκατε. Βίντεο ή/και εκτελέσιμος κώδικας είναι προαιρετικά και στέλνονται μόνο με κάποιο link σε υπηρεσία διαμοιρασμού αρχείων και όχι μέσω του study.eap.gr, στο οποίο υπάρχουν στενοί περιορισμοί όσον αφορά το μέγεθος των αρχείων. 

### ΥΠΟΔΕΙΞΕΙΣ ΓΙΑ ΤΗ ΣΥΓΓΡΑΦΗ ΤΗΣ ΕΡΓΑΣΙΑΣ

Για την υποβολή της τελικής αναφοράς (README.md) της ΓΕ θα χρησιμοποιείται η υπηρεσία φιλοξενίας και διαμοιρασμού αρχείων κειμένου-κώδικα [github](http://github.com). Εκεί θα ανεβάζετε όλα τα αρχεία της εργασίας σας (π.χ. αναφορά, κώδικα), εκτός από τα μεγάλα αρχεία (εικόνες, βίντεο, εκτελέσιμα). Μπορείτε να εργαστείτε είτε μέσω της διαδικτυακής διεπαφής της υπηρεσίας είτε τοπικά στον υπολογιστή σας.

Ο φοιτητής μπορεί να στείλει προαιρετικά πρόσθετα μεγάλα αρχεία (π.χ., βίντεο, εκτελέσιμο) για την εργασία με μορφή συμπιεσμένου αρχείου zip ή rar με ένα link από την αναφορά (README.md) προς μια υπηρεσία διαμοιρασμού αρχείων (π.χ., dropbox, drive). Το όνομα του αρχείου θα είναι: SDYxx_xERG_EPITHETO_ONOMA.zip (συμπληρώστε ανάλογα με τον κωδικό της ΘΕ xx και τον αριθμό x της εργασίας). Συνίσταται η χρήση λατινικών χαρακτήρων για την αποφυγή προβλημάτων.

Για την απάντηση της εργασίας, θα πρέπει να χρησιμοποιηθεί το υπόδειγμα της εργασίας. Οι περισσότερες απαντήσεις βασίζονται σε ενδεικτικές οθόνες από την εκτέλεση λογισμικού, λεζάντες, σύντομες περιγραφές, και αναφορές σε βιβλιογραφία. Οι πολλές εικόνες, ειδικά αν δεν έχουν επεξεργαστεί σωστά, θα δημιουργήσουν μεγάλα αρχεία. Επειδή οι ενδεικτικές οθόνες μπορεί, λοιπόν, να μεγαλώσουν πολύ το μέγεθος του τελικού αρχείου ή να μην έχουν συνέπεια εμφάνισης σε διαφορετικούς υπολογιστές (ειδικά σε προγράμματα όπως το Microsoft Office), η τελική αναφορά πρέπει να είναι σε *PDF*. Για τη μετατροπή από markdown σε PDF, μπορείτε να επιλέξετε την εκτύπωση από τον chrome και μετά να αποθηκεύσετε ως αρχείο PDF. 

Πέρα από την υποβολή στο github είναι **υποχρεωτική** η υποβολή σε .PDF αρχείο της τελικής έκδοσης της ΓΕ στο [study.eap.gr](https://study.eap.gr/login/index.php) πριν της εκπνοή της καταληκτικής ημερομηνίας παράδοσης με όνομα SDYxx_xERG_EPITHETO_ONOMA.pdf που θα περιέχει την απάντηση της εργασίας (συμπληρώστε ανάλογα με τον κωδικό της ΘΕ xx και τον αριθμό x της εργασίας), έτσι ώστε το σύστημα να κάνει έλεγχο λογοκλοπής.

Μην ξεχάσετε να δηλώσετε εάν η εργασία αποτελεί προϊόν αποκλειστικά δικής σας εργασίας και να κάνετε αναφορά σε τυχόν άρθρα και κώδικα τα οποία χρησιμοποιήσατε.

Αν δεν έχετε απαντήσει σε ένα ερώτημα, γράψτε ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ. Αν απαντήσατε με ελλείψεις σε ένα ερώτημα γράψτε ΑΠΑΝΤΗΘΗΚΕ ΕΛΛΙΠΩΣ.

Η συνεργασία στην ανάλυση της εργασίας επιτρέπεται, αλλά καλό είναι να αναφερθεί στον ειδικό χώρο στην πρώτη σελίδα της εργασίας. Η συνεργασία δεν πρέπει να οδηγεί σε από κοινού επίλυση και συγγραφή της εργασίας. Η υποβολή κοινών απαντήσεων από διαφορετικούς φοιτητές που συνεργάστηκαν δεν επιτρέπεται και θεωρείται ως ΑΝΤΙΓΡΑΦΗ. Οι απαντήσεις ελέγχονται, τόσο μεταξύ των φοιτητών του ιδίου τμήματος, όσο και μεταξύ φοιτητών διαφορετικών τμημάτων. Η αντιγραφή έχει ως αποτέλεσμα το ΜΗΔΕΝΙΣΜΟ ΤΗΣ ΕΡΓΑΣΙΑΣ ΣΥΝΟΛΙΚΑ και την παραπομπή των παραβατών στην Κοσμητεία της Σχολής Θετικών Επιστημών & Τεχνολογίας, σύμφωνα με τον εσωτερικό κανονισμό του ΕΑΠ.

Η παρούσα ΓΕ είναι **ΑΤΟΜΙΚΗ**


Στόχος της συγκεκριμένης εργασίας είναι η εξοικείωση και η εμβάθυνση σας σε λειτουργίες σχηματισμού, οργάνωσης, διαχείρισης και ελέγχου ενός συστήματος  ΙοΤ. Μετά την επιτυχή ενασχόληση σας με τα ζητούμενα αυτής της ΓΕ θα είστε σε θέση να εισάγετε συσκευές σε ένα περιβάλλον ΙοΤ, να υλοποιείτε την εγκατάσταση επικοινωνίας μεταξύ αυτών και ενός κεντρικού κόμβου συλλογής δεδομένων κάνοντας χρήση διαφόρων υποστηριζόμενων πρωτοκόλλων, να παρακολουθείτε την ομαλή λειτουργία των διασυνδεδεμένων συσκευών, να επεξεργάζεστε απλά και σύνθετα συμβάντα μέσω του ορισμού κατάλληλων κανόνων καθώς και να έχετε μια εποπτεία των δεδομένων του συστήματος.
   


### Η πλατφόρμα Thingsboard ###  

Για τους σκοπούς της άσκησης θα χρησιμοποιηθεί η πλατφόρμα [Thingsboard]( https://thingsboard.io/). Πρόκειται για μια διαδεδομένη IoT πλατφόρμα ανοιχτού κώδικα για τη συλλογή, επεξεργασία και οπτικοποίηση δεδομένων καθώς και για την αποτελεσματική διαχείριση συσκευών. Η πλατφόρμα υποστηρίζει συνδεσιμότητα των συσκευών μέσω ευρέως χρησιμοποιούμενων πρωτοκόλλων IoT (MQTT, CoAP and HTTP) και υποστηρίζει κλιμακωσιμότητα του περιβάλλοντος IoT καθώς και ανοχή σε σφάλματα.

Η πλατφόρμα Thingsboard διαθέτει πολύ καλό [documentation](https://thingsboard.io/docs/), στο οποίο μπορείτε να ανατρέξετε όχι μόνο για μια πρώτη εξοικείωση με την πλατφόρμα αλλά και για οποιαδήποτε απορία έχετε κατά τη διάρκεια εκπόνησης της εργασίας σας. Πέρα από αυτό το documentation, είναι διαθέσιμη μια σειρά από [εκπαιδευτικά videos]( https://www.youtube.com/results?search_query=thingsboard+ce+education) στα οποία αναλύονται τα κύρια λειτουργικά χαρακτηριστικά της πλατφόρμας, καθώς και πλήθος άλλων [video tutorials]( https://www.youtube.com/channel/UCDb9fsV-YR4JmnipAMGsVAQ/videos), τα οποία ασχολούνται με πιο εξειδικευμένα θέματα. Τέλος, η [Thingsboard Community]( https://thingsboard.io/community/) προσφέρει τη δυνατότητα επαφής και αλληλεπίδρασης με άλλους χρήστες της πλατφόρμας ενώ το αντίστοιχο [blog]( https://blog.thingsboard.io/) παρουσιάζει εμπειρίες από την χρήση της σε συγκεκριμένα use cases. 

Για τους σκοπούς της παρούσας ΓΕ θα εργαστούμε με την Community Edition της πλατφόρμας η οποία διατίθεται δωρεάν. Για την απάντηση των ερωτημάτων συνιστάται ισχυρά η χρήση της [online demo έκδοσης]( https://demo.thingsboard.io/signup), κατόπιν δημιουργίας του αντίστοιχου λογαριασμού, χωρίς αυτό να σημαίνει ότι δεν είστε ελεύθεροι να επιλέξετε και την εγκατάσταση της εφαρμογής, τοπικά (locally), σε ένα workstation της επιλογής σας βάσει οδηγιών που μπορούν να βρεθούν [εδώ](https://thingsboard.io/docs/user-guide/install/installation-options/) αν προτιμάτε. **Προσοχή: αν επιλέξετε κάποια άλλη έκδοση πέρα από τη online demo έκδοση, ελέγξτε πριν ξεκινήσετε τυχόν χρονικούς περιορισμούς**

Στην περίπτωση που χρησιμοποιήσετε την online demo έκδοση της πλατφόρμας θα πρέπει να κοινοποιήσετε εντός της εργασίας που θα παραδώσετε τα credentials σας (username και password) για την είσοδο σε αυτήν. Σε περίπτωση που επιλέξετε την προσέγγιση της τοπικής εγκατάστασης θα πρέπει να παραδώσετε  σε αντίστοιχο φάκελο στο github όλα τα αρχεία που αναπτύξατε προς απάντηση των αντίστοιχων ερωτημάτων. Υπογραμμίζεται ότι σε κάθε περίπτωση θα πρέπει **εντός της εργασίας να τεκμηριώσετε όλα τα βασικά βήματα της διαδικασίας που ακολουθήσατε συνοδευόμενα από κατάλληλα screenshots**.

Για τις ανάγκες του συγκεκριμένου θέματος της ΓΕ δεν απαιτείται η προμήθεια κάποιου εξοπλισμού IoT καθώς τα ζητούμενα μπορούν να απαντηθούν με τη χρήση και προσομοίωση «εικονικών» συσκευών, οι οποίες υποστηρίζονται από την πλατφόρμα. Θα ήταν όμως εξαιρετικά ενδιαφέρον αν κάποιος φοιτητής έχει πρόσβαση σε αντίστοιχο hardware (π.χ. microcontroller με αισθητήρες κτλ.) να προσπαθήσει να το εντάξει στη λύση που θα αναπτυχθεί. Οδηγίες και παραδείγματα για τη διασύνδεση διάφορων τύπου hardware μπορούν να βρεθούν [εδώ]( https://thingsboard.io/docs/guides/#AnchorIDHardwareSamples).

### Η περίπτωση της εισαγωγής ΙοΤ στον τομέα της εστίασης ###  

Όπως γνωρίζετε οι τεχνολογίες ΙοΤ βρίσκουν εφαρμογή σε ένα τεράστιο εύρος περιπτώσεων χρήσης, μερικές από τις οποίες ενδεικτικά παρουσιάζονται [εδώ]( https://github.com/thingsboard/thingsboard). Η εισαγωγή των τεχνολογιών Internet of Things (IoT) σε ολοένα και περισσότερες πτυχές της καθημερινότητάς μας, δε θα μπορούσε να μην επηρεάσει και τον τομέα της παράδοσης φαγητού (food delivery), μετασχηματίζοντας τρέχουσες πρακτικές σε όλες τις φάσεις της υπηρεσίας (παραγγελία, προετοιμασία, παράδοση). Αρκετές καινοτόμες υπηρεσίες και ερευνητικές προσπάθειες, υιοθετούν λύσεις Internet of Things, αλλάζοντας ριζικά τις τρέχουσες πρακτικές και προτείνοντας νέα επιχερηματικά μοντέλα. Κάποια τέτοια ενδιαφέροντα παραδείγματα μπορείτε να δείτε στον εξής [σύνδεσμο](https://www.aeris.com/news/post/food-glorious-food-iot-and-the-restaurant-delivery-market/).

Στα πλαίσια αυτής της ΓΕ, συνεχίζοντας στην ίδια θεματική με τις ΓΕ2 και ΓΕ3, καλείστε να σχεδιάσετε ένα τέτοιο σύστημα παράδοσης φαγητού που θα ενσωματώνει τεχνολογίες IoT για την επίτευξη στόχων όπως την πιο αποτελεσματική, την πιο οικονομική, την πιο φιλική προς το περιβάλλον ή την πιο ασφαλή (όσον αφορά την ποιότητα του φαγητού) παροχή της υπηρεσίας. Εξακολουθούν να ισχύουν οι περιορισμοί για μειωμένο περιβαλλοντικό αποτύπωμα των παραδόσεων, αλλά μπορείτε επιπλέον να προβλέψετε στο σύστημα σας και τη χρήση ηλεκτρικών αυτοκινήτων ή/και μηχανών.

## Μέρος Α – Σχεδιασμός συατήματος Internet of Things για την περίπτωση της παράδοσης φαγητού: 25 μονάδες #

#### Ερώτημα 1 – Μελέτη βιβλιογραφίας και σχετικών διαθέσιμων προϊόντων  [15 μονάδες]

Ετοιμάστε μια σύντομη αναφορά (600-800 λέξεων) η οποία να περιλαμβάνει παρουσίαση σχετικών ερευνητικών εργασιών καθώς και εμπορικά διαθέσιμων προϊόντων στο πεδίο εφαρμογής τεχνολογιών IoT στο χώρο της εστίασης με κύρια έμφαση, όμως, στην παράδοση του φαγητού». Εστιάστε την απάντηση σας στην υποδομή, την τοπολογία και την υλοποίηση επικοινωνίας που υιοθετούνται σε καθεμία από τις παρουσιαζόμενες λύσεις. Ο σκοπός σε αυτό το ερώτημα είναι να γίνει κατανόηση και κριτική σε υπάρχουσες εργασίες ως θεωρητικό πλαίσιο για την ανάπτυξη που θα γίνει στα επόμενα ερωτήματα.

Για την επιστημονική βιβλιογραφία θα βρείτε πολλά σχετικά άρθρα στο [Google Scholar](http://scholar.google.com). Τα άρθρα που θα διαλέξετε θα πρέπει να έχουν τουλάχιστον δύο ετεροαναφορές / έτος και να έχουν δημοσιευτεί μετά το 2014. Η αναφορά των άρθρων στο κείμενό σας θα πρέπει να γίνει με το στυλ APA και θα πρέπει να βρίσκεται στο τέλος της αντίστοιχης απάντησης.  



##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.


Α) Enuke Software

https://www.enukesoftware.com/food-delivery-application-development-company.html

Η Food Box είναι μία δυναμική κινητή εφαρμογή της Enuke (Digital Power House), η οποία αποτελεί Υπηρεσία παράδοσης φαγητού με δυνατότητα εύρεσης αντίστοιχων καταστημάτων εστίασης – από μικρά έως αλυσίδες μεγάλων εταιριών (βλ. Εικόνα Α1 & Α2). 
Στις δυνατότητές της, παρέχεται:

- η εφαρμογή επιλογών διαφορετικών φίλτρων όπως τοποθεσία (κινητής) συσκευής, τύπος κουζίνας, κλπ.
- Λεπτομερής παρακολούθηση της παραγγελίας σε πραγματικό χρόνο από μεριάς του πελάτη με χρήση GPS. (Ανάλογη δυνατότητα παρέχει και η Instacart (https://www.instacart.com/), μέσω της οποίας μπορεί κανείς να παραγγείλει λαχανικά, καλυντικά, κ.α., και η οποία κάνει χρήση του Github για τη φιλοξενία του κώδικά του (https://www.mobindustry.net/blog/the-technology-behind-instacart/)).
- Η συνδεσιμότητα είναι εύκολη, ενώ ο οποιοσδήποτε μπορεί να παραγγείλει χωρίς να υπάρχει το ενδεχόμενο ο μεταφορέας του φαγητού να μη βρει την τοποθεσία της παραγγελίας, αφού αυτή μπορεί να παρέχεται από τη χρήση του ΔτΠ.
- Υπάρχει (όπως ισχυρίζεται η εταιρία) η δυνατότητα της παράδοσης φρεσκομαγειρεμένου φαγητού ακριβώς τη στιγμή άφιξης του πελάτη στο σπίτι του.



![Εικόνα Α1](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/Α1-1.%20Enuke1.jpg)

Εικόνα Α1 - Δυνατότητες της εφαρμογής



![Εικόνα Α2](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/Α1-2.%20Enuke2.jpg)


Εικόνα Α2 - Λειτουργίες της εφαρμογής


Β) Άλλη μία εταιρία παράδοσης φαγητού είναι η Doordash (https://www.doordash.com/), η οποία απέκτησε την Scotty Labs τον Αύγουστο του 2019. Η τελευταία ασχολείται με τον απομακρυσμένο έλεγχο οχημάτων. 
Η βασική αρχή της τελευταίας είναι ότι: “η αυτονομία και ο απομακρυσμένος έλεγχος είναι το μέλλον” (https://techcrunch.com/2019/08/20/doordash-acquires-autonomous-driving-startup-scotty-labs/?guccounter=1&guce_referrer=aHR0cHM6Ly9kdWNrZHVja2dvLmNvbS8&guce_referrer_sig=AQAAAAJVq1CL3ITxaW37-VrfT-oG3HTYRwxuLqfXZtBIY6Itq0wOMg-qUiym8xTGV6ZIoLMhnTr7zRAQCyGqiJSW2k9DxvluQMFuPPGWn7y0HybhhIlGK0FNmnsiAj55zbtHkkQ40JA_1miBwiwItuvDizTkLAnHnUnWcYJA4tDTvyHp και https://www.theverge.com/2019/8/21/20826327/doordash-acquires-scotty-labs-autonomous-vehicle-remote-control-startup). Δύο παραδείγματα προϊόντων της (στις ΗΠΑ) είναι ένα αυτοκινούμενο όχημα σε λεωφόρο της Καλιφόρνια (https://www.youtube.com/watch?v=-ruCxPV8wDk&t=7s) και ο απομακρυσμένος έλεγχος αυτοκινήτου στο Σαν Φρανσίσκο (https://www.youtube.com/watch?v=OYk-IUeiT48&t=2s). Και προφανώς κάποιος θα μπορούσε να σκεφτεί ότι η Doordash έχει στις προοπτικές της την εφαρμογή αυτών των πρωτοτύπων σε σχέση με την παράδοση φαγητού.
Νωρίτερα (2017), σε συνεργασία με την Starship Technologies έκανε μία προσπάθεια παράδοσης φαγητού με χρήση ημιαυτόνομων ρομπότ (Βλ. Εικόνα Α3). (https://www.theverge.com/2017/1/18/14300054/food-delivery-robots-postmates-doordash-us-launch). Αξίζει να αναφερθεί ότι τα εν λόγω ρομπότ έφταναν την ταχύτητα των 6,48 χλμ/ώρα (4 μιλίων/ώρα) (https://www.digitaltrends.com/cool-tech/starship-technologis-doordash-postmates/)

![Εικόνα Α3](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/Α1-3.%20starship-delivery-robot-029.0.0%20-%20β.jpg)

Εικόνα Α3


Ακόμη,  συνεργάστηκε για τον ίδιο λόγο και με την εταιρία Marble (βλ. Εικόνα Α4). (https://medium.com/@DoorDash/welcoming-our-newest-robots-to-the-doordash-fleet-with-marble-e752a85d6602)


![Εικόνα Α4](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/Α1-4.%20Doordash%20-%20Marble.jpeg)

Εικόνα Α4

Τέλος, το ίδιο έτος, συνεργάστηκε με την General Motors για τον έλεγχο λειτουργίας Υπηρεσίας παράδοσης φαγητού στο Σαν Φρανσίσκο, χρησιμοποιώντας αυτόνομα οχήματα (βλ. Εικόνα Α5). (https://www.theverge.com/2019/1/3/18166660/gm-cruise-doordash-test-self-driving-food-delivery και https://www.youtube.com/watch?v=NEj-4d0SHPI)

![Εικόνα Α5](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/A1-5.%20cruise_gm_bolt.0.jpg)

Εικόνα Α5

 Η  Doordash έχει εξαγοράσει και την Φινλανδική Wolt στις 9/11/2021, η οποία δραστηριοποιείται και σε κάποιες πόλεις της Χώρας μας (Θεσσαλονίκη, Λάρισα, Πάτρα, Ηράκλειο, Βόλος, Χανιά, Αθήνα) από το 2019 (https://en.wikipedia.org/wiki/Wolt).

Γ) Η Serve Robotics (https://www.serverobotics.com/) έχει δημιουργήσει εμπορικά διαθέσιμα αυτόνομα οχήματα που μπορούν να ικανοποιούν την ανάγκη για παράδοση φαγητού. Τα οχήματά της περιλαμβάνουν συστήματα πλοήγησης με έξυπνες κάμερες ΔτΠ και χρήση υπερήχων για να αντιλαμβάνονται τα πεζοδρόμια σε μία μεγαλούπολη (βλ. Εικόνα Α6). Η ίδια εταιρεία αναπτύσσει και το Lidar, μία τεχνική που ανιχνεύει το τοπίο σε τρισδιάστατη μορφή.
(Βλ. https://www.youtube.com/watch?v=wfnZnjx37fQ, https://www.youtube.com/watch?v=Zj8uxCHPBQg, https://www.youtube.com/watch?v=sCes61Qr3KA, https://www.youtube.com/watch?v=LnrYfHwCp5A και https://www.youtube.com/watch?v=PZtacRUSMUc).


![Εικόνα Α6](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/A1-6.%20Serve%20Robotics.jpg)

Εικόνα Α6

Έτσι, έχει εξασφαλιστεί μεγάλη επένδυση από την αμερικανική επιχείρηση παροχής υπηρεσιών Uber(https://www.uber.com/) (θυγατρική της οποίας είναι οι εταιρίες παράδοσης φαγητού Uber Eats (https://www.ubereats.com/ και https://en.wikipedia.org/wiki/Uber_Eats) και η Postmates (https://postmates.com/ και https://en.wikipedia.org/wiki/Postmates) (https://www.iotworldtoday.com/2022/01/19/uber-spinoff-starts-all-autonomous-deliveries-in-la/ και https://www.serverobotics.com/serve-secures-funding). Το ρομπότ της Postmates (βλ. Εικόνα Α6), με όνομα Serve, μπορούσε το 2018 να φέρει βάρος έως 22,68 κιλά (50 pound) και να διανύσει απόσταση έως περίπου 48 χλμ (30 μιλίων), που ισοδυναμεί περίπου με 12 παραδόσεις(στις ΗΠΑ). Εφερε αισθητήρες Velodyne Lidar για την αποφυγή εμποδίων και επεξεργαστή Nvidia Xavier (https://www.digitaltrends.com/cars/nvidia-xavier-processor-news-uses-capacities-partnerships/). Επίσης, φέρει φανάρι ασφαλείας στο πάνω μέρος του, τα “μάτια” του κινούνται προς την κατεύθυνση που θα κινηθεί και ο διαχειριστής του μπορεί να το χειριστεί απομακρυσμένα κατά βούληση. Έχει οθόνη αφής για την πληκτρολόγηση του κωδικού παραγγελίας, ώστε ο πελάτης να λάβει την παραγγελία του, ενώ υπάρχει και πλήκτρο βοήθειας, μέσω του οποίου μπορεί κάποιος να επικοινωνήσει με την εταιρία αν προκύψει κάποιο πρόβλημα. Τα πιθανά προβλήματα που μπορεί να προκύψουν από αυτήν τη νέα τεχνολογία είναι τα εξής: είναι επιρρεπή σε βανδαλισμό ή κλοπή, το ενδεχόμενο ο οποισδήποτε να “αστειευτεί” βάζοντας μία κουβέρτα επάνω σ’αυτό (αποπροσανατολίζοντάς το) και η έλλειψη νομοθετικού πλαισίου για την κυκλοφορία τους (https://www.digitaltrends.com/cool-tech/say-hello-to-serve-postmates-cute-autonomous-delivery-robot/). Ανάλογο ρομπότ, κινούμενο στους 2 τροχούς είναι το YAPE(Your Autonomous Pony Express) της Ιταλικής E-Novia (βλ. Εικόνα Α7). Μπορεί να φέρει φορτίο έως 20 κιλά, με ταχύτητα έως 3,7 χλμ/ώρα στα πεζοδρόμια και έως 20 χλμ/ώρα στους ποδηλατόδρομομυς, και κάλυψη απόστασης έως 80 χλμ! Για την παράδοση του πακέτου, ο πελάτης θα πρέπει να 	έχει καταχωρηθεί στο Σύστημα, και λαμβάνει την παραγγελία του με χρήση αναγνώρισης προσώπου. (https://www.digitaltrends.com/cool-tech/delivery-robot-yape-e-novia/, https://newatlas.com/yape-ground-delivery-drone/52751/, https://e-novia.it/startup/yape/, https://www.yapemobility.it/ και https://www.youtube.com/embed/zySD-4Q4sBo?enablejsapi=1)


![Εικόνα Α7](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/A1-7.%20yape.jpg)

Εικόνα Α7


Δ) Η Panasonic έχει δημιουργήσει το προϊόν της με όνομα “Food Locker” (https://na.panasonic.com/us/smart-locker), το οποίο θα μπορούσε να χρησιμοποιηθεί σε μία προσέγγιση υλοποίησης παράδοσης φαγητού με χρήση του ΔτΠ (βλ. Εικόνα Α8 & Εικόνα Α9). Με τη χρήση αυτού του προϊόντος, ο πελάτης ενός εστιατορείου, μπορεί να παραγγείλει το φαγητό του, έχοντας εξασφαλισμένη την ποιότητα και ασφάλεια μεταφοράς φρέσκου φαγητού. Τα “κουτιά” αυτά μπορούν να ανοιχτούν μόνο από τον πελάτη με τον κωδικό παραγγελίας. Ο κωδικός σαρώνεται, το κουτί ανοίγει, ο πελάτης παίρνει το φαγητό του και όταν κλείσει το Food Locker, η διαδικασία παράδοσης/παραγγελίας έχει ολοκληρωθεί.

![Εικόνα Α8](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/A1-8.%20agnostic-584x389.jpg)

 Εικόνα Α8
 

![Εικόνα Α9](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Α1/A1-9.%20panasonic-smart-food-lockers-3-easy-steps-to-a-contactless-carry-out-solution-for-food-service.jpg)
 
 Εικόνα Α9


 


#### Ερώτημα 2 – Σχεδιασμός συστήματος ΙοΤ στην διανομή φαγητού  [10 μονάδες]
Περιγράψτε σύντομα το σύστημα ΙοΤ που σχεδιάζετε να υλοποιήσετε. Αναφερθείτε στο στόχο του, στο πεδίο εφαρμογής του, στις προβλεπόμενες συσκευές, στους εμπλεκόμενους χρήστες κτλ. Παραδείγματα use cases συστημάτων ΙοΤ που έχουν υλοποιηθεί μέσω της πλατφόρμας Thingsboard, μπορούν να βρεθούν [εδώ](https://github.com/thingsboard/thingsboard).

**Προσοχή: Η απάντηση σας δεν χρειάζεται να σχετίζεται με το ερώτημα Α4 της ΓΕ2. Είστε ελεύθεροι να προτείνετε έναν εντελώς ή μερικώς διαφορετικό σχεδιασμό. Σε περίπτωση που επιλέξετε να συνεχίσετε με το σύστημα που είχατε περιγράψει στο ερώτημα εκείνο, παρακαλείστε εδώ να εξειδικεύσετε περαιτέρω την απάντηση σας.** 


##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ. Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.


Οι στόχοι του συστήματος είναι:
α) οι όσο το δυνατόν πιο φιλικές προς το περιβάλλον Υπηρεσίες παράδοσης φαγητού προς τους πελάτες, με ισχυρή προτεραιότητα στο μειωμένο περιβαλλοντικό αποτύπωμα.
β) η ποιοτικότερη παράδοση φαγητού, με ασφάλεια και αναλλοίωτη ποιότητα από το κατάστημα έως τον προορισμό του. Η θερμοκρασία του πακέτου θα πρέπει να είναι εντός συγκεκριμένων ορίων (π.χ. χαμηλά, σε περίπτωση που παραδίδονται παγωτά, αναψυκτικά και άλλα κρύα προϊόντα, και υψηλά, σε περίπτωση που παραδίδονται φρεσκομαγειρεμένα φαγητά, ζεστά σάντουιτς και άλλα ζεστά προϊόντα).
γ) οικονομία καθ'οιοδήποτε τρόπο.
Το πεδίο εφαρμογής του είναι η Υπηρεσία παράδοσης φαγητού σε οποιοδήποτε μέρος, στο οποίο δραστηριοποιείται μία επιχείρηση παράδοσης φαγητού. (Παραδόσεις σε σπίτια, καταστήματα, δημόσιες Υπηρεσίες, εργοστάσια, κλπ.). Η παραγγελία θα λαμβάνεται από το Σύστημα και κάποιος διανομέας θα την παίρνει από το Κατάστημα για να την παραδώσει στον προορισμό του.
Θα χρησιμοποιηθούν για την παράδοση φαγητού ηλεκτρικά ποδήλατα ή/και ηλεκτρικές μοτοσυκλέτες, στον αποθηκευτικό χώρο των οποίων υπάρχουν δύο αισθητήρες. Ο ένας αντιλαμβάνεται την θερμοκρασία του και ο άλλος το εάν για οποιονδήποτε λόγο έχει μείνει ανοικτό το καπάκι του. Αυτοί οι αισθητήρες μπορούν να βρίσκονται εντός μιας συσκευής. Ακόμη, μπορεί να χρησιμοποιηθεί ένας αισθητήρας στην μπαταρία, ο οποίος θα μετράει το πόσο φορτισμένη είναι η μπαταρία του οχήματος. Οι ανωτέρω συσκευές θα ειδοποιούν το διανομέα μέσω bluetooth ασύρματης επικοινωνίας είτε στο κινητό του τηλέφωνο (για να χρησιμοποιηθούν οι αντίστοιχες πληροφορίες κατά περίπτωση από την εφαρμογή μας) είτε στο έξυπνο ρολόι του (με ήχο ή δόνηση).
Οι χρήστες του συστήματός μας θα είναι:
α) οι διανομείς, οι οποίοι θα μπορούν να επιλέγουν τις ώρες εργασίας τους, την περιοχή που θα θέλουν να κινηθούν, τη λήψη παραγγελίας και την παράδοση της παραγγελίας.
β) οι υπεύθυνοι του καταστήματος, οι οποίοι θα μπορούν να κρίνουν εάν οι στόχοι της επιχείρησης ολοκληρώνονται.
γ) οι διαχειριστές του συστήματος, οι οποίοι θα λαβαίνουν επανατροφοδοτήσεις από τις πληροφορίες του συστήματος και αναλόγως θα προβαίνουν σε αλλαγές προκειμένου το σύστημα να προοδεύει.


## Μέρος Β – Υλοποίηση συστήματος IoT στην πλατφόρμα Thingboard για την περίπτωση της χρήσης συστημάτων ΙοΤ στην παράδοση φαγητού: 75 μονάδες #

Στο Μέρος αυτό καλείστε να αναπτύξετε μέσω της πλατφόρμας ThingsBoard ένα περιβάλλον ΙοΤ για την υλοποίηση ενός συστήματος ΙοΤ in food delivery.

#### Ερώτημα 1 – Ορισμός υποδομής, εξασφάλιση επικοινωνίας, παρακολούθηση κατάστασης συστήματος IoT  [35 μονάδες]
 Στα πλαίσια αυτού του ερωτήματος καλείστε:
1.	Να ορίσετε και να εισάγετε στο σύστημα σας **τουλάχιστον 8** συσκευές εισόδου. Η επιλογή του τύπου των συσκευών εξαρτάται από τη φύση και τους στόχους του συστήματος IoT in food delivery που επιθυμείτε να υλοποιήσετε. Δεν χρειάζεται όλες οι συσκευές να είναι διαφορετικού τύπου αλλά δεν έχει νόημα για την ανάπτυξη μιας ολοκληρωμένης λύσης η χρήση π.χ. μόνο 8 θερμομέτρων. 
2.	Η πλατφόρμα Thingsboard δίνει την δυνατότητα επικοινωνίας των συσκευών με το server είτε μέσω IoT Gateway είτε απευθείας. Στα πλαίσια αυτού ερωτήματος θα πρέπει να υλοποιήσετε κατάλληλο Thingsboard IoT Gateway. Πληροφορίες για το ρόλο και τη λειτουργικότητα αυτού του Gateway μπορούν να βρεθούν [εδώ](https://thingsboard.io/docs/iot-gateway/what-is-iot-gateway/). Αρχικά, εγκαταστήστε το gateway βάσει των οδηγιών που θα βρείτε και επιβεβαιώστε ότι οι συσκευές σας το «βλέπουν». Για την επικοινωνία του gateway με την πλατφόρμα Thingsboard, θα πρέπει να υλοποιήσετε αρχικά έναν Connector τύπου [MQTT](https://thingsboard.io/docs/iot-gateway/config/mqtt/), και στη συνέχεια με κατάλληλη πaραμετροποίηση να εγκαταστήστε επικοινωνία μέσω connector άλλου τύπου.
3.	Στο ερώτημα αυτό θα πρέπει να υλοποιήσετε απευθείας επικοινωνία όλων των συσκευών με το server αξιοποιώντας κατάλληλα το [Thingsboard API](https://thingsboard.io/docs/api/), με τη χρήση δυο διαφορετικών πρωτοκόλλων.
4.	Στο ερώτημα αυτό θα υλοποιήσετε μια στοιχειώδη υπηρεσία παρακολούθησης της κατάστασης σύνδεσης των εμπλεκόμενων συσκευών. Για το σκοπό αυτό καλείστε να υλοποιήσετε μηχανισμό ειδοποίησης (alarm) για την περίπτωση που δεν έχει αποσταλεί μέτρηση στον server για περισσότερα από δύο λεπτά. Περισσότερες πληροφορίες για τη συγκεκριμένη υλοποίηση μπορείτε να βρείτε [εδώ](https://thingsboard.io/docs/user-guide/rule-engine-2-0/tutorials/create-inactivity-alarm/).

**Σημείωση 1:** Δεν είναι υποχρεωτικό να υλοποίησετε, στα πλαίσια του μέρους Β, ακριβώς το σύστημα που παρουσιάσατε στο ερώτημα Α2. Αρκεί μία όσο το δυνατόν καλύτερη προσέγγιση αυτού, βάσει των δυνατοτήτων της πλατφόρμας Thingsboard.

**Σημείωση 2:** Στην περίπτωση των εικονικών συσκευών τα δεδομένα εισόδου που θα χρησιμοποιήσετε θα είναι προφανώς συνθετικά, δηλαδή κατασκευασμένα. Μπορούν να προέρχονται είτε από στατικά αρχεία που θα έχετε δημιουργήσει εκ των προτέρων είτε να παράγονται με κάποιο τρόπο δυναμικά τις κατάλληλες χρονικές στιγμές.

##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

Θα χρησιμοποιηθεί η online demo έκδοση του Thingsboard (https://demo.thingsboard.io)

Το όνομα χρήστη για την πρόσβαση στον λογαριασμό μου στο Thingsboard είναι: std150661@ac.eap.gr,
ενώ ο κωδικός μου είναι: 1k@13n@=dy0

**1.**
Η αρχική εικόνα της εφαρμογής παρουσιάζεται στην Εικόνα Β1.

![Εικόνα Β1](https://github.com/FoititisEAP/ERG4/blob/main/Εικόνες/Β1/1.%20Εισαγωγή.jpg)

Εικόνα Β1

Έπειτα, για να εισάγουμε συσκευές εισόδου στο σύστημά μας, ακολουθούμε τα παρακάτω βήματα:
Επιλέγουμε τον σύνδεσμο "Συσκευές", έπειτα "Προσθήκη συσκευής" κάνοντας κλικ στον σταυρό (πάνω δεξιά στην Εικόνα Β2) και "Προσθήκη νέας συσκευής".

![Εικόνα Β2](./Εικόνες/Β1/2.%20Προσθήκη%20συσκευής.jpg)

Εικόνα Β2

Θέτουμε το όνομα της συσκευής ("Θερμόμετρο α'") και πατάμε "Προσθήκη" (Εικόνα Β3).

![Εικόνα Β3](./Εικόνες/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3

Πλέον η συσκευή μας φαίνεται στην καρτέλα "Συσκευές" (Εικόνα Β4 - πρώτη γραμμή).

![Εικόνα Β4](./Εικόνες/Β1/4.%20Θερμόμετρο%20α'%20-2.jpg)

Εικόνα Β4


Συνδέουμε το θερμόμετρό μας με το Σύστημά μας, κάνοντας κλικ στην εγγραφή (σειρά) του και εμφανίζεται η Εικόνα Β5). Επιλέγουμε "Αντιγραφή διακριτικού διαπιστευτηρίου".

![Εικόνα Β5](./Εικόνες/Β1/5.%20Θερμόμετρο%20α'%20-3.jpg)

Εικόνα Β5



(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3


(Εικόνα Β3).

![Εικόνα Β3](./images/Β1/3.%20Θερμόμετρο%20α'.jpg)

Εικόνα Β3





#### Ερώτημα 2 – Επεξεργασία συμβάντων στην πλατφόρμα Thingsboard [20 μονάδες]


Ένα από τα πιο χρήσιμα χαρακτηριστικά της πλατφόρμας ThingsBoard είναι η υποστηριζόμενη Rule Engine.  Πρόκειται για ένα απλό στη χρήση framework μέσω του οποίου μπορεί να γίνει ο χειρισμός και η επεξεργασία (ακόμα και) πολύπλοκων συμβάντων (events). Στα πλαίσια αυτού του ερωτήματος ζητείται:
1.  Αφού δημιουργήσετε τις συσκευές εισόδου στα προηγούμενα ερωτήματα, η υλοποίηση και η διαμόρφωση διαφορετικών Rule Chain(s), όπου με τη χρήση κατάλληλων φίλτρων θα δημιουργείται κατάλληλο alarm για ένα συγκεκριμένο κατώφλι τιμών ή ενδείξεων αυτών (των συσκευών). Χρήσιμες πληροφορίες για τον τρόπο υλοποίησης αυτών μπορείτε να βρείτε [εδώ](https://thingsboard.io/docs/user-guide/rule-engine-2-0/tutorials/create-clear-alarms/). Στα πλαίσια του ερωτήματος καλείστε να ορίσετε και να εισάγετε στο σύστημα σας **τουλάχιστον 3** μηχανισμούς ειδοποίησης (alarms) οι οποίοι θα λειτουργούν βάσει των δεδομένων εισόδου από τους αισθητήρες. Σε περίπτωση που ως ειδοποίηση επιλέξετε την αποστολή e-mail μπορεί να σας φανούν χρήσιμες οι οδηγίες που βρίσκονται [εδώ](https://thingsboard.io/docs/user-guide/rule-engine-2-0/tutorials/send-email/).
2. Να επαληθεύσετε ένα από τα Rule Chains που υλοποιήσατε μέσω της διαδικασίας posting telemetry (ενότητα Validate results στον παραπάνω σύνδεσμο)

##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

#### Ερώτημα 3 – Οπτικοποίηση δεδομένων στην πλατφόρμα Thingsboard [20 μονάδες]


Η πλατφόρμα Thingsboard παρέχει σημαντικές δυνατότητες εποπτείας στους χρήστες και τους διαχειριστές συστημάτων IoT μέσω της δυνατότητας οπτικοποίησης των εμπλεκόμενων δεδομένων και πληροφοριών. Αυτό επιτυγχάνεται με την εισαγωγή και διαμόρφωση κατάλληλων dashboard, τα οποία είναι παραμετροποιήσιμα και δύναται να προσαρμοστούν στα ιδιαίτερα χαρακτηριστικά κάθε συστήματος. Περαιτέρω πληροφορίες μπορείτε να δείτε [εδώ](https://thingsboard.io/docs/user-guide/ui/dashboards/). Στα πλαίσια του συγκεκριμένου ερωτήματος καλείστε να δημιουργήσετε κατάλληλο dashboard το οποίο θα εξυπηρετεί τους σκοπούς του συστήματος "ΙοΤ in food delivery" που σχεδιάσατε, έχοντας υπόψη κατευθυντήριες γραμμές σχεδίασης που συναντήσατε στις προηγούμενες ΓΕ. Ένα dashboard από το οποίο ίσως μπορείτε να αντλήσετε ιδέες μπορείτε να βρείτε [εδώ](https://thingsboard.io/fleet-tracking/), ενώ οδηγίες για το trip animation widget που ενδεχομένως να σας φανεί χρήσιμο για το σχεδιασμό του dashboard σας μπορούν να βρεθούν [εδώ](https://thingsboard.io/docs/user-guide/ui/trip-animation-widget/#device-emulator)


##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

## Μέρος Γ – Παρουσίαση πρόοδου, 10 μονάδες μπόνους

Ετοιμάστε μια παρουσίαση το πολύ 5 λεπτών (5 διαφάνειες) όπου θα αποτυπώνεται η μέχρι τώρα πρόοδος σας στην διαδικασία σχεδιασμού της ζητούμενης εφαρμογής (Μέρος Α). Η παρουσίαση σας θα πρέπει να περιλαμβάνει: 1) συγκριτικό πίνακα σχετικών εργασιών-εφαρμογών και 2) προδιαγραφές της δικής σας εφαρμογής
##### Απάντηση
Δώστε την απάντηση. Εάν δεν έχετε δώσει απάντηση γράψτε με κεφαλαία γράμματα,
ΔΕΝ ΑΠΑΝΤΗΘΗΚΕ Εάν εν γνώση σας δίνετε ελλιπή απάντηση γράψτε με κεφαλαία
γράμματα, ΕΛΛΙΠΗΣ ΑΠΑΝΤΗΣΗ.

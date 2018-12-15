# robotics
Kαγκουρόbot, το έργο ρομποτικής του Εσπερινού ΕΠΑΛ Χανίων

Στην χώρα μας έχουμε πολλά πράγματα για τα οποία θα πρέπει να είμαστε υπερήφανοι, αλλά δυστυχώς αρκετά για τα οποία θα πρέπει να ντρεπόμαστε και να προσπαθήσουμε σθεναρά για να αλλάξουν. Ένα απ’ αυτά αναμφισβήτητα είναι η οδική μας συμπεριφορά, γεγονός που παίζει τον σημαντικότερο ρόλο στην κατάταξη της χώρας μας στην πρώτη θέση στην Ευρώπη σε θανάτους από τροχαία.
Στην πρώτη της κατασκευή η ομάδα «Νυχτερίδες» του Εσπερινού ΕΠΑΛ Χανίων θα προσπαθήσει να αναδείξει το πρόβλημα και να καυτηριάσει δημιουργικά και με χιούμορ την τραγική μας οδική συμπεριφορά στην Ελλάδα κι ένα παραπάνω στον τόπο μας, την Κρήτη.
Για την επίτευξη του παραπάνω στόχου οι «Νυχτερίδες» αποφάσισαν να κατασκευάσουν το… Καγκουρόbot!  To Καγκουρόbot θα είναι ένα αυτόνομο αλλά και τηλεκατευθυνόμενο ρομποτικό όχημα, το οποίο κινούμενο σε μια πίστα (δρόμους πόλης) θα προσομοιώνει την οδική συμπεριφορά ενός συνηθισμένου, καθημερινού… κάγκουρα! Θα προσομοιώνει δηλαδή (στο βαθμό που αυτό είναι εφικτό), την οδική συμπεριφορά ενός συνειδητά ασυνείδητου και επιδειξία οδηγού. 
Πιο συγκεκριμένα η εργασία, την οποία σχεδιάζουν να εκπονήσουν οι «Νυχτερίδες», θα αποτελείται από ένα αυτόνομο (αλλά και τηλεχειριζόμενο) ρομποτικό όχημα βασισμένο σε ένα ελεγκτή Arduino και μια πίστα (πόλη) στην οποία θα κινείται. Το ρομποτικό όχημα (Καγκουρόbot) κατά την διάρκεια της βόλτας του στην πόλη (πίστα) θα σημειώνει μια σειρά από χαρακτηριστικές συνειδητές παραβάσεις, όπως αυτές που καθημερινά βλέπουμε στους δρόμους της πόλης μας:
•	Παραβίαση φωτεινών σηματοδοτών
•	Παράνομες σταθμεύσεις
•	Επικίνδυνη οδήγηση
•	Άσκοπα κορναρίσματα
Για τον έλεγχο φωτεινών σηματοδοτών της πόλης καθώς και για την παραγωγή άλλων σημάτων που θα καθοδηγούν την συμπεριφορά του οχήματος θα χρησιμοποιηθεί ένας δεύτερος ελεγκτής Arduino.
Για την κατασκευή του οχήματος θα χρειαστούν:
  1.	Ένα αυτοκίνητο (παιχνίδι) που θα μετατραπεί στο ρομποτικό όχημα
  2.	Arduino (nano ή micro)
  3.	(2x) Dual H:Bridge motor drive L298 
  4.	(2x) Μοτέρ κίνησης 5Vt (απλά, με 2 καλώδια κόκκινο - μαύρο)
  5.	(1x) σέρβο μοτέρ για σύστημα διεύθυνσης
  6.	(1x) Ενισχυτής ήχου (2x3w)      \
  7.	(2x) Ηχεία 2-3w                 |--> (Για το απαραίτητο ηχητικό σύστημα  που «εμπλουτίζει» ένα τέτοιο όχημα)
  8.	(1x) SD Card Reader και SD Card /
  10.	(2x) Ultrasonic module αισθητήρες μέτρησης απόστασης
  11.	(1x) Bluetooth Wirless Transeiver RF Module
  12.	(20cm) Αντίσταση χρωμονικελίνης (καπνιστικό σύστημα) + κουτάκι πλαστικό για το υγρό
  13.	Led κόκκινα, κίτρινα, λευκά
  14.	RGB Led για την διακόσμηση και τα εφέ που χαρακτηρίζουν ένα όχημα αυτού του τύπου
  15.	Αισθητήρες-πομποί υπερύθρων (IR) 
  16.	Αισθητήρες-δέκτες υπερύθρων (IR) 
  17.	Αντιστάσεις  10k, 220ohm, 100ohm

Για την κατασκευή της πίστας (πόλης) στην οποία θα κινείται το Καγκουρόbot θα χρειαστούν:
  1.	Arduino 
  2.	Ultrasonic module αισθητήρες μέτρησης απόστασης.
  3.	Led κόκκινα, κίτρινα, πράσινα (για τα φανάρια)
  4.	RGB Led για διακόσμηση της πόλης.
  5.	Αισθητήρες-πομποί υπερύθρων (IR) 
  6.	Αισθητήρες-δέκτες υπερύθρων (IR) 
  7.	Αντιστάσεις  10k, 220ohm, 100ohm
  8.	Δάπεδο καουτσούκ (ρολό)
  9.	Χαρτόνια και άλλα πλαστικά μέρη για την κατασκευή της πίστας (όπλης)
Προσεγγιστικά θα χρειαστούν 40-50 LED (κόκκινα, κίτρινα, πράσινα, λευκά), 10 RGB Led και περίπου 50 αντιστάσεις. Επίσης θα χρειαστούν περίπου 10 αισθητήρες υπερύθρων.
Το συνολικό κόστος του έργου θα είναι χαμηλό (υπολογίζεται αρκετά χαμηλότερο των 100€) γιατί δεν απαιτούνται ιδιαίτερα ακριβά εξαρτήματα και υλικά για τη συναρμολόγηση και κατασκευή τόσο του Καγκουρόbot, όσο και της πόλης που θα το φιλοξενεί.
Γενικά το έργο χαρακτηρίζεται εφικτό από το σύνολο της ομάδας και ήδη από την πρώτη φάση έχει προκαλέσει το ενδιαφέρον των εμπλεκομένων μαθητών και καθηγητών. Αναμένεται να ενεργοποιήσει τους μαθητές, εντάσσοντας τους σε μια ευρύτερη κοινότητα, όπου θα προσπαθήσουν (οι περισσότεροι από αυτούς για πρώτη φορά) να δημιουργήσουν και να μοιραστούν γνώση, καλή πρακτική και καινοτομία. 

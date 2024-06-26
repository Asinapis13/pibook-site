Το Microsoft Hololens [^1] είναι η αντίληψη της Microsoft για την επαυξημένη πραγματικότητα, την οποία αποκαλούν «μικτή πραγματικότητα». Το HoloLens υποστηρίζει αρθρωτή είσοδο παρακολούθησης χεριών, η οποία επιτρέπει στον χρήστη να αλληλεπιδράει με αντικείμενα. Χρησιμοποιώντας πολλαπλούς αισθητήρες, προηγμένη οπτική και ολογραφική επεξεργασία που συγχωνεύεται άψογα με το περιβάλλον, αυτά τα ολογράμματα μπορούν να χρησιμοποιηθούν για την εμφάνιση πληροφοριών, την ανάμειξη με τον πραγματικό κόσμο ή ακόμα και την προσομοίωση ενός εικονικού κόσμου. Το HoloLens εκτελεί την πλατφόρμα Mixed Reality των Windows στο λειτουργικό σύστημα Windows 10. Κάποια από την τεχνολογία εντοπισμού θέσης που χρησιμοποιείται στο HoloLens μπορεί να ανιχνεύσει την καταγωγή του στο Microsoft Kinect , ένα αξεσουάρ για τις κονσόλες παιχνιδιών Xbox 360 και Xbox One της Microsoft που παρουσιάστηκε το 2010. 

Το Hololens [^2] 1ης γενιάς κυκλοφόρησε στις 30 Μαρτίου 2016 (Development Edition) και απευθυνόταν σε προγραμματιστές στις Ηνωμένες Πολιτείες και τον Καναδά με τιμή καταλόγου 3000 $ .Στις 12 Οκτωβρίου 2016, η Microsoft ανακοίνωσε την παγκόσμια επέκταση του HoloLens 1 ενώ το 2017 η  εμπορική σουίτα που υπάρχει , με εταιρικά χαρακτηριστικά όπως η ασφάλεια BitLocker πωλήθηκε 5000 $.Το Microsoft HoloLens 2 (δεύτερης γενιάς) είναι ο διάδοχος του αρχικού Microsoft HoloLens . Η πρώτη παραλλαγή της συσκευής, η εταιρική έκδοση HoloLens 2, έκανε το ντεμπούτο της στις 24 Φεβρουαρίου 2019 στο Mobile World Congress (MWC) στη Βαρκελώνη της Ισπανίας. Εκεί, παρουσιάστηκε μια εφαρμογή που δημιουργήθηκε με το Unreal Game Engine. Ακολούθησε μια έκδοση προγραμματιστή που ανακοινώθηκε στις 2 Μαΐου 2019. Το HoloLens 2 κυκλοφόρησε στη συνέχεια σε περιορισμένο αριθμό στις 7 Νοεμβρίου 2019.

{% include figure image_path="/images/hololens1.jpg" caption="Figure 1: Το HoloLens φέρνει την επανάσταση στον τρόπο που o χρήστης αλληλεπιδρά με τον κόσμο.Εκτός από ένα Intel Cherry Trail SoC που περιέχει την CPU και την GPU , το HoloLens διαθέτει μια προσαρμοσμένη μονάδα ολογραφικής επεξεργασίας της Microsoft (HPU), έναν συμεπεξεργαστή που κατασκευάστηκε ειδικά για το HoloLens από τη Microsoft." id="fig:Hololens_specs" %}


{% include figure image_path="/images/hololens2_2nd.jpg" caption="Figure 2: Το HoloLens 2 λειτουργεί με μια πλατφόρμα Qualcomm Snapdragon 850 με μια προσαρμοσμένη μονάδα επεξεργασίας ολογραφικών (HPU) για βελτιωμένη απόδοση. Διαθέτει 4 GB RAM, 64 GB αποθηκευτικό χώρο, συνδεσιμότητα Wi-Fi 5, Bluetooth 5 και θύρα USB-C. Επίσης λειτουργεί ως πελάτης για δεδομένα στην ίδια τη συσκευή, στο cloud Azure ή στον Ιστό γενικά." id="fig:Hololens_2nd_Gen" %}


{% include figure image_path="/images/hololens3_2nd.jpg" caption="Figure 3: Το HoloLens 2 εκτελείται με το Windows Holographic OS , το οποίο βασίζεται σε μια <<γεύση>> των Windows 10, που παρέχει στους χρήστες, τους διαχειριστές και τους προγραμματιστές μια ισχυρή, αποδοτική και ασφαλή πλατφόρμα.Κυκλοφορεί σε τέσσερις εκδόσεις : την απλή ,την HoloLens 2 Industrial Edition, την Trimble XR10 με HoloLens 2 και την HoloLens 2 Development Edition." id="fig:Hololens_2nd_Gen_specs" %}

Η Microsoft παρέχει αρκετά δείγματα εφαρμογών[^3]. Δύο από αυτά είναι ο περιοδικός πίνακας στοιχείων 2.0 και οι Επιφάνειες (Surfaces). Ο περιοδικός πίνακας στοιχείων σχεδιάστηκε αρχικά για HoloLens 1ης γενιάς για να δείξει την εμπειρία από άκρο σε άκρο χρησιμοποιώντας τα δομικά στοιχεία του MRTK. Για να αξιοποιήσει πλήρως τη νέα εισαγωγή αρθρωτής παρακολούθησης χεριών και παρακολούθησης ματιών στο HoloLens 2, η εφαρμογή ενημερώθηκε χρησιμοποιώντας το MRTK v2.
Η εφαρμογή Επιφάνειες διερευνά πώς μπορούμε να δημιουργήσουμε μια αίσθηση αφής με οπτική, ακουστική και πλήρως αρθρωμένη παρακολούθηση χεριών.

{% include figure image_path="/images/hololens_periodictable.jpg" caption="Figure 4: Περιοδικός Πίνακας Στοιχείων 2.0" id="fig:Hololens_Samples" %}

{% include figure image_path="/images/hololens_periodictable1.gif" caption="Figure 5: Περιοδικός Πίνακας Στοιχείων 2.0" id="fig:Hololens_Samples" %}

{% include figure image_path="/images/hololens_surfaces.jpg" caption="Figure 6: Το Surfaces δείχνει πώς να χρησιμοποιήσειο χρήστης το σύστημα εισόδου και τα δομικά στοιχεία του Mixed Reality Toolkit (MRTK) για να δημιουργήσει μια εμπειρία εφαρμογής για το HoloLens 2. " id="fig:Hololens_Samples" %}

{% include figure image_path="/images/hololens_surfaces1.gif" caption="Figure 7: Surfaces " id="fig:Hololens_Samples" %}

Το Hololens έχει χρησιμοποιηθεί σε διάφορες επιστημονικές έρευνες. Μια σημαντική έρευνα που πραγματοποιήθηκε έιναι στην εκπαίδευση και συγκεκριμένα στον τομέα της Φυσικής [^4]. Σχεδιάστηκε ένα σύστημα που βασίζεται στο Hololens στο οποίο οι μαθητές εκτίθενται σε μια αδόμητη μαθησιακή δραστηριότητα στην οποία έμαθαν για την αόρατη φυσική που εμπλέκεται στα ηχεία ήχου. Έμαθαν θέματα όπως το σχήμα των μαγνητικών πεδίων και τις σχέσεις σχέσεις μεταξύ ηλεκτρισμού και μαγνητισμού. Το τελικό σύστημα αποτελείται από ένα διαδραστικό σύστημα υλικού που αναπαράγει ένα ηχείο ήχου. Το σύστημα αποτελείται από πολλαπλές συσκευές Hololens δικτυωμένες μεταξύ τους. Οι φυσικές ηλεκτρονικές μονάδες επιτρέπουν σε ομάδες μαθητών να συνεργάζονται ενώ παρατηρούν τρισδιάστατες απεικονίσεις αόρατων φαινομένων που συμβαίνουν στον φυσικό χώρο. Ο ήχος παράγεται από μια μεμβράνη διαφράγματος με προσαρτημένο μαγνήτη. Το διάφραγμα βρίσκεται δίπλα σε ένα πηνίο καλωδίων, το οποίο λαμβάνει ενισχυμένα ηλεκτρικά σήματα από έναν πίνακα ελέγχου. Οι συμμετέχοντες μπορούν να πατήσουν κουμπιά στον πίνακα ελέγχου για να παίξουν μουσική από ένα smartphone ή να στείλουν σταθερό ρεύμα προς τα εμπρός ή προς τα πίσω μέσω του συστήματος. Οι συμμετέχοντες μπορούν επίσης να ελέγξουν την τοποθέτηση της μεμβράνης του διαφράγματος, να αλλάξουν τον τύπο του πηνίου που χρησιμοποιείται και να προσαρμόσουν την ενίσχυση.

Οι συμμετέχοντες εργάστηκαν στo σύστημα (πατώντας κουμπιά στον πίνακα ελέγχου π.χ. για να παίξουν μουσική από ένα smartphone ,ελέγχοντας την τοποθέτηση της μεμβράνης του διαφράγματος κα.) για 30 λεπτά κάτω από διαφορετικές πειραματικές συνθήκες όπως η αναπαράσταση μαγνητικού πεδίου ,η διαδραστικότητα συστήματος, η αφίσα ηλεκτρομαγνητισμού (AR), η έντυπη αφίσα ηλεκτρομαγνητισμού, η ηχητική & οπτική αναπαράσταση κα.

{% include figure image_path="/images/hololens_system.jpg" caption="Figure 8: Το σύστημα οπτικοποιεί αόρατα φαινόμενα, όπως του ηλεκτρικού ρεύματος (κίτρινα ηλεκτρόνια που κινούνται κατά μήκος του φυσικού καλωδίου, γραφήματα που δείχνουν την ισχύ τάσης), των μαγνητικών πεδίων (καμπύλες γραμμές γύρω από τα κουλουριασμένα καλώδια και τους μαγνήτες και ομοαξονικούς επίπεδους δακτυλίους γύρω από ευθεία καλώδια) , και των ηχητικών κυμάτων (πράσινα ημισφαίρια)." id="fig:Hololens_in_Education" %}

Η έρευνα έδειξε ότι η παρουσία της τεχνολογίας AR είχε σημαντική επίδραση στις στάσεις (αντίληψη και τα συναισθήματα) των συμμετεχόντων προς τη δική τους μάθηση. Επίσης τα αποτελέσματα υποδεικνύουν ότι η παρουσία των αναπαραστάσεων AR επηρέασε την αυτο-αποτελεσματικότητα των συμμετεχόντων. Τέλος οι συμμετέχοντες που είδαν τις αναπαραστάσεις AR είχαν υψηλότερα κέρδη στη μάθηση, ειδικά σε θέματα όπως η αναγνώριση και η σχεδίαση μορφών μαγνητικού πεδίου.

Ως συμπέρασμα τα Hololens 1η και 2ς γενιάς παρέχουν μια πλούσια και διαδραστική εμπειρία.Το Hololens είναι ασύρματο, επιτρέποντας στους χρήστες να κινούνται ελεύθερα χωρίς να περιορίζονται από καλώδια. Μπορεί να ενσωματωθεί με άλλες συσκευές και υπηρεσίες, όπως smartphones , Azure κα. Μπορεί να χρησιμοποιηθεί για την πρόσβαση και την αλληλεπίδραση με ψηφιακά αντικείμενα που είναι ενσωματωμένα στο περιβάλλον του χρήστη και παρέχει την δυνατότητα να προβάλλει ψηφιακά αντικείμενα σε διάφορες επιφάνειες.


[^1]: fig:Hololens

[^2]: fig:Hololens_Production

[^3]: fig:Hololens_Samples

[^4]: fig:Hololens_in_Education


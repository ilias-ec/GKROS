# GKROS
<b>Γυμνάσιο Κανήθου</b><br>
Κεφαλά 64, 341 31 Χαλκίδα<br>
<p align="center"><b>Τηλεκατευθυνόμενο Υποβρύχιο Ρομπότ</b></p><br>

**Αναλυτική περιγραφή ιδέας:**<br>
Κατά το σχολικό έτος 2012-2013 το σχολείο συμμετείχε στο [Hydrobot](http://hydrobots.gr/index/) και [Hydrobot sensor v1](http://hydrobots.gr/index/?page_id=1572) του [Ιδρύματος Ευγενίδου](https://www.eef.edu.gr/?target=_blank) με 5 μαθητές της Γ τάξης. Ελήφθησαν [μετρήσεις](http://hydrobots.gr/index/hydrosensor_values.php?schools=1&latitude=38.46419795662086&longitude=23.640746890624996&distance=30&from=01/01/2010&to=31/12/2013&step=30) στη θαλάσσια περιοχή του Βόρειου Ευβοϊκού καθώς και στον Νότιο Ευβοϊκό με [προκαθορισμένο πρωτόκολλο μετρήσεων](http://hydrobots.gr/index/wp-content/uploads/2013/05/protocol.pdf). Οι μαθητές που συμμετείχαν στην κατασκευή, συναρμολόγηση, δοκιμές, προγραμματισμό, καθώς και στη λήψη των μετρήσεων την επόμενη σχολική χρονιά φοίτησαν στο Λύκειο με αποτέλεσμα το υποβρύχιο ρομπότ  να παροπλιστεί γιατί δεν υπήρξαν μαθητές για να συνεχιστεί το συγκεκριμένο project. <br>
Με αφορμή το 2ο Πανελλήνιο Διαγωνισμό Ανοιχτών Τεχνολογιών στην Εκπαίδευση και την επερχόμενη Κλιματική Αλλαγή έγινε ενημέρωση στους μαθητές της φετινής σχολικής χρονιάς σε αυτό και 8 μαθητές (6 αγόρια και 2 κορίτσια) εξέφρασαν το ενδιαφέρον να συμμετάσχουν αξιοποιώντας το ήδη υπάρχον Hydrobot και Hydrobot sensor v1. <br>
Μετά από συζητήσεις, επεξηγήσεις, παρουσιάσεις των δυνατοτήτων του αρχικού Hydrobot και Hydrobot sensor v1, αποφασίστηκε η επαναφορά του στην ενεργό δράση με αναμορφωμένες δυνατότητες.<br>
Δηλαδή:<br>
- να είναι περισσότερο αυτόνομο στο βαθμό που επιτρέπουν οι δυνατότητες και ικανότητές μας <br>
- να λαμβάνει μετρήσεις από συγκεκριμένα θαλάσσια γεωγραφικά σημεία και να επιστρέφει στην αφετηρία (ανάλογα με την χωρητικότητα της μπαταρίας)<br>
- να λαμβάνει περισσότερες μετρήσεις από ότι αρχικά είχε σχεδιαστεί (εκτός από τη θερμοκρασία του νερού, τη υδροστατική πίεση και τη φωτεινότητα που ήταν ο αρχικός σχεδιασμός και να λαμβάνει επιπλέον: pH, αλατότητα/αγωγιμότητα.<br>
- να λαμβάνει μετρήσεις από 0m έως 3m βάθος ανά 1sec<br>
- να τοποθετηθεί κάμερα για καταγραφή του υποθαλάσσιου συστήματος (σε κάρτα SD)<br>
- να λαμβάνει μετρήσεις για την ατμόσφαιρα της θαλάσσιας γεωγραφικής περιοχής που θα βρίσκεται κάθε φορά (θερμοκρασία αέρα, σχετική υγρασία, ατμοσφαιρική πίεση, ταχύτητα αέρα, κατεύθυνση αέρα, UVA/B)<br>
- να αποθηκεύει όλες τις μετρήσεις σε κάρτα SD και παράλληλα να τις αποστέλλει ασύρματα στην στεριά και να αποθηκεύονται σε φορητό υπολογιστή.<br>


**Λίστα προτεινόμενου εξοπλισμού:**<br>
- ένα Hydrobot (ήδη υπάρχων εξοπλισμός από το προηγούμενο εγχείρημα)<br>
- ένα Hydrobot sensor v1 (ήδη υπάρχων εξοπλισμός από το προηγούμενο εγχείρημα) και θα προστεθεί:<br>
  - ένας αισθητήρας pH<br>
  - ένας αισθητήρας αλατότητας/αγωγιμότητας<br>
  - κάμερα VGA<br>
- καλώδιο UTP μήκους περίπου 3 μέτρα (ήδη υπάρχων εξοπλισμός από το προηγούμενο εγχείρημα - υπάρχει η δυνατότητα για μεγαλύτερο μήκος άρα και βάθος)<br>
- ένα πλωτό σταθμό που θα ακολουθεί το Hydrobot, στην επιφάνεια της θάλασσας, και θα περιλαμβάνει:<br>
  - ένα Arduino Uno<br>
  - ένα αισθητήρα θερμοκρασίας/υγρασίας/ατμοσφαιρικής πίεσης<br>
  - ένα GPS<br>
  - μια μπαταρία 12V – 5ΑΗ – μολύβδου – κλειστού τύπου (ήδη υπάρχων εξοπλισμός από το προηγούμενο εγχείρημα)<br>
  - ένα wireless module για την τηλεμετρία μεταξύ Hydrobot/Hydrobot sensor v1 – στεριά<br>
  - μια SD card για την αποθήκευση μετρήσεων<br>
  - ένα αισθητήρα ταχύτητας αέρα (ιδιοκατασκευή με κινητήρα DC από χαλασμένο παιχνίδι)<br>
  - ένα αισθητήρα κατεύθυνσης αέρα (ιδιοκατασκευή με αντιστάσεις)<br>
  - ένα αισθητήρα UVA/UVB<br>


**Ενδεικτικό κόστος:**<br>

|Είδος|Ποσότητα|€/τεμ|€|
|-----|:---:|:---:|:---:|
|Αισθητήρας pH|1|6,00|6,00|
|Αισθητήρας αλατότητας/αγωγιμότητας|1|5,00|5,00
|Κάμερα VGA|1|10,00|10,00|
|Arduino Uno|1|7,50|7,50|
|Αισθητήρας θερμοκρασίας/υγρασίας/ατμοσφαιρικής πίεσης|1|8,30|8,30|
|GPS module|1|17,00|17,00|
|Wireless module|1|11,00|11,00|
|SD card 32GB SDHC CLASS 10 + module (2,5€ + 4,30€) |1|6,80|6,80|
|Αισθητήρα UVA/UVB|1|7,00|7,00|
|||**Σύνολο €:**|**78,60**|

Οι τιμές είναι με ΦΠΑ 24%.

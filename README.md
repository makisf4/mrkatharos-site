# MrKatharos.gr - Static Website

Επαγγελματικό, mobile-first, one-page site για την επιχείρηση **MrKatharos – Καθαρισμός Καναπέδων, Στρωμάτων & Χαλιών**.

## Δομή Project

```
mrkatharos-site/
 ├─ index.html          # Κύριο HTML αρχείο
 ├─ css/
 │   └─ styles.css      # CSS styles (mobile-first)
 ├─ js/
 │   └─ main.js         # JavaScript για interactivity
 ├─ assets/
 │   ├─ hero.png        # Hero section background
 │   ├─ sofa.png        # Καθαρισμός καναπέδων
 │   ├─ mattress.png    # Καθαρισμός στρωμάτων
 │   ├─ carpet.png      # Καθαρισμός χαλιών
 │   └─ logo.png        # Logo
 └─ README.md
```

## Εγκατάσταση & Εκτέλεση

### Προαπαιτούμενα
- Python 3 (εγκατεστημένο στα περισσότερα συστήματα)

### Εκκίνηση Local Server

1. Ανοίξτε terminal/command prompt
2. Μεταβείτε στον φάκελο του project:
   ```bash
   cd mrkatharos-site
   ```

3. Εκκινήστε το HTTP server:
   ```bash
   python3 -m http.server 8080
   ```

4. Ανοίξτε browser και πηγαίνετε στο:
   ```
   http://localhost:8080
   ```

### Εναλλακτική Εκκίνηση

Εάν έχετε Node.js εγκατεστημένο, μπορείτε να χρησιμοποιήσετε το `http-server`:

```bash
npx http-server -p 8080
```

Ή με PHP:
```bash
php -S localhost:8080
```

## Χαρακτηριστικά

- ✅ **Mobile-First Design** - Βελτιστοποιημένο για mobile συσκευές
- ✅ **One-Page Layout** - Όλες οι πληροφορίες σε μια σελίδα
- ✅ **Smooth Scroll** - Ομαλή κύλιση μεταξύ sections
- ✅ **Interactive FAQ** - Accordion για συχνές ερωτήσεις
- ✅ **Pricing Tabs** - Εναλλαγή μεταξύ Απλού & Βιολογικού καθαρισμού
- ✅ **Sticky Navigation** - Fixed navbar με scroll effect
- ✅ **Mobile Bottom Bar** - Sticky bar για κλήση & WhatsApp (mobile)
- ✅ **Floating WhatsApp Button** - Γρήγορη πρόσβαση στο WhatsApp
- ✅ **SEO Optimized** - Meta tags & Open Graph tags
- ✅ **Responsive Images** - Βελτιστοποιημένες εικόνες

## Sections

1. **Hero** - Κύριο banner με background image
2. **Υπηρεσίες** - Κάρτες με τις 3 κύριες υπηρεσίες
3. **Τιμές** - Τιμολόγηση με tabs (Απλός / Βιολογικός)
4. **Βιολογικός Καθαρισμός** - Πληροφορίες για βιολογικό καθαρισμό
5. **FAQ** - Συχνές ερωτήσεις με accordion
6. **Περιοχή** - Περιοχή εξυπηρέτησης
7. **Επικοινωνία** - Στοιχεία επικοινωνίας

## Τιμολόγηση

### Καναπέδες
- Έως 2,00 μ.: 20 € (Απλός) / 40 € (Βιολογικός)
- +15 € ανά επιπλέον 0,50 μ.
- Γωνιακοί: άθροισμα πλευρών
- Μαξιλάρια περιλαμβάνονται

### Στρώματα
- Μονό: 20 € / 35 €
- Διπλό: 40 € / 55 €

### Χαλιά
- 6 € / τ.μ. (κατ' οίκον)

**Σημειώσεις:**
- Ελάχιστη χρέωση επίσκεψης: 40 €
- Έντονη ρύπανση → κατόπιν συνεννόησης

## Customization

Για να αλλάξετε τα στοιχεία επικοινωνίας, επεξεργαστείτε το `js/main.js`:

```javascript
const PHONE = "+30 69XXXXXXXX";
const WHATSAPP = "+30 69XXXXXXXX";
const AREA = "Ηλιούπολη & Νότια Προάστια";
```

Τα links θα ενημερωθούν αυτόματα σε όλη την ιστοσελίδα.

## Browser Support

- Chrome (τελευταία έκδοση)
- Firefox (τελευταία έκδοση)
- Safari (τελευταία έκδοση)
- Edge (τελευταία έκδοση)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2024 MrKatharos.gr - Όλα τα δικαιώματα διατηρούνται


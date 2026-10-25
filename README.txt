BARBER APP - SETUP (Roman Urdu)

1. console.firebase.google.com par jayein > "Add project" (naam: barber).
2. Build > Authentication > Get started > Sign-in method > Google ko Enable karein.
3. Build > Firestore Database > Create database (production mode).
   Phir "Rules" tab mein firestore.rules ka poora text paste karein. Usme owner@gmail.com ki jagah APNI Gmail likhein. Publish dabayein.
4. Project settings (gear) > "Your apps" > Web (</>) app banayein. Jo config dikhe, uski 4 values firebase-config.js mein paste karein. Wahin OWNERS mein apni Gmail likhein.
5. App ko HTTPS par host karein. Sab se aasan: app.netlify.com/drop par poora "barber-app" folder drag karein. Aap ko ek link milega.
6. Firebase > Authentication > Settings > Authorized domains mein wo Netlify domain add karein.
7. Phone ke Chrome mein link kholein > "APP INSTALL KAREIN" (ya menu > Install app). iPhone par Safari > Share > Add to Home Screen.
8. Owner Gmail se login karke Owner panel mein naam, photos, services bharein. Phir home page ke WhatsApp button se link customers ko bhejein.

Nota: Free plan chhoti shop ke liye kaafi hai. Photos chhoti karke Firestore mein hi save hoti hain, Storage ki zaroorat nahi.

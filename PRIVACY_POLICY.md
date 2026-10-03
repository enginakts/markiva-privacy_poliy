# Privacy Policy for Markiva

**Last updated:** October 3, 2026

Markiva ("we", "our", or "the Extension") is committed to protecting your privacy. This Privacy Policy explains what information is collected, how it is used, and how your data is protected when you use the Markiva Chrome Extension.

---

## 1. Information We Collect

Markiva collects and processes only the minimum data necessary to provide its bookmark management and synchronization features:

### a. User Account Information
- When you register or sign in via **Email/Password** or **Google Sign-In**, we process your email address, display name, and unique Firebase User ID (`UID`).
- All authentication is handled directly and securely through **Google Firebase Authentication**. We never see, store, or have access to your raw passwords.

### b. Bookmark and Folder Data
- **Bookmark Content:** Web page titles, URLs, user-added notes/descriptions, folder classifications, tags, favorite indicators, and timestamps.
- **Active Tab Information:** When you explicitly click "Add Link" or "Fetch Current Page", the extension accesses the title and URL of your current active tab solely to pre-fill the bookmark form. Markiva does **not** track or log your general browsing history.

### c. User Preferences
- Local configuration settings such as your preferred theme (Dark or Light mode) and interface language (Turkish, English, or Japanese).

---

## 2. How We Use Your Information

The collected data is used exclusively to:
- Organize, categorize, and display your saved bookmarks.
- Synchronize your bookmarks and folders across your devices in real-time using Google Firebase Cloud Firestore.
- Authenticate your account and ensure that only you can access and modify your personal data.

---

## 3. Data Storage and Security

- **Local Storage:** Your data is stored locally on your device via Chrome's secure storage API (`chrome.storage.local`) to ensure fast and offline accessibility.
- **Cloud Storage:** When you choose to sign in, your data is securely synchronized with **Google Cloud Firestore**. Data in transit is encrypted using industry-standard TLS/SSL protocols, and data at rest is protected by Google Firebase infrastructure and strict security rules.
- **Access Control:** Our database is configured with Firestore Security Rules ensuring that only authenticated users can read or modify their own data matching their unique user ID.

---

## 4. Data Sharing and Disclosure

- **No Sale of Personal Data:** We do **not** sell, rent, lease, or monetize your personal information or bookmark data to any third party, data broker, or advertising platform.
- **No Third-Party Tracking:** Markiva does not use analytics trackers, telemetry libraries, or third-party advertising scripts.
- **Service Providers:** Your data is processed only by **Google Firebase** strictly for cloud hosting and authentication services.

---

## 5. User Control and Data Deletion

You retain full control over your data:
- **Deletion:** You can delete individual bookmarks or entire folders at any time directly from the extension interface.
- **Account Deletion:** If you wish to delete your account and all associated cloud-synced data, you can do so by contacting us at the email provided below. All your records will be permanently removed from our database.

---

## 6. Permissions Justification

In accordance with Google Chrome Web Store Developer Policies:
- **`storage` / `unlimitedStorage`:** Used strictly to save your bookmarks, folders, and preferences locally without data truncation.
- **`tabs`:** Used exclusively to obtain the title and URL of the active tab upon user request when saving a bookmark.
- **`identity`:** Used to facilitate Google OAuth2 authentication via Firebase.
- **Host Permissions (`googleapis.com`, `firebaseio.com`, `firebaseapp.com`):** Used solely to interact with Firebase Authentication and Firestore database for account sync.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted to this page with an updated "Last updated" date.

---

## 8. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your personal data, please contact us at:

- **Developer:** Markiva Team
- **Email:** support@markiva.app *(veya kendi iletişim e-postanız)*
- **GitHub:** https://github.com/

---
---

# Gizlilik Politikası (Türkçe Özet)

**Son güncelleme:** 3 Ekim 2026

Markiva ("biz", "eklenti"), kullanıcı gizliliğine en üst düzeyde önem verir. Bu Gizlilik Politikası, Markiva Chrome Eklentisi kullanılırken hangi verilerin ne amaçla toplandığını açıklamaktadır:

1. **Toplanan Veriler:** 
   - Giriş yapıldığında Firebase üzerinden e-posta adresi, kullanıcı adı ve benzersiz kullanıcı kimliği (UID).
   - Kullanıcının kaydettiği yer imleri (başlık, URL, notlar, klasör adı, tarih).
   - "Link Ekle" tıklandığında yalnızca o anki aktif sekmenin başlığı ve linki.
   - Tema (koyu/açık) ve dil tercihleri.
2. **Verilerin Kullanımı:** Veriler yalnızca linklerinizi listelemek, aramak ve cihazlarınız arasında Google Firebase aracılığıyla güvenli şekilde eşitlemek için kullanılır.
3. **Veri Satışı ve Paylaşım:** Verileriniz asla üçüncü taraflara satılmaz, reklamcılara verilmez ve izleme amacıyla kullanılmaz.
4. **Veri Güvenliği ve Silme:** Verileriniz Google Cloud altyapısında şifreli olarak korunur. Dilediğiniz zaman eklenti içinden linklerinizi veya klasörlerinizi silebilirsiniz.

# university-menu-automation
### 🇹🇷 Türkçe Açıklamalar:
**1. Proje Amacı:**
- Üniversite yemekhanesinin günlük menüsünü otomatik olarak takip etmek
- Kullanıcıya her sabah e-posta ile menü bilgisi göndermek
- Manuel kontrol gerektirmeden güncel menüye erişim sağlamak

**2. Teknik Detaylar:**
- n8n workflow'u web scraping yöntemiyle menü verisini çeker
- Cron job ile günlük otomatik çalışma sağlanır
- E-poya node'u ile formatlı mail gönderimi yapılır

 ### 🇺🇸 English Explanations:

**1. Project Purpose:**
- Automatically track daily university cafeteria menu
- Send menu information to user via email every morning
- Provide access to current menu without manual checking

**2. Technical Details:**
- n8n workflow uses web scraping to extract menu data
- Cron job enables daily automatic execution
- Email node sends formatted emails to users

### 🛠️ Kurulum

#### 1. Gereksinimler
- n8n kurulumu
- E-posta servisi (Gmail, Outlook, vb.)
- Üniversite menü sayfası URL'si

#### 2. Adımlar
```bash
# Repository'yi klonlayın
git clone https://github.com/Chanbadar/university-menu-automation.git

# n8n'de workflow'u içe aktarın
# Workflow.json dosyasını n8n arayüzünden import edin



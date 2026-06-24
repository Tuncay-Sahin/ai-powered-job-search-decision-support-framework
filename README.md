# AI-Powered Job Search & Decision Support Framework

<p align="center">
  
  <img src="https://img.shields.io/badge/Architecture-Decision%20Support%20Systems-orange?style=for-the-badge&labelColor=111111" alt="Architecture">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google-gemini&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" alt="Markdown">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Methodology-Google%20AI%20Career%20Navigation-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Method">
  <img src="https://img.shields.io/badge/Knowledge%20Base-Obsidian%20%2F%20Markdown-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white" alt="Obsidian">
  <img src="https://img.shields.io/badge/Framework-Modular%20Job%20Search-FF5722?style=for-the-badge" alt="Modular Framework">
</p>

---

Project & Documentation Overview

Bu depo (*repository*), **Google Career - Accelerate Your Job Search with AI** metodolojisinden elde edilen teorik ve pratik içgörülerin, **Obsidian (.md)** mimarisiyle yapılandırılmış dinamik bir **Knowledge Base** (Bilgi Tabanı) ve **Decision Support System (DSS)** dökümantasyonudur[cite: 1]. 

Sıradan bir ders notu dökümünden farklı olarak bu çalışma; iş analizi, veri bilimi ve yapay zeka entegrasyonu süreçlerinin kariyer navigasyonuna **parametrik** ve **modüler** olarak nasıl uygulanacağını gösteren canlı bir mühendislik rehberidir.

---

## Architectural Modules: Ne İşe Yarar & Nasıl Kullanılır?

Dökümantasyon, karmaşık iş arama ve mülakat hazırlık süreçlerini yığın oluşumuna izin vermeden 4 ana fonksiyonel modüle ayırır:

### Module 1: Transferable Skills & Career Identity Matrix
*   **Ne İşe Yarar:** Kişinin geçmiş yaşam, akademik ve teknik deneyimlerini ham veriden çıkarıp, hedef pozisyonun diline tercüme eder.
*   **Nasıl Kullanılır:** Obsidian içindeki notlar, işverenlerin odaklandığı *Skill-Based Hiring* trendlerine uygun olarak yapılandırılmıştır. *Transferable Skills* (Aktarılabilir Beceriler) analizi yapılarak, ham yetkinlikler hedef roldeki *Stakeholder Management* ve *Process Modeling* gibi ihtiyaçlarla eşleştirilir[cite: 1, 2, 4]. Bu modülün çıktısı, kariyerin kuzey yıldızı olan **Career Identity Statement** (Kariyer Kimliği Beyanı) dökümanını besler[cite: 2].

### Module 2: Strategic Resume Tailoring & Marketing Stratejisi
*   **Ne İşe Yarar:** Özgeçmişi geçmişin bir dökümü olmaktan çıkarıp, adayın değer teklifini sunan dinamik bir *Pazarlama Belgesi* haline getirir[cite: 2].
*   **Nasıl Kullanılır:** Notlar içerisindeki **X-Y-Z Formülü** `[X: Başarı/Eylem] + [Y: Ölçülebilir Sonuç/Veri] + [Z: Kullanılan Yöntem/Beceri]` şablonları işletilerek, özgeçmiş maddeleri ve ön yazılar (*Cover Letters*) her iş ilanına özel olarak *ATS-Friendly* (ATS Uyumlu) şekilde *tailor* edilir (yeniden haritalandırılır)[cite: 1, 2, 3].

### Module 3: Information Management & Application Tracking
*   **Ne İşe Yarar:** İş arama sürecindeki veri hatlarını ve açık pozisyonları yapılandırılmış bir düzende kontrol altında tutar.
*   **Nasıl Kullanılır:** İlişkisel veri tabanı mantığıyla çalışan *E-Sheet* tablosundaki veri sütunları (`Application Status`, `Company Name`, `Job Description Keyword Vectors`, `Notes`) ile entegre çalışır. Sürecin siber güvenliği, *Data Privacy (KVKK/GDPR)* protokolleri kapsamında hassas verilerin maskelenmesiyle proaktif olarak yönetilir.

### Module 4: Advanced Interview Hardening & STAR Simulation
*   **Ne İşe Yarar:** Adayı *Davranışsal (Behavioral)*, *Teknik (Technical)*, *Vaka Analizi (Case Analysis)* ve *Panel* mülakat formatlarına karşı kusursuz bir hazır bulunuşluk seviyesine taşır.
*   **Nasıl Kullanılır:** Mülakat hazırlığı sürecinde **NotebookLM** ve **Gemini Live** üzerinde işletilecek gelişmiş *Prompt Engineering* (İstem Mühendisliği) kalıplarını barındırır.

---

## Deep Dive: Job Search & Interview Süreçlerinde Modüler Hazırlık Algoritması

Bu dökümantasyon sistemini kullanarak bir mülakata sıfır hata payıyla hazırlanmak için şu modüler akış uygulanır:

```text
[Hedef İş İlanı + Şirket Raporları] ──> Yükleme ──> [NotebookLM Kaynak Havuzu]
                                                               │
[Özel STAR Yanıt Şablonları] <── Üretim <── Chat & SSS <───────┤
                                                               │
[Mobil Alıştırma Dünyası] <── İndirme <── [Audio Overview] <───┘
Context Grounding (Bağlam Sabitleme): İlgili iş ilanı metni, şirket finansal analiz raporları ve endüstri trendleri NotebookLM platformuna "Source" (Kaynak) olarak yüklenir.

Kişiselleştirilmiş Öğrenme: Kişinin deponun içindeki sterilize edilmiş özgeçmiş ve başarı anekdotları sisteme enjekte edilir.

STAR Generation (Cevap Yapılandırma): Gelişmiş istem kütüphanesi formülleri kullanılarak, NotebookLM'den hedeflenen role özgü 3-4 adet güçlü STAR (Situation, Task, Action, Result) yanıt şablonu üretilmesi istenir.

Audio Overview Deployment (Sesli Strateji): Bilgilerin hareket halindeyken de içselleştirilmesi ve mülakat stresinin parametrik olarak düşürülmesi için sistemden bir Sesli Özet (Podcast) üretilir ve indirilerek dinlenir[cite: 2].

Post-Interview Protocol (Mülakat Sonrası Süreç): Mülakat bittiğinde, adayların %95'inin yapmadığı takip iletişimi tetiklenir; Gemini yardımıyla "Neden Yazıyorum + Değer Teklifi + Nezaketle Kapatış" formülüne uygun 300 karakter altı kişiselleştirilmiş Outreach ve teşekkür mesajları ağa fırlatılır[cite: 1, 2].

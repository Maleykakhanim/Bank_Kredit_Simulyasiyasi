# 🏦 Bank Kredit Analizi

## 🧾 Layihənin adı  
**Bank Kredit Analizi**

---

## 🎯 Layihənin məqsədi  
Bu layihə bank müştərilərinin demoqrafik və maliyyə göstəricilərini analiz edərək onların kredit götürmə ehtimalını və kredit risk səviyyəsini müəyyənləşdirməyi hədəfləyir.
📊 Məqsəd — müştərilərin maliyyə vəziyyətini analiz edərək bank üçün **kredit riskini azaltmaq** və **qərar-veriş prosesini dəstəkləməkdir.**

---

## İstifadə olunan mühit və fayllar  
- ☁️ Layihə **Google Colab** mühitində işlənilib (interaktiv notebook formatında).  
- 💻 Kod faylı: `Bank_Kredit_Simulyasiyasi_proyekt.ipynb`  
- 📂 Məlumat faylı: müştəri məlumatlarını ehtiva edən `*.csv` faylı (CSV formatında)  

---

## Xüsusiyyətlər və funksionallıq  
-  CSV faylından müştəri məlumatlarının yüklənməsi və ilkin təhlili  
-  Məlumatların təmizlənməsi və hazırlanması (məs: boş dəyərlərin tamamlanması, kateqorik dəyişənlərin kodlaşdırılması)  
-  Gəlir, borc, kredit tarixi kimi dəyişənlər əsasında kredit riskinin analizi  
-  Sadə statistik ölçülərin hesablanması  
-  Vizuallaşdırma (məs: gəlir və borc paylanması, kredit statusuna görə qruplaşma)  

---

## İstifadə qaydası  
1️⃣ Colab notebook-u aç:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ao1IOmn5VKKCIpVO9USz3nX4QGOduboL)

2️⃣ Lazımi kitabxanaları yüklə (`pandas`, `numpy`, `matplotlib`, `seaborn`)  
3️⃣ `*.csv` faylını yüklə və notebook-a bağla  
4️⃣ Kod hissələrini ardıcıl icra et:  
   -  Məlumatların oxunması və ilkin təhlili  
   -  Məlumatların təmizlənməsi  
   -  Analiz və vizuallaşdırma  
   -  Yekun nəticələrin çıxarılması

5️⃣ Əlavə analizlər və vizuallaşdırmalar etmək istəyirsənsə, notebook-u uyğunlaşdıraraq genişləndirə bilərsən.  

---

## Layihə aşağıdakı texnologiyalar və Python kitabxanaları üzərində qurulub:

- **Python 3**: Əsas proqramlaşdırma dili.
- **Pandas**: Məlumatların emalı və analizi.
- **NumPy**: Riyazi və statistik hesablamalar.
- **Matplotlib & Seaborn**: Məlumatların vizuallaşdırılması.
- **Google Colab**: Layihənin işləndiyi interaktiv mühit.

---
## Dataset Sütunlarının İzahı

| Sütun adı              | İzahı                                                                     |
|------------------------|----------------------------------------------------------------------     |
| MüştəriID              | Hər bir müştəriyə aid unikal identifikasiya nömrəsi                       |
| AdSoyad                | Müştərinin tam adı                                                        |
| DoğumTarixi            | Müştərinin doğum tarixi                                                   |
| Cins                   | Müştərinin cinsi (Kişi/Qadın)                                             |
| TəhsilSəviyyəsi        | Müştərinin təhsil səviyyəsi (Məktəb, Bakalavr, Magistr və s.)             |   
| MəşğulluqStatusu       | İş vəziyyəti (İşləyir, İşsiz, Tələbə)                                     |
| AylıqGəlir             | Müştərinin aylıq gəliri (AZN və ya digər valyuta)                         |
| KreditNövü             | Müştərinin götürmək istədiyi kredit növü (İstehlak, Avto, Ev və s.)       |
| KreditMəbləği          | Kreditin məbləği                                                          |
| KreditMəqsədi          | Kreditin məqsədi (Avtomobil, Ev, Təhsil və s.)                            |
| FaizDərəcəsi           | Kreditin illik faiz dərəcəsi (%)                                          |
| KreditSkoru            | Müştərinin kredit tarixçəsinə əsasən hesablanan skor                      |
| DigərKreditlərinSayı   | Müştərinin digər mövcud kreditlərinin sayı                                |
| KeçmişdəGecikmə        | Müştərinin əvvəlki kredit ödənişlərində gecikmə olub-olmaması (Bəli/Xeyr) |
| QaraSiyahida           | Müştərinin qara siyahıda olub-olmaması (Bəli/Xeyr)                        |
| MüraciətStatusu        | Kredit müraciətinin nəticəsi (Təsdiqləndi/Qəbul edilmədi)                 |
| YoxlayıcınınQeydləri   | Bank əməkdaşlarının əlavə qeydləri və müşahidələri                        |


---

## Gələcək genişləndirmə imkanları  
- Kredit götürmə ehtimalının proqnozlaşdırılması üçün **maşın öyrənməsi modelləri** (lojistik reqressiya, decision tree və s.)  
- Model qiymətləndirmə (accuracy, precision, recall və s.)  
- **Interaktiv dashboard** (məs: Streamlit və ya Dash ilə)  
- Əlavə məlumat mənbələri (məs: makroiqtisadi göstəricilər)  
- **API inteqrasiyası** ilə real-vaxt analitik sistem  

---

## 👩‍💻 Layihə müəllifi  
**Məleykəxanım Rəfiyeva**   
💡 Layihədə məlumat analizi, vizuallaşdırma və Python bacarıqları ön plandadır.

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/Maleykakhanim/Bank_Kredit_Simulyasiyasi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/maleykakhanim-rafiyeva/)



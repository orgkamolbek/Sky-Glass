# 🌤️ Sky-Glass: Glassmorphic Weather Dashboard

Dizayn va funksionallikni o'zida birlashtirgan, **Glassmorphism (Oynasimon UI)** uslubida yaratilgan interaktiv ob-havo ma'lumotlar paneli. JavaScript yordamida foydalanuvchi tanlagan shaharga qarab butun sahifaning atmosferasi va ranglar gammasi dinamik ravishda o'zgaradi.

---

## 📸 Loyiha ko'rinishi (Visual Preview)

### UI Mockup & Real-time Ambient Flow
> **Dasturning interfeysi quyidagicha vizual ko'rinishga ega:**
>
> |                                                 |
|    [●]  [●]  [●]  Sky-Glass Dashboard           |
| _______________________________________________ |
| |                                             | |
| |   =======================================   | |
| |  ||  [ Toshkent                  [v] ]  ||  | |
| |   =======================================   | |
| |                                             | |
| |        * QUYOSHLI * | |
| |                                             | |
| |        _     _                              | |
| |       ( )   ( )     +32°C                   | |
| |      (_ _ _ _ )                            | |
| |                                             | |
| |   ---------------------------------------   | |
| |  |  NAMLIK: 24%    |   SHAMOL: 4.2 m/s   |  | |
| |   ---------------------------------------   | |
| |                                             | |
| || |
|                                                 |
|       POWERED BY orgkamolbek // 2026            |
|_____|


### 🌌 Dinamik muhit qanday o'zgaradi? (Theme Architecture)

Dastur shunchaki matnlarni o'zgartirmaydi, u shahardagi ob-havo iqlimiga qarab orqa fondagi gradient va neon yorug'lik effektlarini o'zgartiradi:

[ Shahar Tanlanishi ]
│
├──► Toshkent/Dubay ──► Issiq iqlim ──► To'q to'q-sariq / Amber Glow 🔥
│
├──► Samarqand      ──► Mo'tadil    ──► Indigo / Deep Blue Aura 🌌
│
└──► London         ──► Yomg'irli   ──► Slate Gray / Cold Mystic Ambient 🌧️

---

## ⚡ Asosiy Xususiyatlari (Features)

* 🔮 **Premium Glassmorphism:** CSS `backdrop-filter: blur(20px)` yordamida zamonaviy shaffof oyna effekti.
* 🎨 **Dynamic UI Switching:** JavaScript orqali atmosfera yorug'liklari va fon ranglarining real vaqtda almashishi.
* 🌀 **Ambient Animation:** Orqa fonda sekin suzib yuruvchi va aylanuvchi nur effekti (`@keyframes float`).
* 📱 **Responsive Design:** Har qanday ekran o'lchamiga (Mobil, Planshet, Monitor) to'liq moslashuvchan maket.

---

## 🛠️ Texnologiyalar (Tech Stack)

* **HTML5** — Semantik struktura.
* **CSS3** — Custom Properties (Variables), Flexbox, CSS Grid, Glassmorphic blur, Keyframe animatsiyalar.
* **Pure JavaScript (ES6+)** — Ob'ektlar arxitekturasi va DOM manipulyatsiyasi.

---

## 🚀 Ishga tushirish (How to Run)

Loyiha hech qanday qo'shimcha o'rnatishlarni (**npm** yoki **pip**) talab qilmaydi. Shunchaki klonlab, brauzerda ochish kifoya:

```bash
# Loyihani yuklab olish
git clone [https://github.com/orgkamolbek/sky-glass-weather.git](https://github.com/orgkamolbek/sky-glass-weather.git)

# Loyiha papkasiga kirish
cd sky-glass-weather

# index.html faylini istalgan brauzerda oching!

<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>saidjakhonov_t - Ссылки</title>
    
    <!-- Подключаем Tailwind CSS для красивого дизайна -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Настройка фирменных цветов -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'brand-bg': '#0f1423',
                        'brand-card': '#0a0d18',
                        'brand-gold': '#d4b07c',
                    }
                }
            }
        }
    </script>

    <style>
        /* Стили для активной кнопки языка */
        .lang-btn.active {
            background-color: #d4b07c;
            color: #0f1423;
            box-shadow: 0 0 10px rgba(212,176,124,0.4);
        }
        .lang-btn:not(.active) {
            color: rgba(212,176,124,0.6);
        }
        .lang-btn:not(.active):hover {
            color: #d4b07c;
            background-color: rgba(212,176,124,0.1);
        }
    </style>
</head>
<body class="min-h-screen bg-brand-bg flex justify-center py-6 px-4 font-sans text-slate-200">
    <div class="w-full max-w-md relative">
        
        <!-- Кнопки выбора языка -->
        <div class="flex justify-end items-center gap-2 mb-6">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-4 h-4 text-brand-gold"><circle cx="12" cy="12" r="10"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/><path d="M2 12h20"/></svg>
            <div class="flex bg-brand-card rounded-full p-1 border border-brand-gold/20">
                <button onclick="setLang('uz')" id="btn-uz" class="lang-btn active px-3 py-1 text-xs font-bold rounded-full transition-all duration-300 uppercase">uz</button>
                <button onclick="setLang('ru')" id="btn-ru" class="lang-btn px-3 py-1 text-xs font-bold rounded-full transition-all duration-300 uppercase">ru</button>
                <button onclick="setLang('en')" id="btn-en" class="lang-btn px-3 py-1 text-xs font-bold rounded-full transition-all duration-300 uppercase">en</button>
            </div>
        </div>

        <!-- Профиль -->
        <div class="flex flex-col items-center mb-10">
            <div class="w-28 h-28 rounded-3xl bg-brand-card p-1 shadow-[0_0_25px_rgba(212,176,124,0.15)] mb-5 border border-brand-gold/30 rotate-3 hover:rotate-0 transition-transform duration-500">
                <!-- RASM UCHUN JOY: Quyidagi src="..." ichidagi manzil o'rniga postimages.org dan olgan silkangizni qo'yasiz -->
                <img 
                    src="https://i.postimg.cc/9FWxFM2M/IMG-0426.jpg" 
                    alt="Profil" 
                    class="w-full h-full object-cover rounded-[20px] -rotate-3 hover:rotate-0 transition-transform duration-500"
                />
            </div>
            <h1 id="t-name" class="text-2xl font-bold mb-2 tracking-widest text-brand-gold">saidjakhonov_t</h1>
            <div class="w-12 h-0.5 bg-brand-gold/50 mb-4 rounded-full"></div>
            <p id="t-bio" class="text-slate-400 text-center text-sm px-4 leading-relaxed">
                Assalomu alaykum! Mening sahifamga xush kelibsiz. Barcha kerakli ma'lumotlar va havolalar quyida keltirilgan.
            </p>
        </div>

        <!-- Список ссылок -->
        <div class="flex flex-col gap-4">
            
            <!-- Telegram Ссылка (Вставьте вашу ссылку в href="") -->
            <a href="https://t.me/saidjakhonov_timur" target="_blank" class="group relative overflow-hidden flex items-center p-4 rounded-xl transition-all duration-300 bg-brand-gold/10 border border-brand-gold/50 hover:bg-brand-gold/20 shadow-[0_4px_20px_rgba(212,176,124,0.1)]">
                <div class="flex items-center justify-center w-12 h-12 rounded-lg mr-4 shrink-0 shadow-inner transition-colors bg-brand-gold/20">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 text-brand-gold"><path d="m22 2-7 20-4-9-9-4Z"/><path d="M22 2 11 13"/></svg>
                </div>
                <div class="flex flex-col">
                    <span id="t-tg-title" class="font-semibold text-lg transition-colors text-brand-gold">Telegram Kanalim</span>
                    <span id="t-tg-sub" class="text-sm text-slate-500 group-hover:text-slate-400 transition-colors">Eng so'nggi yangiliklar va savdo g'oyalari</span>
                </div>
                <div class="ml-auto opacity-0 group-hover:opacity-100 transform translate-x-2 group-hover:translate-x-0 transition-all duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-brand-gold"><path d="m9 18 6-6-6-6"/></svg>
                </div>
            </a>

            <!-- Админ Ссылка (Вставьте вашу ссылку в href="") -->
            <a href="https://t.me/azcapital_info" target="_blank" class="group relative overflow-hidden flex items-center p-4 rounded-xl transition-all duration-300 bg-brand-card border border-brand-gold/10 hover:border-brand-gold/40 hover:bg-brand-gold/5">
                <div class="flex items-center justify-center w-12 h-12 rounded-lg mr-4 shrink-0 shadow-inner transition-colors bg-[#151b2e] group-hover:bg-brand-gold/10">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 text-brand-gold"><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
                </div>
                <div class="flex flex-col">
                    <span id="t-admin-title" class="font-semibold text-lg transition-colors text-slate-200 group-hover:text-brand-gold">Admin bilan bog'lanish</span>
                    <span id="t-admin-sub" class="text-sm text-slate-500 group-hover:text-slate-400 transition-colors">Loyihalar haqida ma'lumot</span>
                </div>
                <div class="ml-auto opacity-0 group-hover:opacity-100 transform translate-x-2 group-hover:translate-x-0 transition-all duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-brand-gold"><path d="m9 18 6-6-6-6"/></svg>
                </div>
            </a>

            <!-- Телефон (Замените номер в href="tel:...") -->
            <a href="tel:+998909987681" class="group relative overflow-hidden flex items-center p-4 rounded-xl transition-all duration-300 bg-brand-card border border-brand-gold/10 hover:border-brand-gold/40 hover:bg-brand-gold/5">
                <div class="flex items-center justify-center w-12 h-12 rounded-lg mr-4 shrink-0 shadow-inner transition-colors bg-[#151b2e] group-hover:bg-brand-gold/10">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 text-brand-gold"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
                </div>
                <div class="flex flex-col">
                    <span id="t-phone-title" class="font-semibold text-lg transition-colors text-slate-200 group-hover:text-brand-gold">Aloqa uchun raqam</span>
                    <span id="t-phone-sub" class="text-sm text-slate-500 group-hover:text-slate-400 transition-colors">+998 90 998 76 81</span>
                </div>
                <div class="ml-auto opacity-0 group-hover:opacity-100 transform translate-x-2 group-hover:translate-x-0 transition-all duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-brand-gold"><path d="m9 18 6-6-6-6"/></svg>
                </div>
            </a>

            <!-- Локация -->
            <a href="https://maps.app.goo.gl/APdVZujiqEw3ZqyD6" target="_blank" class="group relative overflow-hidden flex items-center p-4 rounded-xl transition-all duration-300 bg-brand-card border border-brand-gold/10 hover:border-brand-gold/40 hover:bg-brand-gold/5">
                <div class="flex items-center justify-center w-12 h-12 rounded-lg mr-4 shrink-0 shadow-inner transition-colors bg-[#151b2e] group-hover:bg-brand-gold/10">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 text-brand-gold"><path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"/><circle cx="12" cy="10" r="3"/></svg>
                </div>
                <div class="flex flex-col">
                    <span id="t-loc-title" class="font-semibold text-lg transition-colors text-slate-200 group-hover:text-brand-gold">Manzil</span>
                    <span id="t-loc-sub" class="text-sm text-slate-500 group-hover:text-slate-400 transition-colors">Toshkent shaxar, Yakkasaroy tumani …</span>
                </div>
                <div class="ml-auto opacity-0 group-hover:opacity-100 transform translate-x-2 group-hover:translate-x-0 transition-all duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-brand-gold"><path d="m9 18 6-6-6-6"/></svg>
                </div>
            </a>

            <!-- Instagram (Вставьте ссылку в href="") -->
            <a href="https://www.instagram.com/saidjakhonov_t?igsh=ZjZ5Y2wxOHpxajM=" target="_blank" class="group relative overflow-hidden flex items-center p-4 rounded-xl transition-all duration-300 bg-brand-card border border-brand-gold/10 hover:border-brand-gold/40 hover:bg-brand-gold/5">
                <div class="flex items-center justify-center w-12 h-12 rounded-lg mr-4 shrink-0 shadow-inner transition-colors bg-[#151b2e] group-hover:bg-brand-gold/10">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-6 h-6 text-brand-gold"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg>
                </div>
                <div class="flex flex-col">
                    <span id="t-inst-title" class="font-semibold text-lg transition-colors text-slate-200 group-hover:text-brand-gold">Instagram sahifam</span>
                    <span id="t-inst-sub" class="text-sm text-slate-500 group-hover:text-slate-400 transition-colors">Foydali ma'lumotlar va qiziqarli videolar</span>
                </div>
                <div class="ml-auto opacity-0 group-hover:opacity-100 transform translate-x-2 group-hover:translate-x-0 transition-all duration-300">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5 text-brand-gold"><path d="m9 18 6-6-6-6"/></svg>
                </div>
            </a>

        </div>

        <!-- Нижние маленькие иконки (соцсети) -->
        <div class="mt-12 flex justify-center gap-6">
            <a href="https://t.me/saidjakhonov_timur" target="_blank" class="w-10 h-10 rounded-full bg-brand-card border border-brand-gold/20 flex items-center justify-center text-brand-gold/70 hover:text-brand-gold hover:border-brand-gold/60 hover:shadow-[0_0_15px_rgba(212,176,124,0.2)] transition-all">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5"><path d="M7.9 20A9 9 0 1 0 4 16.1L2 22Z"/></svg>
            </a>
            <a href="https://www.instagram.com/saidjakhonov_t?igsh=ZjZ5Y2wxOHpxajM=" target="_blank" class="w-10 h-10 rounded-full bg-brand-card border border-brand-gold/20 flex items-center justify-center text-brand-gold/70 hover:text-brand-gold hover:border-brand-gold/60 hover:shadow-[0_0_15px_rgba(212,176,124,0.2)] transition-all">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"/></svg>
            </a>
            <a href="tel:+998909987681" class="w-10 h-10 rounded-full bg-brand-card border border-brand-gold/20 flex items-center justify-center text-brand-gold/70 hover:text-brand-gold hover:border-brand-gold/60 hover:shadow-[0_0_15px_rgba(212,176,124,0.2)] transition-all">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-5 h-5"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
            </a>
        </div>
        
        <p id="t-footer" class="text-center text-brand-gold/40 text-xs mt-8 font-light tracking-wider">
            © 2026 Barcha huquqlar himoyalangan.
        </p>
    </div>

    <!-- Скрипт для смены языков и отрисовки иконок -->
    <script>
        // Словарь переводов
        const translations = {
            uz: {
                name: "saidjakhonov_t",
                bio: "Assalomu alaykum! Mening sahifamga xush kelibsiz. Barcha kerakli ma'lumotlar va havolalar quyida keltirilgan.",
                tgTitle: "Telegram Kanalim", tgSub: "Eng so'nggi yangiliklar va savdo g'oyalari",
                adminTitle: "Admin bilan bog'lanish", adminSub: "Loyihalar haqida ma'lumot",
                phoneTitle: "Aloqa uchun raqam", phoneSub: "+998 90 998 76 81",
                locTitle: "Manzil", locSub: "Toshkent shaxar, Yakkasaroy tumani …",
                instTitle: "Instagram sahifam", instSub: "Foydali ma'lumotlar va qiziqarli videolar",
                footer: "© 2026 Barcha huquqlar himoyalangan."
            },
            ru: {
                name: "saidjakhonov_t",
                bio: "Здравствуйте! Добро пожаловать на мою страницу. Вся необходимая информация и ссылки приведены ниже.",
                tgTitle: "Мой Telegram Канал", tgSub: "Последние новости и торговые идеи",
                adminTitle: "Связаться с админом", adminSub: "Информация о проектах",
                phoneTitle: "Номер для связи", phoneSub: "+998 90 998 76 81",
                locTitle: "Адрес", locSub: "г. Ташкент, Яккасарайский район …",
                instTitle: "Моя страница в Instagram", instSub: "Полезная информация и интересные видео",
                footer: "© 2026 Все права защищены."
            },
            en: {
                name: "saidjakhonov_t",
                bio: "Hello! Welcome to my page. All necessary information and links are provided below.",
                tgTitle: "My Telegram Channel", tgSub: "Latest news and trading ideas",
                adminTitle: "Contact Admin", adminSub: "Information about projects",
                phoneTitle: "Contact Number", phoneSub: "+998 90 998 76 81",
                locTitle: "Location", locSub: "Tashkent city, Yakkasaray district …",
                instTitle: "My Instagram Page", instSub: "Useful information and interesting videos",
                footer: "© 2026 All rights reserved."
            }
        };

        // Функция смены языка
        function setLang(lang) {
            const t = translations[lang];
            
            // Обновляем тексты
            document.getElementById('t-name').innerText = t.name;
            document.getElementById('t-bio').innerText = t.bio;
            
            document.getElementById('t-tg-title').innerText = t.tgTitle;
            document.getElementById('t-tg-sub').innerText = t.tgSub;
            
            document.getElementById('t-admin-title').innerText = t.adminTitle;
            document.getElementById('t-admin-sub').innerText = t.adminSub;
            
            document.getElementById('t-phone-title').innerText = t.phoneTitle;
            document.getElementById('t-phone-sub').innerText = t.phoneSub;
            
            document.getElementById('t-loc-title').innerText = t.locTitle;
            document.getElementById('t-loc-sub').innerText = t.locSub;
            
            document.getElementById('t-inst-title').innerText = t.instTitle;
            document.getElementById('t-inst-sub').innerText = t.instSub;
            
            document.getElementById('t-footer').innerText = t.footer;

            // Обновляем стили кнопок (убираем активный класс у всех, ставим нужному)
            document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
            document.getElementById('btn-' + lang).classList.add('active');
        }
    </script>
</body>
</html>








# vpn-
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سکیورکانکت | امنیت و سرعت برتر</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Vazirmatn', sans-serif;
            scroll-behavior: smooth;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(59, 130, 246, 0.4);
        }
        .testimonial-card {
            transition: all 0.3s ease;
        }
        .testimonial-card:hover {
            transform: scale(1.03);
        }
        .cta-button {
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(59, 130, 246, 0.5);
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            right: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md fixed w-full z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                </svg>
                <span class="mr-2 text-2xl font-bold text-blue-800">سکیورکانکت</span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#features" class="nav-link text-gray-700 hover:text-blue-700 font-medium ml-8">ویژگی‌ها</a>
                <a href="#pricing" class="nav-link text-gray-700 hover:text-blue-700 font-medium ml-8">قیمت‌ها</a>
                <a href="#testimonials" class="nav-link text-gray-700 hover:text-blue-700 font-medium ml-8">نظرات مشتریان</a>
                <a href="#support" class="nav-link text-gray-700 hover:text-blue-700 font-medium">پشتیبانی</a>
            </div>
            <div class="flex items-center space-x-4">
                <a href="#" class="text-blue-700 hover:text-blue-800 font-semibold ml-4">ورود</a>
                <a href="#" class="bg-blue-700 hover:bg-blue-800 text-white px-4 py-2 rounded-md font-semibold transition duration-300">ثبت نام</a>
            </div>
            <button class="md:hidden text-gray-700 focus:outline-none" id="mobile-menu-button">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                </svg>
            </button>
        </div>
        <!-- Mobile menu -->
        <div class="md:hidden hidden bg-white w-full pb-4 px-4" id="mobile-menu">
            <a href="#features" class="block py-2 text-gray-700 hover:text-blue-700 font-medium">ویژگی‌ها</a>
            <a href="#pricing" class="block py-2 text-gray-700 hover:text-blue-700 font-medium">قیمت‌ها</a>
            <a href="#testimonials" class="block py-2 text-gray-700 hover:text-blue-700 font-medium">نظرات مشتریان</a>
            <a href="#support" class="block py-2 text-gray-700 hover:text-blue-700 font-medium">پشتیبانی</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="gradient-bg pt-28 pb-20 px-4 md:px-0">
        <div class="container mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 text-center md:text-right mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold text-white leading-tight mb-4">زندگی دیجیتال خود را با وی‌پی‌ان برتر ایمن کنید</h1>
                <p class="text-blue-100 text-lg md:text-xl mb-8">سرعت فوق‌العاده با رمزگذاری نظامی را تجربه کنید. حریم خصوصی شما اولویت ماست.</p>
                <div class="flex flex-col sm:flex-row justify-center md:justify-end space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="#pricing" class="cta-button bg-white text-blue-700 hover:bg-blue-50 px-8 py-3 rounded-lg font-bold text-lg shadow-lg ml-4">شروع کنید</a>
                    <a href="#features" class="cta-button border-2 border-white text-white hover:bg-white hover:bg-opacity-10 px-8 py-3 rounded-lg font-bold text-lg">بیشتر بدانید</a>
                </div>
            </div>
            <div class="md:w-1/2">
                <svg class="w-full max-w-lg mx-auto" viewBox="0 0 500 400" xmlns="http://www.w3.org/2000/svg">
                    <defs>
                        <linearGradient id="deviceGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                            <stop offset="0%" stop-color="#f0f9ff" />
                            <stop offset="100%" stop-color="#dbeafe" />
                        </linearGradient>
                        <filter id="shadow" x="-10%" y="-10%" width="120%" height="130%">
                            <feDropShadow dx="0" dy="10" stdDeviation="15" flood-color="#1e40af" flood-opacity="0.3"/>
                        </filter>
                    </defs>
                    <!-- Laptop -->
                    <rect x="100" y="100" width="300" height="200" rx="10" fill="url(#deviceGrad)" filter="url(#shadow)"/>
                    <rect x="120" y="120" width="260" height="160" rx="5" fill="#1e3a8a"/>
                    <!-- Shield on screen -->
                    <path d="M250 140 L290 160 V210 C290 230 250 250 250 250 C250 250 210 230 210 210 V160 Z" fill="#3b82f6" stroke="#fff" stroke-width="4"/>
                    <path d="M250 160 L275 172 V205 C275 215 250 230 250 230 C250 230 225 215 225 205 V172 Z" fill="#1e3a8a"/>
                    <path d="M245 190 L255 190 L255 210 L245 210 Z" fill="#fff"/>
                    <circle cx="250" cy="180" r="5" fill="#fff"/>
                    <!-- Laptop base -->
                    <path d="M80 300 L420 300 L390 340 L110 340 Z" fill="#e5e7eb" filter="url(#shadow)"/>
                    <!-- Phone -->
                    <rect x="350" y="180" width="70" height="140" rx="10" fill="url(#deviceGrad)" filter="url(#shadow)"/>
                    <rect x="360" y="190" width="50" height="100" rx="3" fill="#1e3a8a"/>
                    <!-- Lock on phone -->
                    <circle cx="385" cy="220" r="10" fill="#3b82f6" stroke="#fff" stroke-width="2"/>
                    <rect x="380" y="225" width="10" height="15" rx="2" fill="#3b82f6" stroke="#fff" stroke-width="2"/>
                    <circle cx="385" cy="300" r="10" fill="#e5e7eb"/>
                </svg>
            </div>
        </div>
    </header>

    <!-- Trust Indicators -->
    <section class="bg-white py-8 shadow-md">
        <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center items-center text-center">
                <div class="w-1/2 md:w-1/4 mb-6 md:mb-0">
                    <div class="text-blue-700 font-bold text-2xl md:text-3xl">+۲,۵۰۰</div>
                    <div class="text-gray-600">سرور جهانی</div>
                </div>
                <div class="w-1/2 md:w-1/4 mb-6 md:mb-0">
                    <div class="text-blue-700 font-bold text-2xl md:text-3xl">۹۹.۹٪</div>
                    <div class="text-gray-600">آپ‌تایم</div>
                </div>
                <div class="w-1/2 md:w-1/4">
                    <div class="text-blue-700 font-bold text-2xl md:text-3xl">+۵۰</div>
                    <div class="text-gray-600">کشور</div>
                </div>
                <div class="w-1/2 md:w-1/4">
                    <div class="text-blue-700 font-bold text-2xl md:text-3xl">+۱ میلیون</div>
                    <div class="text-gray-600">کاربر راضی</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">چرا سکیورکانکت را انتخاب کنید؟</h2>
                <p class="text-gray-600 text-lg max-w-2xl mx-auto">سرویس وی‌پی‌ان برتر ما با سرعت فوق‌العاده و ویژگی‌های امنیتی بی‌نظیر، شما را در فضای آنلاین محافظت می‌کند.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">رمزگذاری نظامی</h3>
                    <p class="text-gray-600">داده‌های شما با رمزگذاری AES-256 محافظت می‌شود، همان استانداردی که توسط متخصصان امنیتی در سراسر جهان استفاده می‌شود.</p>
                </div>
                
                <!-- Feature 2 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">سرعت فوق‌العاده</h3>
                    <p class="text-gray-600">استریم، دانلود و مرور بدون وقفه. سرورهای بهینه‌سازی شده ما اطمینان می‌دهند که سریع‌ترین اتصال ممکن را دریافت می‌کنید.</p>
                </div>
                
                <!-- Feature 3 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">شبکه سرور جهانی</h3>
                    <p class="text-gray-600">با شبکه‌ای از بیش از ۲,۵۰۰ سرور در بیش از ۵۰ کشور جهان، به محتوای مورد نظر خود از هر کجا دسترسی داشته باشید.</p>
                </div>
                
                <!-- Feature 4 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M3.707 2.293a1 1 0 00-1.414 1.414l14 14a1 1 0 001.414-1.414l-1.473-1.473A10.014 10.014 0 0019.542 10C18.268 5.943 14.478 3 10 3a9.958 9.958 0 00-4.512 1.074l-1.78-1.781zm4.261 4.26l1.514 1.515a2.003 2.003 0 012.45 2.45l1.514 1.514a4 4 0 00-5.478-5.478z" clip-rule="evenodd" />
                            <path d="M12.454 16.697L9.75 13.992a4 4 0 01-3.742-3.741L2.335 6.578A9.98 9.98 0 00.458 10c1.274 4.057 5.065 7 9.542 7 .847 0 1.669-.105 2.454-.303z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">سیاست عدم ثبت لاگ</h3>
                    <p class="text-gray-600">ما هرگز فعالیت‌های آنلاین شما را ردیابی، ذخیره یا به اشتراک نمی‌گذاریم. حریم خصوصی شما با سیاست سختگیرانه عدم ثبت لاگ ما تضمین می‌شود.</p>
                </div>
                
                <!-- Feature 5 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3zM6 8a2 2 0 11-4 0 2 2 0 014 0zM16 18v-3a5.972 5.972 0 00-.75-2.906A3.005 3.005 0 0119 15v3h-3zM4.75 12.094A5.973 5.973 0 004 15v3H1v-3a3 3 0 013.75-2.906z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">چندین دستگاه</h3>
                    <p class="text-gray-600">با یک اشتراک، تا ۶ دستگاه را همزمان محافظت کنید. با تمام پلتفرم‌ها و دستگاه‌های اصلی سازگار است.</p>
                </div>
                
                <!-- Feature 6 -->
                <div class="feature-card bg-white p-8 rounded-xl shadow-lg transition duration-300">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">پشتیبانی ۲۴/۷</h3>
                    <p class="text-gray-600">تیم پشتیبانی متخصص ما در تمام ساعات شبانه‌روز آماده کمک به شما در هر سؤال یا مشکل فنی است.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">قیمت‌گذاری ساده و شفاف</h2>
                <p class="text-gray-600 text-lg max-w-2xl mx-auto">طرحی را انتخاب کنید که برای شما بهترین است. تمام طرح‌ها شامل مجموعه کامل ویژگی‌های ما هستند.</p>
            </div>
            
            <div class="flex flex-col lg:flex-row justify-center gap-8 max-w-5xl mx-auto">
                <!-- Monthly Plan -->
                <div class="bg-white border border-gray-200 rounded-2xl shadow-lg p-8 flex-1 transition-all duration-300 hover:shadow-xl">
                    <div class="text-center mb-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">ماهانه</h3>
                        <div class="text-blue-700 font-bold text-4xl mb-1">۱۲.۹۹ دلار<span class="text-lg text-gray-500 font-normal">/ماه</span></div>
                        <p class="text-gray-500">صورتحساب ماهانه</p>
                    </div>
                    <ul class="mb-8 space-y-3">
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">تمام ویژگی‌های وی‌پی‌ان</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">اتصال تا ۶ دستگاه</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">پشتیبانی ۲۴/۷</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">۳۰ روز ضمانت بازگشت وجه</span>
                        </li>
                    </ul>
                    <button class="w-full bg-blue-700 hover:bg-blue-800 text-white py-3 rounded-lg font-semibold transition duration-300">شروع کنید</button>
                </div>
                
                <!-- Annual Plan (Best Value) -->
                <div class="bg-blue-50 border-2 border-blue-700 rounded-2xl shadow-lg p-8 flex-1 transition-all duration-300 hover:shadow-xl relative lg:scale-110">
                    <div class="absolute top-0 left-0 bg-blue-700 text-white text-sm font-bold px-4 py-1 rounded-tl-xl rounded-br-xl">بهترین ارزش</div>
                    <div class="text-center mb-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">سالانه</h3>
                        <div class="text-blue-700 font-bold text-4xl mb-1">۶.۹۹ دلار<span class="text-lg text-gray-500 font-normal">/ماه</span></div>
                        <p class="text-gray-500">صورتحساب سالانه (۸۳.۸۸ دلار)</p>
                        <p class="text-green-600 font-medium mt-2">۴۶٪ صرفه‌جویی</p>
                    </div>
                    <ul class="mb-8 space-y-3">
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">تمام ویژگی‌های وی‌پی‌ان</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">اتصال تا ۶ دستگاه</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">پشتیبانی ۲۴/۷</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">۳۰ روز ضمانت بازگشت وجه</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">پشتیبانی اولویت‌دار</span>
                        </li>
                    </ul>
                    <button class="w-full bg-blue-700 hover:bg-blue-800 text-white py-3 rounded-lg font-semibold transition duration-300">شروع کنید</button>
                </div>
                
                <!-- Biennial Plan -->
                <div class="bg-white border border-gray-200 rounded-2xl shadow-lg p-8 flex-1 transition-all duration-300 hover:shadow-xl">
                    <div class="text-center mb-6">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">طرح ۲ ساله</h3>
                        <div class="text-blue-700 font-bold text-4xl mb-1">۴.۹۹ دلار<span class="text-lg text-gray-500 font-normal">/ماه</span></div>
                        <p class="text-gray-500">صورتحساب هر ۲ سال (۱۱۹.۷۶ دلار)</p>
                        <p class="text-green-600 font-medium mt-2">۶۲٪ صرفه‌جویی</p>
                    </div>
                    <ul class="mb-8 space-y-3">
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">تمام ویژگی‌های وی‌پی‌ان</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">اتصال تا ۶ دستگاه</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">پشتیبانی ۲۴/۷</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">۳۰ روز ضمانت بازگشت وجه</span>
                        </li>
                        <li class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-700 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                            </svg>
                            <span class="text-gray-600">پشتیبانی اولویت‌دار</span>
                        </li>
                    </ul>
                    <button class="w-full bg-blue-700 hover:bg-blue-800 text-white py-3 rounded-lg font-semibold transition duration-300">شروع کنید</button>
                </div>
            </div>
            
            <div class="text-center mt-10">
                <p class="text-gray-600">تمام طرح‌ها شامل ۳۰ روز ضمانت بازگشت وجه هستند. بدون هیچ سؤالی.</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">مشتریان ما چه می‌گویند</h2>
                <p class="text-gray-600 text-lg max-w-2xl mx-auto">به هزاران مشتری راضی بپیوندید که برای امنیت آنلاین خود به سکیورکانکت اعتماد می‌کنند.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Testimonial 1 -->
                <div class="testimonial-card bg-white p-8 rounded-xl shadow-lg">
                    <div class="flex items-center mb-6">
                        <div class="text-yellow-400 flex">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"من چندین سرویس وی‌پی‌ان را امتحان کرده‌ام، اما سکیورکانکت بهترین است. سرعت‌ها باورنکردنی هستند و من هرگز نگران حریم خصوصی خود نیستم. ارزش هر پنی را دارد!"</p>
                    <div class="flex items-center">
                        <div class="bg-blue-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <span class="text-blue-700 font-bold text-xl">MJ</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">مایکل جانسون</h4>
                            <p class="text-gray-500 text-sm">توسعه‌دهنده نرم‌افزار</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card bg-white p-8 rounded-xl shadow-lg">
                    <div class="flex items-center mb-6">
                        <div class="text-yellow-400 flex">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"به عنوان کسی که مرتباً سفر می‌کند، داشتن یک وی‌پی‌ان قابل اعتماد ضروری است. سکیورکانکت در هر کشوری که بازدید کرده‌ام بدون نقص کار می‌کند و پشتیبانی مشتری آنها فوق‌العاده است."</p>
                    <div class="flex items-center">
                        <div class="bg-blue-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <span class="text-blue-700 font-bold text-xl">SR</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">سارا رودریگز</h4>
                            <p class="text-gray-500 text-sm">وبلاگ‌نویس سفر</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card bg-white p-8 rounded-xl shadow-lg">
                    <div class="flex items-center mb-6">
                        <div class="text-yellow-400 flex">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                                <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                            </svg>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-6">"امنیت برای کسب و کار ما بسیار مهم است و سکیورکانکت آن را تأمین می‌کند. ویژگی دسترسی تیمی برای نیروی کار از راه دور ما عالی است و کنترل‌های مدیریتی بسیار ساده هستند."</p>
                    <div class="flex items-center">
                        <div class="bg-blue-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <span class="text-blue-700 font-bold text-xl">DT</span>
                        </div>
                        <div>
                            <h4 class="font-semibold text-gray-800">داوود تامسون</h4>
                            <p class="text-gray-500 text-sm">مدیر فناوری اطلاعات</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 gradient-bg">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-white mb-6">آماده ایمن‌سازی حضور آنلاین خود هستید؟</h2>
            <p class="text-blue-100 text-lg mb-10 max-w-2xl mx-auto">به بیش از ۱ میلیون کاربر بپیوندید که برای حریم خصوصی و امنیت آنلاین خود به سکیورکانکت اعتماد می‌کنند.</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6">
                <a href="#pricing" class="cta-button bg-white text-blue-700 hover:bg-blue-50 px-8 py-4 rounded-lg font-bold text-lg shadow-lg ml-6">همین حالا شروع کنید</a>
                <a href="#" class="cta-button border-2 border-white text-white hover:bg-white hover:bg-opacity-10 px-8 py-4 rounded-lg font-bold text-lg">۷ روز رایگان امتحان کنید</a>
            </div>
            <p class="text-blue-100 mt-6">بدون نیاز به کارت اعتباری. هر زمان که بخواهید می‌توانید لغو کنید.</p>
        </div>
    </section>

    <!-- Support Section -->
    <section id="support" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">ما اینجا هستیم تا کمک کنیم</h2>
                <p class="text-gray-600 text-lg max-w-2xl mx-auto">تیم پشتیبانی ما ۲۴/۷ در دسترس است تا به شما در هر سؤال یا مشکلی کمک کند.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-4xl mx-auto">
                <!-- Support Option 1 -->
                <div class="bg-blue-50 p-8 rounded-xl text-center">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">تماس با ما</h3>
                    <p class="text-gray-600 mb-4">مستقیماً با تیم پشتیبانی ما صحبت کنید</p>
                    <a href="tel:+18005551234" class="text-blue-700 font-semibold hover:text-blue-800">+۱ (۸۰۰) ۵۵۵-۱۲۳۴</a>
                </div>
                
                <!-- Support Option 2 -->
                <div class="bg-blue-50 p-8 rounded-xl text-center">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
                            <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">ایمیل به ما</h3>
                    <p class="text-gray-600 mb-4">در عرض ۲۴ ساعت پاسخ دریافت کنید</p>
                    <a href="mailto:support@secureconnect.com" class="text-blue-700 font-semibold hover:text-blue-800">support@secureconnect.com</a>
                </div>
                
                <!-- Support Option 3 -->
                <div class="bg-blue-50 p-8 rounded-xl text-center">
                    <div class="bg-blue-100 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-blue-700" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3">گفتگوی زنده</h3>
                    <p class="text-gray-600 mb-4">کمک فوری از تیم ما دریافت کنید</p>
                    <button class="text-blue-700 font-semibold hover:text-blue-800" onclick="alert('گفتگوی زنده اینجا باز می‌شود')">شروع گفتگو</button>
                </div>
            </div>
            
            <div class="mt-16 text-center">
                <h3 class="text-xl font-bold text-gray-800 mb-6">سؤالات متداول</h3>
                
                <div class="max-w-3xl mx-auto">
                    <div class="mb-6">
                        <button class="flex justify-between items-center w-full text-right font-semibold text-gray-800 py-3 px-4 rounded-lg bg-gray-100 hover:bg-gray-200 transition duration-300" onclick="toggleFAQ('faq1')">
                            <svg id="faq1-icon" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-600 transform transition-transform duration-300" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                            </svg>
                            <span>وی‌پی‌ان چگونه از حریم خصوصی من محافظت می‌کند؟</span>
                        </button>
                        <div id="faq1" class="hidden mt-2 px-4 text-gray-600 text-right">
                            <p>وی‌پی‌ان یک تونل رمزگذاری شده برای داده‌های شما ایجاد می‌کند و فعالیت آنلاین شما را از هکرها، ارائه‌دهندگان خدمات اینترنتی و سایر اشخاص ثالث محافظت می‌کند. آدرس IP شما را پنهان می‌کند و ردیابی موقعیت و عادات مرور شما را برای وب‌سایت‌ها دشوار می‌سازد.</p>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <button class="flex justify-between items-center w-full text-right font-semibold text-gray-800 py-3 px-4 rounded-lg bg-gray-100 hover:bg-gray-200 transition duration-300" onclick="toggleFAQ('faq2')">
                            <svg id="faq2-icon" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-600 transform transition-transform duration-300" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                            </svg>
                            <span>آیا می‌توانم از سکیورکانکت در چندین دستگاه استفاده کنم؟</span>
                        </button>
                        <div id="faq2" class="hidden mt-2 px-4 text-gray-600 text-right">
                            <p>بله، تمام طرح‌های سکیورکانکت به شما امکان می‌دهند تا ۶ دستگاه را همزمان محافظت کنید. برنامه ما با ویندوز، مک‌او‌اس، iOS، اندروید، لینوکس و موارد دیگر سازگار است.</p>
                        </div>
                    </div>
                    
                    <div class="mb-6">
                        <button class="flex justify-between items-center w-full text-right font-semibold text-gray-800 py-3 px-4 rounded-lg bg-gray-100 hover:bg-gray-200 transition duration-300" onclick="toggleFAQ('faq3')">
                            <svg id="faq3-icon" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-600 transform transition-transform duration-300" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" />
                            </svg>
                            <span>آیا سکیورکان```

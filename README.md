<div align="center">

# 🌊 UIO - THE ELITE PORTFOLIO TEMPLATE

### 🏆 Achieving the "Golden Score" in Web Performance & Core Web Vitals

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayr-uio-954897370/) ![Perfect Score](https://img.shields.io/badge/Lighthouse-100/100-brightgreen?style=for-the-badge) ![Maintained](https://img.shields.io/badge/Maintained-Yes-blue?style=for-the-badge)

---

[**🌐 Explore Live Demo**](https://ahmed-let-front.github.io/teamplate-web-3/)

---

### 🛠️ CORE TECH STACK

|                                                                                                           |                                                                                                        |                                                                                                                              |                                                                                                                          |
| :-------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) | ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) | ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) | ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) |
|  ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)   |  ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)   |            ![FontAwesome](https://img.shields.io/badge/Font_Awesome-333333?style=for-the-badge&logo=fontawesome)             |           ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)            |

</div>

## 🚀 HIGH-END PERFORMANCE ENGINEERING

Optimization is at the heart of Uio. This project implements advanced techniques to achieve sub-second load times.

![Hero Preview](public/hero.png)

### 💎 Performance Highlights:

- **World-Class Iconography Loading:** Instead of loading the entire FontAwesome library, I used `@font-face` to call only the specific local files needed. I combined this with `--fa-font-display: swap !important` to automatically load a fallback font instantly before the icons render.
- **Smart CSS Variable Architecture:** I explicitly placed the `--fa-font-display` variable inside `:root` within `@layer base`.
  - **Why not `@theme`?** Tailwind's `@theme` is designed to generate utility classes and variants. Placing it there would force PostCSS and the JIT engine to unnecessarily compile an unused utility class, wasting build resources.
  - **Why `:root` inside `@layer base`?** FontAwesome's architecture strictly requires a globally scoped CSS variable (`:root`). Wrapping it in `@layer base` ensures it bundles seamlessly with Tailwind's base files without confusing Vite or exhausting PostCSS, guaranteeing a hyper-optimized build.
- **Reflow & Rendering Optimization:** I strictly avoided using properties like `margin` for movement to prevent expensive browser **Reflows**. Instead, I relied heavily on `transform: translate` for movement and `transform: scale` for resizing. While I did use `width` and `left` for specific layout-dependent positioning, it was a calculated decision for elements that don't consume significant CPU overhead.
- **Resource Prioritization:** Using preload techniques to bypass the browser's discovery phase for critical LCP elements.
- **Efficient Composite Layers:** Strategic use of `will-change` to offload animations to the GPU, ensuring a stable **60 FPS**.

---

## 🔍 LIGHTHOUSE AUDIT: THE PERFECT SCORE

![Lighthouse Overview](public/lighthouse.png)

![Detailed Metrics](public/metrics.png)

| Core Web Vital                     | Score / Value | Engineering Strategy                                |
| :--------------------------------- | :-----------: | :-------------------------------------------------- |
| **Performance**                    |    🟢 100     | Preloading, Asset Minification, WebP Compression    |
| **LCP (Largest Contentful Paint)** |   ⚡ 0.5 s    | Preloading critical hero image & zero-latency fonts |
| **TBT (Total Blocking Time)**      |    ⏱️ 0 ms    | Efficient JS execution & chunking via Vite          |
| **CLS (Cumulative Layout Shift)**  |     📐 0      | Explicit dimensions & `font-display: swap`          |
| **Accessibility & SEO**            |    🟢 100     | ARIA Roles, Semantic HTML, Schema ready             |

---

## 👨‍💻 THE CRAFTSMAN: AHMED YASSER

> "True engineering is not just about making it work; it's about making it perfect."

I am a **15-year-old Junior Front-End Developer** with a relentless obsession for performance.

- **Daily Commitment**: Dedicated **8 to 10 hours** of focused deep-work and coding.
- **Project Portfolio**: Delivered **15+ high-performance projects** in just 2 months, focusing on modern UI/UX.
- **Goal**: Mastering the browser rendering engine to build the next generation of web applications.

![Full Preview](public/preview.png)

---

### 📞 CONTACT ME

<div align="center">

|                                                                            LinkedIn                                                                             |                        GitHub                         |                       Email                       |      WhatsApp      |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------: | :-----------------------------------------------: | :----------------: |
| [![LinkedIn](https://img.shields.io/badge/Ahmed_Yasser-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayr-uio-954897370/) | [Ahmed-let-front](https://github.com/Ahmed-let-front) | [letcosdgp@gmail.com](mailto:letcosdgp@gmail.com) | `+20 105 011 9571` |

</div>

---

<div align="center">

---

---

# 🌊 يويو - قالب النخبة للمواقع الشخصية (UIO)

### 🏆 تحقيق "العلامة الذهبية" في أداء الويب ومؤشرات الأداء الأساسية (Core Web Vitals)

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayr-uio-954897370/) ![Perfect Score](https://img.shields.io/badge/Lighthouse-100/100-brightgreen?style=for-the-badge) ![Maintained](https://img.shields.io/badge/Maintained-Yes-blue?style=for-the-badge)

[**🌐 العرض المباشر للمشروع**](https://ahmed-let-front.github.io/teamplate-web-3/)

---

### 🛠️ البنية التقنية الأساسية

|                                                                                                           |                                                                                                        |                                                                                                                              |                                                                                                                          |
| :-------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) | ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) | ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) | ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) |
|  ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)   |  ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)   |            ![FontAwesome](https://img.shields.io/badge/Font_Awesome-333333?style=for-the-badge&logo=fontawesome)             |           ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)            |

</div>

## 🚀 هندسة الأداء المتقدمة

تحسين الأداء هو جوهر هذا المشروع. تم تطبيق تقنيات متقدمة لضمان تحميل الموقع في أقل من ثانية.

![Hero Preview](public/hero.png)

### 💎 أبرز تحسينات الأداء:

- **تحميل أيقونات فائق السرعة:** بدلاً من استدعاء مكتبة FontAwesome بالكامل، استخدمت `@font-face` لتحميل الملفات المحلية المطلوبة فقط، ودمجت ذلك مع استخدام `--fa-font-display: swap !important`.
- **هندسة المتغيرات والـ Build Process:** قمت بوضع متغير `--fa-font-display` تحديداً داخل `:root` ضمن `@layer base`.
  - **لماذا ليس `@theme`؟** لأن وظيفة `@theme` في Tailwind هي إنشاء Utility Classes بمتغيراتها (Variants). وضع متغير وظيفي هناك سيجبر PostCSS ومحرك JIT على استهلاك موارد المعالجة لتوليد Class لن يتم استخدامه أصلاً، وهذا إهدار لموارد الـ Build.
  - **لماذا `:root` داخل `@layer base`؟** مصممو FontAwesome بنوا المكتبة لتقرأ من متغير عام (CSS Variable)، والمكان الصحيح له هو `:root`. ووضعه داخل `@layer base` يضمن دمجه بسلاسة مع ملفات Tailwind الأساسية، مما يمنع تشتيت Vite أو PostCSS ويضمن عملية بناء نظيفة واحترافية.
- **تحسين الـ Reflow ومعالجة المتصفح:** تجنبت تماماً استخدام خصائص مثل `margin` للتحريك لمنع حدوث **Reflow** مكلف للمتصفح، واعتمدت بشكل أساسي على `transform: translate` للتحريك و `transform: scale` لتغيير الحجم. ورغم استخدامي لـ `width` و `left` في بعض العناصر، إلا أنه كان قراراً هندسياً مدروساً لعناصر تحتاج التموضع في أماكن مختلفة بطبيعتها ولا تستهلك الكثير من الـ CPU.
- **تحديد أولويات الموارد:** استخدام التحميل المسبق لتسريع تحميل العناصر الأساسية (LCP).
- **طبقات المعالجة الفعالة:** استخدام `will-change` بشكل استراتيجي لمعالجة الرسوم المتحركة عبر كارت الشاشة (GPU) لضمان استقرار الأداء عند **60 إطار في الثانية (60 FPS)**.

---

## 🔍 فحص LIGHTHOUSE: الدرجة الكاملة

![Lighthouse Overview](public/lighthouse.png)

![Detailed Metrics](public/metrics.png)

| مؤشر الأداء الأساسي (Web Vital)  | الدرجة / القيمة | الاستراتيجية الهندسية المتبعة                         |
| :------------------------------- | :-------------: | :---------------------------------------------------- |
| **الأداء العام (Performance)**   |     🟢 100      | التحميل المسبق، ضغط الملفات، استخدام صيغ WebP         |
| **سرعة عرض المحتوى (LCP)**       |  ⚡ 0.5 ثانية   | التحميل المسبق لصورة الـ Hero واستضافة الخطوط محلياً  |
| **وقت الحظر الكلي (TBT)**        | ⏱️ 0 ملي ثانية  | تنفيذ أكواد JS بكفاءة وتقسيم الملفات عبر Vite         |
| **تغيير التصميم التراكمي (CLS)** |      📐 0       | تحديد أبعاد واضحة للصور واستخدام `font-display: swap` |
| **سهولة الوصول ومحركات البحث**   |     🟢 100      | استخدام ARIA Roles، و HTML الدلالي، والـ Meta Tags    |

---

## 👨‍💻 المطور: أحمد ياسر

> "الهندسة الحقيقية ليست مجرد جعل الكود يعمل؛ بل جعله مثالياً."

أنا **مطور واجهات أمامية عمري 15 عاماً**، ولدي شغف لا ينتهي بتحسين الأداء.

- **الالتزام اليومي**: أكرس **8 إلى 10 ساعات يومياً** للتعلم والبرمجة بتركيز عميق.
- **معرض الأعمال**: قمت بتسليم **أكثر من 15 مشروعاً عالى الأداء** خلال 2 أشهر فقط.
- **الهدف**: احتراف هندسة معالجة المتصفح (Browser Rendering Engine) لبناء الجيل القادم من تطبيقات الويب.

![Full Preview](public/preview.png)

---

### 📞 تواصل معي

<div align="center">

|                                                                            LinkedIn                                                                             |                        GitHub                         |                       Email                       |      WhatsApp      |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------: | :-----------------------------------------------: | :----------------: |
| [![LinkedIn](https://img.shields.io/badge/Ahmed_Yasser-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayr-uio-954897370/) | [Ahmed-let-front](https://github.com/Ahmed-let-front) | [letcosdgp@gmail.com](mailto:letcosdgp@gmail.com) | `+20 105 011 9571` |

</div>

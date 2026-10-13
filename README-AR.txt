همّة (Himma) - بومودورو للمذاكرة

اختار طريقة من الاتنين:

[أ] من غير ما تنزّل أي حاجة على جهازك (الأسهل)
1) اعمل حساب مجاني على github.com وأنشئ Repository جديد (Private عادي).
2) ارفع محتويات الفولدر ده كله (بما فيه فولدر .github).
3) افتح تبويب Actions > build > Run workflow.
4) استنى حوالي 10 دقايق، وحمّل Himma-Windows من آخر صفحة. فيه himma.exe وملف تثبيت.

[ب] على جهازك
1) نزّل Node.js و Rust (rustup) و Visual Studio Build Tools (Desktop development with C++).
2) افتح PowerShell داخل الفولدر وشغّل:
   npm install
   npm run tauri build
3) الناتج: src-tauri\target\release\himma.exe

صوت الأذان: حط ملف adhan.mp3 جوّه فولدر dist قبل البناء.
للتجربة السريعة من غير بناء: افتح dist\index.html في Edge.

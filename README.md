<p dir="rtl">**المتطلبات:**</p>

<p dir="rtl"> 1. جهاز كمبيوتر شخصي يعمل بنظام التشغيل Linux</p>
<p dir="rtl">2. تحميل الملفات أداة sync3flash
وملف MLO وملف QNX-IFS-REFORMAT من الحزمة REFORMAT 
</p>

<p dir="rtl">  </p>

[REFORMAT_MOD.zip](https://github.com/user-attachments/files/16947866/REFORMAT.MOD.zip) 

<p dir="rtl">3. كيبل ميني يو اس بي mini usb </p>


![IMG_2781](https://github.com/user-attachments/assets/599dc04d-856f-4b08-83f3-ef539d94d8de)

<p dir="rtl"> **هذا كل ما نحتاجه لتحديث Sync 3. ولنبدأ:** </p>

<p dir="rtl">
لابد من تفكيك جهاز Sync 3 للوصول إلى اللوحة الرئيسية باستخدام Omap SoC.
 قم بتشغيل الكمبيوتر مباشرة عبر كابل USB. ( لا تحاول الاتصال عبر لوحة الاتصال Sync 3 USB. لن ينجح هذا ) ابدأ في توفير المزامنة عن طريق إرسال حزم CAN.
</p>

<p dir="rtl">نفتح موجة الاوامر من داخل المجلد الموجود به الملفات الثلاثة</p>

 <p dir="rtl">

![IMG_2986](https://github.com/user-attachments/assets/6dad34fe-f795-4fa4-a0bd-3dd7e9349213)

 </p>

<p dir="rtl"> نمنح اداة sync3flash الصلاحيات عن طريق الأمر </p>

`chmod +rwx sync3flash `

 <p dir="rtl">
تشغيل اداة  sync3flash عن طريق الأمر
 </p>

`sudo ./sync3flash -i QNX-IFS-REFORMAT -m MLO`

<p dir="rtl">

![IMG_2987](https://github.com/user-attachments/assets/bc0b788e-9887-4169-8902-7f7a8443942e)

 </p>

<p dir="rtl">
ملامسة الدائرة باللون الأحمر وفي الصورتين وهنا يوجد نسختين من اللوحة الالكترونية</p>
<p dir="rtl"> هذا اصدار</p>
 
![IMG_2755](https://github.com/user-attachments/assets/73635efe-b57c-4ed1-9644-6037929ac24d)

<p dir="rtl"> وهذا اصدار الاخر</p>

![IMG_2783](https://github.com/user-attachments/assets/0307490b-c557-42ec-a759-9a9130b7b553) 

<p dir="rtl">اللوحة الخاصة بي الاصدار الاول لاحظ التوصيل هكذا ومباشرة وصل كيبل الطاقة سترى الاستجابه على موجة الاوامر على جهاز الكمبيوتر</p>

![IMG_2784](https://github.com/user-attachments/assets/cfdec8fd-cd83-4f39-95a9-d56eb22fbd64) 

<p dir="rtl">ملامسه النقطتين ثم توصيل مصدر الطاقة 12 فولت على للوحة الالكترونية .</p>

![IMG_2755](https://github.com/user-attachments/assets/735c1466-de95-4bcd-a12f-be298ac5a305)

<p dir="rtl"> إذا سارت كل شيء بشكل الصحيح فسترى بعض الاوامر على شاشة الكمبيوتر! </p>

![IMG_2753](https://github.com/user-attachments/assets/56cdc9f7-a68d-4b40-9fba-a38e8b1354f1)

<p dir="rtl"> الان لاحظ هذه الصورة على شاشة sync 3 اي انها جاهزة لاستقبال التحديث</p>

![IMG_2749](https://github.com/user-attachments/assets/a3273e6c-9cfb-48ce-a44e-9fc921da5faa)

<p dir="rtl"> قم بتوصيل mini usb الخاص sync3 </p>

![IMG_2754](https://github.com/user-attachments/assets/37ba2573-83f2-47bc-b1e4-527fb9145d66)

<p dir="rtl"> واشبك الفلاش usb بعد تحميل التحديث الذي تريد
على سبيل المثال sync3 4.3.23188 </p>

![IMG_2772](https://github.com/user-attachments/assets/6fcbddaf-4a89-459c-87f3-0e59fb6e4073)


<p dir="rtl">الان استجابة الشاشة لتحديث وانظر بقية الصور 
 هنا يتم إعادة تقسيم eMMC. </p>

![IMG_2750](https://github.com/user-attachments/assets/398e1f8b-bc3e-4caf-bd18-2c93e3e8d17d)

![IMG_2759](https://github.com/user-attachments/assets/3ae93936-91c8-423e-999f-9d4296ff703f)
![IMG_2760](https://github.com/user-attachments/assets/13bd48db-7446-4258-9dcd-f77c771777dc)
![IMG_2762](https://github.com/user-attachments/assets/43acbaa2-fad5-4b05-aa20-e905de1570b0)
![IMG_2763](https://github.com/user-attachments/assets/70bf8255-951f-432d-8e0f-57a67cf014d5)
![IMG_2765](https://github.com/user-attachments/assets/997a0e2e-43b6-46bd-b529-5448e8d1fc90)
![IMG_2768](https://github.com/user-attachments/assets/99924c3a-c8f4-4f51-8b29-946b9f4fd550)

انتهى التحديث افصل الفلاش usb وسيعاد تشغيل الشاشة 
![IMG_2769](https://github.com/user-attachments/assets/ce6d324a-015c-46b2-8b37-760d6efe7bbc)

<p dir="rtl"> تم تركيب sync 3 وجاهزة لتطبيقها في السيارة </p>

![IMG_2780](https://github.com/user-attachments/assets/d1999d74-7d6d-4b74-9304-d41fbb43d7f8)

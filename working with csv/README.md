در این پروژه شما باید برنامه ایی بنویسید که نمرات افراد مختلف را از یک فایل csv بخواند ومحاسبات زیر را روی نمرات انجام داده و مقادیر حاصل را در یک فایل ذخیره کند

در این پروژه شما ۵ task مختلف را باید پیاده سازی کنید. نمونه ی فایل source.py که باید برای سابمیت باید استفاده کنید در پایین صفحه وجود دارد (گزینه دانلود فایل) برای دانلود فایل روی این گزینه کلیک کنید.

 

به هیچ وجه اسم تابع ها را عوض نکنید و همه‌ی کدهایی که می خواهید بزنید را در همان def  ها پیاده‌سازی کنید (خارج از def ها کدی نگذارید فقط به جز import کردن کتابخانه ها که همان ابتدای فایل قرار دهید)(برای میانگین گرفتن فقط از متد mean استفاده کنید (این متد از کتابخانه‌ی statistics در فایل زیر import شده است. )) (هیچ کدام از مقدار ها رند نشوند ) (تمام کتابخانه هایی که قصد import کردنشان را دارید فقط یکبار در ابتدای فایل و خارج از def ها قرار دهید و در def ها import نکنید) و به ازای هر task تابع مربوطه را کامل کنید و سپس این فایل را حتما با نام  (source.py) و حتما به صورت zip دربیاورید (rar نباشد فقط zip ) و ارسال کنید. 

در صورت رعایت نکردن هر کدام از نکات بالا متاسفانه  نمره شما توسط سیستم صفر خواهد شد .

نکته: سیستم داوری آنلاین از پایتون 3.4 استفاده می کند، در این نسخه دیکشنری ها ترتیب ورود اطلاعات به خود را به یاد نمی آورند و ممکن است در صورت مرتب سازی آنها به نتیجه مطلوب نرسید، برای رفع این مشکل به جای dict از OrderedDict استفاده کنید، این ساختار داده را می توانید از کتابخانه collections در برنامه وارد کنید.

 

1-معدل هر فرد را محاسبه کند و همراه با نام هر فرد ذخیره کند، ترتیب خروجی اسامی باید دقیقا مساوی ترتیب فایل ورودی باشد. 

2-معدل ها را به ترتیب صعودی همراه با نام هر فرد ذخیره کند. لطفا توجه کنید اگر از dict استفاده می کنید ترتیب معدل ها در آن مشخص نیست برای اطلاعات بیشتر به این لینک مراجعه کنید. https://docs.python.org/3.6/tutorial/datastructures.html#dictionaries

۳-سه معدل برتر را با نام هر فرد ذخیره کند.

۴-سه معدل پایین را بدون نام هر فرد ذخیره کند.

5-میانگین معدل ها را محاسبه و ذخیره کند.

نمونه محتوای یک فایل csv

mandana,5,7,3,15
hamid,3,9,4,20,9,1,8,16,0,5,2,4,7,2,1
sina,19,10,19,6,8,14,3
sara,0,5,20,14
soheila,13,2,5,1,3,10,12,4,13,17,7,7
ali,1,9
sarvin,0,16,16,13,19,2,17,8
 

خروجی تسک اول

mandana,7.5
hamid,6.066666666666666
sina,11.285714285714286
sara,9.75
soheila,7.833333333333333
ali,5.0
sarvin,11.375
 

خروجی تسک دوم

ali,5.0
hamid,6.066666666666666
mandana,7.5
soheila,7.833333333333333
sara,9.75
sina,11.285714285714286
sarvin,11.375
 

خروجی تسک سوم

sarvin,11.375
sina,11.285714285714286
sara,9.75
 

خروجی تسک چهارم

5.0
6.066666666666666
7.5
 

خروجی تسک پنجم

8.401530612244898
 

نکته: به این نکته توجه کنید در هر مرحله اگر معدل چند نفر یکسان بود، ترتیب خروجی باید بر اساس حروف الفبا باشد به طور مثال:

hossein 16.5
mona 16.5
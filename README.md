# tabdila.pp
tabdil app [short tags] documentation

# 🍭بخش time

## تقویم
`[tabdil تقویم]`

تقویم کامل شمسی و قمری و میلادی

همراه با توضیحات مناسبت های هر ماه

آژاکس برای ماه قبل و ماه بعد و بازگشت به روز جاری




## امروز
`[tabdil امروز]`

ساعت جاری

تاریخ امروز با معادل شمسی و میلادی و قمری

مناسبت روز جاری



## فردا
`[tabdil فردا]`

تاریخ فردا با معادل شمسی و میلادی و قمری

مناسبت ها



## تبدیل
`[tabdil تبدیل]`

تبدیل تاریخ های شمسی، میلادی و قمری به یکدیگر




`[tabdil تبدیل gh-m]`
`[tabdil تبدیل gh-sh]`
`[tabdil تبدیل sh-m]`
`[tabdil تبدیل sh-gh]`
`[tabdil تبدیل m-sh]`
`[tabdil تبدیل m-gh]`

تبدیل با نوع تقویم مبدا و مقصد مشخص شده



## سن
`[tabdil سن]`

محاسبه سن شخص بر اساس تقویم های شمسی، میلادی و قمری




## تفاوت
`[tabdil تفاوت]`

محاسبه تفاوت دو تاریخ بر اساس تقویم های شمسی، میلادی و قمری




## اضافه
`[tabdil اضافه]`

محاسبه نتیجه ی کم/اضافه کردن تعداد مشخصی روز/هفته/ماه/سال به تقویم شمسی، میلادی و قمری




## کرنومتر
`[tabdil کرنومتر]`



## آلارم
`[tabdil آلارم]`



## تایمر
`[tabdil تایمر]`



## اوقات

`[tabdil اوقات]`

فرم انتخاب استان و شهر

آژاکس برای نمایش اوقات شهر انتخاب شده

ذخیره کوکی شهر انتخابی برای بازدیدهای بعدی


`[tabdil اوقات 11]`

نمایش اوقات شرعی یک استان خاص

مرکز استان پیش فرض خواهد بود

امکان انتخاب سایر شهرهای استان

[لیست شناسه استان ها](https://fa.wikipedia.org/wiki/%D8%A7%D8%B3%D8%AA%D8%A7%D9%86%E2%80%8C%D9%87%D8%A7%DB%8C_%D8%A7%DB%8C%D8%B1%D8%A7%D9%86)





## month

نمایش تقویم برای یک ماه شمسی انتخابی

`[tabdil month 1]`

نتیجه ماه فروردین سال جاری خواهد بود، **یک ماه** که از فروردین گذشت (پایان اردیبهشت)، خروجی فروردین سال بعدی خواهد بود.




## day

نمایش توضیحات یک روز خاص بر اساس ماه-روز شمسی

`[tabdil day 1-13]`

نتیجه روز 13بدر سال جاری خواهد بود، **بعد از دو ماه** از این مناسبت، 13بدر سال بعدی خواهد بود.


`[tabdil day 1-13 title]`

خروجی، شماره سال شمسی، برای استفاده در title صفحه است.




## until

`[tabdil until 2023-1-20]`

نمایش معادل شمسی، میلادی و قمری تاریخ معین میلادی

نمایش ثانیه شمار برای تاریخ انتخابی


`[tabdil until 2023-1-20 15:15:15]`

امکان تعیین زمان دقیقِ مقصد با ساعت و ثانیه


**ثانیه شمار** پیش از مناسبت، **زمان باقیمانده**، و پس از مناسبت، **زمان گذشته** از آن را نمایش می دهد.

`[tabdil until 2023-1-20 yaldaa]`

برای تعیین عنوان مناسبت

.
.
.
# 🍭بخش واحد ها conversion

`[tabdil وزن]`

برای نمایش فقط عنوان

`[tabdil وزن title]`

تعیین محدودیت برای واحدهای قابل تبدیل

`[tabdil وزن kilogram gram pound carat ounce ton mesghal charak sir soot]`






`[tabdil طول]`

`[tabdil حجم]`

`[tabdil دما]`

`[tabdil مساحت]`

`[tabdil فشار]`

`[tabdil سرعت]`

`[tabdil نیرو]`

`[tabdil زمان]`

`[tabdil گشتاور]`

`[tabdil انرژی]`

`[tabdil فرکانس]`

`[tabdil توان]`

`[tabdil شتاب]`

`[tabdil انتقال-داده]`

`[tabdil ذخیره-دیجیتال]`

`[tabdil زاویه]`

`[tabdil چگالی]`

`[tabdil جریان-جرمی]`

`[tabdil جریان-حجمی]`

`[tabdil جریان-الکتریکی]`

`[tabdil ضریب-انتقال-حرارت]`

.
.
.
# 🍭بخش technology

## آی پی من
`[tabdil ip]`

مشخصات آی پی، موقعیت، مرورگر و سیستم عامل کاربر


## رمز عبور تصادقی
`[tabdil password]`

ایجاد پسورد تصادفی امن


## تبدیل timestamp
`[tabdil timestamp]`

تبدیل تایم استمپ به تاریخ شمسی و میلادی

تبدیل تاریخ شمسی به تایم استمپ

تبدیل تاریخ میلادی به تایم استمپ


## تبدیل متن به کد باینری و برعکس
`[tabdil binary]`


تبدیل آنلاین کد باینری به متن فارسی ، انگلیسی و برعکس



## ساخت کد Hash با الگوریتم های MD5, SHA1, SHA256, SHA512 و..
`[tabdil hash]`


ایجاد کد هش برای متن دلخواه، با تمام الگوریتم های هش موجود روی سرور

.
.
.
# 🍭بخش بارکد و QR

## بارکد خطی و ستونی

`[tabdil barcode]`

فرم ایجاد بارکد خطی و ستونی



## کیو آر کد QRCode
`[tabdil qrcode]`

فرم ایجاد کیوآر کد

.
.
.

# 🍭بخش ریاضی


## میانگین اعداد

`[tabdil average]`

فرم محاسبه ی میانگین اعداد



## معادله درجه اول


`[tabdil equation]`

فرم حل معادله درجه1


## معادله درجه دوم

`[tabdil equation2]`

فرم محاسبه دلتا و ریشه های معادله درجه2




## فاکتورهای یک عدد

`[tabdil factors]`

فرم محاسبه فاکتورها (عامل ها) برای یک عدد + بررسی عدد اول





## توان یک عدد
`[tabdil exponent]`


فرم محاسبه یک مجهول در معادله توان یک عدد




## جذر یک عدد

`[tabdil square]`

فرم محاسبه جذر در معادله جذر یک عدد




## لگاریتم در مبنای دلخوای

`[tabdil log]`

فرم محاسبه لگاریتم در مبنای دلخواه



##  تشخیص عدد اول

`[tabdil prime]`

فرم بررسی و تشخیص عدد اول + مقسوم علیه های عدد (مشابه فاکتورهای عدد)



##  محاسبه نسبت طلایی

`[tabdil goldenratio]`

فرم محاسبه نسبت طلایی با دو مجهول



##  مساحت، محیط و قطر مستطیل 

`[tabdil rectangle]`

محاسبه مقدار مساحت و محیط و قطر یک مستطیل



## مساحت، محیط و قطر مربع

`[tabdil squareshape]`


محاسبه مقدار مساحت، محیط و قطر یک مربع


.
.
.

# 🍭بخش سلامت


## محاسبه BMI شاخص توده بدنی

`[tabdil BMI]`

فرم محاسبه شاخص BMI




## محاسبه کالری مورد نیاز روزانه بدن BMR

`[tabdil BMR]`

فرم محاسبه شاخص BMR با 3 فرمول متفاوت

[توضیحات فرمول های BMR](https://en.wikipedia.org/wiki/Basal_metabolic_rate)




## محاسبه مساحت سطح بدن BSA

`[tabdil BSA]`

فرم محاسبه مساحت بدن به مترمربع با 9 فرمول متفاوت





## محاسبه وزن ایده آل 

`[tabdil idealweight]`

فرم محاسبه وزن ایده آل برای مرد و زن با 4 فرمول





.
.
.


# 🍭بخش زنان


## محاسبه طول دوره قاعدگی

`[tabdil menstrualcycle]`

فرم محاسبه طول دوره قاعدگی براساس طول سه دوره آخر




## محاسبه سن بارداری و سن جنین

`[tabdil pregnancy]`

فرم محاسبه سن بارداری و سن جنین





## محاسبه تاریخ زایمان

`[tabdil childbirth]`

فرم محاسبه تاریخ زایمان



.
.
.


# 🍭بخش متن


##  تبدیل حروف متن انگلیسی به حروف بزرگ، کوچک 

`[tabdil convertcase]`

فرم  تبدیل حروف متن انگلیسی به حروف بزرگ، کوچک  در 7 حالت با کپی و دانلود




## ایجاد متن طرح‌نما یا لورم ایپسوم

`[tabdil loremipsum]`

فرم ایجاد متن طرح‌نما یا لورم ایپسوم





## شمارنده کلمات متن

`[tabdil wordcounter]`

فرم شمارنده تعداد کاراکتر، کلمه، جلمه، پاراگراف در متن، با زمان تقریبی خواندن/نوشتن


.
.
.


# 🍭بخش آزمون ها

## آزمون افسردگی بک

`[tabdil beckdepression]`

فرم آزمون افسردگی بک با 21 سوال


## تست خوشبختی

`[tabdil happiness]`

فرم تست میزان خوشبختی با 12 سوال


## تست اعتماد به نفس

`[tabdil selfconfidence]`

فرم آزمون اعتماد به نفس با 32 سوال


.
.
.



# 🍭بخش اعداد


## محاسبه درصد

`[tabdil percentage]`

فرم محاسبه درصد یک عدد



## محاسبه درصد افزایش

`[tabdil percentup]`

فرم محاسبه درصد افزایش یک عدد / مقدار افزایش



## محاسبه درصد کاهش

`[tabdil percentdown]`

فرم محاسبه درصد کاهش یک عدد / مقدار کاهش



## محاسبه تغییر درصد

`[tabdil percentchange]`

فرم محاسبه تغییر درصد دو عدد



## محاسبه درصد خطا

`[tabdil percenterror]`

فرم محاسبه درصد خطا نسبت به عدد مشاهده شده



## تولید اعداد تصادفی

`[tabdil random]`

فرم تولید اعداد تصادفی تکراری / غیرتکراری



## تبدیل اعداد انگلیسی به فارسی و برعکس

`[tabdil numfaen]`

فرم  تبدیل اعداد انگلیسی به فارسی و برعکس 



## تبدیل عدد به حروف

`[tabdil numtoword]`

فرم تبدیل عدد به حروف، تبدیل رقم به حرف



## تبدیل مبنای عدد

`[tabdil baseconvert]`

فرم تبدیل مبنای عدد بین مبنای 2 الی 36


.
.
.


















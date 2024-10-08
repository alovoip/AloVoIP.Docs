
# نحوه طراحی مسیرها و استراتژِی تماس

در این بخش به موضوعات زیر می‌پردازیم:

•	[هدف از نحوه طراحی مسیرها و استراتژی تماس ](#ThePurposeOfHowToDesignRoutesAndContactStrategy)

•	[پیاده سازی یک سناریو ](#ImplementationOfAScenario)

## هدف از نحوه طراحی مسیرها و استراتژی تماس{#ThePurposeOfHowToDesignRoutesAndContactStrategy}

سناریو تماس یک امکان اساسی و کاربردی برای مدیریت، هدایت منطقی و کنترل تماس ها در مرکزتماس می‌باشد و به شما امکان می‌دهد مسیرهای تماس را بصورت اختصاصی در سیستم تلفنی خود پیاده سازی کنید.

## پیاده سازی یک سناریو{#ImplementationOfAScenario}

فرض کنید شما در سازمان خود واحد های مختلفی دارید مانند فروش، پشتیبانی، حسابداری و.... ساعت کاری مجموعه شما از ساعت 8 صبح تا 4 بعداظهر است.قرار است هر مشتری که در این بازه تماس گرفت به منشی تلفنی وصل شود و از آنجا با زدن کلید مربوطه به بخش مورد نظر وصل شود و اگر هر بخش پاسخگو نبود یک درخواست تماس ثبت کند و خارج از این بازه ویس پایان ساعت کاری پخش شود یا به مسیر دیگری هدایت شود.

برای این کار اول باید لیست داخلی های مورد نظر در هر بخش را تهیه کنیدکه هرداخلی روی تلفن مربوطه رجیستر شود .سپس داخلی های هر بخش را در صف مربوط به خود اضافه کنید تا اگر به عنوان مثال در بخش پشتیبانی یک داخلی پاسخگو نبود به داخلی دیگری تماس وصل شود.می‌توان قبل از وصل شدن تماس به صف مربوطه، وارد باشگاه مشتریان شود و مشتری احراز هویت و قراردادش چک شود.در صورت داشتن قرارداد به صف پشتیبانی و در غیر این صورت به صف فروش وصل شود.همچنین تماس می‌تواند به کارشناس مربوطه آن سازمان متصل شود.

سناریو به صورت زیر پیاده سازی می‌شود:

•	ابتدا داخلی های هر بخش را باید مشخص کنید.

داخلی های بخش پشتیبانی:

1026 -1027-1028-1029

داخلی های بخش فروش

1031-103

داخلی های بخش حسابداری

510-511

•	اگر تعداد تماس های شما بیشتر از پاسخ دهنده ها است می‌توانید برای هر بخش صف تعریف کنید و داخلی های آن بخش را در صف مربوطه قرار دهید تا تماس گیرنده در صف انتظار قرار گرفته و به محض آزاد شدن یک داخلی به آن وصل شود.همچنین می‌توانید بعد از اتمام مکالمه تماس را به ماژول نظرسنجی هدایت کنید.و در صورت عدم پاسخگویی اعضاء صف می‌توانید تماس را به ماژول درخواست تماس هدایت کنید تا تماس گیرنده شماره خود را ثبت کند.

صف پشتیبانی

صف فروش

صف حسابداری

•	سپس صدای منشی تلفنی را باید از قبل آماده داشته باشید و براساس صدا هر عددی که در ویس گفته می‌شود به بخش مربوطه وصل ‌شود.برای مثال:
عدد 1: بخش پشتیبانی
عدد2 :بخش فروش
عدد3:بخش حسابداری
عدد0:اپراتور
داخلی اپراتور 1010 می‌باشد.

•	ساعت کاری مجموعه باید کاملا مشخص شود(روزهای کاری مجموعه و ساعت کاری)تا تماس های شما در این بازه زمانی به منشی تلفنی و در غیر این صورت به مسیر دیگری که می‌تواند شامل صدای پایان ساعت کاری و... هدایت شود.

•	صدای پایان ساعت کاری و تمام صداهای مدنظر روی ویندوز سرور آماده گذاشته شود.



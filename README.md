# ReverseTlsTunnel 
## تانل معکوس

تونل معکوس: فرقش با تونل عادی اینه که کانکشن را سرور خارج آغاز میکنه مثل یک بازدید کننده خارجی از یه سایت ایرانی که سرور شما باشه و بعد از اتصال ؛ دیتا مثل تونل عادی رد و بدل میشه ؛ این روش از تونل های عادی که سرور ایران به خارج کانکشن رو شروع میکنه از نظر دیتکت شدن؛ میشه گفت بهتره چون عموما یه سرور کانکشن به جایی شروع نمی کنه (برای مدت طولانی و تعداد کانکشن همزمان بالا!)
.
- [آموزش در کانال @IR_TECH](https://youtube.com/watch?v=1mj1fhA2X6s)
- حالت Load-balancer اضافه شد.
- در حالت مولتی پورت و به صورت سرویس اجرا میشود. 
- از پورت 23 تا 65535 میتوانید استفاده کنید. 
- پورت 1 تا 22 قابل استفاده نیستند. 
- از SNI و پسورد یکسان روی هر دو سرور جهت اتصال به یکدیگر استفاده کنید.
-  برای اپدیت 5 رو انتخاب کنید.
- فایل RTT پس از کامپایل در مسیر ReverseTlsTunnel/dist ذخیره میشود.
- -قابلیت Fake Upload برای سرور ایران اضافه شده.



## Install 

```
bash <(curl -fsSL https://raw.githubusercontent.com/Ptechgithub/ReverseTlsTunnel/main/RtTunnel.sh)
```


![1](https://raw.githubusercontent.com/Ptechgithub/configs/main/media/1.jpg)



- با تشکر از [radkesvat](https://github.com/radkesvat/ReverseTlsTunnel/tree/master)

<div dir="rtl">
 کتابخانه ی درگاه پرداخت پارسپال ( جدید ) برای فریمورک کدایگنایتر <br>
آموزش نصب و استفاده:‌
<hr>
برای استفاده از این کتابخانه کافی است فایل کتابخانه Parspal.php  این ریپوزیتوری را دانلود کنید و در مسیر application/libraries کپی کنید .
این کتابخانه در کل دو عدد تابع داره که یکی به نام request برای ارسال کاربر به صفحه ی پرداخت است و یک تابع دیگر به نام verify برای اعتبارسنجی پرداخت است . به همین سادگی !
‌<hr>
-------------- برای نصب کردن مراحل زیر را به ترتیب طی کنید -------------
‌<hr>
  <ul>
    <li> فایل Parspal.php را از این بخش دانلود کنید .</li>
    <li> فایل Parspal.php را به مسیر application/libraries کپی کنید . </li>
    <li>در کنترلری و متدی که میخواهید پرداخت پارسال انجام پذیرد کتابخانه را به این شکل صدا بزنید
    <div dir="ltr">
      `$this->load->library('parspal',$params);`
      </div>
     </li>
  </ul>

<hr>
<a href="https://avasam.ir">تهیه شده در وب سایت آموزشی آواسام </a>
</div>

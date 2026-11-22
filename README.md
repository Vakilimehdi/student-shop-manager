# سیستم مدیریت فروشگاه | Shop Management System (Student Project)

## فارسی

پروژهٔ دانشجویی آماده: یک سیستم مدیریت فروشگاه کامل در **یک فایل HTML** — بدون نیاز به نصب، بدون سرور و بدون پایگاه‌داده. فقط فایل را در مرورگر باز کنید.

> **نسخهٔ نمایشی (دمو):** فایلی که در این ریپو می‌بینید نسخهٔ دموی برنامه است — می‌توانید کالا اضافه کنید و یک فاکتور آزمایشی ثبت کنید تا ببینید به کارتان می‌آید یا نه؛ دانلود CSV در دمو غیرفعال است. نسخهٔ کامل (بدون محدودیت، بدون بنر دمو) فقط بعد از پرداخت ارسال می‌شود.

### امکانات نسخهٔ کامل

- **مدیریت کالاها:** افزودن و حذف کالا با نام، دسته، قیمت و موجودی؛ کالاهای کم‌موجودی (کمتر از ۵) با قرمز مشخص می‌شوند
- **ثبت فروش:** انتخاب مشتری و کالا، سبد خرید، کنترل موجودی (نمی‌گذارد بیشتر از موجودی بفروشید)، ثبت فاکتور با شمارهٔ خودکار
- **فاکتور و چاپ:** مشاهدهٔ هر فاکتور و چاپ آن با دکمهٔ چاپ (فقط فاکتور چاپ می‌شود)
- **گزارش‌ها:** پرفروش‌ترین کالاها با نمودار میله‌ای، جمع اقلام و تعداد فاکتورها
- **خروجی CSV:** دانلود گزارش فروش برای اکسل
- **ذخیره‌سازی:** همهٔ داده‌ها در `localStorage` مرورگر ذخیره می‌شود؛ دکمهٔ «برگرداندن داده‌های نمونه» داده‌ها را ریست می‌کند

### داده‌های نمونه

۸ کالا و ۲ فاکتور نمونه داخل برنامه هست تا بلافاصله بتوانید آن را امتحان و ارائه کنید. همهٔ نام‌ها و قیمت‌ها فرضی‌اند.

### چطور اجرا کنم؟

1. فایل `index.html` را دانلود کنید
2. با دابل‌کلیک در مرورگر بازش کنید — همین. نیازی به نصب XAMPP یا سرور نیست

### برای ارائهٔ دانشجویی

ساختار کد ساده و خواناست: داده‌ها در `SEED_PRODUCTS` و `SEED_INVOICES`، توابع `render*` برای نمایش هر بخش، و `localStorage` برای ذخیره‌سازی. برای گزارش پروژه می‌توانید این بخش‌ها را توضیح دهید: مدیریت موجودی، صدور فاکتور، گزارش‌گیری و خروجی CSV.

### قیمت و خرید

**۱۰ دلار** — نسخهٔ کامل را از فروشگاه بخرید:

https://digi-market-shop.netlify.app/

1. مبلغ دقیق را با **USDC در شبکهٔ سولانا** به این کیف پول بفرستید: `HqxvhpdWdBvjk1JvCwLdrp3fW47Zt1A8Eg1atDwZ3oQQ`
2. امضای تراکنش و کد محصول (`student-shop`) را به **mehdivakili0@gmail.com** ایمیل کنید
3. پرداخت روی بلاک‌چین بررسی می‌شود و نسخهٔ کامل معمولاً تا یک ساعت بعد، خودکار با ایمیل می‌رسد

---

## English

A ready-made student project: a complete shop management system in **a single HTML file** — no installation, no server, no database. Just open the file in a browser.

> **Demo version:** the file in this repo is the demo of the app — you can add products and record one trial invoice to see if it fits your needs; CSV download is disabled in the demo. The full version (unlimited, no demo banner) is sent only after payment.

### Full version features

- **Product management:** add and delete products with name, category, price and stock; low-stock items (under 5) are highlighted in red
- **New sale:** pick a customer and products, a shopping cart, stock control (it won't let you sell more than in stock), invoices with automatic numbering
- **Invoice & print:** view any invoice and print it with the print button (only the invoice prints)
- **Reports:** best-selling products as a bar chart, total items sold and invoice count
- **CSV export:** download the sales report for Excel
- **Storage:** all data is saved in the browser's `localStorage`; a reset button restores the sample data

### Sample data

8 sample products and 2 sample invoices are included so you can try and present it right away. All names and prices are fictional.

### How to run

1. Download `index.html`
2. Double-click to open it in a browser — that's it. No XAMPP or server needed.

### For a student presentation

The code is simple and readable: data in `SEED_PRODUCTS` and `SEED_INVOICES`, `render*` functions for each section, and `localStorage` for persistence. For your project report you can explain: inventory management, invoicing, reporting and CSV export.

### Price & purchase

**$10** — buy the full version from the store:

https://digi-market-shop.netlify.app/

1. Pay the exact price in **USDC on Solana** to: `HqxvhpdWdBvjk1JvCwLdrp3fW47Zt1A8Eg1atDwZ3oQQ`
2. Email the transaction signature and product code (`student-shop`) to **mehdivakili0@gmail.com**
3. The payment is verified on-chain and the full version is emailed to you automatically, usually within an hour

## License

MIT — see [LICENSE](LICENSE).

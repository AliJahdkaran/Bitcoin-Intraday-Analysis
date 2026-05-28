# 📊 Bitcoin Intraday Volatility & Trend Analysis (1-Min Interval)


این پروژه به تحلیل میکروساختاری بیش از ۱ میلیون ردیف دیتای فرکانس‌بالای بیت‌کوین (تایم‌فریم ۱ دقیقه‌ای) در ۳ سال اخیر می‌پردازد تا الگوهای نوسان درون‌روزی و رفتارهای حجم معاملات را کشف کند.

### 🎯 ویژگی‌های شاخص پروژه:
* **مهندسی و مدیریت حجم داده:** کاهش و نمونه‌برداری دیتای خام ۷.۵ میلیون ردیفی به ۱ میلیون ردیف با اسکریپت پایتون جهت بهینه‌سازی عملکرد سیستم.
* **داشبورد تعاملی تبلو:** پیاده‌سازی منوی آبشاری هوشمند (Hamburger Menu) کانتینری برای جابه‌جایی داینامیک بین نمودارها.
* **فرمول‌نویسی اختصاصی:** تبدیل فرمت زمان یونیکس (Unix Timestamp) به DateTime استاندارد و ساخت فیلد محاسباتی `tradable formula` برای بخش‌بندی روزهای معاملاتی پربازده.

---

### 🌍 English Version

An advanced data analytics project focusing on the microstructural behavior of Bitcoin 1-minute historical data (1M+ rows) over the last 3 years to uncover intraday trading insights and liquidity patterns.

### 🔑 Key Deliverables:
* **Data Volume & Pipeline Management:** Engineered a Python script to sample and filter the raw 7.5 million rows down to 1 million rows, optimized for high-performance BI reporting.
* **Interactive Navigation:** Developed a custom, minimal hamburger menu container in Tableau for seamless cross-chart navigation.
* **Advanced Data Transformation:** Handled data cleaning by transforming Epoch Unix timestamps into standard human-readable DateTime format and created custom trading logic (`tradable formula`) for market volatility segmentation.

### 📂 Repository Structure / ساختار مخزن
* `notebooks/`: Contains the Python script/notebook used for data sampling and volume reduction.
* `row/`: Raw and processed dataset directory.
* `tableau-workbooks/`: The packaged Tableau workbook (.twbx).

### 🔗 Live Interactive Dashboard / لینک داشبورد زنده:
👉 [**Click Here to View the Interactive Dashboard on Tableau Public**](توی_این_پرانتز_لینک_تابلو_پابلیک_خودت_رو_بذار)

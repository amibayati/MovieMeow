# MovieMeow

یک بات تلگرام برای جستجو و نمایش اطلاعات فیلم و سریال با قابلیت ترجمه فارسی!

---

## ویژگی‌ها

- جستجوی فیلم و سریال به زبان فارسی و انگلیسی
- نمایش اطلاعات کامل از جمله عنوان، ژانر، کارگردان، خلاصه داستان، امتیاز IMDb، سال انتشار و مدت زمان
- نمایش پوستر و عکس فیلم/سریال
- پیشنهاد فیلم‌ها و سریال‌های مشابه
- نمایش لیست پربیننده‌ترین و محبوب‌ترین فیلم‌ها و سریال‌های روز
- ترجمه خودکار اطلاعات به فارسی با deep-translator
- کیبورد اختصاصی برای سهولت کاربر

---

## نصب و راه‌اندازی

### پیش‌نیازها

- پایتون ۳.۷ یا جدیدتر
- نصب کتابخانه‌های مورد نیاز:
  - `pyTelegramBotAPI`
  - `requests`
  - `deep-translator`

### مراحل نصب

۱. مخزن را کلون کنید:
```bash
git clone https://github.com/amirebayati/MovieMeow.git
cd MovieMeow
```

۲. کتابخانه‌ها را نصب کنید:
```bash
pip install pyTelegramBotAPI requests deep-translator
```

۳. توکن تلگرام و API Key را در فایل `MM.py` جایگزین کنید.

۴. اجرای بات:
```bash
python MM.py
```

---

## نحوه استفاده

- با ارسال دستور `/start` به بات، کیبورد فعال می‌شود.
- دکمه‌های کیبورد:
  - جستجو 🔍: جستجو بر اساس نام فیلم یا سریال
  - فیلم‌های محبوب امروز 💥: نمایش محبوب‌ترین فیلم‌های روز
  - سریال‌های محبوب امروز 💥: نمایش محبوب‌ترین سریال‌های روز
  - بهترین فیلم‌ها: نمایش لیست برترین فیلم‌ها
  - بهترین سریال‌ها: نمایش لیست برترین سریال‌ها
- با تایپ نام فیلم یا سریال، اطلاعات کامل و فارسی آن برای شما ارسال می‌شود.

---

## API های مورد استفاده

- TMDB (The Movie Database): دریافت اطلاعات فیلم و سریال
- deep-translator: ترجمه توضیحات و اطلاعات به فارسی

---

## توسعه‌دهنده

[@amirebayati](https://github.com/amirebayati)

---

# MovieMeow (English)

A Telegram bot for searching and displaying movie and series information, with automatic Persian translation!

## Features

- Search movies and series in Persian and English
- Show full details: title, genre, director, overview, IMDb rating, release year, runtime
- Show posters/images for movies and series
- Suggest similar movies/series
- Show trending and popular movies/series of the day
- Automatic translation to Persian using deep-translator
- Custom keyboard for easy user experience

## Installation

### Prerequisites

- Python 3.7+
- Required libraries:
  - `pyTelegramBotAPI`
  - `requests`
  - `deep-translator`

### Setup

1. Clone the repository:
```bash
git clone https://github.com/amirebayati/MovieMeow.git
cd MovieMeow
```

2. Install dependencies:
```bash
pip install pyTelegramBotAPI requests deep-translator
```

3. Set your Telegram token and API Key in `MM.py`.

4. Run the bot:
```bash
python MM.py
```

## Usage

- Send `/start` to activate the custom keyboard.
- Keyboard buttons:
  - Search 🔍: Search by movie or series name
  - Popular Movies Today 💥: View today's popular movies
  - Popular Series Today 💥: View today's popular series
  - Best Movies: List of top-rated movies
  - Best Series: List of top-rated series
- Type the name of a movie or series to get its full info in Persian.

## APIs Used

- TMDB (The Movie Database) for movie/series info
- deep-translator for Persian translation



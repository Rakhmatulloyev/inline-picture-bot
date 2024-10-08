# Inline Picture Bot

Bu bot sizga kerakli rasmlarni qidirib topishda yordam beradi. Foydalanuvchi rasm qidiruvini amalga oshirishi uchun ```inline_bot``` orqali botni ishlatishi mumkin.

## Xususiyatlar
- ```inline_bot``` orqali sizga kerakli rasmni qidirsangiz, bu bot sizga kerakli rasmlarni chiqarib beradi.

## Texnologiyalar
- Python 3.7 yoki undan yuqori versiya
- aiogram kutubxonasi

## O'rnatish
1. GitHub repozitoriyasini klonlang:
    ```bash
    git clone https://github.com/Rakhmatulloyev/inline-pictere-bot.git
    cd inline-pictere-bot
    ```
2. Virtual muhit yaratib, uni faollashtiring (ixtiyoriy):
    - Linux/MacOS:
      ```bash
      python -m venv venv
      source venv/bin/activate
      ```
    - Windows:
      ```bash
      python -m venv venv
      venv\Scripts\activate
      ```
3. Zaruriy kutubxonalarni o'rnating:
    ```bash
    pip install -r requirements.txt
    ```
4. `.env` faylini yaratib, quyidagi ma'lumotlarni qo'shing:
    ```bash
    BOT_TOKEN=your-telegram-bot-token
    CHANNELS=your-channels-id
    ADMINS=your-id
    ```

## Filtrlar
- `admin.py`: Adminlar uchun maxsus funksiyalarni filtrlaydigan kodlar joylashgan.
- `check_sub_channel.py`: Foydalanuvchining kerakli kanalga obuna bo‘lganligini tekshiruvchi kodlar.

## Klaviatura tugmalari
- `admin_keyboard.py`: Bot interfeysida adminlar uchun klaviatura tugmalari sozlanadi.

## Menyu buyruqlari
- `set_bot_commands.py`: Telegram bot menyusidagi buyruqlarni o'rnatish uchun skript.

## Ishga tushurish
Botni quyidagi buyruq orqali ishga tushiring:
```bash
python bot.py

# V2Ray کانفیگ مدیر 🚀

سایت GitHub Pages برای مدیریت و اشتراک‌گذاری کانفیگ‌های V2Ray

## 📌 ویژگی‌ها

✅ **کانفیگ‌های آماده**
- VLESS (پیشنهادی)
- VMess
- Trojan
- JSON Config

✅ **ابزارهای مفید**
- کپی کانفیگ با یک کلیک
- تولید UUID
- دانلود کانفیگ

✅ **رابط کاربری فارسی**
- طراحی ریسپانسیو
- دسترسی از تمام دستگاه‌ها
- تم نوری و تاریک

## 🌐 دسترسی آنلاین

https://amirhazbavi.github.io/v2ray-config

## 📋 استفاده از کانفیگ‌ها

### 1. VLESS
```
vless://[UUID]@[SERVER]:443?encryption=none&security=tls&sni=[DOMAIN]&type=ws&host=[DOMAIN]&path=/v2ray
```

### 2. VMess
```
vmess://[BASE64_ENCODED_CONFIG]
```

### 3. Trojan
```
trojan://[PASSWORD]@[SERVER]:443?security=tls&sni=[DOMAIN]&type=ws&host=[DOMAIN]&path=/trojan
```

## ⚙️ راهنمای تنظیم

### مراحل:

1. **جای‌نشان‌گرها را جایگزین کنید:**
   - `[UUID]` → UUID خود
   - `[SERVER]` → آدرس سرور
   - `[DOMAIN]` → دومین سرور
   - `[PASSWORD]` → رمز عبور

2. **کانفیگ را کپی کنید**

3. **در کلاینت V2Ray کپی کنید**

4. **اتصال برقرار کنید**

## 🔐 اطلاعات امنیتی

⚠️ **نکات مهم:**
- هرگز UUID و رمزهای خود را اشتراک‌گذاری نکنید
- فقط از سرورهای معتبر استفاده کنید
- از TLS برای انتقال ایمن استفاده کنید
- این کانفیگ‌ها فقط برای مقاصد آموزشی است

## 📚 منابع مفید

- [V2Ray Official](https://www.v2fly.org/)
- [V2Ray Documentation](https://www.v2fly.org/config/overview.html)
- [VLESS Protocol](https://www.v2fly.org/config/protocols/vless.html)

## 🛠️ پشتیبانی

برای مشکلات و پیشنهادات:
- GitHub Issues: [Issues](https://github.com/amirhazbavi/v2ray-config/issues)
- بررسی مستندات رسمی V2Ray

## 📄 لایسنس

MIT License - برای جزئیات بیشتر فایل LICENSE را بخوانید

---

**⚠️ سلب مسئولیت:** این پروژه برای مقاصد آموزشی است. استفاده از V2Ray باید با رعایت قوانین محلی انجام شود.
# نقل المشروع إلى ريبو جديد | Move to New Repository

مشروع نوره جاهز للرفع على ريبو منفصل: **portfolio-norah**

---

## الخطوة 1 — إنشاء الريبو على GitHub

1. افتحي: https://github.com/new
2. **Repository name:** `portfolio-norah`
3. **Public**
4. **لا** تضيفي README أو .gitignore (الريبو يكون فاضي)
5. اضغطي **Create repository**

---

## الخطوة 2 — رفع الكود

من جهازك أو من Cloud Agent، نفّذي:

```bash
git remote add portfolio-norah https://github.com/Saja12344/portfolio-norah.git
git push portfolio-norah cursor/portfolio-norah-repo-5748:main
```

أو إذا كنتِ على فرع `main`:

```bash
git push portfolio-norah main:main
```

---

## الخطوة 3 — تفعيل الموقع

راجع ملف `ENABLE_PAGES.md`

الرابط النهائي:
**https://saja12344.github.io/portfolio-norah/**

---

## ملاحظة

- ريبو **Awthiqni** يبقى كما هو (مشروع منفصل)
- ريبو **portfolio-norah** مخصص لبورتفوليو نوره فقط
- كل الصور والملفات موجودة داخل الريبو (مسارات محلية)

# Barbershop Management System

ASP.NET Core MVC (.NET 10) + Entity Framework Core + SQL Server — نظام بسيط لإدارة محل حلاقة رجالي.

## التشغيل
1. افتح `BarbershopManagementSystem.slnx` في Visual Studio.
2. عدّل `Server=` في `appsettings.json` لاسم السيرفر عندك (SSMS > Server name).
3. Tools > NuGet Package Manager > Package Manager Console:
   - `Add-Migration InitialCreate`
   - `Update-Database`
4. اضغط F5.

## الوظائف
لوحة تحكم، العملاء (بحث/إضافة/تعديل/حذف)، الخدمات، الحجوزات (إنشاء/تعديل/إلغاء/إتمام)، المدفوعات، والحسابات بفترة زمنية.

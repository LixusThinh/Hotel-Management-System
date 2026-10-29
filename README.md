# Hotel Management System

Desktop app for hotel staff, built with C# WinForms (.NET Framework 4.8) and Guna UI2. Team project (team 3TL).

**Status: early stage.** Staff login, the main dashboard and the *Add room* screen (room number, room type, bed type, price) are implemented. The other dashboard buttons (customer registration, customer details, payment, staff) are not wired up yet.

## Running

1. Open `ChuongTrinhQuanLyKhachSan.sln` in Visual Studio and restore NuGet packages.
2. Create a SQL Server database named `QuanLyKhachSan`.
3. Update the connection string in `ChuongTrinhQuanLyKhachSan/fuction.cs` (it currently points to the original developer's machine, `DESKTOP-4KJH1F5\SQLEXPRESS`).
4. Build and run.

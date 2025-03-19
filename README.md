# **.NET Standard Versions Overview**

## **Table of Contents**
1. [Introduction](#introduction)
2. [.NET Standard Version Breakdown](#net-standard-version-breakdown)
3. [.NET Standard 1.0 (2016)](#net-standard-10-2016)
4. [.NET Standard 1.1 (2016)](#net-standard-11-2016)
5. [.NET Standard 1.2 (2016)](#net-standard-12-2016)
6. [.NET Standard 1.3 (2016)](#net-standard-13-2016)
7. [.NET Standard 1.4 (2016)](#net-standard-14-2016)
8. [.NET Standard 1.5 (2016)](#net-standard-15-2016)
9. [.NET Standard 1.6 (2016)](#net-standard-16-2016)
10. [.NET Standard 2.0 (2017)](#net-standard-20-2017)
11. [.NET Standard 2.1 (2019)](#net-standard-21-2019)
12. [Comparative Table](#comparative-table)
13. [Final Thoughts](#final-thoughts)

---

## **Introduction**
.NET Standard defines a **unified API layer** for multiple .NET implementations, ensuring compatibility between **.NET Framework, .NET Core, Xamarin, and Mono**. Each new version adds **more APIs**, improving **cross-platform development**.

---

## **.NET Standard Version Breakdown**
Each **version of .NET Standard** added more **APIs and features**, increasing compatibility across platforms. Below is a breakdown of all versions released.

---

## **.NET Standard 1.0 (2016)**
- **APIs:** ~7,900
- **Key Features:** Minimum API set for all .NET platforms
- **Compatibility:** .NET Framework 4.5, .NET Core 1.0, Xamarin
- **Limitations:** Lacks reflection, threading, and networking

---

## **.NET Standard 1.1 (2016)**
- **APIs:** ~9,400
- **Added Features:** `System.Xml.ReaderWriter`, `System.Diagnostics.TraceSource`
- **Compatibility:** .NET Framework 4.5.1+, .NET Core 1.0
- **Limitations:** Still lacks full threading and reflection

---

## **.NET Standard 1.2 (2016)**
- **APIs:** ~10,300
- **Added Features:** `System.IO`, `System.Linq.Expressions`, `System.Threading.Thread`
- **Compatibility:** .NET Framework 4.5.2+, .NET Core 1.0, UWP
- **Limitations:** No full reflection support

---

## **.NET Standard 1.3 (2016)**
- **APIs:** ~13,300
- **Added Features:** `System.Net.Http`, `System.Reflection`, `System.IO.FileSystem`
- **Compatibility:** .NET Framework 4.6+, .NET Core 1.0, Xamarin
- **Limitations:** No full reflection support

---

## **.NET Standard 1.4 (2016)**
- **APIs:** ~13,900
- **Added Features:** `System.Linq.Queryable`, `System.Net.Sockets`, `System.Diagnostics.StackTrace`
- **Compatibility:** .NET Framework 4.6.1+, .NET Core 1.0, UWP
- **Limitations:** Lacks serialization features

---

## **.NET Standard 1.5 (2016)**
- **APIs:** ~18,300
- **Added Features:** `System.Runtime.Loader`, `System.Diagnostics.Process`, `System.Reflection.Emit`
- **Compatibility:** .NET Framework 4.6.2+, .NET Core 1.0, UWP
- **Limitations:** Limited Reflection.Emit support

---

## **.NET Standard 1.6 (2016)**
- **APIs:** ~24,300
- **Added Features:** `System.AppContext`, `System.Linq.Parallel`, `System.Security.Cryptography`
- **Compatibility:** .NET Framework 4.6.2+, .NET Core 1.0, Xamarin
- **Limitations:** No WPF/WinForms support

---

## **.NET Standard 2.0 (2017)**
- **APIs:** ~32,000
- **Added Features:** `System.Data`, `System.Drawing`, `System.IO.Ports`, `System.Runtime.Serialization`
- **Compatibility:** .NET Framework 4.6.1+, .NET Core 2.0+, Xamarin
- **Limitations:** Limited COM interop

---

## **.NET Standard 2.1 (2019)**
- **APIs:** ~37,000
- **Added Features:** `Span<T>`, `System.IO.Pipelines`, `System.Threading.Channels`, `System.Memory<T>`
- **Compatibility:** .NET Core 3.0+, Xamarin.iOS 12.16+, Xamarin.Android 10.0+
- **Limitations:** No support for .NET Framework

---

## **Comparative Table**
| Version | Release Year | APIs Count | Key Features | .NET Framework Compatibility |
|---------|-------------|------------|--------------|-----------------------------|
| **1.0** | 2016 | ~7,900 | Minimal API set | ✅ 4.5 |
| **1.6** | 2016 | ~24,300 | Cryptography, Parallel LINQ | ✅ 4.6.2 |
| **2.0** | 2017 | ~32,000 | WCF, Serialization, `System.Data` | ✅ 4.6.1 |
| **2.1** | 2019 | ~37,000 | `Span<T>`, Pipelines, Async APIs | ❌ No support |

---

## **Final Thoughts**
✔ **.NET Standard 2.0 is the most widely used** version due to broad compatibility.  
✔ **.NET Standard 2.1 provides performance improvements**, but **drops .NET Framework support**.  
✔ **New projects should use .NET 5+ instead of .NET Standard** for future-proofing.  

Would you like a **step-by-step migration guide from .NET Standard to .NET 6+?** 🚀

<a href="https://buymeacoffee.com/abdullaherturk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-Batch_&_PowerShell-blue?style=for-the-badge)

![sample](https://github.com/abdullah-erturk/Trusted-Installer-Launcher/blob/main/preview.jpg)

![sample](https://github.com/abdullah-erturk/Trusted-Installer-Launcher/blob/main/preview.gif)

## Link:

[![Stable?](https://img.shields.io/badge/Release-v1.svg?style=flat)](https://github.com/abdullah-erturk/Trusted-Installer-Launcher/archive/refs/heads/main.zip)
# Trusted Installer Launcher

**Trusted Installer Launcher**, Windows sistemlerinde en yüksek yetki seviyesi olan **TrustedInstaller** (TI) haklarıyla dosya, klasör ve programları çalıştırmanızı sağlayan güçlü bir araçtır. Hem sürükle-bırak özelliği hem de sistem entegrasyonu ile kullanım kolaylığı sunar. Bu dosya ile TrustedInstaller yetkisini herhangi bir başka uygulamaya gerek kalmadan Windows'un yerleşik kodlarıyla (cmd + powershell) kullanabilirsiniz.

---

**Trusted Installer Launcher** is a powerful tool that allows you to run files, folders, and programs with **TrustedInstaller** (TI) privileges - the highest permission level in Windows systems. It offers ease of use through both drag-and-drop functionality and system integration. This file allows you to use TrustedInstaller privileges with Windows' built-in code (cmd + powershell) without needing any other application.

---
<details>
<summary><strong>Türkçe Tanıtım</strong></summary>

### ✨ Özellikler

- 🎯 **Sürükle-Bırak Arayüzü**: Herhangi bir dosyayı script üzerine sürükleyerek TI yetkisiyle çalıştırın
- 🔧 **Sistem Entegrasyonu**: Windows sağ tık menüsüne "Trusted Installer Yetkisiyle Aç" seçeneği ekler
- 🌍 **Çok Dilli**: Türkçe ve İngilizce dil desteği (otomatik algılama)
- 📁 **Geniş Dosya Desteği**: EXE, BAT, CMD, REG, PS1, MSC, CPL ve daha fazlası
- 🛡️ **Güvenli**: Orijinal Trusted Installer mekanizmasını kullanır
- 💻 **Kullanıcı Dostu**: Grafiksel popup menüleri ile kolay kullanım

### 🎯 Ne İşe Yarar?

Windows'ta bazı sistem dosyaları, klasörler ve hizmetler Administrator yetkisiyle bile düzenlenemez. Bu dosyalar **TrustedInstaller** tarafından korunur. Bu araç:

- Sistem dosyalarını düzenlemenize olanak tanır
- Sistem hizmetlerini düzenlemenize olanak tanır
- Korumalı klasörlere erişim sağlar
- Sistem kayıt defteri (Registry) düzenlemelerini kolaylaştırır
- Administrator'den bile daha yüksek yetkilerle işlem yapmanızı sağlar

### 📦 Kurulum

1. **Script'i İndirin**: `TrustedInstaller.bat` dosyasını indirin
2. **Script'i Çalıştırın**: Dosyaya çift tıklayın
3. **Kurulum Seçin**: Açılan menüden "Hayır" (Sisteme Kur) seçeneğini seçin
4. **Onaylayın**: UAC (Kullanıcı Hesabı Denetimi) isteğini onaylayın

Kurulum tamamlandığında:
- Script `C:\Windows\ti.bat` konumuna kopyalanır
- Tüm dosya ve klasörlerin sağ tık menüsüne "Trusted Installer Yetkisiyle Aç" seçeneği eklenir

### 🚀 Kullanım Yöntemleri

#### Yöntem 1: Sürükle-Bırak
```
1. Çalıştırmak istediğiniz dosyayı seçin
2. TrustedInstaller.bat dosyası üzerine sürükleyin
3. Dosya otomatik olarak TI yetkisiyle çalışır
```

#### Yöntem 2: Sağ Tık Menüsü (Kurulum Sonrası)
```
1. Herhangi bir dosya/klasöre sağ tıklayın
2. "Trusted Installer Yetkisiyle Aç" seçeneğini seçin
3. UAC isteğini onaylayın
```

#### Yöntem 3: Manuel Başlatma
```
1. Script'e çift tıklayın
2. "Evet" seçeneğini seçin
3. CMD veya Explorer'ı TI yetkisiyle açmayı seçin
```

### 📝 Desteklenen Dosya Tipleri

| Tip | Açıklama | Örnek |
|-----|----------|-------|
| `.exe` | Çalıştırılabilir dosyalar | `notepad.exe` |
| `.bat` | Batch script'leri | `setup.bat` |
| `.cmd` | Komut dosyaları | `install.cmd` |
| `.reg` | Registry dosyaları | `tweaks.reg` |
| `.ps1` | PowerShell script'leri | `script.ps1` |
| `.msc` | MMC Snap-in'leri | `gpedit.msc` |
| `.cpl` | Kontrol Paneli | `sysdm.cpl` |

### ⚠️ Uyarılar

- **Dikkatli Kullanın**: TrustedInstaller yetkileri sistem dosyalarını değiştirebilir
- **Yedek Alın**: Önemli sistem değişikliklerinden önce yedekleme yapın
- **Güvenilir Kaynak**: Sadece güvendiğiniz dosyaları TI yetkisiyle çalıştırın
- **Sistem Bilgisi Gerekli**: Ne yaptığınızı bilmeden sistem dosyalarını değiştirmeyin

### 🗑️ Kaldırma

1. Script'i çalıştırın
2. "Hayır" (Sisteme Kur) seçeneğini seçin
3. "Zaten kurulu" mesajında "Hayır" (Kaldır) seçeneğini seçin
4. Tüm dosyalar ve registry kayıtları temizlenecektir

### 🔧 Teknik Detaylar

- **Hybrid Script**: Batch + PowerShell (minimum versiyon 2.0) kombinasyonu 
- **Platform**: Windows 7, 8, 8.1, 10, 11, Server (Server 2008 R2 ve üstü)
- **Mimari**: x86 ve x64 uyumlu
- **Yetki Sistemi**: Windows TrustedInstaller servisi tabanlı
- **Registry Konumları**: 
  - `HKCR\*\shell\RunAsTI`
  - `HKCR\Directory\shell\RunAsTI`
  - `HKCR\Directory\Background\shell\RunAsTI`

---

## Yazar
**Abdullah ERTÜRK**
* [https://github.com/abdullah-erturk](https://github.com/abdullah-erturk)
* [https://erturk.netlify.app](https://erturk.netlify.app)

---
⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!  

</details>

<details>
<summary><strong>English Introduction</strong></summary>

  ### ✨ Features

- 🎯 **Drag-and-Drop Interface**: Run any file with TI privileges by dragging it onto the script
- 🔧 **System Integration**: Adds "Open with Trusted Installer Privileges" option to Windows context menu
- 🌍 **Multi-Language**: Turkish and English language support (automatic detection)
- 📁 **Wide File Support**: EXE, BAT, CMD, REG, PS1, MSC, CPL and more
- 🛡️ **Secure**: Uses the original Trusted Installer mechanism
- 💻 **User-Friendly**: Easy to use with graphical popup menus

### 🎯 What Does It Do?

Some system files, folders and services in Windows cannot be edited even with Administrator privileges. These files are protected by **TrustedInstaller**. This tool:

- Allows you to edit system files
- Allows you to edit system services
- Provides access to protected folders
- Facilitates system registry modifications
- Enables operations with even higher privileges than Administrator

### 📦 Installation

1. **Download the Script**: Download `TrustedInstaller.bat`
2. **Run the Script**: Double-click the file
3. **Choose Install**: Select "NO" (Install to System) from the menu
4. **Confirm**: Approve the UAC (User Account Control) prompt

After installation:
- Script is copied to `C:\Windows\ti.bat`
- "Open with Trusted Installer Privileges" option is added to context menu of all files and folders

### 🚀 Usage Methods

#### Method 1: Drag-and-Drop
```
1. Select the file you want to run
2. Drag and drop onto the TrustedInstaller.bat file.
3. File runs automatically with TI privileges
```

#### Method 2: Context Menu (After Installation)
```
1. Right-click any file/folder
2. Select "Open with Trusted Installer Privileges"
3. Approve the UAC prompt
```

#### Method 3: Manual Launch
```
1. Double-click the script
2. Select "YES" option
3. Choose to open CMD or Explorer with TI privileges
```

### 📝 Supported File Types

| Type | Description | Example |
|------|-------------|---------|
| `.exe` | Executable files | `notepad.exe` |
| `.bat` | Batch scripts | `setup.bat` |
| `.cmd` | Command files | `install.cmd` |
| `.reg` | Registry files | `tweaks.reg` |
| `.ps1` | PowerShell scripts | `script.ps1` |
| `.msc` | MMC Snap-ins | `gpedit.msc` |
| `.cpl` | Control Panel | `sysdm.cpl` |

### ⚠️ Warnings

- **Use Carefully**: TrustedInstaller privileges can modify system files
- **Backup**: Make backups before important system changes
- **Trusted Source**: Only run files you trust with TI privileges
- **System Knowledge Required**: Don't modify system files without knowing what you're doing

### 🗑️ Uninstallation

1. Run the script
2. Select "NO" (Install to System)
3. In "Already installed" message, select "NO" (Uninstall)
4. All files and registry entries will be cleaned

### 🔧 Technical Details

- **Hybrid Script**: Batch + PowerShell  (minimum versiyon 2.0) combination
- **Platform**: Windows 7, 8, 8.1, 10, 11, Server (Server 2008 R2 and and above)
- **Architecture**: x86 and x64 compatible
- **Permission System**: Based on Windows TrustedInstaller service
- **Registry Locations**: 
  - `HKCR\*\shell\RunAsTI`
  - `HKCR\Directory\shell\RunAsTI`
  - `HKCR\Directory\Background\shell\RunAsTI`

---

## Author
**Abdullah ERTÜRK**
* [https://github.com/abdullah-erturk](https://github.com/abdullah-erturk)
* [https://erturk.netlify.app](https://erturk.netlify.app)

---

⭐ If you like the project, don't forget to give it a star!

</details>



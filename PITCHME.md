# PYTHON FOR REMOTE WORK
<img src="https://www.python.org/static/opengraph-icon-200x200.png" alt="Python"/>

<span style="color:gray">Eko S. Wibowo</span>
<br/>
<span style="color:gray">Hak Cipta [Pythonthusiast](http://coderdojo.id)</span>
---
Ini adalah semua materi essensial yang Anda butuhkan untuk berkarir dari rumah ke perusahaan-perusahaan luar negeri yang menggunakan Python sebagai platform IT-nya, melalui berbagai platform remote work semisal Upwork.com, RemoteOK.io dan RemotePython.com
---
## Understanding Tiered Architecture
- Understanding The Concept of Tiered Architecture |
- Introducing Four Application Platforms : CLI, Desktop, Web and Mobile |

---
## Understanding The Concept of Tiered Architecture
 
---
## Introducing Four Application Platforms : CLI, Desktop, Web and Mobile
- Bagaimana cara membedakannya? |
- Bisakah digabungkan? |
- Atau bisakah berdiri sendiri? |

---
### Command Line Interface: CLI
- Dijalankan melalui console, terminal: Bash/CMD |
- Pengguna berinteraksi dengan keyboard, atau kadang-kadang mouse |
- Aplikasi memberi output umumnya pada tampilan console secara langsung, atau melalui file LOG | 
- Lebih sering dipergunakan DevOps/Admin untuk tugas-tugas automasi yang dijalankan di terminal atau di latar belakang (daemond) |  
- Umumnya, lebih mudah dikembangkan, namun interaktivitas bisa sangat terbatas |
- Memiliki kejayaan pada jamannya, karena dahulu semua aplikasi (DOS) adalah aplikasi CLI |
- Aplikasi CLI dengan Python |
-- Contoh: scraping, monitoring resources web, dsb. |
-- Umumnya semua Package Python bisa berjalan sebagai aplikasi console, kecuali secara spesifik disebutkan hanya berjalan di web/mobile. |
-- Produk-produk commercial, hampir bisa dipastikan selalu menyediakan Python sebagai interface CLI-nya |

---
### Desktop Application
- Berjalan di atas sistem operasi yang sudah support tampilan grafis secara penuh |
- Menggunakan antar muka grafis yang menyatu dengan sistem operasi atau cross platform |
- Sangat mudah dipakai, karena pengguna berinteraksi dengan elemen-elemen grafis yang intuitif seperti tombol, text input dan lain sebagainya |
- Mudah dikembangkan karena berbagai tool sudah tersedia, berdasarkan framework yang dipakai |
- Namun, bisa terjadi vendor lock-in. Karena skill di .NET misalnya, tidak bisa mudah dipindah ke Java |
- Desktop terbatas pengguna pada tempat komputer diinstall, sehingga aplikasi bergerak ke Web |
- Aplikasi desktop dengan Python |
-- Contoh: DropBox, Blender, GIMP, dsb. |
-- Package/framework yang dipakai: PyQt, WxWidget, Kivy, TkInter, dsb |
-- Kepopuleran aplikasi Python desktop akan selamanya kalah dengan aplikasi Native | 

---
### Web Application
- Aplikasi yang menggunakan minimal tiga tiered (layer/lapisan): server, middleware dan browser |
- Secara umum dibagi kedalam frontend dan backend, python berada di posisi Backend |
- Perkembangan web dari Web 1.0 ke Web 2.0 |
- Sejak 2016, pergerakan aplikasi ke arah mobile, dikenal dengan istilah mobile first, python sebagai backend API |
- Aplikasi web dengan Python |
-- Contoh: Instagram, Pinterest, Quora, dsb |
-- Package yang dipakai: Django, Flask, Pylons/Pyramids |
- Catatan penting: Web adalah aplikasi paling rumit dari seluruh jenis aplikasi |
 
---
### Mobile Application
- Aplikasi dengan penetrasi paling besar, karena besarnya penetrasi Handheld device |
- Dua platform utama: Android dan iOS |
- Selalu disarankan mengembangkan aplikasi mobile dalam bentuk native-nya |
- Python memiliki support ke mobile, namun --menurut saya-- tidak menarik |
- Aplikasi mobile dengan Python |
-- Contoh: Game-game Kivy di Playstore, ScramPhoto (discontinued) | 
-- Package yang dipakai: Kivy, PyGame Subset for Android (pgs4a) |

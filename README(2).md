# 📖 Git Handbook / Git El Kitabı

**[English](#english) · [Türkçe](#türkçe)**

---

<a name="english"></a>
## 🇬🇧 English

A comprehensive, single-file Git handbook written in **Turkish**, progressing from absolute basics to professional workflows. No installation required — just open in a browser.

![Version](https://img.shields.io/badge/version-1.0-c0392b) ![Language](https://img.shields.io/badge/content_language-Turkish-c0392b) ![UI](https://img.shields.io/badge/UI-TR%20%2F%20EN-333) ![License](https://img.shields.io/badge/license-MIT-333)

### 📚 Contents

| Chapter | Topic | Covers |
|---------|-------|--------|
| 01 | **Introduction to Git** | Version control, Git history, installation, how Git works |
| 02 | **Core Commands** | init, status, add, commit, log, diff, restore |
| 03 | **Remote Repositories** | Remote, HTTPS/SSH, clone, fetch, pull, push, PR culture |
| 04 | **Branches & Merging** | Branch model, merge types, conflict resolution |
| 05 | **Advanced Techniques** | Rebase, stash, cherry-pick, reset, revert, reflog, bisect |
| 06 | **Professional Workflows** | Git Flow, tags, hooks, submodules, .gitignore, LFS, security |

### ✨ Features

- 🔍 **Live search** — instant full-handbook search with highlighted matches
- 🌐 **TR / EN UI toggle** — switch interface language on the fly
- 🌙 **Dark / Light mode** — preference saved in localStorage
- 📱 **Fully responsive** — hamburger menu, mobile-first layout
- 📍 **Reading progress dots** — tracks which sections you've read
- 🔗 **Anchor links** — copy direct link to any section heading
- 📋 **Code copy buttons** — one-click copy on every code block
- 📊 **Reading progress bar** — red progress bar at the top
- 🖨️ **Print-ready** — sidebar hidden, each chapter starts on a new page
- ⌨️ **Keyboard shortcuts** — `/` search, `Esc` close, `Alt+↓↑` jump chapters

### 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/git-handbook.git

# Open in browser
cd git-handbook

# Linux
xdg-open git-handbook-final.html

# macOS
open git-handbook-final.html

# Windows
start git-handbook-final.html
```

### ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `/` | Focus search |
| `Esc` | Close search |
| `Enter` | Next match |
| `Shift + Enter` | Previous match |
| `Alt + ↓` | Jump to next chapter |
| `Alt + ↑` | Jump to previous chapter |

### 🌐 Language Toggle

The handbook content is written entirely in **Turkish**, but the interface (navigation, buttons, labels, chapter titles) can be switched to **English**.

**Where to find it:** Bottom of the left sidebar — two buttons labelled `TR` and `EN`.

**What changes when you switch to EN:**

| Element | Turkish | English |
|---------|---------|---------|
| Sidebar navigation | Bölümler, İçindekiler… | Chapters, Contents… |
| Chapter titles | Git'e Giriş, Temel Komutlar… | Introduction to Git, Core Commands… |
| TOC subtitles | Versiyon kontrolü, kurulum… | Version control, installation… |
| Cover text | Kapsamlı Teknik Rehber | Comprehensive Technical Reference |
| Button labels | Kopyala, Ara, Kapat | Copy, Search, Close |
| Dark/Light label | Koyu Mod / Açık Mod | Dark Mode / Light Mode |

**What stays in Turkish:** The main body text of all six chapters. This is intentional — the handbook is a Turkish-language learning resource. A full EN translation may be added in a future version.

Your language preference is saved in `localStorage` and remembered on your next visit.

### 🗂️ File Structure

```
git-handbook/
├── git-handbook-final.html   # Main handbook (everything self-contained)
├── git-handbook-context.md   # Content scope document
└── README.md                 # This file
```

### 🛠️ Built With

| Area | Technology |
|------|------------|
| Markup | Pure HTML5 |
| Styling | Pure CSS3 (custom properties, Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES6+, zero dependencies) |
| Fonts | Playfair Display, Lora, Source Code Pro (Google Fonts) |

### 🤝 Contributing

1. Fork this repository
2. Create a feature branch (`git switch -c fix/description`)
3. Commit your changes
4. Open a Pull Request

### 📄 License

MIT — use, modify and share freely. Just keep the copyright notice.

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

Temelden profesyonel seviyeye kadar kapsamlı, **tek dosyalık** bir Git el kitabı. Herhangi bir kurulum gerekmez — tarayıcıda açılır ve çalışır.

![Versiyon](https://img.shields.io/badge/versiyon-1.0-c0392b) ![İçerik Dili](https://img.shields.io/badge/içerik_dili-Türkçe-c0392b) ![Arayüz](https://img.shields.io/badge/arayüz-TR%20%2F%20EN-333) ![Lisans](https://img.shields.io/badge/lisans-MIT-333)

### 📚 İçerik

| Bölüm | Konu | Kapsam |
|-------|------|--------|
| 01 | **Git'e Giriş** | Versiyon kontrolü, Git tarihi, kurulum, çalışma mantığı |
| 02 | **Temel Komutlar** | init, status, add, commit, log, diff, restore |
| 03 | **Uzak Depolar** | Remote, HTTPS/SSH, clone, fetch, pull, push, PR kültürü |
| 04 | **Dallar ve Birleştirme** | Dal mantığı, merge türleri, conflict çözümü |
| 05 | **İleri Teknikler** | Rebase, stash, cherry-pick, reset, revert, reflog, bisect |
| 06 | **Profesyonel İş Akışları** | Git Flow, tag, hooks, submodules, .gitignore, LFS, güvenlik |

### ✨ Özellikler

- 🔍 **Canlı arama** — tüm el kitabında anlık kelime arama, eşleşmeler vurgulanır
- 🌐 **TR / EN arayüz dili** — arayüz dilini anında değiştirme
- 🌙 **Koyu / Açık mod** — tercih localStorage'a kaydedilir
- 📱 **Tam mobil uyumluluk** — hamburger menü, responsive layout
- 📍 **Bölüm ilerleme noktaları** — kaç section okuduğunuzu gösterir
- 🔗 **Anchor linkler** — her başlığa doğrudan bağlantı kopyalama
- 📋 **Kod kopyalama** — tüm kod bloklarında tek tıkla kopyalama
- 📊 **Okuma ilerleme çubuğu** — sayfanın üstünde kırmızı progress bar
- 🖨️ **Yazdırma desteği** — sidebar gizlenir, her bölüm yeni sayfada başlar
- ⌨️ **Klavye kısayolları** — `/` ara, `Esc` kapat, `Alt+↓↑` bölümler arası

### 🚀 Kullanım

```bash
# Repoyu klonla
git clone https://github.com/KULLANICI_ADIN/git-el-kitabi.git

cd git-el-kitabi

# Linux
xdg-open git-handbook-final.html

# macOS
open git-handbook-final.html

# Windows
start git-handbook-final.html
```

### ⌨️ Klavye Kısayolları

| Kısayol | Eylem |
|---------|-------|
| `/` | Aramayı odakla |
| `Esc` | Aramayı kapat |
| `Enter` | Sonraki eşleşme |
| `Shift + Enter` | Önceki eşleşme |
| `Alt + ↓` | Sonraki bölüme atla |
| `Alt + ↑` | Önceki bölüme atla |

### 🌐 Dil Seçeneği

El kitabının içeriği tamamen **Türkçe** yazılmıştır. Ancak arayüz — navigasyon, butonlar, etiketler, bölüm başlıkları — **İngilizce**'ye geçirilebilir.

**Nerede bulunur:** Sol sidebar'ın en altında `TR` ve `EN` butonları.

**EN seçildiğinde değişenler:**

| Öge | Türkçe | İngilizce |
|-----|--------|-----------|
| Sidebar navigasyon | Bölümler, İçindekiler… | Chapters, Contents… |
| Bölüm başlıkları | Git'e Giriş, Temel Komutlar… | Introduction to Git, Core Commands… |
| İçindekiler alt başlıkları | Versiyon kontrolü, kurulum… | Version control, installation… |
| Kapak metni | Kapsamlı Teknik Rehber | Comprehensive Technical Reference |
| Buton etiketleri | Kopyala, Ara, Kapat | Copy, Search, Close |
| Tema etiketi | Koyu Mod / Açık Mod | Dark Mode / Light Mode |

**Değişmeyen:** Altı bölümün tüm gövde metni Türkçe kalmaya devam eder. Bu bilinçli bir tasarım kararıdır — el kitabı Türkçe bir öğrenme kaynağıdır. Tam İngilizce çeviri ilerleyen sürümlerde eklenebilir.

Dil tercihiniz `localStorage`'a kaydedilir ve bir sonraki ziyaretinizde hatırlanır.

### 🤝 Katkıda Bulunmak

1. Bu repoyu fork'la
2. Yeni bir dal aç (`git switch -c fix/aciklama`)
3. Değişikliklerini commit'le
4. Pull Request aç

### 📄 Lisans

MIT — dilediğiniz gibi kullanabilir, değiştirebilir ve paylaşabilirsiniz.

---

<p align="center">
  Türkçe Git kaynağı eksikliğini gidermek amacıyla hazırlanmıştır.<br>
  <em>Made to fill the gap in Turkish Git resources.</em><br><br>
  <strong>⭐ Beğendiyseniz yıldız bırakmayı unutmayın!</strong>
</p>

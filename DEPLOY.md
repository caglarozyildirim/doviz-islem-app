# Deployment Adımları

## ✅ Tamamlanan Adımlar

- [x] Git repository başlatıldı
- [x] İlk commit oluşturuldu
- [x] Dosyalar hazır

## 📋 GitHub'a Push İçin Adımlar

### 1. GitHub'da Yeni Repo Oluştur

GitHub web sitesinde yeni bir repository oluşturun:
- Repository adı: `doviz-islem-app`
- Visibility: Public
- **ÖNEMLİ**: "Initialize with README" seçeneğini işaretlemeyin!

### 2. Remote Ekle ve Push Yap

```bash
cd /Users/caglarozyildirim/Desktop/doviz-islem-app

# Remote ekle (kullanıcı adınızı değiştirin)
git remote add origin https://github.com/caglarozyildirim/doviz-islem-app.git

# Push
git branch -M main
git push -u origin main
```

## 🚀 Vercel Deployment Adımları

### 1. Vercel'e Giriş Yap

```bash
cd /Users/caglarozyildirim/Desktop/doviz-islem-app
vercel login
```

Bu komut bir tarayıcı penceresi açacak. GitHub, GitLab veya Email ile giriş yapın.

### 2. Deploy Et

```bash
vercel --prod
```

Sorulacak sorular:
- **Set up and deploy?** → Y (Yes)
- **Which scope?** → Hesabınızı seçin
- **Link to existing project?** → N (No)
- **Project name?** → doviz-islem-app (veya istediğiniz isim)
- **In which directory is your code located?** → ./ (Enter)
- **Want to modify these settings?** → N (No)

## 🎯 Alternatif: Vercel Dashboard Üzerinden

1. https://vercel.com adresine gidin
2. "Add New Project" tıklayın
3. GitHub repository'nizi import edin
4. Deploy butonuna basın

## 📝 Deployment Sonrası

Deployment tamamlandıktan sonra README.md dosyasını güncelleyin:

```markdown
## 🌐 Canlı Demo

[https://doviz-islem-app.vercel.app](https://doviz-islem-app.vercel.app)
```

## 🔗 Faydalı Linkler

- GitHub: https://github.com
- Vercel: https://vercel.com
- Vercel Docs: https://vercel.com/docs
# rareplay-media

Planlı Instagram paylaşımları için iki şey tutar:

- **Taslak release'ler:** paylaşılacak video, paylaşım saatine kadar görünmez taslak olarak durur, paylaşılınca silinir.
- **alarm iş akışı** (`.github/workflows/alarm.yml`): paylaşım saatine kadar bekler, sonra özel paylaşım reposunu tetikler.
  Bu repoda Instagram token'ı yok; tek secret, paylaşım reposunu başlatabilen `PUBLISHER_TOKEN`.

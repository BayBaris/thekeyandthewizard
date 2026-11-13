# The Key and the Wizard

![Unity](https://img.shields.io/badge/Unity-2021.3.22f1-000000?style=for-the-badge&logo=unity&logoColor=white)
![Language](https://img.shields.io/github/languages/top/BayBaris/The-Key-and-the-Wizard?style=for-the-badge)
![Tür](https://img.shields.io/badge/T%C3%BCr-2D%20Platformer-8A2BE2?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/BayBaris/The-Key-and-the-Wizard?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/BayBaris/The-Key-and-the-Wizard?style=for-the-badge)

Unity ile geliştirilmiş, pixel-art estetikli 2D platform ve macera oyunu. Tuzaklardan kaç, anahtarı bul, kapıyı aç ve maceranı tamamla.

---

## 🍞 Hakkında

GameJam; testerelerin, dikenlerin ve hareketli platformların olduğu seviyelerden oluşan bir 2D platform oyunu. Oyuncu eşyaları toplar, anahtarı bulup kapıyı açar ve seviyeler arasındaki güvenli odalarda NPC'lerle konuşur.

Menüden başlayıp "YOU COMPLETED YOUR ADVENTURE" ekranına kadar uzanan tam bir oyun akışı var.

**Özellikler**

- Koşma, zıplama ve duruma göre değişen animasyonlarla platform kontrolü
- Testere, diken ve ölüm bölgeleri; ölüm animasyonu ve bölümü yeniden başlatma
- Toplanabilir eşyalar ve anlık skor göstergesi
- Anahtar ve kapı mekaniği (anahtar olmadan kapı açılmaz)
- Waypoint ile hareket eden platformlar ve devriye gezen takipçi düşman
- Daktilo efektiyle yazılan NPC diyalogları ve duygu portreleri
- Arka plan müziği ve olay bazlı ses efektleri
- Ana menü, ses ayarı ve oyun sonu ekranı

## Kontroller

| Tuş | Eylem |
|---|---|
| `A` `D` / `←` `→` | Sola / sağa hareket |
| `Space` | Zıpla |
| `E` | Etkileşim (kapı, nesneler) |
| Fare | Menü ve diyalog butonları |

## Oyun Akışı

```
Menu → First Level → saferoom-First → Second Level → saferoom-Second → Game Over
```

## 🍞 Teknik Bilgiler

| | |
|---|---|
| Motor | Unity 2021.3.22f1 |
| Dil | C# |
| Tür | 2D Platformer |

Öne çıkan script'ler:

| Script | Görev |
|---|---|
| `PlayerMovement` | Hareket, zıplama, zemin kontrolü, animasyon durumları |
| `PlayerLife` | Tuzak teması, ölüm ve bölümü yeniden yükleme |
| `ItemCollector` | Eşya toplama ve skor |
| `WaypointFollower` / `Follower` | Hareketli platform ve takipçi rotası |
| `StickyPlatform` | Oyuncuyu hareketli platforma bağlama |
| `DoorManager` / `KeyManager` | Anahtar ve kapı mantığı |
| `Dialogue_One` | Daktilo efektli diyalog akışı |
| `Interactable` | `UnityEvent` tabanlı genel etkileşim bileşeni |

## Teşekkürler

Bu proje dağıtım amacı taşımayan, öğrenme ve deneme odaklı bir çalışmadır. Kullanılan ücretsiz içerikler için emeği geçen herkese teşekkürler:

- **Pixel Adventure** — Pixel Frog
- **Warrior Free Set** — [Clembod](https://clembod.itch.io)
- **Pixel Art Top Down – Basic** — Cainos
- **Fantasy 2D Battlegrounds, Sky with Clouds, Top-Down Crystals ve diğer pixel-art setleri** — [CraftPix](https://craftpix.net)
- **Casual Game Sound – One Shot SFX Pack** — [Dustyroom](https://dustyroom.com) (CC0)
- **Casual Game BGM Pack #5** — müzik paketi
- **Cave Platformer Tileset** — tileset paketi

---

## 💃 Benimle İletişim

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/baybarisk)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BayBaris)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/baybarisk/)
[![itch.io](https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white)](https://baybaris.itch.io/)

Barış Karakaya · Bilgisayar Mühendisi / Solo Oyun Geliştirici

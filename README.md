# Ticket V1 Discord.js v14 Altyapısı

Bu altyapı, Discord.js v14 kullanılarak kodlanmış bir ticket altyapısıdır.

## 🔧 Kurulum

### Gereksinimler
- [Node.js](https://nodejs.org/en/) (v16.9.0 veya üstü)
- Bir metin editörü (örn: VSCode, Sublime Text)
- Bir Discord botu ([Discord Developer Portal](https://discord.com/developers/applications))

### Adımlar
1. Bu repoyu indirin:

Bu projeyi indirin ve metin editöründe açın.

2. Gerekli modülleri yükleyin:
```bash
npm install
```

3. `config.json` dosyasını düzenleyin:
```json
{
    "token": "BOT_TOKEN",
    "clientId": "BOT_ID",
    "ticketParent": "TİCKET_KATEGORİ_ID",
    "staffRoles": ["YETKİLİ_ROL1", "YETKİLİ_ROL2", "YETKİLİ_ROL3"], // Yetkili rolünü çoğaltabilir veya azaltabilirsiniz.
    "guildId": "SUNUCU_ID",
    "embedColor": "#2f3136",
    "ticketLog": {
    "enabled": true,
    "channelId": "LOG_KANAL_ID"
    }
}
```

4. Botu başlatın:
```bash
node .
```

## 📝 Özellikler
- Hızlıca ``/ticket-panel`` komutu ile ticket panelini kurun.
- İstediğiniz gibi özelleştirin.
- Log kanalı ile tüm yapılan işlemleri kaydedin.

## 🤝 Destek
Herhangi bir sorun için [Swenzy Development](https://discord.gg/react) Discord sunucumuza katılabilirsiniz.

## 📜 Lisans
Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.

## ⭐ Star
Beğendiyseniz star atmayı unutmayın!

---
Developed with ❤️ by [Pedox242 & Swenzy](https://discord.gg/react)

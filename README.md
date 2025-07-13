<h1 align="center">IR-ISP-Blocker</h1>

<div align="center">
    <a href="https://t.me/savechannelAmirHosseinCV"> <img src="https://img.shields.io/badge/TelegramChannel-%230577B8?logo=telegram" alt="Telegram channel"/> </a>
    <a href="https://github.com/AmirHosseinCV/IR-ISP-Blocker"> <img src="https://img.shields.io/github/stars/AmirHosseinCV/IR-ISP-Blocker?style=flat" alt="GitHub stars"/> </a>
    <a href="https://github.com/AmirHosseinCV/IR-ISP-Blocker/releases/latest"> <img src="https://img.shields.io/github/release/AmirHosseinCV/IR-ISP-Blocker.svg" alt="Latest release"/> </a>
</div>

## A simple bash script to block IP ranges of **Iranian ISPs** to prevent your server from being blocked by GFW.
**[آموزش فارسی](https://telegra.ph/IR-ISP-Blocker-05-18-2)**

ISPs that script support now
- MCi ( Hamrah Aval )
- MTN ( Irancell )
- TCi ( Mokhaberat )
- Rightel
- Shatel
- AsiaTech
- Pishgaman
- MobinNet
- ParsOnline
### Using
Open your terminal and run the script with
```
bash <(curl -s https://raw.githubusercontent.com/AmirHosseinCV/IR-ISP-Blocker/main/ir-isp-blocker.sh)
```
Select ISP that you want to block/unblock

### Quick Start - Block all ISPs except Irancell & Rightel

To quickly block all ISPs except Irancell and Rightel, run the script and select option **10** from the main menu:

```bash
sudo bash ir-isp-blocker.sh
# Then select option 10: All Except Irancell & Rightel
```

This will block all Iranian ISPs (MCI, TCI, Shatel, AsiaTech, Pishgaman, MobinNet, ParsOnline) except Irancell and Rightel.

<img src="https://telegra.ph/file/ffcf11e6177faa23ba613.jpg" align="right" width="200" height="200"/>

# BUZZ Music Bot <img src="https://img.shields.io/github/v/release/justteen/buzz?color=black&logo=github&logoColor=black&style=social" alt="RELEASE">

[BUZZ Music Bot](https://github.com/justteen/buzz) adalah Bot Musik + Video Telegram yang Kuat yang ditulis dengan Python menggunakan Pyrogram dan Py-Tgcalls yang dengannya Anda dapat melakukan streaming lagu, video, dan bahkan streaming langsung dalam panggilan grup Anda melalui berbagai sumber.

* Dukungan Youtube, Soundcloud, Apple Music, Spotify, Resso dan Telegram Audio & Videos.
* Ditulis dari awal, membuatnya stabil dan lebih sedikit crash.
* Thumbnail, font, dan gambar yang menarik, menjadikan pengalaman lebih ramah pengguna dan interaktif.
* Dukungan Loop, Seek, Shuffle, Skip Spesifik, Daftar Putar, dll
* Statistik Global, Pengguna, Obrolan Top 10 trek yang dimainkan
* Dukungan Multi-Bahasa


# 🔗 Latar Belakang

Gambaran tentang BUZZ Music Bot:

Proyek ini berdasarkan [Pyrogram](https://github.com/pyrogram) and [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls) .

* untuk database, BUZZ menggunakan MongoDB untuk menyimpan data dan keys. [MongoDB](https://www.mongodb.com/) isdatabase dokumen dengan skalabilitas dan fleksibilitas yang Anda inginkan dengan kueri dan pengindeksan yang Anda butuhkan.
* Proyek ini menggunakan scrapping web bs4 untuk mendapatkan banyak detail platform.. [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) pustaka Python untuk menarik data dari file HTML dan XML.
* BUZZ project menggunakan font [`Raleway`](../assets/font2.ttf) adalah font utama untuk menampilkan detail di Thumbnail
* Proyek ini menggunakan gambar dan ikon menarik yang bisa Anda dapatkan [assets](../assets/) directory.

Untuk informasi lebih lanjut tentang BUZZ silahkan kunjungi [BUZZ](https://t.me/buzzsupport).



# 📝️ Mari kita mulai

### Sebelum menggunakan BUZZ Music Bot , harap lihat [semua vars konfigurasi yang tersedia](../config/README.md) , juga cek [semua commands](../strings/command.yml) di Proyek ini.

> Jika Anda ingin mulai bekerja dengan BUZZ Music Bot, Anda dapat melakukan fork atau mengimpor repo.
> Jika Anda ingin berbicara dengan kami, bergabunglah dengan kami di [Grup Telegram](https://t.me/buzzsupport)


## 🖇 Prasarat

> Untuk menghindari konflik dalam proyek Anda, Anda harus memiliki/menginstal

- [Python3.9](https://www.python.org/downloads/release/python-390/)
- [Telegram API Key](https:/t.me/TGScrapAPIDbot)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_apac_indonesia_search_core_brand_atlas_mobile&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12564980861&adgroup=116332186061&gclid=Cj0KCQjw8_qRBhCXARIsAE2AtRbQuGyJzZinG7CoM9x23WvPdOOfir-3w47syTt_mtP7KRPWjXQdOMQaAmT_EALw_wcB)

## 🖇 Dapatkan Pyrogram String Session

- Dapatkan Pyrogram String Session via [Replit](https://replit.com/@justteen/String-Session)

- Dapatkan Pyrogram String Session via [Telegram String Generation Bot](https://t.me/stringsessionbuzz_bot)


## 🚀 Heroku Deploy
<details>
<summary><b>🔗 Deploy to Heroku</b></summary>

<h4>Click tombol dibawah untuk deploy BUZZ di Heroku!</h4>

<p><a href="https://heroku.com/deploy?template=https://github.com/justteen/buzz"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

</details>

## 🖇 VPS Deploy


```console
buzz@cruviax~ $ git clone https://github.com/justteen/buzz
buzz@cruviax~ $ cd buzz
buzz@cruviax~ $ sudo bash setup
```
> Setup will install each and every requirement, nodejs and pip packages automatically. After successfull installation of requirements , setup will ask you to input your vars.
> Please input your vars correctly.

```console
buzz@cruviax~ $ bash start
```


<img src="https://telegra.ph/file/6b75b57da50ef1183fcdc.jpg" align="center">


## 🏷 Support

Reach out to the maintainer at one of the following places:

- [GitHub Issues](https://github.com/TeamYukki/yukkimusicbot/issues/new?assignees=&labels=question&template=SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/TeamYukki)
- [Telegram Support](https://t.me/YukkiSupport)

## 🎗 Project assistance

If you want to say **thank you** or/and support active development of YukkiMusicBot:

- Add a [GitHub Star](https://github.com/TeamYukki/YukkiMusicBot) to the project.
- Fork the Repo :)
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

PS: You can buy me a coffee too :)
<p><a href="https://www.buymeacoffee.com/notreallysy" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 35px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a></p>

Together, we can make YukkiMusicBot **better**!

## ✍🏻 Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.

Please read [our contribution guidelines](CONTRIBUTING.md), and thank you for being involved!

## 👨🏻‍💻 Authors & contributors

The original setup of this repository is by [Team Yukki](https://github.com/TeamYukki).

For a full list of all authors and contributors, see [the contributors page](https://github.com/TeamYukki/YukkiMusicBot/contributors).

## ⚠️ Security

YukkiMusicBot follows good practices of security, but 100% security cannot be assured. YukkiMusicBot is provided **"as is"** without any **warranty**. Use at your own risk.

For more information and to report security issues, please refer to our [`SECURITY.md`](SECURITY.md)


## 🗂 License

This project is licensed under the **GNU General Public License v3**. All designs were created by [@NotReallyShikhar](https://github.com/NotReallyShikhar) .

See [LICENSE](../LICENSE) for more information.

## 📑 Acknowledgement

Special thanks to these amazing projects/people which/who help power Yukki Music Bot:

- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
- [CallsMusic Team](https://github.com/Callsmusic)
- [TheHamkerCat](https://github.com/TheHamkerCat)
- [Charon Baglari](https://github.com/XCBv021)


Reminder that you are great, you are enough, and your presence is valued. If you are struggling with your mental health, please reach out to someone you love and consult a professional.

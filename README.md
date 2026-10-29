# Xunison-Exigo-Hub-D50-5G-NSS
My OpenWrt SNAPSHOT / LuCI Main build for the Xunison Exigo Hub D50 5G router [Build: 29.10.2026].

<p align="center">
<img src="https://github.com/4IceG/Personal_data/blob/master/xunisondevb.png?raw=true" />
</p>

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/Xunison-Exigo-Hub-D50-5G-NSS?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/Xunison-Exigo-Hub-D50-5G-NSS?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/Xunison-Exigo-Hub-D50-5G-NSS?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/Xunison-Exigo-Hub-D50-5G-NSS/total)

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Languages ​​available in test images / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Dostępne języki w obrazach testowych

<img src="https://hatscripts.github.io/circle-flags/flags/pl.svg" width="36" title="Polish (Polski)" alt="Polish language" /> <img src="https://hatscripts.github.io/circle-flags/flags/gb.svg" width="36" title="Enlish (Angielski)" alt="English language" />
<!--

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Languages available / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Dostępne języki

<img src="https://hatscripts.github.io/circle-flags/flags/cz.svg" width="36" title="Czech (Čeština)" alt="Czech language" /> <img src="https://hatscripts.github.io/circle-flags/flags/dk.svg" width="36" title="Danish (Dansk)" alt="Danish language" /> <img src="https://hatscripts.github.io/circle-flags/flags/de.svg" width="36" title="German (Deutsch)" alt="German language" /> 
<img src="https://hatscripts.github.io/circle-flags/flags/es.svg" width="36" title="Spanish (Español)" alt="Spanish language" /> <img src="https://hatscripts.github.io/circle-flags/flags/fr.svg" width="36" title="French (Français)" alt="French language" /> <img src="https://hatscripts.github.io/circle-flags/flags/it.svg" width="36" title="Italian (Italiano)" alt="Italian language" /> 
<img src="https://hatscripts.github.io/circle-flags/flags/jp.svg" width="36" title="Japanese (日本語)" alt="Japanese language" /> <img src="https://hatscripts.github.io/circle-flags/flags/kr.svg" width="36" title="Korean (한국어)" alt="Korean language" /> <img src="https://hatscripts.github.io/circle-flags/flags/nl.svg" width="36" title="Dutch (Nederlands)" alt="Dutch language" /> 
<img src="https://hatscripts.github.io/circle-flags/flags/pl.svg" width="36" title="Polish (Polski)" alt="Polish language" /> <img src="https://hatscripts.github.io/circle-flags/flags/br.svg" width="36" title="Brazilian Portuguese (Português Brasil)" alt="Brazilian Portuguese language" /> <img src="https://hatscripts.github.io/circle-flags/flags/ru.svg" width="36" title="Russian (Русский)" alt="Russian language" /> <img src="https://hatscripts.github.io/circle-flags/flags/vn.svg" width="36" title="Vietnamese (Tiếng Việt)" alt="Vietnamese language" /> <img src="https://hatscripts.github.io/circle-flags/flags/cn.svg" width="36" title="Simplified Chinese (简体中文)" alt="Simplified Chinese language" /> <img src="https://hatscripts.github.io/circle-flags/flags/tw.svg" width="36" title="Traditional Chinese (繁體中文 - 台灣)" alt="Traditional Chinese language" /> <img src="https://hatscripts.github.io/circle-flags/flags/hk.svg" width="36" title="Traditional Chinese (繁體中文 - 香港)" alt="Traditional Chinese language" />

-->



### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> OpenWrt installation procedure / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Procedura instalacji OpenWrt

<details>
   <summary>Show me</summary>

![](https://forum.openwrt.org/uploads/default/original/3X/d/9/d92a1660e463e3b93a9c53158456a9fa1b3599ce.png)

Installing firmware / Recovery steps
1. Turn off the power
2. Press and hold the reset button
3. Turn on the power (reset cannot be released, the internet light will stay on after 10s)
4. Set the computer IP address to 192.168.1.2
subnet mask 255.255.255.0
gateway 192.168.1.1
5. Open the computer browser and enter 192.168.1.254
6. Select the firmware file (factory)
7. Click the update button once and wait for the router to restart
  
</details>

<details>
   <summary>Pokaż</summary>

![](https://forum.openwrt.org/uploads/default/original/3X/d/9/d92a1660e463e3b93a9c53158456a9fa1b3599ce.png)

Instalacja oprogramowania / Procedura przywracania
1. Wyłącz zasilanie
2. Naciśnij i przytrzymaj przycisk reset (z tyłu routera)
3. Włącz zasilanie (nie zwalniaj przycisku reset, dioda "Internet" (na froncie) powinna zostać włączona po 10 sekundach)
4. Ustaw adres IP komputera na 192.168.1.2, maskę podsieci 255.255.255.0, bramę 192.168.1.1
5. Otwórz przeglądarkę na komputerze i wpisz adres 192.168.1.254 (czyli mamy http://192.168.1.254)
6. Wybierz plik oprogramowania (factory)
7. Kliknij raz przycisk aktualizacji i poczekaj, aż router się zrestartuje

</details>

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> What You Should Know / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Co powinieneś wiedzieć

+ #### Installation of additional packages / Instalacja dodatkowych pakietów
> Snapshots are built daily, and that sets time limits to installing new packages with apk. Due to kernel version checksums, you can only install “kmod” kernel modules and other kernel version dependent modules from the exactly same snapshot build. So, a few hours after flashing the firmware you may not be able to install new modules with opkg any more (as the next snapshot has been built into the download repo and has different checksums).   
> Obrazy snapshots budowane są codziennie, a to ustawia limity czasowe na instalację nowych pakietów za pomocą apk. Z powodu sum kontrolnych wersji jądra, możesz zainstalować tylko moduły "kmod" i inne moduły zależne od wersji jądra z dokładnie tego samego snapshotu. Tak więc, kilka godzin po flashowaniu firmware możesz nie być w stanie zainstalować nowych modułów za pomocą opkg (ponieważ następny snapshot został wbudowany w repo i ma inne sumy kontrolne).

+ #### User's own configuration / Konfiguracja przez użytkownika
> The user must configure on his own:
- set up Wi-Fi/passwords
> Użytkownik musi skonfigurować we własnym zakresie:
- skonfigurować Wi-Fi/hasła

+ #### LuCI theme / Motyw LuCI
> Main theme: Bootstrap.   
> Główny motyw: Bootstrap.

+ #### My modifications / Moje modyfikacje
> I installed the [luci-app-exigo-hub-d50-5g-nss](https://github.com/4IceG/luci-app-exigo-hub-d50-5g-nss/tree/main) package (it configures router and my packages, controls 4G and 5G LEDs).   
> Dodałem pakiet [luci-app-exigo-hub-d50-5g-nss](https://github.com/4IceG/luci-app-exigo-hub-d50-5g-nss/tree/main) (wstępnie ustawia router i moje pakiety, steruje LED-ami 4G i 5G).

+ #### Modem requires following packages to work in pcie mode / Modem do działania w pcie wymaga pakietów
> [Quectel-mhi-NSS-drivers-for-6.18-kernel](https://github.com/LS3434/Quectel-mhi-NSS-drivers-for-6.18-kernel) (mhi_q + rmnet-nss) + [wwand](https://github.com/ddimension/wwand) + [luci-app-exigo-hub-d50-5g-nss](https://github.com/4IceG/luci-app-exigo-hub-d50-5g-nss)

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Preview / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Podgląd
Coming soon.. / Niebawem..

## <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Thanks to / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Podziękowania dla
- [kuncy7](https://github.com/kuncy7)
- [LS3434](https://github.com/LS3434)

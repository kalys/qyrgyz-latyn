<img width="739" alt="Screenshot 2023-02-12 at 22 48 09" src="https://user-images.githubusercontent.com/155511/218324694-bb37d9a4-d395-420a-a5d8-fee45f2d0c28.png">

# Ornotuu

## Windows

1. Bul [baraqa](https://github.com/kalys/qyrgyz-latyn/releases/tag/v0.0.3) ötüñüz
2. **Qyrgyz.win.zip** ce **Qyrgyz30.win.zip** (1928-çi cyldyq versjasy) fajlyn cüktöp alyñyz
3. **setup.exe** ni iştetip, tergiçti sistemağa ornotuñuz
4. Cañy tergiçti Windows tun kontrol panelinen koşup alyñyz

## macOS

Bul [baraqtan](https://github.com/kalys/qyrgyz-latyn/releases/tag/v0.0.3) **Qyrgyz.pkg** fajlyn cüktöp, paketti ornotup,
sistemağa `Qyrgyz` ce `Qyrgyz 30` tergiçti qoşuñuz.

# Tergiçti özgörtüü

Repozitorijdi aluu

    git clone https://github.com/kalys/qyrgyz-latyn.git

## Windows

### Köz qarandylyqtar

- [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
- Microsoft .NET Framework 3.5

MSKLC arqyluu `windows/qyrgyz.klc` ce `windows/qyrgyz30.klc` fajldaryn açyp, tergiçti özgörtsö bolot.

### Paket jasoo

MSKLCnin ornotuu paketin jasooğo cöndömdülügü bar

## macOS

### Köz qarandylyqtar
- [Ukulele](https://software.sil.org/ukelele/)
- [Packages](http://s.sudre.free.fr/Software/Packages/about.html)

Ukulele menen `macos/Qyrgyz.bundle` fajlyn açyp, kerektüü özgörüülördü qylğyla.

### Paket jasoo
Packages ti koldonuu astynda bul komandany arqarğyla

    sudo launchctl load /Library/LaunchDaemons/fr.whitebox.packages.build.dispatcher.plist

**Packages** arqyluu `macos/Qyrgyz.pkgproj` fajlyn açyp, menjudan Build -> Build ti atqarğyla.
`macos/build` tin içinde paket fajl pajda bolot.

# Tergiçti casoodo qylynğan çeçimder

**QWERTY tergiçinde negizdelgen.**
- Latyn aribinde Dvorak, AZERTY, Colemak syjaqtuu köptögön tergiçter bar. Alardyn arasynda QWERTY eñ köp taralgan. 
- Türk tilinde 2 tergiç casalğan: QWERTYnin negizinde **Türkçe-Q** cana optimizasjalanğan **Türkçe-F**. **Türkçe-F** köp taralğan cok.
- Klaviaturalarda QWERTY tamgalary cazylğan.

**QWERTYdegi W cana X terdin orduna Ö cana Ş**
- Cañy Qyrğyz aribiinde X tamgasy cok.
- W cañy aribde dialekttik tamğa. Az qoldonulat.
- W tamğasyn Alt/Option + ö ce Ö arqyluu terse bolot.
- X tamğasyn Alt/Option + ş ce Ş arqyluu terse bolot.

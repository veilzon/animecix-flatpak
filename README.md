# AnimeciX Flatpak

AnimeciX'in Flathub dışı, kendi imzalı Flatpak deposu.

## Kurulum

```bash
flatpak install --from https://veilzon.github.io/animecix-flatpak/animecix.flatpakref
```

Flatpak uygulamayı bu depodan kurar; yalnızca GNOME 50 runtime'ı Flathub'dan
gelir. Flathub'a uygulama gönderilmez.

## Güncelleme

```bash
flatpak update io.github.veilzon.AnimeciX
```

## Kaldırma

```bash
flatpak uninstall io.github.veilzon.AnimeciX
```

## Depo

- Flatpakref: <https://veilzon.github.io/animecix-flatpak/animecix.flatpakref>
- OSTree deposu: <https://veilzon.github.io/animecix-flatpak/repo/>
- Ana proje: <https://github.com/veilzon/animecix-linux>

Depo, GitHub Actions'ta `veilzon/animecix-linux` sürüm tag'inden derlenir ve
GPG ile imzalanır. İmza açık anahtarı: `animecix-flatpak.gpg`.

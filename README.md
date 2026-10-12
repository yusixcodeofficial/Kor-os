# Kor OS

An Android system based on [LineageOS](https://lineageos.org) that routes network traffic through Tor.

> **Status:** In development. There is no downloadable build yet.

## Goals

- **Tor for the whole system:** App traffic goes through Tor via a built-in Orbot. If the Tor connection drops, the internet drops too.
- **LineageOS base:** An established open-source Android base that ships without Google apps.
- **Offline AI (Kor AI):** An on-device assistant that runs fully offline, with no internet permission.
- **Open source:** Source code and build files are published here.

## Target device

Xiaomi Redmi Note 10 Pro (`sweet`), 6 GB RAM, Snapdragon 732G.

## Repository structure

```
kor-os/
├── index.html          # GitHub Pages site
├── bootanimation/      # Boot animation (zip + generator script)
├── README.md
└── LICENSE             # (to be added)
```

Build files (manifests, device trees, patches) will be added later.

## Website languages

The site (`index.html`) is available in English, Türkçe, Deutsch, Français, Español, Português, Italiano, Русский, العربية, 中文, 日本語 and 한국어. It picks the language from the browser and remembers the visitor's choice. To add a language, add one more entry to the `T` object in the script and one `<option>` to the language menu.

## License and attribution

Kor OS is based on the source code of LineageOS and AOSP. The licenses of those projects (Apache 2.0, GPL, etc.) apply, and changes are shared under the same licenses. Kor OS is not affiliated with the LineageOS project or The Tor Project; their names and logos belong to their respective owners.

# Kor OS

An Android system based on [/e/OS](https://e.foundation/e-os/) that routes network traffic through Tor.

> **Status:** In development. There is no downloadable build yet.

## Goals

- **Tor for the whole system:** App traffic goes through Tor via a built-in Orbot. If the Tor connection drops, the internet drops too.
- **De-Googled base:** Built on /e/OS and compatible with microG.
- **Open source:** Source code and build files are published here.

## Website languages

The site (`index.html`) is available in English, Türkçe, Deutsch, Français, Español, Português, Italiano, Русский, العربية, 中文, 日本語 and 한국어. It picks the language from the browser and remembers the visitor's choice. To add a language, add one more entry to the `T` object in the script and one `<option>` to the language menu.

## Repository structure

```
kor-os/
├── index.html      # GitHub Pages site
├── README.md
└── LICENSE         # (to be added)
```

Build files (manifests, device trees, patches) will be added later.

## License and attribution

Kor OS is based on the source code of /e/OS and LineageOS. The licenses of those projects (Apache 2.0, GPL, etc.) apply, and changes are shared under the same licenses. Kor OS is not affiliated with /e/ Foundation, Murena, or The Tor Project; their names and logos belong to their respective owners.

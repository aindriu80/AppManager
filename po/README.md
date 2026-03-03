# Translating AppManager

## How to Contribute Translations

1. **Edit an existing translation**: Find the relevant `.po` file for your language and submit a PR with your improvements.
2. **Add a new language**: Use `app-manager.pot` as a template, save it as `po/xx.po` (where `xx` is your language code), translate the strings, and create a PR.

## Translation Status

| Language | Code | Status |
| -------- | ---- | ------ |
| Arabic | ar | 89.9% (249/277) |
| German | de | 89.9% (249/277) |
| Greek | el | 89.9% (249/277) |
| Spanish | es | 89.9% (249/277) |
| Estonian | et | 89.9% (249/277) |
| Finnish | fi | 89.9% (249/277) |
| French | fr | 94.6% (262/277) |
| Italian | it | 89.9% (249/277) |
| Japanese | ja | 89.9% (249/277) |
| Kazakh | kk | 89.9% (249/277) |
| Korean | ko | 89.9% (249/277) |
| Lithuanian | lt | 89.9% (249/277) |
| Latvian | lv | 89.9% (249/277) |
| Norwegian Bokmål | nb | 89.9% (249/277) |
| Dutch | nl | 89.9% (249/277) |
| Polish | pl | 89.9% (249/277) |
| Portuguese (Brazil) | pt_BR | 89.9% (249/277) |
| Swedish | sv | 89.9% (249/277) |
| Ukrainian | uk | 89.9% (249/277) |
| Vietnamese | vi | 89.9% (249/277) |
| Chinese (Simplified) | zh_CN | 89.9% (249/277) |

## Note

> Some translations are machine-generated and may contain mistakes. Native speakers are welcome to review and improve them!

## Testing Translations Locally

After building with meson, translations are compiled automatically. To test:

```bash
meson setup build --prefix=$HOME/.local
meson compile -C build
meson install -C build
```

Then run the app with a specific locale:

```bash
LANGUAGE=de app-manager
```

## Further Reading

- [GNU gettext Manual](https://www.gnu.org/software/gettext/manual/gettext.html)
- [Vala i18n documentation](https://wiki.gnome.org/Projects/Vala/TranslationSample)

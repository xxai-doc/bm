<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

A ka ɲi ka nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) sigi fɔlɔ, o kɔfɛ `direnv allow` donna ɲɛbilasɛbɛn kɔnɔ ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) bɛna baara kɛ a yɛrɛma ɲɛbilasɛbɛn donlen kɔfɛ).

O kɔrɔ ye ko: Sinuwakan bamanankan na Zapɔnkan, Korekan, Angilɛkan, Angilɛkan bamanankan na kan tɔw bɛɛ la. Ni aw b’a fɛ ka Sinuwakan ni Angilɛkan dɔrɔn de dɛmɛ, aw bɛ se ka `zh: en` sɛbɛn dɔrɔn.

O kɔrɔ ye ko: Sinuwakan bamanankan na Zapɔnkan, Korekan, Angilɛkan, Angilɛkan bamanankan na kan tɔw bɛɛ la. Ni aw b’a fɛ ka Sinuwakan ni Angilɛkan dɔrɔn de dɛmɛ, aw bɛ se ka `zh: en` sɛbɛn dɔrɔn.

* [ɲɛfɛla-kode](https://github.com/xxai-art/web)
* [Kanko pakew ka ɲɛsin yɔrɔ bɛɛ ma](https://github.com/xxai-art/web/tree/main/i18n)
* [Kanko pakew doncogo moduluw kama](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Site web kan caman sɛbɛnni](https://github.com/xxai-doc)

Porogaramukan min bɛ ɲɛfɛ, o ye [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ye, min bɛ fɛn dɔw fara a kan ka da kafesɛbɛnni daɲɛw labɛncogo kan, a’ ye [./coffee_plus.md](./coffee_plus.md) lajɛ.

## Sitiw ni sɛbɛnw ka diɲɛnatigɛ kɛli

Aw ye jɔ nin porozɛ 3 ninnu kan

* [@w5/mdt ye](https://www.npmjs.com/package/@w5/mdt)

  O kɔfɛko ye `.mdt` ye, i bɛ se ka baara kɛ ni daɲɛgafe ye min ni `<+ ./coffee_plus/import.js>` bɛ tali kɛ ɲɔgɔn na walasa ka kɛnɛma dosiyew kofɔ, ani ka markdown lawuli ni `.md` kɔfɛta ye.

* [@w5/trmd ye](https://www.npmjs.com/package/@w5/trmd)

  Markdown bamanankan bamanankan tɛna kodɔn ni jɛgɛnsira baara, wa a bɛna kumasen bamanankan na. Ni bamanankan bayɛlɛmani b’a la, nka sɛbɛnni fɔlɔ ma ladilan, n’i y’a waleya kokura, o tɛna bamanankan bamanankan sɛmɛntiyalen sɛbɛn.

* [@w5/i18n ye](https://www.npmjs.com/package/@w5/i18n)

  Kanko dosiyew ka `yaml` sitiw bamanankan na.

### Sɛbɛnw bamanankan baarakɛcogo otomatiki cikanw

Aw ye kode marayɔrɔ lajɛ [xxai-art/doc](https://github.com/xxai-art/doc)

A ka ɲi ka nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) sigi fɔlɔ, o kɔfɛ `direnv allow` donna ɲɛbilasɛbɛn kɔnɔ ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) bɛna baara kɛ a yɛrɛma ɲɛbilasɛbɛn donlen kɔfɛ).

Walasa ka n yɛrɛ tanga kode basigilenba ma min bamanankanna kan kɛmɛ caman na, n ye kode basigi danfaralen dɔ da kan kelen-kelen bɛɛ kama ani ka jɛkulu dɔ dabɔ walasa ka kode basigilen mara

Lamini fɛn caman sɛgɛsɛgɛli `GITHUB_ACCESS_TOKEN` sigili ka sɔrɔ ka [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) boli, o bɛna kode marayɔrɔ da a yɛrɛma.

Tiɲɛ don, i bɛ se k’a bila fana kode basigilen dɔ kɔnɔ.

Bamanankan baarakɛcogo ɲɛfɔli [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

Sɛbɛnni kode bɛ kɔrɔfɔ nin cogo la:

[bunx](https://bun.sh/docs/cli/bunx) ye npx nɔnabila ye, o min ka teliya. Tiɲɛ don, ni bun installé (bun) ma i bolo, i bɛ se ka baara kɛ `npx` ye o nɔ na.

`bunx mdt zh` bɛ `.mdt` jira zh ɲɛbilasɛbɛn kɔnɔ i n’a fɔ `.md` , aw ye filen 2 lajɛ minnu bɛ tali kɛ ɲɔgɔn na jukɔrɔ

* [kafe_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [kafe_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ye bamanankan baarakɛcogo jɔnjɔn ye (ni `nodejs` dɔrɔn de bɛ i bolo, nka `bun` ni `direnv` ma sigi, i bɛ se fana ka `npx i18n` boli walasa ka baara kɛ).

A bɛna [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) parse , `i18n.yml` labɛncogo nin sɛbɛn in kɔnɔ nin ye:

```
en:
zh: ja ko en
```

O kɔrɔ ye ko: Sinuwakan bamanankan na Zapɔnkan, Korekan, Angilɛkan, Angilɛkan bamanankan na kan tɔw bɛɛ la. Ni aw b’a fɛ ka Sinuwakan ni Angilɛkan dɔrɔn de dɛmɛ, aw bɛ se ka `zh: en` sɛbɛn dɔrɔn.

O laban ye [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ye , min bɛ kɔnɔkow Bɔ kan kelen-kelen bɛɛ ka `README.md` tɔgɔba ni tɔgɔ fɔlɔ cɛ walasa ka sɛbɛnni dɔ Sɔrɔ `README.md` . Kode in ka nɔgɔn kosɛbɛ, i yɛrɛ bɛ se k’a lajɛ.

Google API bɛ baara kɛ ni bamanankan baara fu ye. Ni i tɛ se ka don Google la, i ka proxy dɔ labɛn ani k’a sigi sen kan, i n’a fɔ:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

Bamanankan-falen-falen-sɛbɛn bɛna bamanankan-falen-falen-sɛbɛn dɔ Bɔ `.i18n` ɲɛbilasɛbɛn kɔnɔ, i k’a Lajɛ ni `git status` ye k’a Fàra kode marayɔrɔ kan walasa ka i yɛrɛ tanga bamanankan bamanankan segin-segin ma.

Aw ye `bunx i18n` boli tuma o tuma n’aw bɛ bamanankan baarakɛcogo sɛmɛntiya walasa ka cache kura.

Ni sɛbɛnni fɔlɔ ni bamanankan bamanankan bε Yεlεma waati kelen na, cache bεna bεn, o la n’i b’a fɛ ka bεnkansεbεn, i bɛ Se ka kelen dɔrɔn bεε Lakodɔn, ka sɔrɔ ka `bunx i18n` boli walasa ka cache (dakun) kura ye.

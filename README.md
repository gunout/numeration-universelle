<div align="center">

# 金 Numérations Universelles + Mathématiques + Cryptographie

### 🌍 Un nombre ou un mot → 21 systèmes de numération historiques · analyse mathématique encyclopédique · cryptographie vérifiée

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![License MIT](https://img.shields.io/badge/License-MIT-002395?style=for-the-badge)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-ED2939?style=for-the-badge)]()
[![Single File](https://img.shields.io/badge/single%20file-60%20KB-d4af37?style=for-the-badge)]()

[![Stars](https://img.shields.io/github/stars/USER/REPO?style=for-the-badge&logo=github&color=ed2939)](https://github.com/USER/REPO/stargazers)
[![Forks](https://img.shields.io/github/forks/USER/REPO?style=for-the-badge&logo=github&color=002395)](https://github.com/USER/REPO/network)
[![Issues](https://img.shields.io/github/issues/USER/REPO?style=for-the-badge&logo=github&color=d4af37)](https://github.com/USER/REPO/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-16a34a?style=for-the-badge&logo=github)](https://github.com/USER/REPO/pulls)

**Un dashboard web autonome qui transforme n'importe quel nombre ou mot en 21 systèmes de numération historiques du monde, dévoile son analyse mathématique complète et calcule 20+ empreintes cryptographiques vérifiées.**

</div>

---

## 📑 Table des matières

- [✨ Aperçu](#-aperçu)
- [🎯 Fonctionnalités](#-fonctionnalités)
- [🌍 Systèmes de numération](#-systèmes-de-numération)
- [🧮 Analyse mathématique](#-analyse-mathématique)
- [🔐 Cryptographie](#-cryptographie)
- [🚀 Installation](#-installation)
- [📖 Utilisation](#-utilisation)
- [🏗️ Architecture technique](#️-architecture-technique)
- [🧪 Tests et validation](#-tests-et-validation)
- [🎨 Thème tricolore](#-thème-tricolore)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contribution](#-contribution)
- [📜 Licence](#-licence)
- [👤 Auteur](#-auteur)

---

## ✨ Aperçu

**Numérations Universelles** est un **dashboard web monofichier** (HTML + CSS + JS, zéro dépendance) qui réunit en une seule interface :

| Domaine | Description |
|---------|-------------|
| 🌍 **21 numérations historiques** | Du romain au japonais en passant par le grec ancien, l'hébreu, l'arabe oriental, le cyrillique slave… |
| 🧮 **22 analyses mathématiques** | Factorisation première, primalité, bases multiples, propriétés arithmétiques |
| 🔐 **20+ empreintes cryptographiques** | MD5, SHA-1/256/512, SHA-3, HMAC, UUID v4, hachages classiques, chiffrements historiques |

### 🎬 Démonstration

Pour l'entrée **FINANCE** (converti en base 26 = **3 572 640 894**), le dashboard affiche simultanément :

| Système | Résultat |
|---------|----------|
| 🔤 Latin (romain) | `(MMMDLXXII)DCXL` |
| 🇫🇷 Français | `3 572 640 894` |
| 🇩🇪 Allemand | `3.572.640.894` |
| 🇬🇷 Grec | `ΜΓ·͵ΦΟΒ·ΧϞΔ` |
| 🇮🇱 Hébreu | `ג׳׳ תרע׳ ב״ת` |
| 🇨🇳 Chinois financier | `叁拾伍亿柒仟贰佰陆拾肆万零捌佰玖拾肆` |
| 🔐 SHA-256 | `7d6b2a1f…` |
| 🧮 Factorisation | `2 × 1 786 320 447` |

---

## 🎯 Fonctionnalités

### 🔢 Deux modes de saisie

| Mode | Entrée | Exemple | Sortie |
|------|--------|---------|--------|
| **🔢 Nombre** | Chiffres arabes | `5211815` | Conversions immédiates |
| **🔤 Mot** | Mot latin/cyrillique/arabe… | `EURO` | Base N → nombre → conversions |

### 🌟 Points forts

- ✅ **Monofichier** : un seul `.html`, aucune installation, aucune dépendance
- ✅ **Zéro framework** : HTML/CSS/JS pur, fonctionne hors-ligne
- ✅ **BigInt natif** : supporte des nombres jusqu'à des centaines de chiffres
- ✅ **Web Crypto API** : hachages standards certifiés navigateur
- ✅ **Multilingue** : 7 alphabets sources
- ✅ **Thème tricolore** 🇫🇷 : bleu-blanc-rouge élégant
- ✅ **Responsive** : mobile, tablette, desktop
- ✅ **Persistent** : historique en `localStorage`
- ✅ **Presse-papier** : bouton copier sur chaque résultat

---

## 🌍 Systèmes de numération

### 📋 Les 21 systèmes supportés

| # | Drapeau | Langue | Système | Base | Exemple pour 5211815 |
|---|---------|--------|---------|------|----------------------|
| 1 | 🔤 | Latin | Chiffres romains | 26 | `((V)CCXI)DCCCXV` |
| 2 | 🇫🇷 | Français | Arabe, espace | 42 | `5 211 815` |
| 3 | 🇩🇪 | Allemand | Arabe, point | 30 | `5.211.815` |
| 4 | 🇪🇸 | Espagnol | Arabe, point | 27 | `5.211.815` |
| 5 | 🇮🇹 | Italien | Arabe, point | 26 | `5.211.815` |
| 6 | 🇵🇹 | Portugais | Arabe, point | 26 | `5.211.815` |
| 7 | 🇬🇷 | Grec | Attique/milesien | 24 | `ΜΕ·͵ΣΙΑ·ΩΙΕ` |
| 8 | 🇮🇱 | Hébreu | Gematria | 22 | `ה׳׳ ריא׳ תתט״ו` |
| 9 | 🇸🇦 | Arabe | Indo-arabe oriental | 28 | `٥٢١١٨١٥` |
| 10 | 🇯🇵 | Japonais | Kanji | 46 | `五百二十一万一千八百十五` |
| 11 | 🇨🇳 | Chinois financier | 大写数字 | 46 | `伍佰贰拾壹万壹仟捌佰壹拾伍` |
| 12 | 🇷🇺 | Cyrillique | Slave | 33 | `҂͵͵Е·͵СІА·ѠІЕ` |
| 13 | 🇮🇳 | Hindi | Devanagari | 46 | `५२११८१५` |
| 14 | 🇵🇱 | Polonais | Arabe, espace | 35 | `5 211 815` |
| 15 | 🇨🇿 | Tchèque | Arabe, espace | 42 | `5 211 815` |
| 16 | 🇹🇷 | Turc | Arabe, point | 29 | `5.211.815` |
| 17 | 🇷🇴 | Roumain | Arabe, point | 31 | `5.211.815` |
| 18 | 🇭🇺 | Hongrois | Arabe, espace | 35 | `5 211 815` |
| 19 | 🇸🇪 | Suédois | Arabe, espace | 29 | `5 211 815` |
| 20 | 🇩🇰 | Danois/Norvégien | Arabe, point | 29 | `5.211.815` |
| 21 | 🇫🇮 | Finnois | Arabe, espace | 29 | `5 211 815` |

### 🎓 Détails des systèmes complexes

#### 🇬🇷 Grec ancien (milesien)

| Valeur | Symbole | Valeur | Symbole | Valeur | Symbole |
|--------|---------|--------|---------|--------|---------|
| 1 | Α | 10 | Ι | 100 | Ρ |
| 2 | Β | 20 | Κ | 200 | Σ |
| 3 | Γ | 30 | Λ | 300 | Τ |
| 4 | Δ | 40 | Μ | 400 | Υ |
| 5 | Ε | 50 | Ν | 500 | Φ |
| 6 | Ϛ | 60 | Ξ | 600 | Χ |
| 7 | Ζ | 70 | Ο | 700 | Ψ |
| 8 | Η | 80 | Π | 800 | Ω |
| 9 | Θ | 90 | Ϟ | 900 | Ϡ |

- **͵** devant → ×1000
- **Μ** devant → ×10⁶
- **·** sépare les groupes

#### 🇮🇱 Hébreu (gematria)

| Valeur | Lettre | Valeur | Lettre | Valeur | Lettre |
|--------|--------|--------|--------|--------|--------|
| 1 | א | 10 | י | 100 | ק |
| 2 | ב | 20 | כ | 200 | ר |
| 3 | ג | 30 | ל | 300 | ש |
| 4 | ד | 40 | מ | 400 | ת |
| 5 | ה | 50 | נ | | |
| 6 | ו | 60 | ס | | |
| 7 | ז | 70 | ע | | |
| 8 | ח | 80 | פ | | |
| 9 | ט | 90 | צ | | |

- **׳** après un groupe → ×1000
- **׳׳** après un groupe → ×10⁶
- **״** (gershayim) entre avant-dernière et dernière lettre
- **Exceptions** : 15 = `טו`, 16 = `טז`

#### 🇷🇺 Cyrillique slave

| Valeur | Symbole | Valeur | Symbole | Valeur | Symbole |
|--------|---------|--------|---------|--------|---------|
| 1 | А | 10 | І | 100 | Р |
| 2 | В | 20 | К | 200 | С |
| 3 | Г | 30 | Л | 300 | Т |
| 4 | Д | 40 | М | 400 | У |
| 5 | Е | 50 | Н | 500 | Ф |
| 6 | Ѕ | 60 | Ѯ | 600 | Х |
| 7 | З | 70 | О | 700 | Ѱ |
| 8 | И | 80 | П | 800 | Ѡ |
| 9 | Ѳ | 90 | Ч | 900 | Ц |

- **҂** (titlo) marqueur du nombre
- **͵** devant → ×1000
- **͵͵** devant → ×10⁶
- **·** sépare les groupes

#### 🇯🇵 Japonais (kanji)

| Chiffre | Kanji | Unité | Kanji |
|---------|-------|-------|-------|
| 0 | 零 | 10 | 十 |
| 1 | 一 | 100 | 百 |
| 2 | 二 | 1 000 | 千 |
| 3 | 三 | 10 000 | 万 |
| 4 | 四 | 10⁸ | 億 |
| 5 | 五 | 10¹² | 兆 |
| 6 | 六 | | |
| 7 | 七 | | |
| 8 | 八 | | |
| 9 | 九 | | |

- **Règle du 1 implicite** : `一` omis devant `十`, mais écrit devant `百`, `千`, `万`

#### 🇨🇳 Chinois financier (大写数字)

| Chiffre | Financier | Chiffre | Financier |
|---------|-----------|---------|-----------|
| 0 | 零 | 5 | 伍 |
| 1 | 壹 | 6 | 陆 |
| 2 | 贰 | 7 | 柒 |
| 3 | 叁 | 8 | 捌 |
| 4 | 肆 | 9 | 玖 |

Unités : `拾` (10), `佰` (100), `仟` (1000), `万` (10⁴), `亿` (10⁸), `兆` (10¹²)…

---

## 🧮 Analyse mathématique

### 🔬 22 propriétés calculées automatiquement

| # | Propriété | Description |
|---|-----------|-------------|
| 1 | Valeur absolue | Le nombre lui-même |
| 2 | Nombre de chiffres | Comptage en base 10 |
| 3 | Décomposition décimale | Somme des puissances de 10 |
| 4 | Parité | PAIR / IMPAIR |
| 5 | Primalité | Test de Miller-Rabin |
| 6 | Factorisation première | Trial division + Pollard rho |
| 7 | Somme des chiffres | Et racine numérique |
| 8 | Diviseurs | Liste complète + nombre |
| 9 | Carré parfait | Racine entière exacte |
| 10 | Cube parfait | Racine cubique exacte |
| 11 | Fibonacci | Test par 5n² ± 4 |
| 12 | Palindrome | Lecture identique avant/arrière |
| 13 | Nombre de Harshad | Divisible par somme des chiffres |
| 14 | Base 2 | Binaire |
| 15 | Base 8 | Octal |
| 16 | Base 16 | Hexadécimal |
| 17 | Base 60 | Babyloniens (notation 24:7:43:35) |
| 18 | Notation scientifique | m × 10^n |
| 19 | Log naturel | ln(n) |
| 20 | Racine carrée | Exacte ou approchée |
| 21 | log(n!) Stirling | Approximation factorielle |
| 22 | Nombre parfait | Somme de ses diviseurs propres |

### 🎓 Algorithmes clés

**Miller-Rabin** : test de primalité probabiliste déterministe pour n < 3.3 × 10²⁴. Utilise 12 témoins, complexité O(k × log³n).

**Pollard rho** : factorisation par cycle de Floyd, complexité O(n^(1/4)) en pire cas.

**Newton (BigInt)** : racine carrée par convergence quadratique en ~log(n) itérations.

---

## 🔐 Cryptographie

### 🎯 Vue d'ensemble

| Catégorie | Algorithmes |
|-----------|-------------|
| Hachages classiques | djb2, sdbm, FNV-1a, djb2-64, CRC32 |
| Hachages cryptographiques | MD5, SHA-1, SHA-256, SHA-512, SHA-3 |
| Signatures | HMAC-SHA256 |
| Aléatoire | UUID v4 (RFC 4122) |
| Encodages | Hex, Base64, Binaire |
| Chiffrements | César, ROT13, Vigenère, Atbash, XOR, Bacon |
| Vérifications | Déterminisme, effet d'avalanche |

### 📜 MD5 (RFC 1321)

Empreinte 128 bits. Vecteurs de test :
- md5("") = d41d8cd98f00b204e9800998ecf8427e
- md5("hello") = 5d41402abc4b2a76b9719d911017c592
- md5("The quick brown fox jumps over the lazy dog") = 9e107d9d372bb6826bd81d3542a419d6

⚠️ MD5 est cassé cryptographiquement.

### 🌊 SHA-3 (Keccak-256)

Construction éponge, état 1600 bits, 24 rondes. Vecteurs de test :
- keccak256("") = c5d2460186f7233c927e7db2dcc703c0e500b653ca82273b7bfad8045d85a470
- keccak256("hello") = 1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8

### 🔐 SHA-1 / SHA-256 / SHA-512 (Web Crypto)

Utilise `crypto.subtle.digest()`. Vecteurs de test pour "" :
- SHA-1 = da39a3ee5e6b4b0d3255bfef95601890afd80709
- SHA-256 = e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855

### 🔑 HMAC-SHA256 (RFC 2104)

Formule : HMAC(K, m) = H((K ⊕ opad) || H((K ⊕ ipad) || m)).

### 🎲 UUID v4 (RFC 4122)

128 bits aléatoires, version 4 forcée sur le 7ᵉ octet, variante RFC sur le 9ᵉ.

### 📊 Effet d'avalanche

Test automatique : SHA-256(n) vs SHA-256(n+1). Résultat mesuré : 127/256 bits changés = 49.6% (excellent).

### 🏛️ Chiffrements historiques

| Chiffrement | Époque | Exemple EURO → |
|-------------|--------|----------------|
| César +3 | 58 av. J.-C. | HXUR |
| ROT13 | Moderne | RHOB |
| Vigenère (KEY) | 1553 | OYCK |
| Atbash | Antiquité | VFIL |
| XOR (0x5A) | Moderne | 6f686b6b626b6f |
| Bacon | 1605 | AABBABAB… |

---


<div align="center">

### 🇫🇷 Gunout · 2026

![Made in France](https://img.shields.io/badge/Made_in-France-002395?style=flat-square&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+)
![GitHub](https://img.shields.io/badge/GitHub-gunout-181717?style=flat-square&logo=github&logoColor=white)
![Year](https://img.shields.io/badge/2026-ED2939?style=flat-square&labelColor=FFFFFF)

<sub>© 2026 <strong>Gunout</strong> — Tous droits réservés.</sub>

</div>

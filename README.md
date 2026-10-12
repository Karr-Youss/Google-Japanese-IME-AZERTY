
<h1 align="center">🎌 Google Japanese Input - AZERTY Fix</h1>

<p align="center">
  <b>A custom Romaji table that makes typing Japanese on a French AZERTY keyboard feel native and frictionless.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-Windows-blue?style=flat-square&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Keyboard-AZERTY (FR)-orange?style=flat-square" alt="AZERTY">
  <img src="https://img.shields.io/badge/Language-Japanese-red?style=flat-square" alt="Japanese">
</p>

---

## ❓ The Problem

By default, Google Japanese Input (Google IME) on Windows expects a standard QWERTY layout. While modern Windows operating systems successfully translate the basic `A-Z` keys of an AZERTY keyboard, **it completely breaks punctuation and symbols**.

If you use a French AZERTY keyboard, you know the struggle:
* You have to use frustrating `Shift` combinations just to type basic Japanese periods `。` and commas `、`.
* Typing the Japanese long vowel dash `ー` is a nightmare.
* Standard corner brackets `「` and `」` are almost impossible to trigger naturally.

## 💡 The Solution

This repository provides a custom `romantable.txt` that maps Japanese punctuation, long vowels, and brackets directly to your natural, **unshifted** French AZERTY physical keys. No more fighting your keyboard layout!

---

## ⌨️ Shortcuts & Key Mappings Cheatsheet

Once installed, your keyboard will behave exactly as it should. Here are the optimized mappings (no `Shift` required!):

### 📝 Basic Punctuation
| Physical Key (AZERTY) | Output | Japanese Name |
| :--- | :---: | :--- |
| `,` *(Comma)* | **`、`** | Touten (Comma) |
| `;` *(Semicolon)* | **`。`** | Kuten (Period) |
| `:` *(Colon)* | **`・`** | Nakaguro (Middle dot) |
| `6 / -` *(Dash key)* | **`ー`** | Chōonpu (Long vowel) |

### 🔣 Advanced "Z" Shortcuts
To avoid using `AltGr` (which breaks the IME), use the `z` key combined with another key to instantly type brackets and symbols:

| Type this... | Output | Description |
| :--- | :---: | :--- |
| `z` then `(` *(the 5 key)* | **`「`** | Opening bracket |
| `z` then `)` *(the ° key)* | **`」`** | Closing bracket |
| `z` then `;` | **`…`** | Ellipsis |
| `z` then `-` *(the 6 key)*| **`〜`** | Wave dash |
| `z` then `h / j / k / l` | **`← ↓ ↑ →`** | Directional arrows |

---

## ⚙️ Installation Guide

It takes less than 2 minutes to install. 

1. **Download** the `romantable.txt` file from this repository.
2. Click on the **Google Japanese Input** icon in your Windows taskbar (it usually looks like `A` or `あ`).
3. Select **Properties** (*プロパティ*).
4. Under the **General** (*一般*) tab, look for **Romaji table** (*ローマ字テーブル*) and click **Edit...** (*編集...*).
5. In the new window, click on the **Edit** drop-down menu at the bottom left, then select **Import from file...** (*ファイルからインポート...*).
6. Select the `romantable.txt` you downloaded.
7. Click **OK**, then **Apply**, then **OK**.

🎉 **You're done!** Your AZERTY keyboard is now fully optimized for Japanese.

---

## 🧪 Test Your Setup

Switch your IME to Hiragana mode (`あ`) and type these exact keys to verify your setup is working. **Do not use Shift or AltGr.**

**1. Basic Alphabet Test:**
> **Type:** `w a t a s h i w a q u i z u n i m a y o u` <br>
> **Result:** `わたしわくいずにまよう`

**2. Natural Punctuation Test:**
> **Type:** `a , i i ; s u - p a - : k e - k i` <br>
> **Result:** `あ、いい。すーぱー・けーき`

**3. Brackets & Slang Test:**
> **Type:** `z ( y a t t a z ) w w w w w` <br>
> **Result:** `「やった」ｗｗｗｗｗ`

---

## 🤝 Contributing
Feel free to open an issue or submit a pull request if you have ideas for additional AZERTY-friendly shortcuts or improvements!

## 📜 License
This project is open-source and free to use. Share it with your fellow French/AZERTY Japanese learners!

# Orbit

**An AI helper that lives at your cursor.** Select text in any Windows app, press one shortcut, and pick what you want done with it: translate, explain, rewrite, fix, summarize and more. The answer appears right next to your pointer. Orbit is free.

Website: chwy wa9t :>

## Download

Get the latest installer from the [**Releases** page](../../releases/latest). Download `Orbit-Setup-<version>.exe` and run it.

- **Needs:** Windows 10 or 11, 64-bit.
- **SmartScreen:** the installer is not code-signed yet, so Windows may warn you. Choose *More info*, then *Run anyway*.
- **Updating:** Orbit tells you when a newer version is out (a notification, an item in the tray menu, and a line in Settings, About). Download the new installer, quit Orbit from the tray, and run it. Your settings and API key are kept.
- **Uninstalling:** use *Apps & features* in Windows. Your settings are kept in case you reinstall.

## Get started in 2 minutes

1. **Run Orbit.** It lives in the system tray (bottom right of the taskbar). The first launch shows a short guided tour; you can replay it any time from the tray menu or Settings, About.
2. **Add an AI key.** Open Settings from the tray icon, go to **AI provider**, pick a provider and paste your API key. Press **Test connection** to check it.
   - Supported: Anthropic, Google Gemini, OpenAI.
   - Prefer to stay offline? Choose **Ollama** and a local model, no key needed.
3. **Select some text** in any app: a browser, a PDF, a chat, a document.
4. **Press `Ctrl+Alt+Space`.** A menu of actions opens at your pointer.
5. **Pick an action** with the number keys, or the arrow keys and Enter. `Esc` closes the menu.
6. **Read the answer** in the box that appears beside your pointer.

## Shortcuts

| Shortcut | What it does |
|----------|--------------|
| `Ctrl+Alt+Space` | Open the action menu for the selected text |
| `1` to `9`, arrows, `Enter` | Pick an action in the menu |
| `Ctrl+Alt+C` | Copy the answer |
| `Ctrl+Alt+V` | Replace your selected text with the answer (only when you press it) |
| `Ctrl+Alt+D` or `Esc` | Close the answer box |
| `Ctrl+Alt+R` | Read the selected text aloud (press again or `Esc` to stop) |
| `Ctrl+Alt+T` | Translate the selection into your language, then read the translation aloud |

The three main shortcuts can be changed in Settings.

## What you can do with it

**Actions.** Orbit comes with eight: **Translate, Explain, Examples, Synonyms, Rewrite, Summarize, Fix** and **Simplify**. The menu puts the most useful ones first, depending on whether you selected a word, a sentence, a paragraph, code or a link.

**Make them yours.** In Settings, Actions you can rename, edit or delete any default action (deleted ones can be restored, and edited ones reset), and add up to 4 actions of your own. Write what you want done in plain words, for example *"Reply politely and keep it under 50 words"*. Use `{language}` in a description to insert your target language.

**Two looks for the menu.** Choose **Ring**, a circle of actions around your pointer, or **Stack**, a vertical list beside it, in Settings, General. A short corner-bracket flash around the pointer shows when a shortcut fires; switch it off if you prefer.

**Long answers.** The answer box keeps a fixed size. If the text is longer, press **Show full answer** to open all of it, and **Show less** to fold it back.

**Read aloud.** Orbit can speak the selection or a translation. Voices: Google Gemini, OpenAI, or the voices built into Windows (works offline). Pick the voice and speed in Settings, Voice.

**Languages.** Translate into any of 111 languages. Orbit's own menus and settings are available in English, French, Spanish, German and Arabic.

**Look.** Light and dark themes that follow Windows, or choose one yourself.

**History (optional).** Off by default. If you turn it on, Orbit keeps your recent results on your PC for 7 days, then deletes them. You can search, copy or delete entries in Settings, History.

## Privacy

- Nothing is sent until you pick an action.
- The selected text goes only to the provider you chose. With Ollama it never leaves your PC.
- Your API key is stored encrypted on your PC (Windows data protection) and is only sent to the provider you picked.
- Orbit briefly copies your selection to read it, then restores your clipboard. A clipboard manager may record that copy.
- No account and no tracking. Orbit logs never contain your text.
- Cloud read-aloud voices send the text to Google or OpenAI.
- **Update check:** once a day Orbit asks this repository for the latest release number. It sends no data about you, and you can turn it off in Settings, General, Check for updates.

## Good to know

- Orbit can't read text inside windows running as administrator.
- The installer is unsigned, so SmartScreen shows a warning the first time.
- You need your own API key for Anthropic, Gemini or OpenAI, and those providers may charge for use. Ollama is free.
- Some error messages and screen-reader labels stay in English.

## Help and feedback

This page only hosts the installers. If something doesn't work, open an [issue](../../issues) and say which Orbit version you have (Settings, About).

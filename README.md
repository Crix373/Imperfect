# Imperfect

A clean, custom BetterDiscord theme by Crix.

## Install

1. Download `Imperfect.theme.css`.
2. Open BetterDiscord Settings → Themes → "Open Themes Folder".
3. Drop the file in.
4. Toggle it on in BetterDiscord.

## Host on your own GitHub

1. Create a new **public** repo named `Imperfect` under your GitHub account.
2. Enable GitHub Pages: Settings → Pages → Source: `main` branch → `/root`.
3. Upload the whole bundle to the repo root, preserving structure:
   ```
   Imperfect/
     Imperfect.theme.css
     imperfect.css
     ImperfectTag.css
     README.md
     Components/
       ChannelHeader.css
       ChatArea.css
       Embeds.css
       EmojiPicker.css
       UserArea.css
       WindowsButtons.css
     Addons/
       AccountDetailsGrid.css
       AvatarOnlyMemberList.css
       ColoredLinks.css
       FolderRedesign.css
       FriendGrid.css
       HideAnnoyingElements.css
       IconPackEdited.css
       SettingsModalEdited.css
     Wallpapers/
       (optional)
   ```
4. Open every CSS file and find/replace `YOUR_GITHUB_USERNAME` with your actual GitHub username. (VS Code global replace does it in one shot.)

## Customize the top-left wordmark

Open `Components/WindowsButtons.css` and edit:

```css
content: "‏‏‎ i m p e r f e c t";          /* resting */
content: "‏‏‎ i m p e r f e c t   t h o u g h t";   /* on hover */
```

Keep the invisible bidi characters at the start (`‏‏‎`) — they anchor the text correctly.

---

**Imperfect** — by Crix

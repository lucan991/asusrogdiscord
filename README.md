cd "/mnt/games/GitHub/Discord Themes/asusrogdiscord"

cat << 'EOF' > README.md
# ASUS ROG - Republic of Gamers (Discord Theme)

A dark carbon & crimson neon theme inspired by **ASUS Republic of Gamers (ROG)** aesthetics for **Vencord** and **BetterDiscord** (forked and customized from *Lande della Discordia* by `ungiglio`).

![https://i.imgur.com/R68Se3G.png](https://lucan991.github.io/asusrogdiscord/awkglass/assets/preview.png)

## Features
- **Dark Carbon & Crimson Neon** color palette (`#ff0028`) with a custom ROG motherboard background.
- Full styling support for the **Spotify Controls** plugin (Vencord / BetterDiscord).
- Custom ROG Home icon and top title bar branding (`REPUBLIC OF GAMERS`).
- Performance-optimized with blur disabled by default (`--app-blur: 0px`) to prevent UI lag.

## Installation
1. Download [`ASUS-ROG.theme.css`](https://raw.githubusercontent.com/lucan991/asusrogdiscord/main/ASUS-ROG.theme.css) (Right-click -> *Save Link As...*).
2. Move the file into your client's themes folder:
   - **Vencord (Linux):** `~/.config/Vencord/themes/`
   - **BetterDiscord (Linux):** `~/.config/BetterDiscord/themes/`
   - **Windows:** `%appdata%\Vencord\themes\` or `%appdata%\BetterDiscord\themes\`
3. Open Discord -> **User Settings** -> **Themes** and enable **ASUS ROG - Republic of Gamers**.

## Customization
You can easily swap the wallpaper or adjust colors inside the `:root` block of `ASUS-ROG.theme.css`:
- `--custom-image-url`: Replace the URL to use your own background image.
- `--app-blur`: Increase from `0px` (e.g., `4px` or `8px`) if you want a frosted glass background effect.

---
*Credits: Base theme structure by [ungiglio/DiscordDiscordia](https://github.com/ungiglio/DiscordDiscordia)*
EOF

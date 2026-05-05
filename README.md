<img src="Pictures/wallpaper1.jpg">

<h1 align="center">Dotfiles (Arch + Hyprland)</h1>

<p align="center">My personal Linux configuration setup (Hyprland + Arch).</p>

<h2>📦 Setup</h2>
<ul>
    <li><b>WM:</b> Hyprland</li>
    <li><b>Bar:</b> Waybar</li>
    <li><b>Shell:</b> zsh</li>
    <li><b>Terminal:</b> kitty</li>
    <li><b>Launcher:</b> rofi</li>
    <li><b>File Manager:</b> yazi / dolphin</li>
    <li><b>Theme:</b> custom (colors + fonts)</li>
</ul>

<h2>📁 Structure</h2>
<pre>
├── hypr/
├── waybar/
├── rofi/
├── kitty/
├── zsh/
└── assets/
</pre>

<h2>⚙️ Installation</h2>

<h3>1. Clone</h3>
<pre>
git clone https://github.com/your-username/dotfiles.git
cd dotfiles
</pre>

<h3>2. Copy configs</h3>
<pre>
cp -r hypr ~/.config/
cp -r waybar ~/.config/
cp -r rofi ~/.config/
cp -r kitty ~/.config/
cp zsh/.zshrc ~/
</pre>

<p>Or using stow:</p>
<pre>
stow .
</pre>

<h2>🔧 Dependencies</h2>
<pre>
sudo pacman -S hyprland waybar rofi kitty zsh git
</pre>

<p>Additional:</p>
<ul>
    <li>Nerd Fonts</li>
    <li>Papirus Icons</li>
    <li>wl-clipboard</li>
    <li>grim / slurp (screenshots)</li>
    <li>pipewire (audio)</li>
</ul>

<h2>🧠 Features</h2>
<ul>
    <li>Minimal and fast</li>
    <li>Keyboard-driven workflow</li>
    <li>Highly customizable</li>
</ul>

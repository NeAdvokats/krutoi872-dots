<img src="https://github.com/NeAdvokats/krutoi872-dots/blob/main/image.png?raw=true" />

```bash
mkdir -p ~/.config ~/walls && git clone https://github.com/NeAdvokats/krutoi872-dots ~/krutoi872-dots && for d in alacritty mango rofi; do [ -e ~/.config/$d ] && mv ~/.config/$d ~/.config/${d}.backup_$(date +%Y%m%d_%H%M%S); ln -s ~/krutoi872-dots/$d ~/.config/$d; done && cp ~/krutoi872-dots/wall1.png ~/walls/wall1.png && echo -e "\n\033[0;32m Установка успешно завершена! \033[0m"
```

# Настройка Astrovim

1. Создать директорию C:\Users\user\.config\nvim
2. `git clone --depth 1 https://github.com/AstroNvim/AstroNvim C:\Users\user\.config\nvim`
3. `setx XDG_CONFIG_HOME "C:\Users\user\.config"`
4. `git clone https://github.com/dmitriybo/astrovim-config C:\Users\user\.config\nvim\lua\user`

## Установка Starship Shell

1. winget install starship
2. В Powershell ввести `echo $PROFILE`
3. В выведенный файл вставить `Invoke-Expression (&starship init powershell)`

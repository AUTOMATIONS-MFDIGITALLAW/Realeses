# Repositorio para Robos

***LEIA COM ATENÇÃO***

Aqui ficara todos os instaladores de robos da ***Meireles E Freitas***.

>Apenas instaladores e todos na aba de ***Realese*** a direita do git.

Em caso de mudança de codigo ou alterações como: ***Login, Senhas, imagens***, ***NÃO MUDARÁ AUTOAMTICAMENTE NESSE REPOSITORIO***.
lembrar de buildar novamente o instalador para a nova versão dele.

Maior parte dos instaladores são utilizado o PyInstaller, abaixo deixarei o codigo de sugestão para buildar o codigo novamente:
***Lembre de mudar o nome do arquivo e pastas do seu projeto***

`pyinstaller --onedir --hidden-import "flet_desktop" --hidden-import "pyautogui" --add-data "img;img" --add-data "function;function" --add-data "src;src" --add-data "Task;Task" --add-data ".env;." --icon=nomedoicone.ico --name NomeParaAplicação  main.py` 

Se você deseja um novo instalador, instale "InnoSetup", este é um programa para criar novos instaladores :
[How to make a installer](https://www.youtube.com/watch?v=5U-nBAfbSek)

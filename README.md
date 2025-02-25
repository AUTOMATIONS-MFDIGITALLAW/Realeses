# Repositorio para Robos

***LEIA COM ATENÇÃO***

Aqui ficarão todos os instaladores dos robôs da ***Meireles & Freitas***.

>Somente os instaladores serão armazenados aqui, e todos estarão disponíveis na aba ***Releases***, à direita no GitHub.

***⚠️ Importante:***

Qualquer alteração no código, como ***login, senhas, imagens ou outras modificações, NÃO SERÁ ATUALIZADA AUTOMATICAMENTE NESTE REPOSITÓRIO***.
Sempre que houver mudanças no código, ***é necessário gerar uma nova versão do instalador***.

***🔧 Como gerar um novo instalador:***

A maioria dos instaladores é criada usando ***PyInstaller***. Abaixo está um comando sugerido para gerar um novo instalador:

📌 ***Lembre-se de alterar o nome do arquivo e das pastas do seu projeto antes de executar!***

`pyinstaller --onedir --hidden-import "flet_desktop" --hidden-import "pyautogui" --add-data "img;img" --add-data "function;function" --add-data "src;src" --add-data "Task;Task" --add-data ".env;." --icon=nomedoicone.ico --name NomeParaAplicação  main.py` 

***📦 Criando um instalador:***

Se precisar gerar um ***novo instalador***, utilize o programa ***Inno Setup***.
Este software permite criar instaladores personalizados para seus robôs.

Para mais informações, ***procure por "How to make an installer using Inno Setup"***.

🚀 Lembre-se de sempre buildar o instalador novamente após qualquer atualização no código!:

[How to make a installer](https://www.youtube.com/watch?v=5U-nBAfbSek)

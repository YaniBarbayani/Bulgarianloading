BC_LOADING за QBCore / FiveM

Инсталация:
1. Качи папката bc_loading в resources/[standalone]/
2. Добави в server.cfg:
   ensure bc_loading
3. Спри друг loading screen ресурс, ако имаш такъв.
4. Смени html/assets/background.jpg с твоя снимка 1920x1080.
5. Сложи MP3 файл на html/assets/music.mp3.
6. Смени Discord адреса, текстовете и екипа в html/index.html.

Важно:
Файлът client.lua затваря loading screen при стартиране на мрежовата сесия.
За по-късно затваряне премахни loadscreen_manual_shutdown и client.lua.

Името на ресурса няма значение, но не оставяй два loading screen ресурса включени едновременно.

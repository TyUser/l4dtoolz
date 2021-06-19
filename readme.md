# l4dtoolz

<p>Метамод плагин игры L4D1 и L4D2. Нужен для расширения количества слотов.</p>

* Оригинальный исходник: [github.com/ivailosp/l4dtoolz](https://github.com/ivailosp/l4dtoolz/)
* Пожелания и предложения: [forums.alliedmods.net](https://forums.alliedmods.net/showthread.php?t=93600)

Сборка под debian 8 x32:
* mkdir -p alliedmodders
* cd alliedmodders
* git clone --depth=1 --branch=l4d2 https://github.com/alliedmodders/hl2sdk hl2sdk-l4d2
* git clone --depth=1 --branch=1.10-dev https://github.com/alliedmodders/metamod-source mmsource-1.10
* git clone --recursive https://github.com/TyUser/l4dtoolz
* cd l4dtoolz
* make -f l4d2_make

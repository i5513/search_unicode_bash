# search_unicode
* Inspired on http://pusling.com/blog/?p=451
* Implemented with bash
# Usage
```
$ ./search_unicode -h
For each term search unicode character where its definition contain the term.
Usage: ./search_unicode [-h] [-l] [-r] term1 term2
	-h this help
	-l large description
	-r choose a random character
```
## Examples:
```
$ ./search_unicode -l " car " " bus "
⛍ 26CD;DISABLED CAR;So;0;ON;;;;;N;;;;;
⛐ 26D0;CAR SLIDING;So;0;ON;;;;;N;;;;;
𐕂 10542;CAUCASIAN ALBANIAN LETTER CAR;Lo;0;L;;;;;N;;;;;
🏎 1F3CE;RACING CAR;So;0;ON;;;;;N;;;;;
🚃 1F683;RAILWAY CAR;So;0;ON;;;;;N;;;;;
🚋 1F68B;TRAM CAR;So;0;ON;;;;;N;;;;;
🚓 1F693;POLICE CAR;So;0;ON;;;;;N;;;;;
🚔 1F694;ONCOMING POLICE CAR;So;0;ON;;;;;N;;;;;
🚌 1F68C;BUS;So;0;ON;;;;;N;;;;;
🚍 1F68D;ONCOMING BUS;So;0;ON;;;;;N;;;;;
🚏 1F68F;BUS STOP;So;0;ON;;;;;N;;;;;
$ ./search_unicode -r " car " " bus "
𐕂
🚍
$ ./search_unicode " car " " bus "
⛍ ⛐ 𐕂 🏎 🚃 🚋 🚓 🚔
🚌 🚍 🚏
```



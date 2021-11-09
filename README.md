# D2R-YouCha-MOD

## 적용 화면

![](/images/ex1.jpg?raw=true)

![](/images/ex2.jpg?raw=true)

![](/images/ex3.jpg?raw=true)

![](/images/ex4.jpg?raw=true)

![](/images/ex5.png?raw=true)

![](/images/ex6.png?raw=true)

![](/images/ex7.png?raw=true)

1. 아이템 이름 및 옵션 강조  
   소켓 O, 에테, 고급 → 흰색  
   소켓 X, 에테 X, 일반, 손상된 → 회색  
   골드 및 기타 → 회색  
   주요 접미, 접두 → 주황색  
   주요 옵션 → 주황색

   ```
   윗첨자 숫자 : 주요 소켓 수 (일반)
   윗첨자 E : 에테일때 사용
   윗첨자 M : 비싼 매직아이템 존재
   윗첨자 R : 비싼 레어아이템 존재
   윗첨자 U : 주요 유니크 아이템 존재
   윗첨자 S : 주요 세트 아이템 존재
   ```

2. 용병 위치  
   소환수 및 용병 체력 바 위 오른쪽으로 표시  
   파티원들 왼쪽 아래부터 위로 표시 (16:9 이하일시 미표시 가능)
3. 도움말 및 호라드릭  
   룬워드, 패캐, 아이템 정보 Hover 시 Tooltip 표시  
   호라드릭 큐브에 주요 레시피 표시
4. 아이콘 변경  
   룬 : 숫자+이름  
   대용량 체력, 마나 포션 크기 변경
5. 드랍 아이템 크기 변경  
   기존 36에서 28로 축소

## 설치 방법

![](/images/how1.png?raw=true)

![](/images/how2.jpg?raw=true)

1. 디아2레저렉션 폴더안에 mods 폴더를 만듬.
1. mods 폴더에 압축을 품 (디아2/mods/YouCha/YouCha.mpq)
1. 명령인수줄추가 -mod YouCha -txt (-mod앞 공백 1칸)
1. 재접속 해야함

[다운로드](https://github.com/chanha0406/D2R-YouCha-MOD/archive/refs/heads/main.zip)  
[스마트키](https://github.com/chanha0406/D2R-SmartKey.git)

## 경로

1. 폰트 사이즈 수정

```
./YouCha.mpq/data/global/ui/layouts/_profilehd.json
```

![](/images/path1.jpg?raw=true)

> TooltipFontSize 가 아이템 드랍 폰트 사이즈 입니다.

2. 큐브 스킨

```
./mods/YouCHa/YouCHa.mpq/data/hd/global/ui/controller

./mods/YouCHa/YouCHa.mpq/data/hd/global/ui/panel
```

3. 도움말

```
./mods/YouCha/YouCha.mpq/data/global/ui/layouts/helppanelhd.json

./mods/YouCha/YouCha.mpq/data/hd/global/ui/panel/help_recipe.sprite

./mods/YouCha/YouCha.mpq/data/hd/global/ui/panel/help_recipe.lowend.sprite
```

4. 아이템 옵션

```
./mods/YouCha/YouCha.mpq/data/local/lng/strings/item-modifiers.json
```

5. 폰트 변경

```
./mods/YouCHa/YouCHa.mpq/data/hd/ui/fonts/kodia.ttf

./mods/YouCHa/YouCHa.mpq/data/hd/ui/fonts/irisl.ttf

./mods/YouCHa/YouCHa.mpq/data/hd/ui/fonts/blizzardglobaltcunicode.ttf
```

> blizzardglobaltcunicode.ttf - 채팅창 폰트

6. 룬드랍 사운드

```
./YouCHa/YouCHa.mpq/data/hd/global/sfx/item/item_rune_hd.flac
```

7. 웨이와 지역맵 TC, 룬표시

```
./mods/YouCHa/YouCHa.mpq/data/local/lng/strings/levels.json
```

8. 툴팁

```
./mods/YouCha\YouCha.mpq\data\local\lng\strings\ui.json
```

> id 4169, 4170, 4171, 4173

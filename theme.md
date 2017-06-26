### 테마
* Android 6.0 이상에서는 어플에서 테마파일을 불러오기 위해 저장권한이 필요합니다.

### 예시
1. `clien` 폴더를 생성 후 `custom.json` 파일에 다음 내용을 추가합니다.
```json
{
  "parent": "light",
  "scheme": {
    "text_color": "#f06595",
    "bg_color": "#fff0f6",
    "alt_text_color":"#d6336c",
    "alt_bg_color":"#fcc2d7",
    "disabled_text_color":"#adb5bd",
    "divider_color":"#e64980",
    "toolbar_bg_color":"#c2255c",
    "status_bar_color":"#a61e4d",
    "spinner_color":"#a61e4d",
    "list_notice_bg_color":"#ffdeeb",
    "bottom_toolbar_bg_color":"#fcc2d7"
    }
}
```
2. 어플 실행 후 custom 테마를 선택하시면...
![custom](https://hu9678.github.io/aaa.png)

3. `parent`는 변경할 테마를 `light`, `dark`, `black` 중 한가지를 선택할수 있고, `scheme`에는 변경할 테마 키값을 `#argb` 형태로 지정합니다.

4. 전체 키값은
[light](https://hu9678.github.io/color_scheme_light.json) [dark](https://hu9678.github.io/color_scheme_dark.json)
[black](https://hu9678.github.io/color_scheme_black.json)
에서 확인하실수 있구요.. 각 키값 설명은 추후에 붙이겠습니다;;

4. `..._bg_color`와 `..._divider_color`는 `null`값을 허용합니다.
```json
"list_divider_color": "null"
```
-> 게시물 목록 구분선을 없앱니다.


#### 계속 업데이트하겠습니다 ㄷㄷㄷ

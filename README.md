# vrchat-world-data

DIGIWB's Planet VRChat 월드가 실행 중에 읽어 가는 데이터입니다. 여기 파일을 고치면 월드를 다시 업로드하지 않아도 반영됩니다(이미 월드에 들어와 있는 사람은 재입장 후).

GitHub Pages(`main` 브랜치, 루트 폴더)로 공개되며 월드는 아래 주소를 읽습니다.

| 파일 | 주소 | 용도 |
|---|---|---|
| `r18-whitelist.txt` | https://furpark-community.github.io/vrchat-world-data/r18-whitelist.txt | R-18 갤러리 출입 명단 |
| `tools/r18-hash.html` | https://furpark-community.github.io/vrchat-world-data/tools/r18-hash.html | 명단용 해시 생성기 |

## R-18 명단에 사람 추가하기

1. `tools/r18-hash.html` 을 열고 그 사람의 VRChat **표시 이름**을 정확히 입력합니다.
2. 나온 해시를 `r18-whitelist.txt` 에 한 줄로 추가하고 커밋합니다.
3. 1~2분 뒤 Pages 에 반영되면, 월드 안에서는 R-18 문을 한 번 누르면 바로 열립니다.

명단 파일에는 이름 대신 해시만 들어가므로 누가 출입할 수 있는지 공개되지 않습니다.
표시 이름을 바꾸면 해시도 바뀌므로 다시 추가해야 합니다.

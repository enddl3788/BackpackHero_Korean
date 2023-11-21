<div style="border: 2px solid #aaa; border-radius: 12px; overflow: hidden;">
    <img src="https://i.ytimg.com/vi/iUaUem4kWLw/maxresdefault.jpg" alt="BackpackHero" style="width: 10% align="center"; height: auto;">
</div>

# BackpackHero 한글 패치

이 프로젝트는 BackpackHero 의 한글 패치를 제공합니다.<br>
기존 한글패치의 문제점, 번역 미적용 문제를 해결했습니다.<br>
직접 번역하여 오역이 있을 수 있습니다!

+ 현재 시청 건물에서 건물 이름이 □으로 표기되는 문제가 있음. 게임 파일에서 그 부분에만 korean 폰트가 적용되지 않은것으로 예상함. 이 경우 저의 능력 부족으로 변경 불가능.
+ 깃허브 LFS 사용법이 까다로워, 다운로드 방법을 구글 드라이브로 이동하였습니다.

## 패치 적용 방법

1. 게임을 최신 버전으로 업데이트하세요.
2. [[구글 드라이브로 이동]](https://drive.google.com/file/d/1V1YYwgPo43C3ipv7KFbaSyxa3tpoj_t1/view?usp=sharing) 좌측 링크를 클릭하여, 한글 패치 파일을 다운받으세요.
3. 'Backpack Hero_Data.zip' 파일을 압축 해제 하세요.
4. Steam 라이브러리에서 Backpack Hero를 우클릭하여 '관리 -> 로컬 파일 보기' 를 클릭하세요.
5. SteamLibrary\steamapps\common\Backpack Hero 폴더가 열리는데,<br>
   다운받은 'Backpack Hero_Data' 폴더를 붙여넣기 하여 '덮어쓰기'를 하세요.
6. 게임을 실행하고 환경설정에서 '언어 - KOREAN' 을 선택하고, 변경된 내용을 확인하세요.

## 주의 사항

- 패치를 적용하고 문제가 생긴다면<br>
  Steam 라이브러리에서 Backpack Hero를 우클릭하여 '속성 -> 설치된 파일 -> 무결성 검사' 를 클릭하여, 재설정하세요.
- 이 패치는 게임 버전 v1.0.907.1 에 대해 테스트되었습니다.
- 문제가 발생할 경우 이슈를 생성해주세요.

## 기여

기여는 언제나 환영합니다! 버그를 발견하거나 기능을 추가하고 싶다면 풀 리퀘스트를 보내주세요.

## 번역 방법
1. '\Backpack Hero_Data\StreamingAssets\Language\translations\Korean.csv' 파일을 엑셀로 연다.
2. 아래 표와 같은 형식으로 번역한다. <br>

| Category | Key | English | Korean | Notes |
|:---------:|:--------:|:---------:|:---------:|:---------:|
| 카테고리| 아이템 ID| 영어| 한글| 주석|
| items| ACIDIC POTION| ACIDIC POTION| 산성 물약| # ACIDIC = 산성|

3. 이슈를 통해 업로드 또는 이슈를 통해 오역을 지적해준다.
- pressToStart 에서 /x 이 아닌 'Press /x '로 해야 적용됨

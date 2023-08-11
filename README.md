# TermProject - 게임 순위 데이터 분석(Python) 

## 프로젝트 소개

- 'Steam', '게임메카', 'newzoo', '게임트릭스'의 데이터를 분석하여 국내와 국외 게임 순위를 분석한다.

## 기술 스택
`jupyterNotebook`, `Python` - `beautifulSoup`,`pandas`,`maplotlib`,`selenium`

### `Steam`

- 데이터 획득 : 스팀의 게임 순위는 해당 게임의 동접자 수를 기준으로 한다.
<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/3a340435-7cf5-4e13-9e6c-0f874a3cf00b" width="400" height="400">
</p>

##

<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/cef5cc7b-ce21-42eb-bc8d-0caacd04a7c3" width="400" height="200">
</p>


### `GameMeca`

- 데이터 획득 : 게임메카 홈페이지 사용자들의 투표를 기준으로 한다.
- `BeautifulSoup`
<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/44df53e3-5882-4e15-a437-ffc8ae8a4cb7" width="400" height="400">
</p>

##

<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/67223d1d-d794-454e-a628-ce0ba61e82e6" width="600" height="200">
</p>

### `newzoo`

- 데이터 획득 : newzoo는 전세계 게임의 순위를 플레이 횟수, 스트리밍 횟수로 나누어 순위를 알려준다.
<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/5e4790fd-5ffc-4b77-b2a6-8a9c807df297" width="400" height="400">
</p>

##

<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/2f44c271-bb63-4024-a345-851ab951707a" width="400" height="200">
</p>

### `GameTrics`

- 데이터 획득 : 게임트릭스에서는 pc방 점유율을 기준으로 순위를 정한.
<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/5fdbe65c-97eb-4a54-b973-30fd2832c99d" width="400" height="400">
</p>

##

<p align="center">
  <img src="https://github.com/GyuHyeokjjookki/GameRankingPython/assets/112180318/2a95a9f8-c481-4ade-94cf-e6e7a0e89f5b" width="400" height="200">
</p>

# 참고문헌

- 스팀 게임순위 : https://store.steampowered.com/stats/
- 게임메카순위: https://www.gamemeca.com/ranking.php
- Newzoo 게임순위(플레이): https://newzoo.com/insights/rankings/top-20-core-pc-games/
- Newzoo 게임순위(스트리밍): https://newzoo.com/insights/rankings/top-games-twitch-youtube/
- 게임트릭스: http://www.gametrics.com/rank/Rank02.aspx


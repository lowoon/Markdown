# 블랙잭
### 기능목록
- **화면**
1. 게임에 참여 플레이어 이름 입력받는다.
	- **쉼표(,)** 를 기준으로 분리
1. 플레이어 별로 배팅금액 입력받는다.
	1. 플레이어와 딜러들의 카드 출력한다.
	1. 플레이어들에게 카드를 더 받을 것인지 입력받고 카드들을 출력한다.
	1. 딜러의 카드 결과 16이하이면 한장의 카드를 더 받았다고 출력한다.
	1. 플레이어와 딜러의 최종 카드들과 결과를 출력한다.
	1. 최종 수익을 출력한다.
	
- **실행**
1. 플레이어와 딜러에게 랜덤으로 2개의 카드를 준다.
	- 전체 카드에서 나누어지기 때문에 그 카드를 다시 줄 수 없다.
1. 플레이어가 카드를 더 받는다고 하면 랜덤으로 1개의 카드를 더 준다.
1. 딜러의 카드가 16이하이면 카드를 더 받고 17이상이면 멈춘다.

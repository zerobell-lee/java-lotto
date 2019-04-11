# 3주차 미션 - 로또

## 기능

### Main -> getMoney() 

구매 금액을 입력받는 메소드.

### Lotto -> getNumbers()

numbers에 대한 getter

### Lotto -> hasNumber()

Lotto 객체가 해당 int를 가지고 있는지 판별하는 메소드.

### WinningLotto -> Match()

입력받은 로또와 우승 번호를 매칭시키는 메소드.
매칭된 수로 적절한 Rank를 반환

### Main -> initNumSeq()

무작위 숫자 생성을 위한 numSeq을 추가했다.
그러므로 numSeq를 1부터 45의 수를 가지는 배열로 초기화해주는 메소드를 추가함.

### Main -> shuffleNumSeq()

numSeq을 무작위로 섞어주는 메소드.

### Main -> buyLotto()

로또를 구매하는 메소드. Random 번호를 생성하여 Lotto를 생성한다.

### Main -> buyMultipleLotto()

입력된 횟수만큼 로또 구매를 반복하는 메소드.

### Main -> separateToList()

입력받은 String을 ,로 분리하여 Integer의 List로 반환하는 메소드.

### Main -> getWinningLotto()

인자를 입력받아 당첨에 해당하는 Lotto를 생성하는 메소드.

### Main -> matchLottos()

winningLotto와 lottoList를 반복하면서 매칭해보는 메소드.
각 랭크를 추가한다.

### Main -> initRankMap()

rankMap을 각자 rank,0의 pair로 초기화시켜주는 메소드.

### Main -> formatRank()

rank를 보기 쉬운 string 형태로 변환하는 메소드.

### Main -> calculateBenefit()

로또로 얻은 금액을 계산하는 메소드.

### Main -> printResult()

매칭결과를 계산하여 그것을 출력해주는 메소드.
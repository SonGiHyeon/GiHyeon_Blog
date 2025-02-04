# GiHyeon_Blog

## 25.01.31 - OT

- OT
    - 전반적인 채용시장
    - 커리큘럼
    - 어떠한 채용 전략을 가지고 있는지
    - Github 사용법(마크다운 포함)
    - CLI

## 25.02.03 - 블록체인 역사와 개념 및 금융시장에 대한 이해

전반적인 블록체인의 역사와 개념 및 과거에서부터 현재까지의 금융시장과 그에 따른 비트코인의 등장 배경에 대해서 알아본 시간이였다.

아래는 상세한 정리본

- ### 사이버펑크 선언문

        무언가를 숨기기 위해서는 암호화와 암호화된 서명이 필요하다.
        
        정보는 이용 가능한 저장 공간을 채우기 위해서 확장되어 왔다.
        
        지식은 합의를 필요로 한다. 정보는 암호화 될 수 없다.

        사이버펑크는 코드를 사용한다. 비밀을 보호하기 위해서 소프트웨어를 사용한다. 
        소프트웨어는 널리 퍼져있는 장점이 있다. 
        사용자가 허용하지 않는 한 접근할 수 없다.
    
        사이버펑크는 암호학에서의 규제를 비판한다.
    
        사이버펑크는 익명 체계를 만들어냈으며, 익명과 디지털 서명 그리고 전자 돈을 사용해서 비밀을 막아왔다.

- ### Before going in…

블록체인 => 혁신적인 기술? 탈중앙화? 무결성? 제일 중요한 것은 ‘신뢰’이다.

블록체인은 신뢰가 뒷받침 되어야 하는 기술이다.

- ### 비트코인은 최초의 블록체인이 아니다?

최초의 블록체인 아이디어: 디지털 문서의 타임 스탬프를 보장하기 위한 아이디어 
=> 스튜어트 하버 & 스콧 스토네타 제안

1989년 저명한 연구자의 ‘연구’ 결과가 조작된 것이라는 스캔들을 봄 => 다른 잉크 사용
=> 디지털 기록의 중요성 절감 => ‘디지털 기록의 불변성’에 대한 공동 연구 시작

‘연구’ => 시스템(서버): 해시 + 디지털 서명 
=> 데이터를 해시 -> 해시된 데이터를 타임스탬프 권한을 이용해서 기록 -> 타임스탬프 정보에 디지털 서명 -> 서명된 결과로 인해 ‘특정 시점에 이미 존재하던 데이터’임을 증명

시스템: 데이터들이 하나의 블록에 저장, 새로운 블록의 해시값은 이전 블록의 해시값을 포함함

두 연구자들은 이를 “문서 체인의 연결”이라는 문구를 논문에 인용하면서 ‘블록체인’이라는 용어가 사용됨

    1. 블록이라는 단위에 데이터가 담겨있음(데이터가 블록에 있음)
    2. 블록이 순서를 가지고 연결됨(블록의 해시값을 담고 있는 모습)

- ### 화폐의 역사

물건이 지니는 가치가 ‘교환’할 때마다 달라진다. 서로의 요구사항이 맞지 않으면 물건을 교환하지 못할 수도 있다.

### 1 - 실물 화폐

물건을 교환하는게 불편해짐 -> 특정 물건을 ‘화폐’로 정함 => 실물화폐

Ex) 조선시대의 실물화폐: ‘쌀’

실물화폐의 ‘문제점’

    1. 내구성이 없음
    2. 상품의 질이 같지 않음
    3. 휴대성이 없음	

=> 문제점들을 보완하기 위해서 ‘금속화폐’가 등장함

### 2 - 금속화폐 & 지폐

문제점: 산업과 기술의 발달 => 그 어떤 자원도 모든 금속 화폐를 공급하는게 불가능해짐
=> 동, 알루미늄, 니켈, 주석 등의 소재가 보조화폐가 되었고, 이후 중국에서 종이가 개발됨

### 3 - 신용 화폐

금속 => 실물 가치로서 교환하는 물건의 가치와 같을 수 없음 -> 가치 보장 ‘장치’ 필요

장치 => ‘국가’ => 사회적 신뢰나 국가의 법적 권위를 바탕으로 통용되는 화폐

발행 주체에 대한 ‘신용(신뢰)’이 가치의 근간이 된다.

신용화폐 => 신용을 매개로 한 실물이 없는 화폐 => 통제가 힘들어서 강력한 중앙기관의 통제가 필요하다.

### - 화폐가 가지는 특성 5가지

    1. 휴대성
    2. 가분성
    3. 내구성
    4. 동질성
    5. 가치의 안정성

### - 화폐의 3대 기능

    1 - 교환의 매개체 => 물물교환의 불편함을 없애고 보다 편히 물건을 교환할 수 있도록하는 기능
    
    2 - 가치 척도의 기능 => 화폐가 어떤 물건의 가치를 재는 ‘잣대’로써 기능하는 것
    
    3 - 가치 저장 기능 => 가치를 저장하는 수단

### - 화폐의 기능으로 본 암호화폐

화폐로서의 비트코인

    1. 교환의 매개체로서는 아직 부족하다 => 공식적인 방법을 통해 비트코인으로 물건을 살 수 있는 가게를 찾기 힘들기 때문
    2. 가치 척도 기능도 부족하다 => 큰 변동폭 때문
    3. 가치 저장 수단으로서 그나마 쓰이고 있다.(예를 들어 대한민국에서 ‘가상 자산’으로 인정한 부분)

### - 신용 창출(Credit Creation)

신용 창출(Credit Creation) => 은행을 통해 국가에 유통되는 ‘화폐 총량’이 늘어나는 현상

예금 창조(Deposit Creation) => 은행의 ‘신용’과 ‘예금’을 통해 유통되는 화폐의 양이 늘어나는 현상

    ‘본원통화’ => 한국은행이 직접 발행한 돈
    
    ‘지급준비금’ => 은행이 보유하고 있는 예금의 일정 부분(ex) 5%)을 지급준비금으로 보관하고, 나머지 금액(95%)만으로 대출을 해주는 것

시중은행이 예금된 금액을 사용해서 전체 통화량을 불리는 방법: 예금 -> 지급준비금을 제외한 나머지 금액 대출 -> 예금 -> 지급준비금을 제외한 나머지 금액 대출 반복
=> 신용이라는 힘이 화폐 가치를 증폭시키는 새로운 동력으로 작동하고 있다

### - 세계 금융 위기

서브프라임 모기지(Subprime mortgage)

2000년대 초반에 미국의 여러 가지 악재들로 인해 경기가 악화되자 경기부양책으로 초 저금리 정책을 펼치게 된다. 

당시 주택 가격을 아주 높인 상승률을 보이고 있는 상태 => 신용 등급이 낮은(Subprime)사람에게도 주택 담보로 대출(Mortgage)해주는 시스템이 생기게 되었다.

2004년 미국의 경제가 회복세에 접어듬 -> 초저금리 정책 종료 -> 서브프라임 사람들의 대출 상환 능력이 부족하게 되어서 결국 이 시스템을 유지하도록 하던 고객들의 능력이 안되자 결국 부동산 버블이 터져서 연쇄 파산으로 이어지며 세계 금융 위기가 시작되었다.
또한 대다수의 금융 회사들이 모기지 채권을 가지고 있었기 때문에 금융회사들도 엮여서 파산하게 된다.

### - 양적 완화

미국 연방준비제도(Fed)의 경기 침체 해결 방안

1. 재정 정책: 구제금융(Bailout) => TARP(Troubled Asset Relief Program): 부실자산(주로 서브프라임 모기지 관련 파생상품)을 보유한 대형 금융회사에 공적 자금을 투입
2. 경기부양책(Stimulus Package) => 오바마 행정부 초기(2009) 대규모 재정 지출(인프라 투자, 일자리 창출 프로그램 등)을 실행
3. 통화 정책: 양적 완화(Quantitative Easing: QE)와 초저금리
    - 초저금리: 정책금리를 거의 0% 수준으로 낮춰, 시중은행의 차입비용을 극도로 낮추는 것
    - 양적완화: 연방준비제도에서 화폐를 계속해서 찍어낸다 -> 찍어낸 화폐로 서브프라임 모기지에 있던 국채나 주택저당증권(MBS) 등을 대규모로 매입한다 => 시장에 많은 유동성 공급, 금리가 낮아짐, 기업 or 가계가 대출을 받을 수 있어서 경기 활동 활성화

### - 양적 완화 리스크

    1. 자산 가격 버블
    2. 인플레이션 위험
    3. 부의 양극화 심화
    4. 달러 가치 하락과 환율 문제
    5. 금융 시스템 왜곡
    6. 정책 의존성 증가
    7. 국제적 불균형 확대

### - 암호화폐의 등장(비트코인)

서브프라임 모기지 사태의 원인
    => 기관들의 판단에 의해 서브프라임 모이기 사태 발생
    => 국가의 사태 해결 정책으로 인해 의도치 않은 영향 발생

이러한 중앙화 시스템에 문제점이 있다고 인식하면서 이러한 시스템에 저항하는 사이버 운동을 준비하게 된다.

- 사이버 펑크(Cypher punk)

‘사이버 펑크’ => 개인의 프라이버시를 중요시 생각해 온 사람들

### - 주요 인물

    데이비드 차움: 디지털 서명을 활용해 익명의 전자화폐 개념을 제안
    웨이 다이: 탈 중앙화된 전자 화폐 시스템의 개념적 초안을 마련
    닉 재보: 작업 증명(Proof of Work)을 활용한 디지털 화폐의 설계 아이디어를 구현함

### - 사토시 나카모토의 등장

2008년 10월 31일 사이버 펑크 메일 리스트에 “Bitcoin P2P e-cash paper”라는 이름의 메일이 등장

메일 안에는 9쪽짜리 비트코인 백서(“Bitcoin: A Peer-to-Peer Electionic Cash System”)가 담겨 있었다

2009년 1월 첫 번째(제네시스 블록) 채굴을 시작으로 소스 코드 공개와 함께 세상에 처음 나왔다.

제네시스 블록 안에는 특별한 메세지가 있었다.

    “The Times 03/Jan/2009 Chancellor on brink of second bailout for banks”
    => The Times 2009/01/03 영국 재무주 장관의 은행에 대한 두 번째 구제금융

위의 메세지는 다음과 같은 의미를 내포했을 것으로 추측된다.

    1. 중앙화 금융 시스템에 대한 비판
    2. 탈중앙화 금융의 대안 제시
    3. 역사적 맥락을 기록

## 25.02.04 - 해시의 역할과 기능, 디지털 서명의 역할과 기능

### - Before going in…

스튜어트 하비와 스콧 스토네타가 고안한 블록체인은 암호화폐를 위한 것이 아닌 디지털 문서에 보장된 타임 스탬프를 찍기 위함이다.

### - 해시(Hash) => 타임 스탬프

해시(Hash)란? 데이터를 압축한 고정된 크기의 출력값(해시 값)이다. 해시는 주로 ‘데이터의 무결성’을 확인하거나 ‘암호학적 보안’을 제공하는 데 사용된다.

- 타임 스탬프 해시 과정

1. 데이터 준비 => 타임스탬프를 부여하려는 디지털 데이터 준비(Ex: txt, jpg…)
2. 데이터의 해시 값 생성  => 암호학적 해시 함수(Hash Function) 적용 => 해시 함수는 데이터를 고정된 길이의 ‘해시 값’으로 변환한다. 

	* 입력 데이터가 어떤 크기이든 상관없이 고정된 크기의 해시 값으로 압축된다.
	* 데이터가 조금이라도 변경되면 완전히 다른 해시 값이 생성된다.

3. 해시 값을 타임스탬프 기관(Timestamp Authority, TSA)에 제출 => 타임스탬프 기관은 논문 상에서 “신뢰할 수 있는 제 3자가 해시를 서명하고, 시간 정보를 포함하여 문서의 유효성을 보장”한다고 설명한다.

	* TSA의 기능
	- 해시 값을 기록: 데이터의 원본 대신 해시 값만 저장하여 프라이버시를 보장
	- 타임스탬프 추가: 현재 날짜와 시간 정보를 해시 값과 결합
	- 디지털 서명: 타임스탬프 정보에 디지털 서명을 추가하여 데이터의 ‘무결성’과 ‘신뢰		성’을 보장한다

4. 타임 스탬프와 해시 값 반환 => TSA는 사용자가 제출한 해시 값에 타임스탬프와 서명을 추가한 결과를 사용자에게 반환한다.

5. 데이터 검증 방법 => 데이터의 타임스탬프의 검증 방법: 원본 데이터의 해시 값을 다시 계산(SHA-256으로 자신의 데이터를 해싱) => 계산한 해시 값과 TSA가 발행한 타임스탬프의 해시 값을 비교한다.

	* 해시가 동일? 데이터 변조 X
	* 해시가 동일 X? 데이터 변조 or 변경

6. 타임스탬프의 블록체인 활용 => 각 해시 값은 이전 해시와 연결되어서 체인을 형성한다.

	* 각 타임스탬프가 이전 타임스탬프의 해시 값을 포함하도록 설계 => 이렇게 하면 시간 
	순서가 기록되며, 이전 데이터의 무결성을 보장

 ### - 해시 함수(Hash Function)

- 해시 생성 방법: 해시 함수(Hash Function)이용 => 해시 함수: 임의의 길이를 가진 입력 데이터를 ‘고정된 길이’의 해시 값으로 매핑하는 함수

	* SHA-256 알고리즘: 어떤 입력값을 넣어도 256 비트 길이의(64자)의 값을 출력함
	* SHA-1 알고리즘: 160 비트 길이의(40자)의 값을 출력함

- 해시 함수의 특징
	
        1. 고정된 출력 길이: 모든 암호학적 해시 함수는 입력 데이터의 크기와 관계없이 고정된 길이의 출력(해시 값)을 생성한다.
        2. 충돌 회피: 서로 다른 입력 데이터가 동일한 해시 값을 가질 확률은 극도로 낮다.
        3. 역상 저항성(Preimage Resistance): 해시 값을 통해 원래 입력값을 역으로 계산하는 것이 계산적으로 불가능 * 역(거스를 역) 상(모양 상): 어떤 연산의 결과를 보고 거꾸로 원래 값을 찾아가는 개념
        4. 효율성: 현대 컴퓨터에서 빠르게 계산 가능(긴 데이터를 넣어도 결과를 빠르게 확인 가능)
        5. 강력한 보안성: 현재까지 실직적인 공격이 매우 어려움

- 해시 함수의 활용

        1. 블록체인: 비트코인 및 기타 암호화폐에서 데이터의 ‘무결성’을 보장하고 ‘체인’을 연결하는데 사용
        2. 디지털 서명: 데이터 인증 및 무결성 확인
        3. 암호화 저장: 중요한 데이터를 안전하게 저장
        4. 데이터 무결성 검증: 파일 다운로드 및 전송 중 데이터 손상 여부 확인

- SHA-256 알고리즘 작동 과정

        1. 입력 데이터 준비: 입력 받은 임의의 길이의 데이터는 고정된 크기(512비트 블록)로 처리되며, 필요한 경우 패딩(padding)을 통해 데이터를 맞춘다.
        2. 패딩: 입력 데이터를 512비트 블록으로 나누기 위해 패딩을 추가한다.
        3. 초기 해시 값 설정: 8개의 32비트 초기 해시 값을 정의한다. 
        4. 메시지 처리: 입력 데이터는 512비트 블록 단위로 처리된다.

	(a) 메시지 스케줄 생성 
	=> 각 512 비트 블록은 32비트 단위로 나뉘며, 한 블록 당 16개의 워드(word)로 시작		한다. * 워드: 비트 단위(정보 표현)
	=> 추가적으로 48개의 워드 생성 => 총 64개의 워드가 생성된다.
	=> 새로운 워드는 이전 워드의 XOR 및 시프트 연산으로 생성된다.
		* XOR(베타적 논리합): 입력 비트가 다를 때만 1(True)을 반환하는 논리 연산
		* 시프트 연산(Shift Operation): 비트 단위로 데이터를 왼쪽 또는 오른쪽으로 이
		동시키는 연산

	(b) 해시 압축 함수(라운드 연산)
	=> 초기 해시 값과 64개의 워드 그리고 라운드 상수(64개의 고정된 32비트 상수 값)이 
	Round function의 인자 값으로 들어가게 된다.

	* 라운드 상수: 소수(2~311)의 세제곱근의 소수점 부분을 32비트로 변환
	* Round Function: 메시지 블록을 처리하여 해시 값을 계산하는 핵심 연산
	* 초기 해시 값과 메시지 워드, 상수 값 등을 조합하여 새로운 해시 값을 생성하는 과정을 
	64번 반복한다. 이 때 초기 해시값은 라운드 초기 a, b, c, d, e, f, g, h로 각 대입되어 
	각 라운드를 거치면서 갱신된다.

- 최종 출력

* 최종 해시 값 갱신 => 라운드가 끝난 후 a, b, c, d, e, f, g, h 값을 초기 해시 값에
추가한다. => 모든 블록 처리가 완료되면, 초기 해시값을 연결하여 256비트(32바이트)의 
최종 해시 값을 생성한다.

초기 해시 값들은 64번의 Round를 거친 후 나오게 된다.

### - 해시 => 비트코인

- 블록 정보(블록 해시 값 생성 인자)

        1. 이전 블록 해시 값
        2. 머클 루트: 블록 내 모든 트랜잭션의 요약 값
        3. 타임스탬프
        4. 난이도 목표(해시레이트)
        5. 논스: 작업 증명을 완료하기 이해 반복적으로 변경된 값

=> 위의 데이터를 결합하여 SHA-256 해시 함수를 두 번 적용해서 블록 해시 값을 생성한다.
=> Block Hash = SHA256(SHA256(Block Header))

블록 해시의 역할을 블록 간 연결성을 유지하고, 변경된 데이터를 탐지한다.

- 작업 증명 => 비트코인 네트워크에서는 채굴자가 블록체인의 새로운 블록을 연결하기 위해서는 작업 증명(PoW)라는 해시 퍼즐을 풀어여 한다.

- 작업 증명 해시 함수의 입력 값

        1. 버전
        2. 이전 블록 해시
        3. 머클 루트
        4. 타임스탬프
        5. 난이도 목표
        6. 논스: 이것을 계속 변경한다.

=> 위의 입력 값들 중에서 논스, 타임 스탬프 , 머클 루트가 해시 퍼즐을 어렵게 만드는 요인들이다.

- 트랜잭션 ID => 블록에 들어가는 각 트랜잭션에는 ‘트랜잭션의 변경 여부’를 확인하고, 무결성을 보장하기 위한 트랜잭션 ID값이 존재한다.

* 트랜잭션 데이터: 입력, 출력, 금액 등이 포함돼있다.
* 머클 트리: 블록에 포함된 모든 트랜잭션을 요약하며, 데이터 검증 및 효율적인 검색을 
가능하게 해주는 기술

- 비트코인 주소 생성: 비대칭키 암호화를 기반으로 생성, 비대칭키 암호화에서는 공개키와 비밀키가 사용된다. 
- 비트코인 주소는 공개 키를 SHA-256과 RIPEMD-160으로 해싱한 값으로 생성된다.

- 디지털 서명 => 트랜잭션의 무결성 보장, 소유권 증명하는데 핵심적인 역할을 함, 이 과정에서 쓰이는 것이 해시 함수이다.

- 디지털 서명 역할

* 트랙잭션 데이터 해싱: 트랜잭션 데이터의 해시 값을 서명한다.
* 서명 생성: 개인 키로 해시 값을 서명한다.
* 서명 검증

### - 암호학의 역사

- 컴퓨터 시대의 암호화: 1990년대에 양자암호학의 등장
  
	* 암호 화폐에도 암호 기술이 많이 사용됨
	=> 해시 함수, 공개 키 암호화, 디지털 서명과 같은 다양한 암호화 기술을 사용하며,
	블록체인에 저장된 데이터의 ‘일관성’을 보호하고 거래를 ‘인증’하는 데 사용한다.
	=> 타원곡선 전자서명 알고리즘(Elliptical Curve Digital Signature Algorithm, 
	ECDSA)는 블록체인에 기록된 자산을 정당한 ‘소유주’만이 사용할 수 있도록 보장한다.
	

### - 대칭키 암호화 & 비대칭키 암호화

- 대칭키 암호화: 암호화 및 복호화를 할 때 동일한 키를 사용하는 방식 => 여러 사용자 사이에 공유된 단 하나의 키를 기반으로 동작한다.
- 대칭키 암호 방식 동작 원리

        1. 키 생성: 대칭키(비밀 키)를 생성한다. 이 키는 암호화 & 복호화에 모두 사용한다.
        2. 암호화: 평문 데이터를 입력받아 비밀 키를 사용하여 암호문으로 변환한다.
        3. 전송: 암호문은 안전하지 않은 네트워크를 통해 수신자에게 전송된다.
        	     : 비밀 키를 아는 사람만 암호문을 복호화 할 수 있다.
        4. 복호화: 수신자가 동일한 비밀 키를 사용하여 암호문을 평문으로 복호화한다.

- 비대칭키 암호화: 공개키와 개인키를 한 쌍으로 사용하는 암호화 방식이다.
- 공개키와 개인키가 만들어지는 과정

        1. 개인 키를 난수 생성기를 통하여 생성한다(16진수 or Base58Check 인코딩을 이용하여 문자열로 변환한다)
        2. 개인키로부터 공개키를 생성한다 => 공개키는 타원 곡선 암호화를 기반으로 개인 키에서 파생된다.
            => 개인키로 공개키 유추 가능, 공개키로 개인키 유추 불가능
        3. 공개키는 다시 해싱되어 주소가 생성된다.

- 공개키로 암호화
	
* 송신자가 수신자의 공개키로 데이터를 암호화
* 수신자는 자신의 개인키를 사용해 데이터를 복호화

- 개인키로 암호화

* 송신자가 자신의 개인키로 데이터를 서명(암호화)한다.
* 서명된 데이터는 수신자에게 전송된다.
* 수신자는 서명된 데이터와 발신자의 공개키를 사용해 서명을 검증한다.
* 이를 통해 데이터가 발신자로부터 생성되었고, 중간에 변경되지 않았음을 증명한다.


- 블록체인에서의 활용

        1. 블록체인에서 공개키 사용: 
        	=> 주소 생성: 개인키로 생성된 공개키는 블록체인 주소가 된다.
        	=> 검증: 서명 검증을 위해서 사용
        2. 블록체인에서 개인키 사용: 서명
        3. 자산 제어: 개인키를 이용해서 블록체인 자산의 소유권을 증명한다.

### - 디지털 서명(Digital Signature)

- 서명이란? ‘나’라는 사람이 문서를 확인하고 문서의 내용에 동의하며 문서가 변조하지 않았음을 보증하는 것
- 디지털 서명: 디지털 서명은 개인키를 사용하여 생성한다, 디지털 서명된 데이터를 수신한 사용자는 공개키를 사용해 서명을 검증함으로써 다음을 확인할 수 있다.

        1. 무결성 보증
        2. 진위성 확인

- 디지털 서명의 동작방식

        1. 해싱: 해시 값은 데이터의 고유한 요약 정보
        2. 서명: 무결성과 진위성 보장
        3. 검증: 송신자가 개인키를 이용해서 암호화하고. 수신자가 공개키를 이용해서 복호화 했을때의 해시값이 동일하다면 정상적으로 송신자에 의해 서명된 것임을 확인할 수 있다.

- 디지털 서명 시스템의 필요조건

        1. 알고리즘
        2. 구현
        3. 개인키

### - 디지털 서명 => 타임 스탬프

- 타임스탬프에서 디지털 서명의 사용 목적

        1. 데이터 무결성 증명: 서명 이용
        2. 시간 인증: 타임스탬프 이용
        3. 신뢰 제공: 서명 이용

- 디지털 서명의 사용 과정
    
        1. 데이터 해싱: 해시 함수 이용 => 데이터 크기 감소 및 디지털 서명을 위해서, ‘요약 정보’로 활용된다.
        2. 타임스탬프 생성: 생성된 해시 값을 타임스탬프 기관에 전송한다
        3. 검증: 타임스탬프의 공개키를 사용해 서명이 유효한지 검증하고, 데이터의 해시 값이 타임스탬프에 기록된 해시 값과 동일한지 확인한다.

- 디지털 서명에서 사용된 앙고리즘

        1. RSA or DSA
        2. 해시 알고리즘

### - 디지털 서명 => 비트코인

- 비트코인에서 디지털 서명의 역할

        1. 트랜잭션 무결성 보장
        2. 소유권 증명
        3. 탈중앙화된 검증

- 디지털 서명의 생성 및 검증 과정

	* 서명 생성

        1. 트랜잭션 데이터 준비
        2. 해싱
        3. 개인키를 사용한 서명
        4. 서명과 트랜잭션 데이터 전송

	* 서명 검증

        1. 트랜잭션 데이터 해싱
        2. 공개키를 사용한 검증
        3. 검증 결과 확인

- 비트코인에서 디지털 서명 활용의 특징

        1. ECDSA 사용
        2. 공개키를 이용해서 주소 생성
        3. 비교적 작은 서명 크기(64바이트)











 










# GiHyeon_Blog

## 25.1.31 - OT

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

### 주요 인물

    데이비드 차움: 디지털 서명을 활용해 익명의 전자화폐 개념을 제안
    웨이 다이: 탈 중앙화된 전자 화폐 시스템의 개념적 초안을 마련
    닉 재보: 작업 증명(Proof of Work)을 활용한 디지털 화폐의 설계 아이디어를 구현함

### 사토시 나카모토의 등장

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



 










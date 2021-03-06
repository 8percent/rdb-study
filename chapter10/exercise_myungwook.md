1. 관계가 왜 중요한지, 대표적인 이유 두개를 서술하라
   - 논리적으로 연관이 있는 두 테이블 사이의 연결을 설정한다.
   - 테이블 구조를 정제하고 중복 데이터를 최소화 하는것을 돕는다.
1. 관계의 세 유형을 적어라
   - 일대일
   - 일대다
   - 다대다
1. 어떤 관계가 가장 많은 문제를 일으키는가?
   - 다대다
1. 다대다 관계에서 마주칠 수 있는 두 개의 문제를 서술하라.
   - 대량의 중복데이터 발생
   - 데이터 삽입, 갱신, 삭제 불편
1. 자가 참조 관계는 무엇인가?
   - 한 테이블 안에있는 레코드 사이의 관계
1. 데이터베이스에 있는 테이블 사이에 관계를 식별하는 절차는 어떻게 시작하는가?
   - 모든 테이블 목록을 이용해 관계표를 만든다.
1. 이미 있는 관계를 식별하기 위해 사용할 수 있는 두 종류의 질문은 무엇인가?
   - 소유권기반 질문, 활동기간 질문
1. 테이블 행렬에 있는 1대다 관계를 지정할 때 사용하는 단축 기호는 무엇인가?
   - 1:N
1. 행렬에 있는 각 쌍의 테이블 사이에 어떤 종류의 관계가 공식적으로 존재하는지는 어떻게 결정하는가?
   - a->b, b->a 관계를 판단하고, 관계 덧셈을 통해 관계를 식별한다.
1. 1대다 관계는 어떻게 설정하는가?
   - '다' 쪽에 '1' 쪽 관계키 필드를 추가한다.
1. 참/거짓 문제: 자가 참조 관계를 가진 테이블에서 정보를 추출하는 것은 지루하고 다소 어려울 수 있다.
   - 참
1. 자가 참조 다대다 관계는 어떻게 설정하는가?
   - 연결테이블을 설정한다.
1. 데이터베이스에 있는 외래 키는 어떻게 개선하는가?
   - 복사된 기본 키의 이름과 같은 이름을 갖게한다.
1. 외래 키의 필드 명세 중에서 어떤 두 요소들을 반드시 수정해야 하는가?
   - 키 종류, 유일성
1. 삭제 규칙의 기능은 무엇인가?
   - 관계 테이블의 데이터가 삭제될 때 연관된 데이터의 처리방법 결정
1. 테이블에 대하여 지정할 수 있는 두 가지 참여 종류는 무엇인가?
   - 의무적, 선택적
1. 참여의 정도는 무엇을 나타내는가?
   - 맞은편 테이블에 얼마나 많이 연결될 수 있나를 표현한다.
1. 관계는 언제 관계 수준 무결성을 획득해야하는가?
   - 관계와 이에 대한 특징이 적절하게 설정된 이후

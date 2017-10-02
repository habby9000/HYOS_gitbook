# 1. 오픈소스의 정의

## Open Source란?

우리는 오픈 소스에 대해 얼마나 알고있을까? "오픈 소스"라는 단어를 들었을 때 드는 생각은 '소스 코드가 오픈되어 있으니 무료로 사용할 수 있겠구나!'와 같을 것이다. 실제로 네이버 지식백과에 오픈 소스를 검색해보면 다음과 같이 설명한다. <br />
'오픈소스란 누구나 이용 가능한 퍼블릭 도메인이다. 오픈 소스 운동은 독점적이고 상용화한 소프트웨어에 반하는 것이다. 즉, 오픈소스를 이용하면 그 이용으로 파생된 2차 저작물의 소스코드도 공개해야 한다.' <br />
하지만 이 내용만으로는 오픈 소스에 대한 설명을 마무리지을 수 없다. <br />
보다 더 정확하고 자세한 내용을 알아보기 위해 오픈 소스의 정의를 정리하여 발표한 오픈 소스 이니셔티브(Open Source Initiative)에 게재된 내용을 살펴보자.


0. 소개
> 오픈 소스는 단지 소스 코드에 대한 접근만을 의미하는 것이 아니다. 오픈 소스 소프트웨어를 배포할 때에는 아래의 기준을 준수해야한다.

1. 무료 재배포
> 라이센스는 여러 다른 출처의 프로그램이 포함된 총괄적인 소프트웨어 배포의 구성 요소로 소프트웨어를 판매하거나 양도하지 못하도록 제한하지 않는다. 라이센스는 그러한 판매에 대해 로열티 또는 기타 수수료를 요구하지 않는다.

2. 소스 코드
> 프로그램은 소스 코드를 포함해야하며 컴파일 된 양식뿐만 아니라 소스 코드로도 반드시 배포할 수 있어야한다. 어떤 형태의 제품이 소스 코드와 함께 배포되지 않는 경우, 합리적인 복제 비용 이상으로 소스코드를 얻는 방법이 널리 알려져 있으며, 인터넷을 통해 무료로 다운로드하는 것이 바람직하다. 소스 코드는 프로그래머가 프로그램을 수정하는 기본 형식이어야한다. 의도적으로 읽기 어렵게 만든 소스 코드는 허용되지 않는다. 전처리기 또는 변환기의 출력과 같은 중간 양식은 허용되지 않는다.

3. 파생 작업
> 라이센스는 수정 및 파생된 저작물을 허용해야하며 원본 소프트웨어의 라이센스와 동일한 조건으로 배포할 수 있어야한다.

4. 저자 소스 코드의 무결성
> 라이센스는 빌드 타임에 프로그램을 수정하기위한 목적으로 소스 코드와 함께 "패치 파일"의 배포가 허용되는 경우에만 소스 코드가 수정된 형태로 배포되는 것을 제한할 수 있다. 라이센스는 수정된 소스 코드로 빌드된 소프트웨어의 배포를 명시적으로 허용해야한다. 라이센스는 파생된 저작물이 원래 소프트웨어와 다른 이름 또는 버전 번호를 포함하도록 요구할 수 있다.

5. 개인이나 단체에 대한 차별 금지
> 라이센스는 어떤 개인이나 집단을 차별해서는 안된다.

6. 노력의 분야에 대한 차별 금지
> 라이센스는 특정 분야에서 프로그램을 사용하지 못하도록 제한해서는 안된다. 예를 들어, 프로그램이 비스니스에서 사용되거나 유전 연구에 사용되는 것을 제한하지 않아야한다.

7. 라이센스 배포
> 프로그램에 첨부된 권리는 프로그램이 재배포되는 모든 사람에게 해당 당사자가 추가 라이센스를 발급할 필요 없이 적용되어야 한다.

8. 제품 고유 라이센스 금지
> 프로그램에 첨부된 권리는 특정 소프트웨어 배포의 부분이 되는 프로그램에 의존해서는 안된다.
프로그램이 해당 배포에서 추출되어 프로그램 라이센스 조건에 따라 사용되거나 배포되는 경우, 프로그램을 재배포하는 모든 당사자는 원래 소프트웨어 배포와 함께 부여된 원본과 동일한 권한을 가져야한다.

9. 라이센스로 다른 소프트웨어 제한 금지
> 라이센스는 라이센스가 부여된 소프트웨어와 함께 배포되는 다른 소프트웨어에 제한을 두어서는 안된다.
예를 들어, 라이센스는 동일한 매체에 배포된 다른 모든 프로그램이 '오픈 소스 소프트웨어'여야 한다고 주장해서는 안된다.

10. 라이센스의 기술 중립성
> 라이센스의 조항은 개별 기술 또는 인터페이스 스타일에 근거할 수 없다.
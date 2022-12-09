# 서비스 진단하기 - 웹 성능 테스트

## 웹 성능 테스트 
    [] 웹 성능 예산 작성 후 서버 목표 응답시간 도출
측정 항목 키워드 정리
FCP(First Contentful Paint)
     : 첫 번째 텍스트 또는 이미지가 표시되는 시간
    페이지가 로드를 시작한 시점부터 의미있는 컨텐츠가 처음 렌더링 되는 시점까지의 시간

TTI(Time to Interactive)
    : 페이지와 완전히 상호작용할 수 있게 될 때까지 걸리는 시간 
    사용자와 웹페이지가 안정적인 상호작용을 하기 위해 소요되는 시간

SI(Speed Index) 
    : 속도 색인은 페이지 콘텐츠가 얼마나 빨리 표시되는지 보여줍니다.
    웹 페이지가 얼마나 빨리 컨텐츠를 채우는지를 측정

TBT(Total Blocking Time)
    : FCP와 상호작용 시간 사이의 모든 시간의 합으로 작업 지속 시간이 50ms를 넘으면 밀리초 단위로 표현됩니다.
    FCP와 TTI 사이의 기간동안 사용자와 상호작용하지 못하는 모든 시간을 합친 지표

LCP(Largest Contentful Paint)
    : 콘텐츠가 포함된 최대 페인트는 최대 텍스트 또는 이미지가 표시되는 시간
    웹페이지의 콘텐츠 요소 중 가장 큰 영역을 차지하는 콘텐츠가 화면에 나타나기까지 걸리는 시간

CLS(Cumulative Layout Shift)
    : 누적 레이아웃 변경은 표시 영역 안에 보이는 요소의 이동을 측정합니다. 
    페이지 렌덩링 이후, 사용자가 기대하지 않은 레이아웃의 움직인 거리에 대해 측정
    0.1 이하이면 해당 웹 페이지에서 해당 수치는 좋은 것으로 판단됨.
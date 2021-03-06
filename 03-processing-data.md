```UML
@startmindmap
+ 데이터처리
++ 처리 방식
+++ 배치(Batch)처리
++++ 특징
+++++ 다양한 경로로 데이터소스 유입
+++++ 특정 단위(시간, 양)의 데이터를 한꺼번에 처리
+++++ 처리 비용이 비교적 저렴
++++ 제품
+++++ Hadoop
++++++ 배치 처리에 능숙
+++++ ASW Batch
+++ 실시간(Real-time)처리
++++ 특징
+++++ 데이터 소스를 발생 즉시 처리
+++++ 큰 메모리 필요
++++++ 처리비용이 높다
++++ 인-메모리 처리기술 필요
++ 확장성
+++ 수직 확장(Scale UP)
+++ 수평 확장(Scale OUT)
++ 결함 허용 시스템
+++ 방식
++++ Multiple Region
+++++ 시스템을 물리적으로 다른 위치에 설치
++++ Load Balancing
+++++ 하나의 시스템에 요구가 몰리는 것을 방지
++++ Active/Standby
++++ Data Mirroring
+++++ 데이터를 동시에 다른 디스크에도 저장
++++ Data Replication
+++++ 데이터를 동시에 다른 곳에도 저장
++ 다양한 도구지원
+++ 빅데이터 수집도구
+++ 빅데이터 분석도구
+++ 빅데이터 시작화 도구
@endmindmap
```
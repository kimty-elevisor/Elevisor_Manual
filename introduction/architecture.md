# 아키텍쳐

***

### ◼ 개요

<figure><img src="../.gitbook/assets/1gragh.png" alt=""><figcaption></figcaption></figure>

* Elevisor for PostgreSQL은 웹어플리케이션 기반의 DPM 솔루션으로써 Elevisor Server 및 대상 Agent 설치/구성하면 손쉽게 웹브라우저만을 통해 모니터링이 가능하다.
* 특히 성능 데이터 수집 는 DB 서버의 부하를 최소화 하기 위하여 Statement Cache 기법으로 Soft parse 없이 수행되며 Repository DB에 실시간 저장되어 사후 분석에 활용된다.
* Elevisor 서버 기동시 등록된 인스턴스는 DB와 JDBC Pool을 생성하기 때문에 별도의 인증 없이 DB와 Access 한다.


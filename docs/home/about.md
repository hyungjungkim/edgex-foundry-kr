# 엣지X 파운드리(EdgeX Foundry)에 대해
엣지X 파운드리(EdgeX Foundry)는 리눅스 재단이 사물인터넷(Internet of Things, IoT) 엣지 컴퓨팅을 위한 공통 오픈 프레임워크(common open framework)를 구축하여 진행하는 벤더 중립적인(vendor-neutral, 어느 장비에서나 사용될 수 있는) 오픈 소스 프로젝트 중 하나입니다. 이 프로젝트의 핵심은 시장을 통합하고 IoT 솔루션 개발을 가속화하기 위한 플러그 앤 플레이(plug-and-play) 구성요소의 생태계가 가능하도록 어떤 하드웨어나 운영체제(OS)에 구속되지 않는 참조 소프트웨어 플랫폼 내에서 상호운용성(interoperability) 프레임워크를 호스팅 하는 것입니다.

엣지X는 이해당사자들(interested parties)이 그들의 혁신 기술이 포함된 기존의 연결 표준을 사용하여 구축된 개방적이고 상호 운용이 가능한 IoT 솔루션에 대해 자유롭게 협업을 할 수 있는 중요한 요소입니다.

엣지X 파운드리의 목표:
* 엣지X를 IoT 엣지 컴퓨팅을 통합하는 공통 개방형 플랫폼으로 구축 및 홍보
* 엣지X 플랫폼 아키텍처 상에 상호 운용 가능한 플러그 앤 플레이 구성요소의 생태계가 만들어질 수 있도록 빠르게 성정하고 있는 IoT 솔루션 공급업체 커뮤니티를 활성화하고 장려
* 다음에 대한 사업적 가치 창출:
  * 새로운 데이터 기반 서비스의 시장 출시 시간 단축 - 새로운 수익 창출
  * 사용자가 새로운 기능(AI, 엣지에 있는 ML)과 여러 복합적인 솔루션의 부가가치를 활용할 수 있도록 지원
  * 변화하는 비즈니스 요구 사항에 쉽게 적응할 수 있는 엣지X 기반 IoT 엣지 솔루션을 신속하게 만들 수 있는 툴 제공
* 다음을 통해 IoT 도입의 위험 감소:
  * 상호운용성 및 호환성을 보장하기 위한 엣지X 구성 요소 인증
  * (내부 개발 및 기술 독점적인 대안들과 다르게) 엣지X 사용자, 참여자, 부가가치 제공자로 구성된 글로벌 생태계에 참여
  * 위험을 공유하는 파트너로 구성된 글로벌 생태계를 활용하고 엣지X 혁명을 가속화하기 위한 세계 최고 수준의 리더십을 제공하여 규모의 경제를 통한 비용 절감
  * 사용 사례(use-case)와 상관없는 일관된 소프트웨어 인프라를 통해 보안과 시스템 관리를 개선
* IoT 간의 지속성과 상호운영성을 보장하기 위해 LF Edge, 연관된 오픈 소스 프로젝트, 표준 그룹, 산업 연합들과 협업

**다른 주도적인 IoT 기술들 사이에 엣지X 파운드리의 위치는 어디쯤인가요?**

![](https://www.edgexfoundry.org/wp-content/uploads/sites/25/2017/04/EXF_Focused-at-IoT-Edge-1-1024x639.png)

엣지X 파운드리는 산업용 IoT 엣지에 초점을 맞추고 있습니다. 엣지X 파운드리는 느슨하게 결합된 마이크로 서비스, 플랫폼 독립성과 같은 클라우드 본연의 원칙(cloud-native principles)을 활용하지만, IP 및 비 IP 기반 연결 프로토콜, 넓게 분산된 컴퓨팅 노드에 대한 보안 및 시스템 관리, 매우 제약적인 기기로의 확장 등을 포함하는 IoT 엣지의 특정한 요구 사항을 충족하도록 설계되었습니다.

* 이 프로젝트의 가장 큰 장점은 임베디드 PC, 허브, 게이트웨이, 라우터 및 온프레미스 서버와 같은 엣지 노트로 분산된 IoT 엣지 아키텍처에서 "남과 북, 동과 서가 만나는" 주요 상호운용성에 대한 해결책을 제시합니다.
* 위 그림에 나온 것처럼 느슨하게 결합된 플랫폼은 하나의 엣지 노드에서 실행되거나 다양한 노드로 분산될 수 있습니다.
* 또한, 장치 서비스(Device Services)는 스마트 센서에서 독립적으로 실행되고 한 계층 위의 코어 서비스(Core Services)와 직접 통신을 할 수 있습니다.

엣지X 파운드리는 산업별 상호운용성에 도움이 되고 생태계의 생태계를 조성하고 서로 다른 구성요소를 통합할 수 있는 최대의 유연성을 제공하여 단일화된 힘이 되도록 노력할 것 입니다.

엣지X 파운드리의 주요 원칙은 플랫폼 독립성을 최대 규모로 유지하는 것 입니다:

* 모든 칩(Silicon)(예, x86 또는 ARM)
* 모든 운영체제(예, 리눅스, 윈도우, 맥)
* 모든 앱 환경(Java, Javascript, Python, Go, C/C++ 등으로 작성된 마이크로 서비스가 공통 API를 통해 함께 작동하도록 허용)

**느슨한 결합의 마이크로 서비스 플랫폼 아키텍처**
![제안된 아키텍처](https://www.edgexfoundry.org/wp-content/uploads/sites/25/2018/09/EdgeX_PlatformArchitectureDiagram-1024x651.png)

엣지X 파운드리의 기반은 느슨하게 결합된 계층형 IoT 아키텍처로, 사용자는 호스트 장치의 능력, 솔루션 스택 상의 위치 및 사용 사례에 따라 엣지 컴퓨팅 노드에 혼합된 마이크로 서비스를 배치할 수 있습니다. 창립 멤버들의 초기 코드 기여에 기초하여 오늘날 프로젝트에는 커뮤니티에서 계속 완성될 수 있는 완전한 기능을 갖춘 알파 플랫폼이 있습니다. 오픈 소스이고 커뮤니티 주도의 프로젝트로서, 현재의 아키텍처 계획은 시간이 지남에 따라 진화할 것 입니다.

필수 상호운용성 기반(보라색으로 강조 표시)

* **Core Services, Device Services SDK, Loosely-Coupled Microservice Deployment Framework,Foundational APIs for Data Flow, System Management and Security, Developer Value-add**

선택적 참조 서비스(회색)
* 프로젝트 코드 베이스에는 완전한 엣지 소프트웨어 플랫폼을 구성하는 참조 서비스가 포함되어 즉시 사용할 수 있습니다. 개발자는 이러한 선택적 서비스를 활용하거나 선호하는 다른 대안으로 대체할 수 있습니다.
* 이 플랫폼은 엣지 분석, 데이터 통합, 데이터베이스, 보안, 시스템 관리 및 서비스와 같이 부가가치에 대한 독점적 현신을 사용할 수 있도록 하면서 동시에 기본 프로토콜 표준 간의 상호 운용이 가능하도록 특별히 고안되었습니다.

이 아키텍처는 IoT 에지에서 필요에 따라 "북, 남, 동, 서" 통신을 지원하며 계층화된 컴퓨팅 아키텍처에서 다양한 에지 노드에 구현할 수 있습니다. 서로 다른 플러그 앤 플레이 마이크로 서비스를 조합한 배치는 간단히 호스트 장치의 사용 사례와 사양에 달려 있습니다.

![](https://www.edgexfoundry.org/wp-content/uploads/sites/25/2017/04/EXF_Tiered-IoT-Deployments-1024x633.jpg)

**이 프로젝트에 참여하면 어떤 이익을 얻을 수 있나요?**

**최종 사용자**: 변화하는 비즈니스 요구 사항에 동적으로 적응할 수 있는 유연성을 통해 IoT 엣지 솔루션을 빠르고 쉽게 구축

**하드웨어 OEM**: 상호 운용 가능한 파트너 생태계와 보다 강인한 보안 및 시스템 관리를 통해 더 빠르게 확장, 하드웨어 구축이 쉬워지고, EXF를 통해 더욱 광범위하게 지원됨

**ISV**: 연결성을 재개발하지 않고 타사 애플리케이션 및 하드웨어와 상호운영, 인증 및 상호운영 가능한 구성 요소를 위한 복합적인 솔루션 구축

**센서/장치 제조사**: 장치 서비스 SDK(Device Service SDK)와 모든 솔루션 제공자로부터 받은 장치 서비스를 이용하여 선택한 프로토콜로 장치 드라이버를 한 번에 작성

**SI(System Integrators)사**: 자체 혁신과 결합된 플러그 앤 플레이 요소로 시장 출시 시간 단축

**어떻게 참여할 수 있나요?**
1. **개발자 리소스**: 오픈 소스 프로젝트로서 코드에 접속하거나 메일링 리스트 및 토론 포럼에 참여하기 위해 회원가입이 필요하지 않습니다. 자세한 내용은 https://www.edgexfoundry.org/get-started/을 참조.
1. **회원 되기**: 회원에게는 네트워킹, 인증 프로그램 개발에 의견 개진, 마케팅 기회 등 부가적인 기회가 제공됩니다. 자세한 내용은 http://edgexfoundry.org/about/members/join을 참조.
 
원문: https://www.edgexfoundry.org/about/
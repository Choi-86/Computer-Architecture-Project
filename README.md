# Computer-Architecture-Project

### System Call Hooking  
- ftrace 기반 커스텀 시스템콜 후킹을 구현하여 프로세스의 VMA, 파일 매핑, 메모리 접근 흐름을 추적.  
- 특정 PID의 메모리 영역과 파일 정보를 커널 레벨에서 수집하고 출력 구조를 설계함.

### Process Tracing  
- fork 호출 횟수를 커널 소스 수정으로 계측하고, 프로세스 생성·종료 흐름을 분석.  
- /proc 기반 정보와 task_struct를 참조하여 프로세스 상태 변화를 관찰.

### CPU Scheduling  
- FCFS, SJF, RR 스케줄러를 직접 구현하고 Gantt Chart로 시각화.  
- 평균 대기 시간, 반환 시간, 응답 시간 계산 및 알고리즘 비교.

### Multi-processing Performance  
- 동일 연산을 fork vs thread로 수행하며 clock_gettime으로 성능 측정.  
- 메모리 공유 여부, context switching 비용 차이를 통해 성능 특성 분석.

### Page Replacement Algorithms  
- FIFO, LRU, Clock 알고리즘 구현 및 페이지 폴트 수 비교.  
- 다양한 페이지 프레임 수에 따른 동작 변화를 시뮬레이션.

### Pipeline Hazard Analysis  
- MIPS 파이프라인 코드에서 Data/Control Hazard를 식별하고 NOP 제거·Forwarding 설계.  
- 시뮬레이션을 통해 사이클 수 감소 효과 검증.

### Cache Architecture & AMAT Analysis  
- Bubble Sort / Random Access의 캐시 접근 패턴 분석 (I-cache, D-cache hit/miss).  
- SimpleScalar 기반으로 cache size, block size, associativity 변화에 따른 AMAT 비교.

### Virtual Memory & Demand Paging  
- 가상 주소 → 물리 주소 매핑, TLB 역할, page fault 처리 과정 이해.  
- Demand Paging 환경에서 메모리 사용 패턴 및 swap 동작 분석.

### Technologies Used:
Languages  
- C, Assembly(MIPS), Shell Script

Environment  
- Linux (Ubuntu), Linux Kernel 5.x  
- Logisim-E, SimpleScalar, Icarus Verilog

Tools & APIs  
- gcc, Makefile  
- ftrace, dmesg  
- clock_gettime  
- GDB, objdump  
- Verilog simulation tools  
- PLA design tools (Single Cycle / Multi-Cycle CPU)

Core Concepts  
- Process Management, Scheduling, System Call Hooking  
- Pipeline Hazard (Data/Control/Structural)  
- Cache Design, AMAT, Memory Hierarchy  
- Page Replacement Algorithms, Virtual Memory, TLB  
- Multi-threading vs Multi-processing  
- CPU Datapath, Microprogramming, FSM

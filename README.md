# Computer-Architecture-Project

### MU0 Processor 설계  
- Transmission Gate 기반 MUX, Latch, D-FF, Up/Down Counter 구현 후 MU0 2-cycle CPU 동작 검증.

### MIPS Single-Cycle CPU 구현  
- AND/NOR/ADDI/SLTU 등 명령어 추가, datapath·제어신호 설계, PLA 기반 명령어 디코딩 구현.

### MIPS Multi-Cycle CPU 구현  
- Microprogramming(FSM) 기반 DISP_ROM / MICRO_ROM 설계, 다단계 실행 흐름 구성.

### Pipeline Hazard 분석  
- 제공된 sort 코드에서 Data/Control Hazard 분석, NOP 최소화 및 Forwarding 적용해 성능 최적화.

### Cache Architecture 분석  
- Bubble Sort / Random Access의 I-cache·D-cache hit/miss 동작 비교, SimpleScalar로 AMAT 실험.

#### 전체 흐름 요약
- CPU 구조(단일/다중 사이클), 파이프라인, 캐시·메모리 계층, 주소 변환·가상 메모리 전반 이해 및 구현.


### Technologies Used:
- Languages: Verilog, C, MIPS Assembly  
- Tools: Logisim-E, SimpleScalar, Icarus Verilog, gcc, Makefile  
- Environment: Linux (Ubuntu)  
- Concepts: Datapath & Control, Microprogramming, Pipeline Hazard, Cache & AMAT, Virtual Memory

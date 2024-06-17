# **🕊 Bird's Bones and Living Habits Dataset**

## **0. 데이터 소개**
- [자료 출처](https://www.kaggle.com/datasets/zhangjuefei/birds-bones-and-living-habits/data) 
- 새의 뼈에 대한 자료를 바탕으로 새의 생태학적 그룹을 분류한 데이터
- Id 포함 11개의 독립변수와 1개의 종속변수(type)로 구성
  
  <img src = "https://github.com/chasubeen/Birds/assets/98953721/9190a656-fb9a-4d7f-927d-568d5673e3a0" height = 500 width = 350>
  
  - 독립변수 설명
    - Id number : 1~420까지의 id
    - huml : Humerus(위날개뼈)의 길이 (mm)
    - humw : Humerus(위날개뼈)의 지름 (mm)
    - ulnal : Ulna(자뼈)의 길이 (mm)
    - ulnaw : Ulna(자뼈)의 지름 (mm)
    - feml : Femur(넓적다리뼈)의 길이 (mm)
    - femw : Femur(넓적다리뼈)의 지름 (mm)
    - tibl : Tibiotarsus(정강발목뼈)의 길이 (mm)
    - tibw : Tibiotarsus(정강발목뼈)의 지름 (mm)
    - tarl : Tarsometatarsus(뒷발목뼈)의 길이 (mm)
    - tarw : Tarsometatarsus(뒷발목뼈)의 지름 (mm)
  - 종속변수 설명
    - type: 6개의 카테고리 존재
      - SW : Swimming Birds (수영하는 조류)
      - W : Wading Birds (물가에 서식하는 조류)
      - T : Terrestrial Birds (지상조류)
      - R : Raptors (사냥하는 조류)
      - P : Scansorial Birds (산악지대에 서식하는 조류)
      - SO : Singing Birds (노래하는 조류)    
  
  ** 새의 생태학적 그룹은 8종류로 나뉘나, 2종류(Cursorial Birds와 Marine Birds)에 대한 정보는 데이터셋에 포함되어 있지 않음

## **1. 참여자**
|**팀원 1**|**팀원 2**|**팀원 3**|**팀원 4**|
|:----------:|:----------:|:----------:|:----------:|
|<img src="https://github.com/chasubeen/Birds/assets/98953721/d0c36724-2af3-44f6-be26-b689db0cd52f" width = 100 height = 100>|<img src = "https://github.com/chasubeen/Birds/assets/98953721/d3770423-221a-4e58-9a62-fe0ac32731ef" width = 100 height = 100>|<img src = "" width = 100 height = 100>|<img src = "https://github.com/chasubeen/Birds/assets/98953721/897c44b7-c0d5-46ba-98d4-fb9e5b39a83e" width = 100 height = 100>|
|[김경민](https://github.com/kkyung0131)|[이도경](https://github.com/dklee1118)|[장단]()|[차수빈](https://github.com/chasubeen)|

## **2. 진행 과정**
- **기간**: 2024.05 ~ 2024.06
- **세부 일정**
  
  <img src = "https://github.com/chasubeen/Birds/assets/98953721/60af38ae-5c00-4f40-8be9-aae8d9c8e106" width = 600 height = 350>

- **역할**
  
|**이름**|**역할**|
|:-----:|:----------:|
|김경민|데이터 전처리, 탐색적 데이터 분석(EDA), 정준상관분석, 주성분분석, 판별분석(LDA/QDA), 발표자료 완성|
|이도경|데이터 전처리, 탐색적 데이터 분석(EDA), 정준상관분석, 보고서 완성|
|장단|데이터 전처리, 탐색적 데이터 분석(EDA), 군집분석, 주성분분석, 발표자료 완성|
|차수빈|데이터 전처리, 탐색적 데이터 분석(EDA), 군집분석, 보고서 완성|

---
## **회고**
### **김경민**
- 다변량 데이터를 분석하는 다양한 방법들(CCA, PCA, LDA/QDA, Clustering)을 모두 적용해보며 하나의 데이터를 여러 시각으로 살펴볼 수 있었던 경험이었습니다.
- PCA와 CCA 분석 시에 각 주성분과 정준변수를 어떻게 해석하면 좋을지 고민할 수 있었고, 이 과정에서 데이터 안에서 인사이트를 얻는 방법을 터득할 수 있었습니다.
- LDA/QDA 분석을 통해 변수마다 분산이 다른 데이터에서는 이차판별분석이 더 적합함을 알 수 있었으며, QDA가 LDA보다 과적합 가능성이 높은 것에 주의해야 함을 알 수 있었습니다.
- 결과적으로 데이터의 분포와 특성에 따라 분석 방법의 방향과 적합한 모델이 달라지므로 EDA와 전처리 과정에서 데이터를 충분히, 그리고 깊게 살펴봐야 함을 깨달을 수 있었던 프로젝트였습니다. 

### **이도경**

### **장단**

### **차수빈**
- 다양한 변수를 가진 데이터를 활용하여 여러 가설을 설정하고, 다각도로 데이터를 분석해 볼 수 있어서 뜻깊었던 경험이였던 것 같습니다.
- 또한, 군집화 시 군집화 기법에 따른 결과 차이가 상당하다는 점을 확인할 수 있었고, 이를 통해 데이터 분석 시 데이터의 특성을 잘 파악하는 것 또한 분석 성능이나 방향을 설정하는 데 주요한 영향을 미침을 알 수 있었습니다.

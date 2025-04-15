# YouTube 및 Naver 댓글 수집 및 NLP 텍스트 마이닝 자동화 프로젝트
Python 기반의 웹 크롤러를 개발하여 Selenium WebDriver를 사용해 YouTube와 Naver에서 댓글을 수집하였습니다. 수집된 데이터는 LDA, Word2Vec, WordNet, WordCloud와 같은 NLP 기법을 사용하여 처리됩니다. 결과는 시각화되며, 연구 논문 및 학술 발표를 통해 통찰력을 제공합니다.

![image](https://github.com/user-attachments/assets/3f1fce98-6a0b-4ad3-b6d8-7685db6b210e)
![image](https://github.com/user-attachments/assets/40347547-94aa-4ded-842e-1061ce6677f0)
![image](https://github.com/user-attachments/assets/0d9379f4-b86a-4bc1-b17b-35d03519d442)
![image](https://github.com/user-attachments/assets/cd973648-895e-4f83-8c26-9f6f85c31699)
![image](https://github.com/user-attachments/assets/0f97bb0c-3006-461c-bdf2-6ae7f6c0f9be)

# 초보 게임 개발자를 위한 최적 게임 엔진 선택 가이드 (요약)

## 서론

### 분석 배경 및 동기
초보 게임 개발자가 게임 개발에 입문하는 과정에서는 어떤 게임 엔진을 선택해야 하는지에 대한 궁금증이 발생할 수 있습니다. 이 논문은 이러한 궁금증을 해결하고자 합니다.

### 분석 목적 및 범위
본 논문의 목적은 초보 게임 개발자들이 자신의 성향에 맞춰 게임 개발에 최적화된 엔진을 선택하는데 도움을 주기 위해 다양한 게임 엔진의 특성과 장단점들을 특정 유튜브 영상에서 이미 여러 게임 엔진을 경험한 사용자들의 관심사와 경험 및 반응을 크롤링해 자동으로 수집하고 분석하는 것입니다.

## 분석 방법론 소개

특정 유튜브 영상 댓글을 수집한 후 불용어를 전부 제거합니다. 그 후, 댓글을 저장하고 댓글 전처리를 통해 “LDA” 모델링 및 “Word2Vec” 모델링, “WordCloud” 생성, 영상 내에서 불용어를 제외한 상위 빈출 단어 그래프를 산출합니다. 그 후 시각화하여 사용자들의 의견과 생각을 분석합니다.

## 분석 방법

### 게임 엔진 선정 기준
초보 개발자가 게임 엔진을 선택할 때 고려해야 할 주요 기준을 중심으로 선정했습니다.

- **커뮤니티 지원 및 활성화**: 게임 개발 과정에서 문제가 발생할 경우, 커뮤니티의 지원이 중요합니다. 대규모 커뮤니티가 있는 엔진은 문제 해결이 빠를 수 있고, 인간의 도움 없이 AI를 사용하여 독학할 기회를 제공합니다.
  
- **플랫폼 지원**: 게임을 개발하는 목표 플랫폼에 따라 엔진의 지원 범위를 고려해야 합니다. Unity와 Unreal은 각기 다른 플랫폼을 지원하며, 개발자는 자신이 타겟으로 하는 플랫폼을 지원하는 엔진을 선택해야 합니다.

- **학습 곡선**: 언어 학습 곡선과 엔진의 복잡성을 고려해야 합니다. 예를 들어, C#은 상대적으로 쉬운 언어인 고급 언어이며 Unity에서 사용됩니다. 반면 Unreal은 C++을 사용하여 보안성과 속도가 뛰어난 저급 언어를 사용합니다.

- **비용**: 초기 개발 비용과 라이센스 비용은 초보 개발자에게 중요한 요소일 수 있습니다. Unity는 무료이고, 상대적으로 저렴하여 접근이 용이한 인식이 있습니다. Unreal은 무료로 제공되며, 작은 게임 개발 스튜디오나 1인 개발자에게 유리한 수익 분배 조건을 가집니다.

- **미래 전망**: 게임 엔진의 기술적 발전 가능성과 새로운 기술 트렌드에 대한 대응력을 평가해야 합니다. Unity는 모바일, VR/AR 등 새로운 플랫폼과 기술을 지원하는 데 유리합니다.

## 분석 결과

### 게임 엔진 비교 분석
모바일 게임 시장은 지속적으로 성장하고 있으며, 2028년까지 연평균 6.8%의 성장률을 기록할 것으로 예상됩니다. Unity와 Unreal 엔진의 특성을 비교 분석한 결과는 다음과 같습니다.

#### Unity 엔진

- **다양한 플랫폼 지원**: Unity는 모바일, PC, 콘솔 등 다양한 플랫폼을 지원합니다.
- **거대한 커뮤니티**: 개발자들 간의 정보 공유와 협력이 활발히 이루어집니다.
- **낮은 진입 장벽**: 독립 개발자나 소규모 스튜디오도 부담 없이 사용할 수 있는 낮은 초기 개발 비용을 제공합니다.
- **모바일 게임 시장 점유율**: 특히 모바일 게임 개발에서 높은 점유율을 보입니다.
- **개발 언어**: C#을 사용하며, 학습이 용이한 언어로 평가됩니다.
- **개발 확장성**: WebGL, XR, VR, MR, AR 등 다양한 기술에 대한 지원을 제공합니다.

#### Unreal 엔진

- **우수한 물리 시스템**: Unity에 비해 더 안정적이고 정교한 물리 엔진을 제공합니다.
- **풍부한 게임 제작 기능**: 고품질의 그래픽과 다양한 게임 제작 도구를 제공합니다.
- **개발자 지원**: 메가스캔, 월별 무료 에셋 등 개발자를 위한 편의 시스템이 잘 갖춰져 있습니다.
- **AAA 게임 개발 선호**: 대규모 예산의 고품질 게임 개발에 주로 사용됩니다.
- **개발 언어**: C++을 사용하며, 더 세밀한 최적화가 가능합니다.

### 언어 학습의 관점
개발자들 사이에서는 C#을 먼저 배운 후 C++로 넘어가는 것이 학습 곡선 측면에서 유리하다는 의견이 많습니다. C#은 상대적으로 고급 언어로 분류되어 초보자가 접근하기 쉬운 반면, C++는 더 낮은 수준의 제어를 제공하는 저급 언어의 특성을 가지고 있습니다.

### 결과 해석

- **시장 적합성**: Unity는 특히 모바일 게임 시장에서 강세를 보이며, 빠르게 성장하는 모바일 게임 산업에 잘 부합합니다. Unreal은 고품질의 AAA 게임 개발에 적합합니다.
- **개발자 진입 장벽**: Unity는 낮은 초기 비용과 쉬운 학습 곡선으로 인해 독립 개발자에게 유리합니다. Unreal은 더 복잡한 기능과 높은 품질을 요구하는 대규모 프로젝트에 적합합니다.
- **기술적 특성**: Unreal은 물리 엔진과 그래픽 품질 면에서 우위를 보이지만, Unity는 다양한 플랫폼 지원과 개발 확장성에서 강점을 가집니다.
- **개발 언어**: C#은 학습이 용이하고 생산성이 높지만, C++는 더 세밀한 최적화가 가능합니다.
- **커뮤니티 및 지원**: 두 엔진 모두 강력한 커뮤니티와 지원 시스템을 갖추고 있으나, Unity의 커뮤니티가 더 크고 다양한 것으로 보입니다.
- **미래 기술 대응**: Unity의 WebGL, XR, VR, MR, AR 지원은 새로운 기술 트렌드에 대한 높은 적응력을 보여줍니다.

## 결론

### 요약
본 분석은 초보 게임 개발자들이 Unity와 Unreal 엔진 중에서 어떤 엔진을 선택해야 할지를 결정하는 데에 중점을 두었습니다. 두 엔진은 각기 다른 특성과 장단점을 가지고 있으며, 이를 통해 개발자들은 자신의 프로젝트 목표와 기술적 선호도에 맞춰 최적의 선택을 할 수 있습니다. Unity는 다양한 플랫폼 지원과 낮은 진입 장벽으로 많은 독립 개발자들이 선호하는 엔진입니다. Unreal 엔진은 뛰어난 그래픽 품질과 정교한 물리 시뮬레이션을 제공하여 AAA급 게임 개발에 적합합니다.

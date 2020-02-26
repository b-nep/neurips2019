# NeurIPS 2019 논문 통계

본 문서는 2019년 12월에 개최되었던 NeurIPS 2019(the Thirty-third Conference on Neural Information Processing Systems)에 게재된 논문들의 각종 통계 수치를 분석한 글입니다.


![1920px-Logo_for_Conference_on_Neural_Information_Processing_Systems](https://user-images.githubusercontent.com/60768732/75364742-8d5fec00-58ff-11ea-9f8d-d3a78a77fc7a.png)


## Introduction
NeurIPS는 세계 최고 권위의 인공지능 학회로, 1987년부터 매해 컨퍼런스를 개최하여 2019년 12월에는 캐나다 밴쿠버에서 33번째 컨퍼런스를 개최하였습니다. 해마다 폭넓은 범주의 AI 관련 연구 논문들이 게재되고 있으며 특히 NeurIPS 2019에서는 @@, @@, @@ 등 다양한 분야에서 1428 편의 논문이 게재되었습니다. 본 포스팅에서는 논문 내용에 대한 분석이 아닌, 논문들의 각종 통계 수치에 대한 분석을 다루었습니다.

## NeurIPS의 시작과 현재
NeurIPS는 1987년에 Bell-lab과 caltech의 주도하에 처음 개최되었습니다. 처음에는 이름이 NIPS 였으나, 현재는 NeurIPS로 공식 명칭이 바뀌었습니다. 첫 컨퍼런스인 NIPS 1987에서는 게재된 논문이 90편으로 규모가 그리 크지 않았지만, 해마다 규모가 커져서 NeurIPS 2019 에서는 무려 1428편의 논문이 게재되었습니다. 특히 2016년부터 논문 수가 급격히 증가하고 있는데(그림 1)  이는 AI 에 대한 관심과 이를 받쳐줄 수 있는 하드웨어 및 인프라 발달 덕분이라고 볼 수 있습니다. 게재 논문 수는 꾸준히 늘어나고 있지만 acceptance rate는 20~24% 로 유지(그림 2)되고 있습니다.

인공지능에 대한 학계의 높은 관심과 기대치로 봤을때 앞으로 더욱 규모가 커질 것으로 예상됩니다.

## 기관 별 논문 수
2010년 중반 이후로, 학교나 기업 등 기관 종류를 가리지 않고 굉장히 많은 AI 관련 연구가 이루어지고 있습니다. 어떤 기관이 가장 활발한 연구 활동을 하고 있는지 NeurIPS 2019를 통해 알아보기 위해 총 1428편의 NeurIPS 2019 accepted paper 에서 기업과 학교 이름을 파싱하여 분석하였습니다.

한 논문 내에서 저자들의 소속 기관이 모두 같을 경우 하나의 기관으로 카운트 하였고, 소속 기관이 여러개일 경우 각 기관마다 카운트 하였습니다. 또한, [Google, google brain, google research], [microsoft, microsoft research] 등과 같이 모기업이 같은 여러 기관의 경우엔 모기업의 이름으로 통일하였습니다.

그 결과, google이 총 165편으로 가장 활발한 연구 활동을 하고 있었습니다. 2~4위를 차지한 기관이 각각 86편, 81편, 78편을 제출한 것을 감안하면 NeurIPS 2019에서 google의 논문 제출 수는 가히 압도적이라 할 수 있습니다. google 외  기업 으로는 microsoft(81편), facebook(43편) 등이 많은 연구를 하고 있었고, 학교로는 stanford university(86편), MIT(78편), carnegie mellon university(77편) 등이 많은 연구를 하고 있었습니다.


NeurIPS 2019 accepted paper의 기업과 학교의 수를 분리하여 비교해 보았습니다. 그 결과, 기관 수는 비슷하지만, 논문 수는 학교가 좀 더 많은 것을 알 수 있었습니다. (그림 4)
기업의 경우, 앞서 언급한 것처럼 google이 압도적으로 많은 연구 활동을 하고 있었고 microsoft, facebook, inria, ibm, amazon등의 기업이 그 뒤를 따라가고 있었습니다. 학교의 경우 stanford와 MIT, CMU가 가장 많은 연구 활동을 하고 있었고, uc berkeley, princeton, columbia, oxford  등이 그 뒤를 따라가고 있었습니다. 



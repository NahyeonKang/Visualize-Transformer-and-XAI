# Visualize-Transformer-and-XAI
Transformer의 self-attention과 대표적인 XAI 기법의 결과를 비교합니다.

## NLP - classification
### Transformer [cls] token self-attention
![다운로드](https://github.com/NahyeonKang/Visualize-Transformer-and-XAI/assets/24906028/cdd2db6d-bbce-4406-9a7e-2e718c30e5b4)
각 layer와 head의 attention값 평균했을 때 상위 토큰  
(1) [SEP]  
(2) [CLS]  
(3) ##eville  
(4) ##eville  
(5) 89  
(6) 88  
(7) the  
(8) .  
(9) .  
(10) -  
(11) model  
(12) .  
(13) .  
(14) .  
(15) ##s  
(16) .  
(17) buy  
(18) models  
(19) .  
(20) on  
(21) 88  
(22) 89  
(23) -  
(24) the  
(25) 89  
(26) organization  
(27) le  
(28) info  
(29) demand  
(30) features  
(31) bonn  
(32) performance  
(33) ##se  
(34) the  
(35) book  
(36) value  
(37) book  
(38) bonn  
(39) ##ei  
(40) differences    
### Lime
<img width="420" alt="스크린샷 2023-07-03 150007" src="https://github.com/NahyeonKang/Visualize-Transformer-and-XAI/assets/24906028/02746779-7264-4102-97c6-5efdfcb0753f"><br/>
<img width="430" alt="스크린샷 2023-07-03 150058" src="https://github.com/NahyeonKang/Visualize-Transformer-and-XAI/assets/24906028/3787bcfe-8395-40c6-9b5b-bf0b8b279e03">

## Tabular
### TabTransformer
### Lime
### Shapley

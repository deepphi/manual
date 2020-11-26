# Version 2020-04.1126016

#### New Feature

- TODO

#### Improvement

- Hyper-parameter Auto-Tunning 과정에서 over-fitting을 피하기 위해 perturbation을 주는 로직을 추가하였습니다.
- Image to Image 학습을 위해 'Transformation' AI label type을 추가하였습니다.(업로드  : https://deepphi.github.io/manual/chapter4/4-1.데이터셋_템플릿.html,  
예제 프로젝트 : )

#### Bug

- 데이터셋 업로드시 확장자가 대문자인 경우 업로드가 안되는 버그 수정 ex) NII가 확장자인 경우
- Hyper-parameter Auto-Tunning 과정에서 learning rate이 1보다 커지는 버그 수정


#### Task

- 튜토리얼 동영상 추가
  - [1-1. Upload Dataset](https://www.youtube.com/watch?v=Lq3aRIJWJzU)  
  - 1-2. Dataset Structure
    - [1-2-1. Classification Dataset Structure](https://www.youtube.com/watch?v=C_kyji4VdFY)
    - [1-2-2. Segmentation Dataset Structure](https://www.youtube.com/watch?v=1alhmYLbJVM)
    - [1-2-3. Detection Dataset Structure](https://www.youtube.com/watch?v=fnlcc8pNpFY)
    
- 메뉴얼 업데이트
  - [3-5.6. Hyper-parameter Auto-Tunning](https://deepphi.github.io/manual/chapter3/3-5.성능_고도화.html#6-hyper-parameter-auto-tunning)
  - [4-1.4. Transformation 데이터셋 구조](https://deepphi.github.io/manual/chapter4/4-1.데이터셋_템플릿.html)
# Study_Number (숫자 공부)

숫자 그림을 머신 러닝을 통해 숫자 결과를 출력해주는 안드로이드 어플리케이션입니다.

구글 Colab과 Android Studio를 사용해서 만들어졌습니다.

--------------------------------------
## 프로그램 용도
어린 아이들이 아라비아 숫자를 배우는데에 있어서 어플리케이션을 가지고 쉽게 배웠으면 하는 바람으로 제작함.

-------------------------------------
## TensorFlow 코드

머신 러닝을 적용할 참고 코드입니다.

Colab 환경에서 코딩했습니다.

[머신 러닝 코드](https://colab.research.google.com/github/tensorflow/examples/blob/master/lite/codelabs/digit_classifier/ml/step2_train_ml_model.ipynb)

파이썬 코드를 모두 실행하고 tflite파일을 다운받아 Android Studio에서 './app/src/main/assets/' 경로에 다운로드 받은 tflite파일을 추가해야 합니다. (추가되어있음)

------------------------------------
## Andorid Studio 관련
* './app/src/main/java/org/tensorflow/lite/codelabs/digitclassifier/DigitClassifier.kt/'
  + 숫자 그림에 대한 결과 값과 정확도를 출력하는 클래스
* './app/src/main/java/org/tensorflow/lite/codelabs/digitclassifier/MainActivity.kt'
  + Main 클래스

----------------------------------
## 프로그램 사용방법
![0](https://user-images.githubusercontent.com/87689191/150134666-7d80a668-5a9d-4911-965c-33b600e7cf34.PNG)

1. 검은 화면(Draw_view)에 숫자를 그린다.
2. 검은 화면 아래 흰 화면에 그림에 대한 결과 숫자와 정확도가 출력이 된다.
3. 'CLEAR' 버튼을 클릭하면 검은 화면(Draw_view)가 초기화가 된다.
4. 반복...



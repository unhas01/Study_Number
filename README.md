# Study_Number (숫자 공부)

숫자 그림을 머신 러닝을 통해 숫자 결과를 출력해주는 안드로이드 어플리케이션입니다.

구글 Colab과 Android Studio를 사용해서 만들어졌습니다.

-------------------------------------
## TensorFlow 코드

머신 러닝을 적용할 참고 코드입니다.

[Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/lite/codelabs/digit_classifier/ml/step2_train_ml_model.ipynb)

파이썬 코드를 모두 실행하고 tflite파일을 다운받아 Android Studio에서 './app/src/main/assets/' 경로에 다운로드 받은 tflite파일을 추가해야 합니다. (추가되어있음)

------------------------------------
## Andorid Studio 관련
* './app/src/main/java/org/tensorflow/lite/codelabs/digitclassifier/DigitClassifier.kt/'
  + 숫자 그림에 대한 결과 값과 정확도를 출력하는 클래스
* './app/src/main/java/org/tensorflow/lite/codelabs/digitclassifier/MainActivity.kt'
  + Main 클래스

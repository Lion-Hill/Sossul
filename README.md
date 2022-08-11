# 사자동산의 Final Project README!

# 프로젝트 주제: 이미지 분류 및 추천 시스템 활용 코디 추천 모델
![image](https://images.unsplash.com/photo-1483985988355-763728e1935b?ixlib=rb-1.2.1&q=80&cs=tinysrgb&fm=jpg&crop=entropy)


# Fashion_Recommendation_System
TQDM Tracking Conv-AE Model Training

nb_epochs = 100
batch_size = 64

start = time.time()
tqdm_callback = tfa.callbacks.TQDMProgressBar()
history = model.fit(X_train, X_train, epochs=nb_epochs, batch_size=batch_size, shuffle=True,
                    callbacks=[early_stopping, cp, tqdm_callback], validation_split=0.05).history
end = time.time()

현재 진행률 85%

![image](https://img1.daumcdn.net/thumb/R720x0/?fname=https%3A%2F%2Ft1.daumcdn.net%2Fliveboard%2FCodibook%2Ff25ad16fbf5e4282b18e7499d6dcfcf2.JPG)

## Streamlit Dashborad 제작에 관한 3줄 설명
- 파이널 프로젝트 결과를 배포하기 위해서 Streamlit을 선택하였다.
- 사용자가 인풋 사진을 넣으면 그에 따른 코디를 추천해준다.
- Local에서 개발하고 Git에 Push하는 개발방식으로 개발 진행중이다.

우리는 짱이댜!!!  
진짜루 짱이댜!!!  
Absolutly VEEEEEERY GOOOODD 


![image](https://github.com/J-PARK11/Computer-VISION/blob/master/Image%20Based%20Fashion%20Recommendation%20System/figure/ConvAE0810.png)
# 사자동산의 Final Project README!

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


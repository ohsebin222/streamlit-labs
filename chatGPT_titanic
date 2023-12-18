import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# 타이타닉 데이터 불러오기
titanic_data = pd.read_csv('./titanic.csv')

# 상관 계수 계산
correlation_matrix = titanic_data.corr()

# heatmap으로 상관 계수 시각화
plt.figure(figsize=(10, 8))
sns.heatmap(correlation_matrix, annot=True, cmap='coolwarm', fmt='.2f')
plt.title('데이터 변수 간 상관 관계')
plt.show() 

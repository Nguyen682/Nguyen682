import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error

# Đọc dữ liệu từ tệp CSV
data = pd.read_csv('car_price_data.csv')  # Thay đổi đường dẫn nếu cần

# Khám phá dữ liệu
print(data.head())
print(data.info())
print(data.describe())
'







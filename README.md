# Bank-customer-segmentation

# Introduction
PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows. 

In this project, I will perform an unsupervised clustering of customer data from a bank with PyCaret. Customer segmentation is the process of grouping customers who share certain traits or characteristics into segments in order to optimize marketing strategy, maximize customer’s value to the business, and improve customer experience and satisfaction.

# Installation
```
pip install pycaret
```
```
import pandas as pd
import pandas_profiling as pp
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from pandas_profiling import ProfileReport
```
# Data overview
The original dataset contains 113066 data points and 10 attributes. The attributes are as followed:

customer_id: Mã số định danh của khách hàng
prod_ca: Sản phẩm tài khoản thanh toán
prod_td: Sản phẩm tiền gửi có kì hạn
prod_credit_card: Sản phẩm thẻ tín dụng
prod_app: Sản phẩm app chuyển tiền trên mobile
prod_secured_loan: Sản phẩm vay thế chấp
prod_upp: Sản phẩm vay tín chấp
amount: Tổng tài sản khách hàng nắm giữ
segment: Phân khúc khách hàng
province_city: Tỉnh/Thành phố nơi khách hàng sinh sống

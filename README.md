# AI 工具手把手工作坊 Hands-on-AI-Tools

## 簡介

會使用到的 Python 函式庫有：

1. NumPy：矩陣運算函式庫
2. Scikit-learn：機器學習函式庫
3. Pandas：資料處理函式庫
4. Jieba：中文斷詞函式庫
5. Jupyter Notebook：編譯器環境

學生需要預先安裝好 Python 2.7 的環境，安裝教學請見「安裝簡易教學」，建議非資訊科背景同學請資訊科同學在一旁協助。（請注意：由於每個人的電腦開發環境不同，安裝簡易教學並非適用於每個人的電腦，若遇到安裝問題，請善用 Google 查詢錯誤關鍵字尋求答案）

## 安裝簡易教學

### Mac OS X

#### Step1 安裝

Installing Python on Mac OS X（使用 homebrew）：https://pythonguidecn.readthedocs.io/zh/latest/starting/install/osx.html

#### Step2 Virtualenv 安裝與使用

打開終端機（Terminal），輸入：

```shell
pip install virtualenv
```

創建虛擬環境：

```shell
virtualenv ENV
```

啟動虛擬環境：

```shell
source ENV/bin/activate
```

#### Step3 下載教學範例環境

下載[程式碼](https://github.com/fukuball/Hands-on-AI-Tools)，使用 git clone 指令（或是下載壓縮檔也可以）：

```shell
git clone https://github.com/fukuball/Hands-on-AI-Tools.git
```

進入教學範例資料夾：

```shell
cd Hands-on-AI-Tools
```

安裝相關套件：

```shell
pip install -r requirements.txt
```

#### Step4 確認安裝完成，開啟 Jupyter Notebook

確認安裝完成，開啟 Jupyter Notebook：

```shell
jupyter notebook
```

Jupyter Notebook 會開啟一個伺服器，通常網址是：[http://localhost:8888](http://localhost:8888)，在瀏覽器輸入網址就可以看到筆記本了，到這邊應該就完成課程開發環境的安裝了～

### Windows

#### Step1 安裝

Installing Python on Windows：https://pythonguidecn.readthedocs.io/zh/latest/starting/install/win.html

#### Step2 Virtualenv 安裝與使用

打開命令提示字元（CMD），輸入：

```shell
pip install virtualenv
```

創建虛擬環境：

```shell
virtualenv ENV
```

啟動虛擬環境：

```shell
ENV\Scripts\activate
```

#### Step3 下載教學範例環境

下載[程式碼](https://github.com/fukuball/Hands-on-AI-Tools)，解壓縮後，進入教學範例資料夾：

```shell
cd Hands-on-AI-Tools
```

安裝相關套件：

```shell
pip install -r requirements.txt
```

#### Step4 確認安裝完成，開啟 Jupyter Notebook

確認安裝完成，開啟 Jupyter Notebook：

```shell
jupyter notebook
```

Jupyter Notebook 會開啟一個伺服器，通常網址是：[http://localhost:8888](http://localhost:8888)，在瀏覽器輸入網址就可以看到筆記本了，到這邊應該就完成課程開發環境的安裝了～

## 監督式學習

### 分類學習

1. 惡性腫瘤分類問題（二元分類）：使用 Logistic Regression Classifier、Stochastic Gradient Descent Classifier
2. 手寫數字分類問題（多元分類）：使用 Support Vector Machine Classifier

### 回歸預測

1. 美國波士頓房價問題：使用 Linear Regression、Stochastic Gradient Descent Regression

2. 美國波士頓房價問題：使用 Support Vector Machine Regression、Cross Validation 的技巧

## 非監督式學習

1. K-Means 分群，如何應用在手寫數字分類問題上

## 自然語言處理

1. Jieba 中文斷詞工具使用
2. 使用 LSA 潛在語意分析

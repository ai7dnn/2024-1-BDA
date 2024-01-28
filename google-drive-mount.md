# 코랩에서 구글 드라이브 연결 방법

## Colab에 연결해 새노트 파일 생성 후 다음 확인 

```sh
pwd
ls
```

## 다음으로 구글 드라이브(MyDrive)와 Colab(/content/gdrive/MyDrive)을 마운트(연결)

```python
from google.colab import drive
drive.mount('/content/gdrive')
```

## 연결된 상태 확인
> ![image](https://github.com/ai7dnn/2024-1-BDA/assets/70050528/7f95112a-bd86-4512-9a95-756dd831e668)

## 구글 드라이브의 저장 폴더 생성 및 이동

```sh
pwd
cd gdrive/MyDrive
mkdir 2024-big-data
cd 2024-big-data
```

## 깃허브의 다음 저장소를 클론(복제)

```python
!git clone https://github.com/EasysPublishing/do_it_pandas.git
```

## 저장소 복제 확인
> ![image](https://github.com/ai7dnn/2024-1-BDA/assets/70050528/610c5160-daaa-4afd-960f-d3cb70d7102d)





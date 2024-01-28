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

- 다음 아이콘으로도 바로 마운트 가능, 이 경우 /content/drive/MyDrive 로 자동 연결
> ![image](https://github.com/ai7dnn/2024-1-BDA/assets/70050528/33d8219d-9d9f-450e-adf3-a7d149c320b3)
 

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

## 복제된 노트북 파일 편집
> - 구글 드라이브에서 노트북 파일로 이동해 열기
> ![image](https://github.com/ai7dnn/2024-1-BDA/assets/70050528/e41e9d8e-e8dd-4e37-af72-877fc389c5e7)






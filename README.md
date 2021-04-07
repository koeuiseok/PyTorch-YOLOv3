# PyTorch-YOLOv3 실행 방법
### HW 차량지능기초 

##구현 환경
	- linux (window 10에서 WSL 사용)
	- pip3
  - python 3.5.2

##코드 실행
1. 코드 다운로드

2. python3, pip3 다운로드 

3. 필요 패키지 다운로드
```
pip3 install –r requirements.txt
```  

4. ~/weights, 즉 code의 weights 디렉토리에 존재하는 download_weights.sh을 실행
```
bash download_weights.sh
```  
4.1 만약 에러가 난다면, .sh 파일 내부의 shell 명령어를 하나씩 직접 실행하는 방법이 존재한다.

5. /coco 디렉토리에 존재하는 get_coco_dataset.sh를 bash를 통해 실행 시킨다.
```
bash get_coco_dataset.sh
```  

6. 다음 명령어로 실행 가능
```  
python3 detect.py --image_folder data/samples/
```  

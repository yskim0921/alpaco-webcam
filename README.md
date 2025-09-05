# alpaco-webcam
윈도우에서 웹캠을 열 수 있는 예제 프로젝트입니다.

# 🚀 Webcam Streaming with FastAPI & OpenCV

## 🛠️ 환경
- **OS**: Windows  
- **Python**: 3.8 (conda 가상환경)  
- **Frameworks**: FastAPI, Uvicorn  
- **Library**: OpenCV  

---

## 📦 설치 및 실행 방법

### 1. Conda 환경 생성 및 접속
```
conda activate base
conda create -n alpaco python==3.8
conda activate alpaco
```
### 2. 필수 라이브러리 설치
```
pip install fastapi
pip install "uvicorn[standard]"
pip install opencv-python
```

### 3. FastAPI 서버 실행
```
python webcam_server.py
```

서버 실행 후 브라우저에서 확인:
```
http://localhost:8500/test → API 테스트 ({"msg":"hi"} 출력)
```
```
http://localhost:8500/video → 웹캠 스트리밍 확인
```

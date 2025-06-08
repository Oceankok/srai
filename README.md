# Final Project: Spatial Representations for Artificial Intelligence (SRAI)

## 🎯 Goal

This project extends the open-source `srai` library by contributing documentation and functionality improvements to better support geospatial data representation in AI systems.

The purpose of this project is to understand the structure of open-source collaboration through:
- Forking a mother repository
- Becoming a contributor
- Modifying and enhancing parts of the project
- Creating and verifying a working Docker image

## 📋 Requirements

- Python >= 3.9
- Libraries used:
 
  - srai
 

## 🐳 How to Run

You can run the code directly with Python or via Docker.

git clone https://github.com/Oceankok/srai.git
cd srai
pip install -r requirements.txt

# 또는 도커 사용 시:
docker build -t final_2021040019:v1 .
docker run -it final_2021040019:v1
📁 Project Structure
bash
복사
편집
srai/
├── srai/                     # Core library
│   └── embedders/            
├── tests/                    
├── examples/                 
├── pyproject.toml            # 프로젝트 환경 정의
└── README.md                 # 이 파일
✅ Execution Result

# 예시 실행 결과
python -m srai.examples.run_embedding
Output:
> Embeddings generated successfully with buffered region support
> 
📌 Notes
본 프로젝트는 Chungbuk Univ. OSS Final Project로 제출됩니다.

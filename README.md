# learning_mate
AI에게 지문을 보여주고 질문해 보세요!


해당 코드는 샘플 모델과 이미지들과 가상환경이 전부 빠져있는 순수 서버 코드 입니다.

압축을 풀고 사용하세요!

# usage

1. 아래 종속성 패키지를 전부 파이썬 가상환경에 설치하세요

2. Team4_server\Flask\flask_deep\static\models 경로에 ocr 모델을 넣으세요

3. Team4_server\Flask\flask_deep\tacotron2_project 경로에 타코트론 모델을 넣으세요

4. 파이썬 가상환경에서 start_flask.py 실행하세요 

5. 웹 페이지에서 실행 사용해보세요!

# models
구글 드라이브 링크입니다!

https://drive.google.com/file/d/1I-fA2unBB3aGb_tSIearYnemSxPfVaOT/view?usp=sharing


# requirements

파일에 첨부했습니다!

absl-py==1.0.0
appdirs==1.4.4
astunparse==1.6.3
audioread==2.1.9
cachetools==5.0.0
certifi==2021.10.8
cffi==1.15.0
charset-normalizer==2.0.12
click==8.1.2
colorama==0.4.4
decorator==5.1.1
easyocr==1.4.2
filelock==3.6.0
Flask==2.1.1
flatbuffers==2.0
gast==0.5.3
google-auth==2.6.5
google-auth-oauthlib==0.4.6
google-pasta==0.2.0
grpcio==1.44.0
h5py==3.6.0
huggingface-hub==0.5.1
idna==3.3
imageio==2.17.0
itsdangerous==2.1.2
Jinja2==3.1.1
joblib==1.1.0
keras==2.8.0
Keras-Preprocessing==1.1.2
libclang==13.0.0
librosa==0.9.1
llvmlite==0.38.0
Markdown==3.3.6
MarkupSafe==2.1.1
networkx==2.6.3
nltk==3.7
numba==0.55.1
numpy==1.21.6
oauthlib==3.2.0
opencv-python-headless==4.5.4.60
opt-einsum==3.3.0
packaging==21.3
pandas==1.3.5
Pillow==9.1.0
pooch==1.6.0
protobuf==3.20.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycparser==2.21
pyparsing==3.0.8
python-bidi==0.4.2
python-dateutil==2.8.2
pytz==2022.1
PyWavelets==1.3.0
PyYAML==6.0
regex==2022.3.15
requests==2.27.1
requests-oauthlib==1.3.1
resampy==0.2.2
rsa==4.8
sacremoses==0.0.49
scikit-image==0.19.2
scikit-learn==1.0.2
scipy==1.7.3
six==1.16.0
SoundFile==0.10.3.post1
tensorboard==2.8.0
tensorboard-data-server==0.6.1
tensorboard-plugin-wit==1.8.1
tensorflow-io-gcs-filesystem==0.24.0
termcolor==1.1.0
tf-estimator-nightly==2.8.0.dev2021122109
threadpoolctl==3.1.0
tifffile==2021.11.2
tokenizers==0.12.1
torch==1.11.0
torchaudio==0.11.0
torchvision==0.12.0
tqdm==4.64.0
transformers==4.18.0
typing_extensions==4.2.0
Unidecode==1.3.4
urllib3==1.26.9
Werkzeug==2.1.1
wrapt==1.14.0


만약 실행이 안된다면 텐서플로우 1.15 혹은 1.14 버전을 설치하세요

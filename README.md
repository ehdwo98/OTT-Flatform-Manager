# OTT-Manager

##Settings

sudo apt update
sudo apt install python3-zip
sudo apt install python3-venv

가상환경 생성
cd
mkdir vevns
cd venvs
python3 -m vevnv webp
//source ~/venvs webp /bin/activate 를 치면 가상환경이 활성화됨
source ~/venvs webp /bin/activate

pip install wheel
pip install -U Flask
pip install -U Flask Script
pip install -U Flask WTF
pip install -U Flask Migrate

프로젝트 생성, 해당 위치에서 프로젝트 진행
cd
mkdir projects
cd projects

//projects 디렉토리에 첨부한 webp를 이동시켜 위치
cd webp
flask run
//실행됨!

# Usage

## 环境要求
- python 3.7
- pip3

## 部署步骤
- 克隆本仓库 `git clone https://github.com/LeeJAJA/Microsoft_Speech_API.git`
- `cd Microsoft_Speech_API`
- `pip3 install -r requirements.txt`
- `cd Microsoft_Speech_API⁩/sda⁩/data && wget 'https://github.com/LeeJAJA/Microsoft_Speech_API/releases/download/1.0/crema.dat' && wget 'https://github.com/LeeJAJA/Microsoft_Speech_API/releases/download/1.0/grid.dat' && wget 'https://github.com/LeeJAJA/Microsoft_Speech_API/releases/download/1.0/timit.dat' && cd ../..` 
- `python3 run.py`
- 使用浏览器（推荐 Chrome）打开 Microsoft_Speech_API/index.html
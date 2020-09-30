# STOCK-LAB

## Install Anaconda

https://www.anaconda.com/distribution

## How to Run

### Anaconda Prompt

아나콘다 가상환경 변수를 32bit로 설정(COM은 32bit에서만 사용할 수 있음.)
`set CONDA_FORCE_32BIT=1` 

가상환경 생성
`conda create -n stocklab python=3.6.8`

가상환경 실행
`activate stocklab`

가상환경 종료
`deactivate`

### Anaconda 32-bit 환경으로 만들기
set CONDA_FORCE_32BIT=1 \rightarrow→ 아나콘다 가상환경 변수를 32bit로 설정
conda create -n py35_32 python=3.5 \rightarrow→ 가상환경 이름이 py35_32이고 python 3.5를 생성
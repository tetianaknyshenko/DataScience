# DateAnalysis

Створити віртуальне середовище https://dev-gang.ru/article/kak-sozdat-virtualnuu-sredu-python-eq6y9hvsc3/


Ось тут можна почитати, як створити віртуальне середовище для python

https://docs.python.org/3/library/venv.html

Зтворюємо папку .venv у корні репозиторію

 mkdir .venv 

Зтворюємо environment

 python -m venv .venv 

Заходимо в нього

 source .venv/bin/activate 

Встановлюємо бібліотеки із requirements.txt

 pip install -r requirements.txt 

Зтворюємо kernel, який можна використовувати у Jupyter notebook

https://janakiev.com/blog/jupyter-virtual-envs/

 python -m ipykernel install --user --name=myenv 

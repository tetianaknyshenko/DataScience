# DateAnalysis

Створити віртуальне середовище https://dev-gang.ru/article/kak-sozdat-virtualnuu-sredu-python-eq6y9hvsc3/
UBUNTU VisualCode
Як переходити по папках
https://comp-security.net/%D0%BA%D0%B0%D0%BA-%D0%BF%D0%B5%D1%80%D0%B5%D0%B9%D1%82%D0%B8-%D0%B2-%D0%BF%D0%B0%D0%BF%D0%BA%D1%83-%D0%B2-%D1%82%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%B0%D0%BB%D0%B5-linux/
python3 -m venv .venv

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

Приклад
SDAN:~$ cd ..
SDAN:/home$ cd \forecasting
SDAN:/home$ cd mantula/
SDAN:~$ pwd
/home/mantula
SDAN:~$ ls
'forecasting'   test_ve
SDAN:~$ cd test_ve/
SDAN:~/test_ve$ python3 -m venv .venv
SDAN:~/test_ve$ source "/home/mantula/test_ve/.venv/bin/activate"
(.venv) SDAN:~/test_ve$ echo $test_ve
(.venv) mantula@WIN-7GNRQC1SDAN:~/test_ve$ pip freeze
(.venv) mantula@WIN-7GNRQC1SDAN:~/test_ve$ pip install numpy
Collecting numpy
  Using cached numpy-1.25.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (17.6 MB)
Installing collected packages: numpy
Successfully installed numpy-1.25.1
(.venv) mantula@WIN-7GNRQC1SDAN:~/test_ve$ pip freeze
numpy==1.25.1
(.venv) mantula@WIN-7GNRQC1SDAN:~/test_ve$ 

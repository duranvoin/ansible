# ansible
Personal ansible repo!

для работы с репой нужно

1) создаем виртуальное окружение
```
python3.14 -m venv ./.venv
source ./.venv/bin/activate
pip install -r requirements.txt
deactivate && source ./.venv/bin/activate
```
2) для подгрузки ролей
```
ansible-galaxy install -r requirements.yml
```

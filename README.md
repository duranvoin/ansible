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
2) для подгрузки ролей и коллекций
```
ansible-galaxy install -r requirements.yml
```

Состав репы: 
1) Плейбук common - позволяет настроить хосты в зависимости от роли. (на 27.04.2026 добавлен функционал по базовой установке пакетов и подготовки кубер нод)

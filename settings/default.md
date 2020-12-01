# Основные настройки git клиента

1. **git config name *[название параметра]* value *[значение параметра]***
      
      `git config name value`  

## Полезные настройки:

- **user.name** — Имя, которое будет использоваться при создании коммита

- **user.email** — Email, который будет 
использоваться при создании коммита

- **core.excludesfile** — Файл, шаблон которого будет использоваться для игнорирования определённых файлов глобально

- **core.editor** — Редактор по умолчанию
commit.template — Файл, содержимое которого будет использоваться для сообщения коммита по умолчанию (См. Работа с коммитами).

- **help.autocorrect** — При установке значения 1, git будет выполнять неправильно написанные команды.

- **credential.helper *[mode]*** — Устанавливает режим хранения учётных данных. ***[cache]*** — учётные данные сохраняются на определённый период, пароли не сохраняются (--timeout ***[seconds]*** количество секунд после которого данные удаляются, по умолчанию 15 мин). ***[store]*** — учётные данные сохраняются на неограниченное время в открытом виде (--file ***[file]*** указывает путь для хранения данных, по умолчанию ~/.git-credentials).
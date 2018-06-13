﻿# Хранилище списка групп с американскими фьючерсами
Нужно для легкого способа корректировки (удаление, добавление, переименование) списка групп символов.

## Как пользоваться:
Если удаляем/добавляем/заменяем группы фьючей, правим файл [list.json](./list.json)
Коммитим, пушим.  
После этого клиенты (скринер) при очередном обновлении символов подтянут эти изменения.

## ВАЖНО!
Важно понимать, что добавляя группу в соответствующий файл, мы должны быть уверены в ее наличи на udf-proxy всех клиентов во всех локейшенах
# dadata_search_by_inn
Поиск информации о юридических лицах и ИП по ИНН. 

- Код на R.
- Используется сервис https://dadata.ru/

Для использования необходимо зарегистрироваться на сервисе и получить токен, который нужно вставить в код в соответствующем месте.

На бесплатном тарифе лимит составляет 10000 запросов в сутки

Настроены следующие поля:
- inn - ИНН, который ищется
- inn_found - Найденный ИНН, используется для контроля, т.к. 10 символов ИНН юрлица могут входить в 12 символов ИНН ИП
- name - Название ЮЛ или ИП
- status - Статус (действующее / ликвидировано и т.д.)
- n_branches - Количество филиалов
- ogrn - ОГРН
- okpo - ОКПО
- okato - Код ОКАТО
- oktmo - Код ОКТМО
- okogu - Код ОКОГУ
- okved - Код основного вида деятельности по ОКВЭД
- geo_lat - Гео позиция (широта)
- geo_lon - Гео позиция (долгота)
- address - Адрес
- opf_name - Организационно-правовая форма
opf_code - Код организационно-правовой формы 
liq_date - Дата ликвидации ЮЛ / ИП

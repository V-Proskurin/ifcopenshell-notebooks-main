# ifcopenshell-notebooks-main

Задачи:
1. Научится изменять свойства и добавлять новые свойства в ifc файл к объекту
2. Прикрутить этот скрипт к веб интерфейсу https://x1team.ru/bim-viewer/ (прорисовать дизайн как менять, верстку и прикрутить бэк)
3. Связать веб интерфейс с чатами вордпресс. Понять где сохраняется view_point и как она привязывается к ifc файлу. Скорее всего viwepoint не хранятся в ifc. Они хранятся
в вордпресс, но могут содержать в себе координаты точки абсолютные и возможно относительные. И тогда надо понять, что будет если именно 3d всех объектов переместится, 
переместятся ли точки view_point. 
4. Смотреть чаты можно будет только на сервере, так как разграничение прав хранится на сервере. Пока это не преодолимый минус. Их нельзя в контейнер
или еще как то децентрилизовать. 
5. Но для MVP это отлично. А дальше можно будет все под децентрализованный мессенджер переписать.
6. Есть стандарт bcf и вот пример файла https://github.com/V-Proskurin/ifcopenshell-notebooks-main/blob/master/ifcopenshell-notebooks-main/bcfViewpoint.json он описывает как сохранять viewpoint, привязывать к чату, хранить чаты, чтобы все в автодеске открывалось, но нам на первом этапе не надо

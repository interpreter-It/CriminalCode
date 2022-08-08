![image](https://user-images.githubusercontent.com/84613812/147426474-85751a47-9f96-41ce-b5c7-028277be2d97.png)

# IBook
-проект социальной сети. Оригинальность идеи заключается в её возможностях: отсутствие ограничений на передачу файлов, работа серверов по типу торента, открытие 3д моделей, возможности персонализации(цвет страницы пользователя, музыка при входе), бесплатная музыка, расшаривание разных чатов на одном экране, снижение нагрузки серверов путём передачи ip целевым устройствам, применение vpn, бизнес сообщества и криптаволюта для начинающихся стартапов.
#
Гланый принцип: отсутсвие цензуры и анонимность.
# Цели
- [ ] Сделать возможным хранить сообщения на гугл диске.
- [ ] Обдумать и изучить алгоритм хеширования для использования в чатах.
- [ ] Максимально продумать способы децентрализации соцсети.
- [ ] сделать авторизацию через Яндекс
- [ ] И много чего ещё :)
# На данный момент:
![Screenshot_20220808_073939](https://user-images.githubusercontent.com/84613812/183340567-191ca7aa-fbea-4752-a0a4-c7c566a29fc4.png)
Реализована авторизация через гугл и решена прроблема уведомлений в фоновом режиме:
Реализован текстовый мессенджер:
![Screenshot_20220808_074112](https://user-images.githubusercontent.com/84613812/183340692-cac69d28-5b95-49c7-8027-90ded5c2b58e.png)

# Выявленные проблемы версии 2.5.1:
- При потери сети фоновая работа приложения завершается и восстанавливается только после входа.
- Не работает скроллинг до последнего сообщения при вводе нового.
- Можно отправлять пустые сообщения.
- При авторизации через гугл нет проверки авторизации на сервере (может привести к ошибкам при повторном входе при неудачной авторизации).
- Приходят уведомления, когда находишься в чате.
- Приходящие новые сообщения отображаются во всех чатах.

#Скачать версию 2.5.1(update to optimize phone battery consumption):
https://drive.google.com/drive/folders/1bpka4aQ-VYA0u6BjWbHk3QMvAlDVkf3a?usp=sharing

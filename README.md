# 🛒 Тестирование веб-приложений

Для учебного проекта онлайн-магазина [demoshopping.ru](https://demoshopping.ru/) была создана подробная тестовая документация, проведено тестирование, заведены баг-репорты, а также выполнен перехват трафика.

## Тест-план тестирования
По ссылке ниже находится таблица на тест-план к проекту "Интернет-магазин". <br>
[Тест-план](https://docs.google.com/spreadsheets/d/1ewmkm0XOZo3cwC9w6tht4DHTId7oZuz7Z-rYuBXASDc/edit?usp=sharing)

## Чек-лист и тест-кейсы
По ссылкам ниже можно найти:
- Чек-лист для проверки модулей Регистрация, Авторизация, Каталог Продукта, Корзина и Форма Оплаты.<br>
  Тестовые данные для проверок находятся на отдельных листах в таблице.<br>
  [Чек-лист](https://docs.google.com/spreadsheets/d/1LXiLJHsiDnpp6RF_jgjyOO9FZk5U4eUnZhTmsBW8ExU/edit?usp=sharing)
  
- Тест-кейсы к модулям Корзина, Форма оплаты, Регистрация/Авторизация и Каталог в формате PDF, импортированные из QASE.<br>
  [Тест-кейсы](https://app.qase.io/project/TD)<br>
  [Тест-кейсы в формате PDF](https://drive.google.com/file/d/1-7-RhV2_XvTtvhcQPE5zO3lj5U0P5GRk/view?usp=sharing)

## Тестирование модулей Корзина и Оплата
По ссылкам ниже находятся тестовые артефакты по результату тестирования модулей. <br>
- Таблица google sheets с баг-репортами. <br>
  [Баг-репорты](https://docs.google.com/spreadsheets/d/1O1KP0rok2-2D1IU6N4IQIR8fVpAH1MGfOr3ZuuuwA0M/edit?usp=sharing)

- Ссылка на скриншоты к баг-репортам на google drive. <br>
  [Вложения](https://drive.google.com/drive/folders/1xQpavRVQmHFDCo3-61Z8JB-XgkKyQNBu?usp=sharing)

##  Перехват трафика

Также при работе с веб-приложениями изучался перехват траффика с использованием Charles Proxy. Был выполнен перехват запроса и изменено колличество товара, добавляемого в корзину. Смоделирована ситуация, перенаправления трафика с продовой версии сайта на тестовое окружение. А также смоделирована ситуация, когда запрос возвращает ошибку 403.


[Видео](https://drive.google.com/file/d/1f8-tC5PCVBSFTuEliJUf89BKD6rKhKxJ/view?usp=sharing)
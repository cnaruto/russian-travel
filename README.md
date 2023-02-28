# Проект: Путешествие по России

### Обзор
* Интро
* calc
* media

**Интро**

Проект направленный на отработку адаптивной и отзывчивой верстки,
а также использование технологии Grid Layout.

**calc**

Для создания отзывчего макета требуется воссоздать линейное изменение различных размеров таких как font, margin и тд. Линейное изменение можно изобразить прямой на графике функций.
![Линейный график функции](/image/linear.jpg)  

И используя формулу прямой через две точки (x-x1)/(x2-x1)=(y-y1)/(y2-y1) совместно с calc получим:
*calc( (100vw - Vmin)/(Vmax - Vmin) * (Fmax - Fmin) + Fmin);*
* [Короткое объяснение](https://iskraa.ru/blog/development/responsive-font)
* [Подробное объяснение](https://habr.com/ru/company/vk/blog/315196/)

**media**

Одного отзывчего макета недостаточно для правильного отображения сайта, на помощь приходят Медиавыражения:
* @media screen and (min-width: 100px) {}

1. *screen - ключевое слово для вывода информации с помощью экрана*
2. *and - объединяющее "И"*
3. *(min-width: 100px) - размер при котором срабатывает медиа запрос.*



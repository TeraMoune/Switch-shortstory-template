# Change-shortstory-template-DLE
Переключатель шаблонов коротких новостей.

![Image alt](https://user-images.githubusercontent.com/44625352/54727544-ae10b500-4b78-11e9-850a-0f64054bdf9f.jpg)

Данный модуль не то, что есть у [Sander'а](https://sandev.pro/web/24-pereklyuchenie-shablonov-shortstory.html), который меняет class'ы.
И смена вида осуществляется лишь за счёт правил CSS.

Мне же данный подход не очень приглянулся, хотя бы из за того, что каждый раз видно как при загрузке страницы в начале видны стандартный вид, а потом переключает на какой нужно. Мне это напоминает полумеру.

---
 - Использует Cookie для хранения префикса шаблона.
 - Использует отдельные tpl шаблоны.
 - Работает с включённым кэшем.
 - Неограниченное создание шаблонов.
 - Ajax метод переключения.
---

Загрузите плагин, Подключите скрипт (Если используете свой скрипты для создания Cookie, отредактируйте плагин в файле над правками main.php js код) для изменений Cookie.
В **Настройке системы** в разделе **Новости** есть одно единственное поле в котором перечисляются списки шаблонов, точней их префиксы. 

Перечислите шаблоны через запятую.

  - prefix шаблона tpl файла | Название стиля (в качестве названий можно использовать html код и вставлять картинку)
  
default|Стандартный вид,thumb|Кубики миниатюр

default в данном случае являеться shortstory.tpl, а **thumb** уже будет префиксом shortstory_**thumb**.tpl

### Donate
Для материальной благодарности.

<img src="https://qiwi.com/favicon.ico" width="16" height="16"> [Qiwi](https://qiwi.me/teramoune)

 - Z990082286464
 - 4100115063692304 (yandex)

teramoune@gmail.com на всякий случай.

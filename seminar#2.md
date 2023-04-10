# Создание туториала по GIT

## Как создать репозиторий


**Чтобы создать локальный репозиторий, напишите следующую команду в терминал:**
```
git init
```

# Руководство по Markdown

## Раздел первый - Заголовки 





## Раздел второй - Списки




4. Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse id sem consectetuer libero luctus
adipiscing.
На самом деле не важно как в коде пронумерованы пункты,
главное, чтобы перед элементом списка стояла цифра
(любая) с точкой. Можно сделать и так:
0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4
Список с абзацами:
* Раз абзац. Lorem ipsum dolor sit amet, consectetur
adipisicing elit.
* Два абзац. Donec sit amet nisl. Aliquam semper ipsum
sit amet velit. Suspendisse id sem consectetuer libero
luctus adipiscing.
* Три абзац. Ea, quis, alias nobis porro quos laborum
minus sed fuga odio dolore natus quas cum enim
necessitatibus magni provident non saepe sequi?
 Четыре абзац (Четыре пробела в начале или один tab).


## Раздел третий - Исходный код

Бла-бла-бла, исходный текст какой-то код:
```css
*{
    font-famile: Montserrat;
}
```
## Раздел третий - Исходнрый код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">

 <span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```

Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.

## Раздел четвёртый - Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:


| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.


| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.


## Как добавить файл на отслеживание

**Чтобы добавить новый единственный файл на отслеживание, вам будет необходимо сделать следующее:**

- Прописать команду git add .

**Для добавления нового непервого файла в репозиторий нужно прописать следующее:**

- Прописать команду git add "имя_файла.расширение_файла"

**Для фиксации изменений в файле нужно прописать следующее:**

- Прописать команду git commit -m "<комментарий>", где <комментарий> - это комментарий о фиксированном изменении, написанный в определённом формате, принятом в индустрии/на предприятии

**Для просмотра версий, дат их создания и их авторов нужно прописать:**
```
git log
```

**Для укороченного просмотра версий нужно прописать:**

- git reflog

**Для оформления цитат используется символ ">"**

- > This is an example to showcase the usage of symbol ">".

**Для переключений между ветвями дерева версий нужно прописать:**

* git checkout [<branch>]
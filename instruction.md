![логотип git](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/640px-Git-logo.svg.png)

---

# <div align="center"> <span style="color:green"> Инструкция по работе с командами git </span> </div>

---

## <div align="center"> <span style="color:red"> Основные команды </span> </div>

* __git init__ - _инициализирует новый репозиторий **git** и начинает отслеживание существующего каталога._

* __git add__ - _добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита._

* __git commit__ - _берёт все данные, добавленные в индекс с помощью **git add**, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок._

* __git status__ - _показывает состояния файлов в рабочем каталоге и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов._

* __git log__ - _используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. Также возможен вывод в виде графа/дерева (**git log --graph**)._

* __git diff__ - _используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между рабочей копией и индексом (**git diff**), разница между индексом и последним коммитом (**git diff --staged**), или между любыми двумя коммитами (**git diff master branch_name**)._

* __git checkout__ - _используется для переключения коммитов/веток и выгрузки их содержимого в рабочую директорию._

* __git rm__ - _используется для удаления файлов из индекса и рабочей директории._

---
## <div align="center"> <span style="color:red"> Команды по ветвлению и слиянию </span> </div>

* __git branch__ - _используется для перечисления веток, а также создания новых (**git branch branch_name**), удаления существующих (**git branch -d branch_name**) и смены их имени (**git branch -m old-name new-name**)._

* __git merge__ - _используется для слияния одной или нескольких веток в текущую. Затем она устанавливает указатель текущей ветки на результирующий коммит._

---

*Пример создания конфликта.*

test git pull



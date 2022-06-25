# Рассмотрим работу с Git

1. Вам необходимо скачать и установить Git по ссылке https://git-scm.com/downloads выбрав свою операционную систему.

2. После скачивания b ecnfyjdrb Git, Вам необходимо запустить командную строку Git Bash и ввести следующие команды:
> **git config --global user.name "Ваше ФИО"**

> **git config --global user.email "ваш_адрес_электронной@почты.ru"**

3. Скачать и установить Visual Studio Code по следующей ссылке https://code.visualstudio.com/download, выбрав свою операционную систему.

4. После скачивания и устанвоки, при необходимости устанвоить в Visual Studio Code русский язык, для этого, вам нужно нажать кнопку Расширения в левом столбике (нижняя иконка "квадратики"),
после чего в поисковике набрать Russian Language Pack и установить расширение. Перезапустить Visual Studio Code.

5. После того как будет все готово, Вам необходимо создать папку в корне диска с названием на английском языке, без пробелов. Далее в VSCode Перейти и нажать сверху слева - ФАЙЛ > Открыть Папку > и открыть ранее созданную Вами папку.

6. Дальше переходим сверху в раздел Вид > Терминал.

7. В строке терминала вводим команду:
> **git init**

После чего Git начинает отслеживать изменения в вашей созданной папке.

8. Создаем файл с любым названием на английском языке, например readme.md с расширением md.

9. Ввводим в терминале команду:
> **git add readmi.md**

После чего в репозиторий будет добавлен Ваш файл readme.

10. алее вносим данные, текс и т.д. в созданный вами файл readme. После внесения всех изменений, необходиом Перейти сверху слева в ФАЙЛ > Сохранить.

11. После сохранения ваших изменений, необходимо данные изменения предоставить (передвть/добавить) в репозиторий, для этого набираем следующие команды:
> **git add readme.md**
> **git commit -m "любое название или версии"**

12. Далее переходим в левый столбик и кликаем на иконку, третья сверху (с тремя кружочками) и нажимаем отправка фиксаций.

13. Преходим на GitHub и видим свои изменения и сохранения.
# MomoTranslator
Pure OpenCV comic translation tool

![Commit activity](https://img.shields.io/github/commit-activity/m/alicewish/MomoTranslator)
![License](https://img.shields.io/github/license/alicewish/MomoTranslator)
![Contributors](https://img.shields.io/github/contributors/alicewish/MomoTranslator)

Реконструировано мое программное обеспечение для помощи в переводе комиксов MomoTranslator с помощью GPT4


Текущими функциями переработанной версии являются：

1. Найдите сетку комиксов

2. Найдите комические пузыри

3. Отсортируйте пузырьки в соответствии с сеткой и распознайте текст

4. Перевод


Функция встраивания еще не была восстановлена, поэтому она не будет введена.

Кроме того, мне также нужно понаблюдать, не будет ли злоупотреблений после раскрытия кода, таких как создание некачественных “китаизированных” комиксов и видеороликов.


Предыдущее видео с демонстрацией функции смотрите в <url>/video/BV1P54y1Q7fW/

После рефакторинга функции встраивания я сделаю новое демонстрационное видео.


Особенностью программного обеспечения является то, что основные функции основаны на opencv, и pytorch не требуется.

Вы также можете использовать pytorch для повышения точности.


Причина, по которой я не раскрывал код раньше, была связана с плагиатом, сексуальными домогательствами и насилием в Интернете со стороны ряда видео-рассказчиков. Я беспокоюсь, что написанный мной код станет инструментом для моего убийства после того, как он станет открытым исходным кодом.

В связи с текущим развитием ChatGPT, я думаю, могут быть и другие способы избежать худших результатов. Сначала вы можете попробовать open source.


Оригинальное программное обеспечение (Mo Mo Sinicization) имеет полную функцию гашения, встраивания и экспорта в PSD в Photoshop. Эта функция реконструируется. Дополнительные требования могут быть указаны в выпуске.

# устанавливать

Во-первых, убедитесь, что на вашем компьютере установлен Python 3.9 или более поздней версии.Вы можете проверить версию Python, введя следующую команду в командной строке：
```bash
python --version
```

Клонируйте этот репозиторий или загрузите ZIP-файл и распакуйте его.

Используйте следующую команду для установки необходимых библиотек Python：
```bash
pip install -r requirements.txt
```

# использовать

В командной строке перейдите в папку проекта и запустите pyqt5_momotranslator.файл py：

```bash
python pyqt5_momotranslator.py
```

После запуска программы появится графический пользовательский интерфейс.



# разрешение

Лицензия MIT
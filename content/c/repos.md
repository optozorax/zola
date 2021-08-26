+++
title = "Репозитории"
description = "Краткое описание моих репозиториев."

[extra]
image = "ideas/thumbnail.jpg"
+++

Все репозитории отсортированы по моей субъективной оценки годности. Чем выше, тем более годным я его считаю.

# Мои проекты с кодом

Все проекты, где есть программирование.

|Ссылка|Описание|
|-|-|
|[space_objects](https://github.com/optozorax/space_objects)|Библиотека для работы с системами координат и преобразованиями между ними. Она настолько мощно абстрагирует работу с системами координат, что я использую её в каждом своем проекте, где есть хоть немного графики.|
|[portals_opengl](https://github.com/optozorax/portals_opengl)|Рендеринг порталов при помощи OpenGL, поддерживает не только рекурсивные порталы, но ещё и объёмные.|
|[path-tracing](https://github.com/optozorax/path-tracing)|Полностью заного переписал [этот рейтрейсинг](https://github.com/optozorax/ray-tracing), улучшил архитектуру, добавил возможность рисовать не только path-tracing (фотореалистичная графика), но и ray-tracing (быстрый, но не такой реалистичный). Используется в множестве моих других проектов.|
|[ray-tracing](https://github.com/optozorax/ray-tracing)|Форк кода одного чувака с гитхаба. Выбрал именно его код, потому что он был максимально простым, и компилировался без проблем, а результаты давал впечатляющие. При помощи этого кода я впервые понял как работает рейтрейсинг и решил разобраться в нем ещё лучше, улучшив код, добавив пару фич.|
|[keyboard_layout](https://github.com/optozorax/keyboard_layout)|Моя раскладка клавиатуры плюс инструменты для записи и показа статистики нажатий.|
|[TinyWindowsGraphics](https://github.com/optozorax/TinyWindowsGraphics)|Вторая оболочка над функциями WinApi. Наследует идеи [GraphWinApi](https://github.com/optozorax/GraphWinApi), но уже с намного более продуманной архитектурой. Так же имеет в себе оболочку над [AGG](https://github.com/tomhughes/agg) для рисования со сглаживанием, [EasyBMP](http://easybmp.sourceforge.net/) и [STB](https://github.com/nothings/stb) для сохранения изображений в файлы. Используется в множестве моих других проектов, но не как библиотека для создания приложений, а как графическая библиотека. И я думаю, надо выносить часть, отвечающую за цвет, точки и рисование в отдельную либу.|
|[olymp](https://github.com/optozorax/olymp)|Решение олимпиадных задач. Пока что все задачи в этом репозитории берутся и проверяются на [olymp.nstu.ru](http://olymp.nstu.ru).|
|[partially-drawing-image-algorithm](https://github.com/optozorax/partially-drawing-image-algorithm)|Алгоритм для рисования изображения, когда оно получено не полностью. Задает не только порядок обхода пикселей, но и сам алгоритм рисования этого изображения. Использовалось для рейтрейсинга, чтобы в реальном времени показывать то, что рендерилось очень долго. Время работы от количества пикселей: линейное. К сожалению имеет в зависимостях [TWG](https://github.com/optozorax/TinyWindowsGraphics), поэтому не получится использовать её кому-то кроме меня.|
|[GraphWinApi](https://github.com/optozorax/GraphWinApi)|Оболочка над функциями WinApi. Одна из первых библиотек и больших программ на C++, поэтому написано очень некрасиво.|
|[slovo-gonka](https://github.com/optozorax/slovo-gonka)|Программа для изучения английских слов. Интерфейс простейший: слово на английском и четыре кнопки, где надо выбрать правильный ответ. Написана на основе [TWG](https://github.com/optozorax/TinyWindowsGraphics). Слова я по ней не учу \*facepalm\*.|
|[slovo_gonki2](https://github.com/optozorax/slovo_gonki2)|Проект по написанию нового приложения для изучения английских слов совместно с [Ldaon](https://github.com/Ldaon). Пока в разработке.|
|[fast_tree_point_in_polygon](https://github.com/optozorax/fast_tree_point_in_polygon)|Попытка изобрести алгоритм для определения нахождения точки внутри полигона при помощи разложения пространства полигона в дерево. Попытка неудачная, либо мне просто не хватило терпения.|
|[keyboard](https://github.com/optozorax/keyboard)|Попытка написать код для нахождения оптимальной раскладки на основе идеи об аккордах. Забросил проект по причине невероятной сложности, которую себе воздвиг (хотел одновременно учитывать слои и продублированные клавиши). [Дневник разработки раскладки](http://klavogonki.ru/u/#/517589/journal/5b6df4cddf4e4d55728b4567).|

# Статьи и разного рода писанина, LaTeX

|Ссылка|Описание|
|-|-|
|[newtons_method_article](https://github.com/optozorax/newtons_method_article)|Объясняю как работает метод Ньютона для решения систем нелинейных уравнений. Стараюсь рассказать это максимально подробно и качественно. Захотел написать после того, как сам разобрался в нём и не нашел чего-то подобного в интернете.|
|[Формулы по математике](https://github.com/optozorax/math-formulas)|Собираю все возможные формулы по математике ещё со школы.|
|[Отчет по лабораторной работе в LaTeX](https://github.com/optozorax/latex_report)|Так как я с третьего курса пишу отчеты в LaTeX, то я решил собрать большинство штук, которые я использую в одно место, а так же заготовку титульного листа. Намного удобнее Word'а для генерации таблиц, графиков, а так же математических формул. Но к сожалению очень большой порог вхождения и за полгода существования репозитория, никто из моих одногруппников так этим и не воспользовался.|
|[Этот сайт](https://github.com/optozorax/optozorax.github.io)|Без комментариев.|
|[sun-eclipses](https://github.com/optozorax/sun-eclipses)|Как-то собрал в одно место все солнечные затмения за 21 век благодаря одной проге, чтобы это индексировалось поисковиками, и я обрел популярность. Хоть попытка неудачная, зато я знаю когда будет ближайшее солнечное затмение в моем городе.|


# Лабораторные работы для универа.

Выложил для того, чтобы говорить одногруппникам: `посмотри на гитхабе как я сделал`, а так же чтобы в ежедневной активности было много зеленых точек, типо что я не фигней занимаюсь. Так же там есть реально годные репозитории.

|Ссылка, Название|Описание предмета|
|-|-|
|[cgi_labs](https://github.com/optozorax/cgi_labs), [Компьютерная графика](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%8F_%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B0)|Программируем простые приложения с использованием OpenGL.|
|[numerical_methods](https://github.com/optozorax/numerical_methods), [Численные методы](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A7%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%BD%D1%8B%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B)|Пишем методы для решения СЛАУ. Но СЛАУ задаются не в плотном формате, а в формате, когда имеется много нулей. Решаться она должна в этом же формате. Это применяется в МКЭ, где у каждого элемента лишь несколько соседей, и когда оперативная память ограниченая гигабайтами, а время - неделями (если составлять матрицу с нулями, то вы не найдете столько оперативки чтобы это всё хранить и столько времени, чтобы это ждать).|
|[labs_emf](https://github.com/optozorax/labs_emf), [Уравнения математической физики ч.2](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A3%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F_%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9_%D1%84%D0%B8%D0%B7%D0%B8%D0%BA%D0%B8_(%D0%A7%D0%B0%D1%81%D1%82%D1%8C_2))|Реализуем методы для решения дифференциальных уравнений что проходили на первой части этого предмета при помощи методов, похожих на [МКЭ](https://ru.wikipedia.org/wiki/%D0%9C%D0%B5%D1%82%D0%BE%D0%B4_%D0%BA%D0%BE%D0%BD%D0%B5%D1%87%D0%BD%D1%8B%D1%85_%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2). В этом предмете плохо то, что методичка написана ужасно, ничего не понятно, исследования бессмысленные, и мы не проводим никаких симуляиций физических процессов, только абстрактные кони в вакууме. Зато курсач я написал почти божественно.|
|[optimization_methods](https://github.com/optozorax/optimization_methods), [Методы оптимизации](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%9C%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D0%BE%D0%BF%D1%82%D0%B8%D0%BC%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8)|Пишем и исследуем методы для нахождения минимумов и максимумов многомерных и одномерных функций.|
|[matstat_rgz](https://github.com/optozorax/matstat_rgz), РГЗ по [математической статистике](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A2%D0%B5%D0%BE%D1%80%D0%B8%D1%8F_%D0%B2%D0%B5%D1%80%D0%BE%D1%8F%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9_%D0%B8_%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F_%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0_(%D0%A7%D0%B0%D1%81%D1%82%D1%8C_2))|Просто латех очень красивый, вот и всё.|
|[labs_machine_learning](https://github.com/optozorax/labs_machine_learning), [Проектная деятельность ч.2](https://project-study.nstu.ru/project.php?id=373)|Изучаем computer vision с помощью сверточных нейронных сетей на примере распознавания кошек и собак.|
|[numerical_simulation_of_ODE](https://github.com/optozorax/numerical_simulation_of_ODE)|Пишем решатели однородных дифференциальных уравнений и применяем это в каких-то физических задачах. Так как предмет появился только при нас, попытался написать свою методичку.|
|[labs_translation_methods](https://github.com/optozorax/labs_translation_methods), [Методы трансляции](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%AF%D0%B7%D1%8B%D0%BA%D0%B8_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%B8_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%82%D1%80%D0%B0%D0%BD%D1%81%D0%BB%D1%8F%D1%86%D0%B8%D0%B8)|Пишем свой компилятор очень маленького подмножества Си. Предмет предназначен для понимая устройства компиляторов и изучения таких фишек в программировании, как: конечный автомат и грамматики. Код писал в основном не я.|
|[cryptography](https://github.com/optozorax/cryptography), Криптография|Простые лабы на освоение основных криптографических концепций, таких как: частотность букв, хеш, протокол Диффи-Хеллмана, открытый и закрытый ключ, симметричное, асимметричное шифрование. Самое крутое что есть в этом репозитории - это программа автоматической расшифровки текста, зашифрованного перестановкой букв в алфавите. Для этого я использую генетический алгоритм и хитрые метрики по частотности биграмм и триграмм. Для этого смотри папку `1`.|
|[assembler](https://github.com/optozorax/assembler)|Изучение ассемблера MASM, и использование его в C++.|
|[resources_control_labs](https://github.com/optozorax/resources_control_labs), [Управление ресурсами в вычислительных системах](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D1%80%D0%B5%D1%81%D1%83%D1%80%D1%81%D0%B0%D0%BC%D0%B8_%D0%B2_%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D1%85_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0%D1%85)|Пишем программы, которые используют такие фичи линукса, как: `fork`, `pipe`, `execl`, `openp`. Благодаря этому предмету я понял, что либо я не понимаю Linux, либо у него ужасная архитектура!|
|[prolog](https://github.com/optozorax/prolog), [Пролог](https://fami.codefreak.ru/learning/wiki/index.php?title=%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B2_%D0%B8%D1%81%D0%BA%D1%83%D1%81%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9_%D0%B8%D0%BD%D1%82%D0%B5%D0%BB%D0%BB%D0%B5%D0%BA%D1%82_%D0%B8_%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)|Пишем простые программы на этом языке.|
|[machine_learning](https://github.com/optozorax/machine_learning)|Какие-то деревья решений, нифига непонятно.|

# Форки чужих репозиториев

|Ссылка|Описание|
|-|-|
|[differential-evolution](https://github.com/optozorax/differential-evolution)|Чуть-чуть доработал оригинальную [дифференциальную эволюцию](https://ru.wikipedia.org/wiki/%D0%94%D0%B8%D1%84%D1%84%D0%B5%D1%80%D0%B5%D0%BD%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%8D%D0%B2%D0%BE%D0%BB%D1%8E%D1%86%D0%B8%D1%8F), сделав её одним файлом, и убрав зависимость от boost.|
|[my-keyboard-layout-editor](https://github.com/optozorax/my-keyboard-layout-editor)|Моя версия [этого сайта](http://www.keyboard-layout-editor.com/) с красивым стилем и исправленным сохранением раскладки в JSON.|
|[keyboard-layout-editor](https://github.com/optozorax/keyboard-layout-editor)|Моя версия [этого сайта](http://www.keyboard-layout-editor.com/) исправления сохранения раскладки в JSON, создано для того, чтобы показать в [Issue](https://github.com/ijprest/keyboard-layout-editor/issues/223#issuecomment-427575038) как можно эту проблему просто решить.|
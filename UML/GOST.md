@startmindmap
top to bottom direction
* Техническое задание (ТЗ)
  **:ГОСТ 34

Структура ТЗ на создание именно СИСТЕМЫ,
в которую входят:
* ПО,
* аппаратное обеспечение,
* люди, которые работают с ПО,
* и автоматизируемые процессы

  С 1 января 2022 – 34.602-2020
  ;
  **:ГОСТ 19

Структура ТЗ относится
к разработке именно ПО
;
**:IEEE STD 830-1998
Recommended Practice
for Software Requirements Specifications
(рекомендательный характер)

Требования к разрабатываемому ПО (SRS),
но также может применяться, чтобы помочь
в выборе собственных и коммерческих программных изделий.

Адаптированный шаблон Карла Вигерса

;

***:IEEE 29148-2011
Международный стандарт по инженерии требований,
который обеспечивает единую трактовку
процессов и продуктов для всей **системы** и **ПО**

Заменяет IEEE 830-1998, IEEE 1233-1998, IEEE 1362-1998

Объединяет ГОСТ 34.602-89 и ГОСТ 19.201-78

В отличие от BABOK, делит требования к ПО на:
* требования стейкхолдеров,
* системные требования, которые описывают:
  ** определение,
  ** поведение и свойства каждой функции системы,
  ** ограничения по реализации,
  ** технические и качественные метрики

Два шаблона спецификации требований
;

****:System Requirements Specification (SyRS)
Технические требования для выбранной системы
и удобства взаимодействия предполагаемой системы и человека

Определяет высокоуровневые требования
к системе с точки зрения предметной области,
а также информацию об общей цели системы,
ее целевой среде и ограничениях,
допущениях и нефункциональных требованиях

Может включать в себя концептуальные модели,
спроектированные для иллюстрации:
* содержания системы,
* сценариев использования,
* основных сущностей предметной области,
* данных,
* информаций и рабочих процессов
  ;
  ****:Software Requirements Specification (SRS)
  Технические требования для
* определенного программного изделия,
* программы или набора программ (продукт),
  которые выполняют определенные функции
  в конкретном окружении

Аналог ТЗ, описанного в ГОСТ 19,
а по структуре очень напоминает SRS
из стандарта IEEE 830
;

***: RUP (Rational Unified Process)
Документ, в котором необходимо
описать артефакты,
полученные в процессе
специфицирования требований

Шаблон SRS в RUP адаптирован
из стандарта IEEE STD 830
и содержит два варианта:
• Традиционный шаблон SRS
со структурированными ФТ по функциям Системы,
максимально похож на 830 стандарт
• Упрощенный шаблон SRS
со структурированными ФТ в виде вариантов
использования (use cases)

;

***: SWEBOK, BABOK
Документ, в котором необходимо
описать артефакты,
полученные в процессе
специфицирования требований

При упоминании SRS ссылаются
на вышеупомянутые зарубежные стандарты

* FRD (Functional Requirements Document),
* RD (Requirements Document),
* ПЗ (Постановка задачи или Пояснительная записка)
  ;
  @endmindmap






@startmindmap
<style>
mindmapDiagram {
    node {
        BackgroundColor lightYellow
    }
    :depth(0) {
      BackGroundColor lightBlue
    }
}
</style>
* Классификация стандартов
  ** По объекту
  *** Стандарты на продукты и услуги
  *** Стандарты на процессы и технологии
  ** По предмету
  *** Функциональные стандарты\n (стандарты на языки программирования,\n протоколы, интерфейсы)
  *** Стандарты на организацию ЖЦ\n АС и ПО
  ** По статусу
  *** Официальные стандарты
  **** Международные стандарты\n (ISO, ANSI, IDEF0/1)
  **** Стандарты РФ (ГОСТ Р)
  **** Отраслевые стандарты (ОСТ)
  **** Ведомственные стандарты
  ***** Стандарт научно-технического\n или инженерного общества (СТО)
  ***** Технические условия (ТУ)
  *** Стандарты «де-факто»
  left side
  ** Корпоративные (Стандарт предприятия (СТП))
  *** Стандарты проектирования
  **** Набор необходимых моделей (диаграмм)\n на каждой стадии проектирования\n и степень их детализации
  **** Правила именования объектов,\n оформления диаграмм,\n включая требования к форме\n и размерам объектов
  **** Требования к конфигурации\n рабочих мест разработчиков,\n включая настройки\n операционной системы
  **** Правила интеграции\n подсистем проекта,\n правила поддержания проекта\n в одинаковом для всех\n разработчиков состоянии,\n правила проверки проектных\n решений на непротиворечивость
  *** Стандарты оформления\n проектной документации
  **** Комплектность, состав\n и структуру документации\n на каждой стадии проектирования
  **** Требования к ее оформлению,\n включая требования к содержанию\n разделов, подразделов,\n пунктов, таблиц и т. д.
  **** Правила подготовки,\n рассмотрения, согласования\n и утверждения документации\n с указанием предельных сроков\n для каждой стадии
  **** Требования к настройке\n издательской системы,\n используемой в качестве\n встроенного средства\n подготовки документации
  **** Требования к настройке\n CASE-средств для обеспечения\n подготовки документации\n в соответствии\n с установленными требованиями
  *** Стандарты пользовательского\n интерфейса
  **** Правила оформления экранов\n (шрифты и цветовая палитра),\n состав и расположение\n окон и элементов управления
  **** Правила использования\n клавиатуры и мыши
  **** Правила оформления\n текстов помощи
  **** Перечень стандартных\n сообщений
  **** Правила обработки\n реакции пользователя
  @endmindmap
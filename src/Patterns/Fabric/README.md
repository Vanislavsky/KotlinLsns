
`Фабричный метод` — это порождающий паттерн проектирования, который определяет общий интерфейс для создания объектов в суперклассе, позволяя подклассам изменять тип создаваемых объектов.

Этот паттерн прадлагает создавать объекты не на прямую, а через методы фабрики.

Теперь, в случае необходимости изменить какой-то объект, нужно будет переопределить только метод в фабрике.

Единственное требование - общий интерфейс, для генерации объектов одного класса.



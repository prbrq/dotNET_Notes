
Объект типа [[Struct|struct]] можно [[Upcast и Downcast|апкастить]] до объектов типа [[Классы и объекты|class]]. Из-за опасности ошибок мы не можем делать ссылки на **стек**, поэтому `struct` перемещается в кучу. Это действие называется **boxing**. Обратная операция называется **unboxing**.

**Boxing** и **unboxing** это сложные и дорогие по времени выполнения действия, при возможности их нужно избегать. 
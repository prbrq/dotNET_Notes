
Если [[Методы|метод]] помимо возвращаемого значения может ещё и возвращать `null`, то нужно в объявлении метода после типа возвращаемого значения поставить `?`.

```cs
public static int? IntOrNull(int someItem)
{
    return null;
}
```
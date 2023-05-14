# Изучения алгоритмов

## Сложность алгоритмов
Оценка сложности оценивается в количестве выполняемых шагов.\
BigO - от **передаваемых параметров** зависит **количество операций**, которые будут выполнены перед тем, как алгоритм завершится.
| Сложность               | Обозначение     | Результативность|
| :---                    |      :---       |       :---      |
| Константная             | $O({1})$        | Отличная/Лучшая |
| Логарифмическая         | $O({logN})$     | Хорошая         |
| Линейная                | $O({N})$        | Нормальная      |
| Линейно-логарифмическая | $O({N * logN})$ | Плохая          |
| Квадратичная            | $O({N^2})$      | Ужасная/Худшая  |
| Экспоненциальная        | $O({2^n})$      | Ужасная/Худшая  |
| Факториальная           | $O({N!})$       | Ужасная/Худшая  |
| Сублинейная сложность   | $O(\sqrt{N})$   | Ужасная/Худшая  |

![BIGO](https://github.com/Vijorich/sorting-algorithms/assets/88296320/ac497979-c7ad-4283-9103-3d4cacc819d0)

### Константная $O({1})$
```csharp
private void LulLel (int a, int b) {
    return a + b
}
Всегда складываем только 2 переменные
```
```csharp
void f()
{
	for(int i = 0; i < 100, i++)
	{
		...
	}
}
}
Перебираем константное число 100
Алгоритм всегда делает 100 шагов перед тем как выполнится
Если код всегда выполняется за одно и тоже время, и никак не зависит от размера входных данных,
 то такая сложность является константной O(1)
```

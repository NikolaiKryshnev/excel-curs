## Testing in Move

Для тестирования в языке Move используйте следующий пример функции:

```move
// Пример тестовой функции в Move
fun test_function(): bool {
    assert!(1 + 1 == 2, 0); // Проверка, что 1 + 1 действительно равно 2
    true
}

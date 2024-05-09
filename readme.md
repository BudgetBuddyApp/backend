[![Java CI with Maven](https://github.com/BudgetBuddyApp/backend/actions/workflows/ci.yml/badge.svg)](https://github.com/BudgetBuddyApp/backend/actions/workflows/ci.yml)

### Backend проекта MoneyTracker.

###### Предоставляет REST API для работы над расходами:
- Выборка данных: расходы по периодам, агрегация, поиск
- Добавление расходов
- Обновление расходов
- Удаление расходов

---
Todo:
- [ ] Документация (wiki)
- [ ] Swagger
- [ ] Аутентификация

---
#### Генерация отчета о покрытии тестами
```shell
mvn clean test jacoco:report
```

> Минимальное требование к покрытию тестами проекта **50%**
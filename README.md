# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"
https://monosnap.com/file/8jxpkX1O1g5LK9jrdMobjEgQH5SwcC

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/7c5Rm5xzqUVMb6VWIhp5oubFvjJKfN

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/rzMurHHappVSw8nxpLtU8pFEmb2xdt

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/xo3pGwJQZ3GpgpksemB4nx9uxyrokj

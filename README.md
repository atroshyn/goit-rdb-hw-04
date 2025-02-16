# Домашнє завдання, тема 4

1. Створіть базу даних для керування бібліотекою книг згідно зі структурою, наведеною нижче. Використовуйте DDL-команди для створення необхідних таблиць та їх зв'язків.

![Screenshot_1](https://github.com/user-attachments/assets/082308e0-0cc5-4141-8872-b82145f85e4c)

![Screenshot_2](https://github.com/user-attachments/assets/905db6e0-7cc5-4280-87a1-c9e533454f14)

![Screenshot_3](https://github.com/user-attachments/assets/d8c857d2-5122-46de-98c7-629ff9fcfd47)

2. Заповніть таблиці простими видуманими тестовими даними. Достатньо одного-двох рядків у кожну таблицю.

![Screenshot_4](https://github.com/user-attachments/assets/2104f9d7-9282-4a2a-9e06-3e0653cfd556)

![Screenshot_5](https://github.com/user-attachments/assets/b6be5b91-9e09-44e9-8719-709ea9d403b3)

![Screenshot_6](https://github.com/user-attachments/assets/a72ebfb6-d8e0-42b8-a53f-a6fdd4a22369)

![Screenshot_8](https://github.com/user-attachments/assets/208d9564-a515-48b4-a194-84f5b38b1340)

![Screenshot_7](https://github.com/user-attachments/assets/25261c31-c673-40bd-bbfe-a1f036b0c9a5)

3. Перейдіть до бази даних, з якою працювали у темі 3. Напишіть запит за допомогою операторів FROM та INNER JOIN, що об’єднує всі таблиці даних, які ми завантажили з файлів: order_details, orders, customers, products, categories, employees, shippers, suppliers. Для цього ви маєте знайти спільні ключі. Перевірте правильність виконання запиту.

![Screenshot_9](https://github.com/user-attachments/assets/b94a5abd-897b-4880-856a-94b7e89822da)


4. Виконайте запити, перелічені нижче.

- Визначте, скільки рядків ви отримали (за допомогою оператора COUNT).

![Screenshot_10](https://github.com/user-attachments/assets/3aa7751e-4eb7-4b1e-8ba4-63cbc5b5d165)


- Змініть декілька операторів INNER на LEFT чи RIGHT. Визначте, що відбувається з кількістю рядків. Чому? Напишіть відповідь у текстовому файлі.

![Screenshot_11](https://github.com/user-attachments/assets/3f764f7c-dbc2-4ee6-be30-6b9a193c64bd)

![Screenshot_12](https://github.com/user-attachments/assets/d6388c69-a3f3-4e01-a27c-1fdccea55e54)

Як бачимо, для даних випадків кількість рядків не змінилася, бо це залежить від наповнення тестових таблиць.

- Оберіть тільки ті рядки, де employee_id > 3 та ≤ 10.

![Screenshot_13](https://github.com/user-attachments/assets/b878e55b-982e-4b75-b174-78c48be36163)


- Згрупуйте за іменем категорії, порахуйте кількість рядків у групі, середню кількість товару (кількість товару знаходиться в order_details.quantity)

![Screenshot_14](https://github.com/user-attachments/assets/59236356-547e-45c0-9116-93055e2c337e)


- Відфільтруйте рядки, де середня кількість товару більша за 21.

![Screenshot_15](https://github.com/user-attachments/assets/04ae0131-f3d8-42d4-bc5a-2197b4f04615)


- Відсортуйте рядки за спаданням кількості рядків.

![Screenshot_16](https://github.com/user-attachments/assets/dc04b658-faf1-492e-981d-49f3fe8fd56d)


- Виведіть на екран (оберіть) чотири рядки з пропущеним першим рядком.

![Screenshot_17](https://github.com/user-attachments/assets/48210952-6f25-4986-a204-5f20a726cdce)


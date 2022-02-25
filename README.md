## Laboratory work 1
1-2. Скачивание и распаковка
```
wget <ссылка>
tar -xf <имя>
```
![image](https://user-images.githubusercontent.com/87879854/155756871-5fe504bf-d976-4e2b-9275-17f02093096c.png)

3. Подсчет количества файлов и директорий без вложенных папок 
![image](https://user-images.githubusercontent.com/87879854/155758712-ac0a37ea-22fe-472b-9390-ae3d8540d1e1.png)

4. -.- с вложенными папками `tree boost_1_69_0`

![image](https://user-images.githubusercontent.com/87879854/155759161-e115e83c-99ac-4b62-989f-3d41ff0fb7b1.png)

5. Количество файлов с расширением .cpp 
```
tree boost_1_69_0 -P "*.cpp"
```

![image](https://user-images.githubusercontent.com/87879854/155759765-c82a477c-d1db-43ae-86a9-ec2eeed3cb69.png)

Без файлов с расширением .cpp и .hpp `tree boost_1_69_0 -I "*.cpp|*.hpp"`

![image](https://user-images.githubusercontent.com/87879854/155760253-ea2d890f-ee86-4790-8d2d-3d0dbc4cca94.png)

6. Поиск по имени и вывод полного пути `find ./boost_1_69_0 -name "any.hpp"`

![image](https://user-images.githubusercontent.com/87879854/155760915-272ad669-0b7e-4212-9bc1-f3b06df7d488.png)

7. Все файлы, где упоминается boost::asio `grep -rL "boost::asio"`

![image](https://user-images.githubusercontent.com/87879854/155762558-3ff2f5e6-d0b8-4d0d-b4e8-f57d65fbe741.png)

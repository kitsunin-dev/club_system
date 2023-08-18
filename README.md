## Тестовое задание на вакансию C++ Intern/Trainee in Telecom
### Содержание репозитория

Репозиторий состоит из следующих файлов:

- `task.cpp`: исходник с кодом программы
- `task.h`: заголовочный файл с пользовательскими функциями и структурами
- `CMakeLists.txt`: файл CMake для автоматической сборки
- `test_file.txt`: текстовый файл для проверки работы программы
- `README.md`: файл с информацией о репозитории

### Инструкция по сборке

Программу можно собрать и запустить на платформах Linux и Windows. Для начала склонируйте репозиторий к себе на компьютер через команду терминала:
```
git clone git@github.com:kitsunin-dev/test-task.git
```
Далее способ сборки будет зависеть от операционной системы.
#### Linux: 

Откройте терминал в папке с репозиторием. В окне терминала выполните следующую команду:
```
clang task.cpp -o task -lstdc++ -lm
```
То же самое можно выполнить с помощью компилятора `gcc`:
```
gcc task.cpp -o task -lstdc++ -lm
```
В обоих случаях в папке появится исполняемый файл `task`. После этого выполните команду:
```
./task [имя текстового файла]
```
В терминале появится вывод программы. (Убедитесь, что имя файла указано верно.)

#### Windows:

_Тут что-то скоро появится..._
Для решения задания я использовал QtCreator 5.15; 
Создал Widget, используя UI;
В проект был добавлен класс Logger; 
Также был создан шаблонный тип LinkedList и на основании его было создано два поля в классе MainWindow (один для хранения всех слов, второй для хранения QPair, состоящий из слова и колличества его в файле);
После выбора файла для сканирования (использовал QFileDialog), происходит происходит заполнения widget showfile и активация кнопки для сканирования;
По нажатию вызываем метод onScanFileClicked и заполняем поле sortedWords_ c последующим вызовом сигнала для записи в файл ResultPairs.txt и вывода информации в widget textEnglish.

\# Домашнє завдання №2. Файлова система і права доступу

\#\#\# Завдання 1\. Ієрархія каталогів Linux  
\- Перехід в корінь та перегляд вмісту: \`cd / && ls\`  
\- Перехід в /etc та перегляд вмісту: \`cd /etc && ls\`  
\- Перехід в /home та перегляд списку: \`mkdir /home && cd /home && ls\`

\#\#\# Завдання 2\. Файли, каталоги та посилання  
\- Створення каталогу: \`mkdir projects && cd projects\`  
\- Створення файлу: \`touch test.txt\`  
\- Копіювання: \`cp test.txt copy\_test.txt\`  
\- Перейменування: \`mv copy\_test.txt final\_file.txt\`  
\- Жорстке посилання: \`ln test.txt hardlink\_test\`  
\- Символічне посилання: \`ln \-s test.txt symlink\_test\`  
\- Пошук: \`find /home/projects \-name final\_file.txt\`

\#\#\# Завдання 3\. Права доступу  
\- Перегляд прав: \`ls \-l test.txt\`  
\- Тільки читання: \`chmod 444 test.txt\`  
\- Права власнику на запис: \`chmod 644 test.txt\`  
\- Робота з umask: \`umask 022\`

\#\#\# Завдання 4\. Користувачі  
\- Створення користувача: \`adduser trainee\`  
\- Додавання до групи: \`addgroup trainee root\`  
\- Перевірка: \`id trainee\`  

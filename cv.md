## Sergey Shapkarin

***

### About:
Male, 35 years old, was born on 1984 18 april

married, have two children

Kazakhstan, Nur-Sultan

---

### Contact information:
- Mobile phone: +7 701 749 90 64

- Telegram: [@SergeyShapkarin](https://t.me/SergeyShapkarin)

- Email: [sergey.shapkarin@gmail.com](mailto:sergey.shapkarin@gmail.com),  [sergey.shapkarin@mail.ru](mailto:sergey.shapkarin@mail.ru)

###Summary:
I want to become a python-developer. So far, I have finished "Interactive Course Python basics" at [geekbrains.ru](https://geekbrains.ru/certificates/705198.en). And now, I want to learn JS in order to build comfortable and practical user interfaces.

###Skills:

- Python core

- HTML5

- CSS3

- GIT

### Code examples;

```typescript
import os
import shutil
import datetime


def write_file(file_name, text, encoding, message):
    try:
        with open(file_name, 'w', encoding=encoding) as f:
            if text:
                f.write(text)
        logging('INFO', message)
    except LookupError:
        logging('ERROR', f'Указана неизвестная кодировка файла. Создан пустой'
                         f' файл {file_name}')

def logging(type_message, message):
    result = (f'{datetime.datetime.now().strftime("%d.%m.%Y %H:%M:%S")}'
              f' - {type_message} - {message}\n')
    with open('log.txt', 'a', encoding='utf-8') as f:
        f.write(result)
    print(result)

def get_list(argument=None):
    if argument == 'folders_only':
        result = [f for f in os.listdir() if os.path.isdir(f)]
    elif argument == 'files_only':
        result = [f for f in os.listdir() if os.path.isfile(f)]
    elif argument == None:
        result = os.listdir()
    else:
        result = 'Введен некорректный параметр команды'
    print(result)

def create_folder(folder_name):
    try:
        os.mkdir(folder_name)
    except FileExistsError:
        logging('ERROR', f'Каталог или файл с именем {folder_name} уже '
                         f'существует. Задайте другое имя.')
    else:
        logging('INFO', f'Каталог {folder_name} успешно создан.')
```

###Experience:

2017.12 - 2019.10 -> JSC "Sportmaster Kazakhstan" - Deputy Head of Information Technology

2014.10 - 2017.11 -> JSC "Sportmaster Kazakhstan" - СhiefIT  Administrator

2012.02 - 2014.09 -> JSC "Sportmaster Kazakhstan" - IT Administrator

2011.02 - 2012.01 -> JSC "Railway Hospital of Disaster Medicine" - IT Admnistrator

2008.09 - 2009.10 -> JSC "National Information Technology" - IT engeneer

2006.11 - 2008.08 -> JSC "New Age Technologies" - software implementation and support specialist

###Education:

2020.01.30 - 2020.03.10 - "Interactive Course HTML/CSS" - geekbrains.ru

2020.01.14 - 2020.01.29 - "Introduction to Git" - geekbrains.ru

2019.11.29 - 2020.01.13 - "Interactive Course Python basics' - geekbrains.ru

2004.09.01 - 2007.05.25 - bachelor Faculty of Computer Science and Computer Engineering - Kazakh-Russian University

2004.09.01 - 2007.03.15 - software technician Faculty of Computer Engineering and Automated Systems - Polytechnic College of Astana

###English:

My English level is approximately A2. I can read texts in English and understand them in most cases. But I have a very rare practice of spoken in English. At the moment I am engaged in independent study of the English language.

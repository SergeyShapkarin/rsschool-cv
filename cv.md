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
I want to become python-developer on web. At the moment, I finished course "Interactive Course Python basics" in online school [geekbrains.ru](https://geekbrains.ru/certificates/705198.en). And now, I want to learn JS in order to build comfortable and practical user interfaces.

###Skills:

- Python core

- HTML5

- CSS3

- GIT

### Code examples;

'''
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
'''

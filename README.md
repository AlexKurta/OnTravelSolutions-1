# OnTravelSolutions-1

#1
Предположим, есть страница, на которой всего одно поле:

<style>.red {color: red;}</style>
input type="text" name="name" class="js_name" value="Xxxx">

Задача: написать скрипт, который при вводе данных в поле будет добавлять ему класс red, если его текущее значение поля не совпадает с изначальным, и удалять этот класс, если значения совпадают


# language-detector

**Installation**

`npm install git+ssh://git@sshgit.codemaster.by:sf/language-detector.git`

**Run tests**

`npm test`

**Example**

`import languageDetector from 'language-detector';`

`const locale = languageDetector();`

`console.log(locale);`

`// output: 'en' / 'ru' / false`

`// method return locale or false if it cannot obtain any locale from browser`

**Adding an SSH key to your GitLab account**

https://docs.gitlab.com/ee/ssh/#rsa-ssh-keys

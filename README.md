# Language Guesser Using franc, Langs and Nodejs
This is a simple language guesser based on user input that show in the terminal. 

![Screenshot of language guesser](https://user-images.githubusercontent.com/66502910/111325903-18488b80-86a7-11eb-89d1-c94242d32a14.jpg)

#### The packages used in this application: 
* [franc](https://github.com/wooorm/franc)
   ```var franc = require('franc')
      franc('Alle menslike wesens word vry') // => 'afr'
      franc('এটি একটি ভাষা একক IBM স্ক্রিপ্ট') // => 'ben'
      franc('Alle menneske er fødde til fridom') // => 'nno'

      franc('') // => 'und' (language code that stands for undetermined)

      // You can change what’s too short (default: 10):
      franc('the') // => 'und'
      franc('the', {minLength: 3}) // => 'sco'

* [Langs](https://github.com/adlawson/nodejs-langs)
   ```var langs = require('langs');
      langs.all();
      // [
      //     {"name":"English", "local":"English", "1":"en", "2":"eng", "2T":"eng", "2B":"eng", "3":"eng"},
      //     {"name":"Korean", "local":"한국어", "1":"ko", "2":"kor", "2T":"kor", "2B":"kor", "3":"kor"},
      //     ...
      // ]

      langs.codes("3");
      // [
      //     "eng",
      //     "kor",
      //     ...
      // ]

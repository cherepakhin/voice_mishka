Главное: ЗАПУСТИТЬ

````shell
docker run -d -p 2700:2700 alphacep/kaldi-ru:latest
````
Распознавание:

````shell
python3 ./test.py mishka.wav > miska_out.txt
````

Результат смотреть в конце файла miska_out.txt.
Это JSON. Результат по JSON PATH ./text .

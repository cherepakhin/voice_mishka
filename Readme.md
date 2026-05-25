Главное: ЗАПУСТИТЬ

````shell
docker run -d -p 2700:2700 alphacep/kaldi-ru:latest
````
Распознавание:

````shell
python3 ./test.py mishka.wav > miska_out.txt
````
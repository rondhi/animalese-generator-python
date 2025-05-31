# Animalese Audio Generator

## General info
This project allows you to generate audio from text in the style of animalese from the Animal Crossing games. 

## Usage

```
$ ./animalese.py the quick brown fox jumps over the lazy dog
```

The program accepts two options, one to control the pitch (available options: 'lowest', 'low', 'med', 'high')
and one to control the output file
```
$ ./animalese.py the quick brown fox jumps over the lazy dog --pitch high --out output_name.wav
```


## Technologies
Project is created with:
* pydub

## Installing required dependencies

`audioop` was deprecated in Python 3.11 and removed in Python 3.13. [See here](https://docs.python.org/3/library/audioop.html)
Use `audioop-lts` instead

```
$ pip install pydub audioop-lts
```

[You'll also need to install `ffmpeg` or `libav` for this to work](https://github.com/jiaaro/pydub#dependencies)
```
$ brew install ffmpeg
```
or
```
$ brew install libav
```

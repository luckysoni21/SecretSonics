# SecretSonics
Embedding secret messages in wave audio file

# What is SecretSonics
SecretSonics is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

# Requirements
This tool require python3

# Installation
```
git clone https://github.com/luckysoni21/SecretSonics.git
cd SecretSonics
```
# Usage
<p>SecretSonics have two python scripts. </p>
<ul>
<li><b>SecretSonics.py :</b> for hide secret information.</li>
<li><b>ExWave.py :</b> for extract secret information for wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python3 SecretSonics.py -f Demo.wav -m "Secret Msg" -o output.wav
```
### Extract Secret Information from Audio file

```
python3 ExWave.py -f output.wav
```

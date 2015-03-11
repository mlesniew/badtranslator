# Bad Translator

Bad translator translates your text to a random language, takes the result and translates it to another random language, repeats this a few times and then it translates it back to the original language.  

In theory the result text should be the same as the input (or it should at least have the same meaning).  However, usually the output is completely different, but often much more interesting than the original.


## Basic usage

To use this tool, simply call ./translate and supply the text to be translated as parameter.
```bash
./translate "Is this the real life, is this just fantasy?"
```

The tool assumes that the text is written in your system language.  However, you can specify the language using a switch, for example:
```bash
./translate --language=de "Neunundneunzig Luftballons auf ihrem Weg zum Horizont."
```


## Requirements

The tool requires the goslate package, which can be installed using pip:
```bash
pip install goslate
```

Optionally, you can install the argcomplete package to enable autocompletion in bash.
```bash
pip install argcomplete
```

This is an experiment to compare performance of some programming languages.

## String Searching

### The goal

The program will read the following from standard input
- A long `text` of length `textLength` from the first line.
- An integer `wordsCount` from the second line.
- `wordsCount` words from the next `wordsCount` lines.
Then print how many `words` are included in the `text`.

### Configuration
```js
{
  "textLength": 1000000,
  "wordsCount": 10000,
  "wordLength": 7
}
```

### Results
```
PHP7: 6.151s
Python3: 7.015s
Nodejs: 8.053s
C++: 11.121s
```

## Running the tests yourself
- You should have a Unix system with `g++`, `python3`, `PHP` and `node` installed.
- Run `./run-all` script.

## Generating inputs with other configurations
- run `npm i` to install dependencies if you want to regenerate the random inputs.
- edit the `config.json` file.
- run `./generate-all` to generate new inputs.
- run `./run-all`.
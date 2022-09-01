# idea-vim-talk
Road to INIT Talk - IdeaVim is a KING

### Essential Modes

```
NORMAL MODE => Esc
INSERT MODE => i: Insert, a: Append, cc/C: change
VISUAL MODE => v, V
COMMAND MODE => :, /
```
### Basic movements

```
k => move up one line
j => move down one line
h => move left one character
l => move right one character
w => move by one word forward
b => move by one word back
```

### With numbers

```
3j => move three lines down
3k =>  move three lines up
3w => move three words forward
5$ => move to the end of the fifth line down
6+ => move six lines down to start of line
```

### Vim As a Language

```
Verbs(operators), nouns, adverbs
Verbs => d: delete, c: change, y: yank/copy, p: paste v: visual
Nouns => w: word s: sentence, b: block, t: tag, p: paragraph
Adverbs => i: inside, a: around, t: until something, f: find something, num: number
```

### Building commands

```
dw => delete word
d3w => delete three words
dt. => delete till dot
c2w => change two words
ci) => change inside parentheses
ct} => change till closing curly bracket
ca( => change around opening parentheses
y5w => copy five words
yip => copy inside paragraph
```

### Idea Vim is a King

```
. - dot command
5. - repeat the last change 5 times
     gi - go to last insert place
     gv - go to last visual selection
* - search for the current word
```

### Plugins for IdeaVim

```
Nerdtree
Surround
Easymotion
```
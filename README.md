### Play Tetris written in Asembly (TASM)

### Steps to set up 

1. Download Dosbox [dosbox.com](https://www.dosbox.com/download.php?main=1)
2. Clone repository into some folder
3. Open Dosbox
4. mount cloned directory to dosbox  and switch to it with commands:

```
mount c path/to/cloned/folder # mount
c: # swithc to mounted drive
```

5. compile assembly file and start program

```
makecom tetris # compile + link + execute 
```

6. if already compiled programm can be runned with 

```
tetris # run
tetris /off # quit 
```

### Demonstation

https://github.com/user-attachments/assets/0a6fae29-5f00-4101-889c-aaf9f8cac07b

### Controlls 

" - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - "
-> press <P> to start the game and pause/resume it later
-> press <D> to move left   and <F> to move right
-> press <J> to rotate left and <K> to rotate right
-> press <V> to move down immediatly
-> press <P> again to restart the game after game is over
" - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - "



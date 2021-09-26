## run
```
$ python sokoban.py -l test1.txt -m bfs

*with memory display

$ python sokoban.py -l test1.txt -m bfs -M

```
```
rUUdRdrUUluL
Runtime of bfs: 0.15 second.
```
## detail

* BFS：

```
$ python sokoban.py -l test1.txt -m bfs
rUUdRdrUUluL
Runtime of bfs: 0.15 second.
```

* DFS：

```
$ python sokoban.py -l test1.txt -m dfs
rrUrdllluRRlldrrrUlllururrDLrullldRldrrUruLrdllldrrdrUlllurrurDluLrrdllldrrdrUU
Runtime of dfs: 0.09 second.
```

* A star

```
$ python sokoban.py -l test1.txt -m astar
rUUdRdrUUluL
Runtime of astar: 0.01 second.
```
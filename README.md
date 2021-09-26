## run
```
$ python sokoban.py -l test1.txt -m bfs memo
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

$ python sokoban.py -l test1.txt -m bfs
rUUdRdrUUluL
Runtime of bfs: 0.13 second.

$ python sokoban.py -l test2.txt -m bfs
UUddrrrUU
Runtime of bfs: 0.01 second.

$ python sokoban.py -l test3.txt -m bfs
LrdrddDLdllUUdR
Runtime of bfs: 0.27 second.

$ python sokoban.py -l test4.txt -m bfs
llldRRR
Runtime of bfs: 0.01 second.

test5.txt: more than 1 minute.

$ python sokoban.py -l test6.txt -m bfs
dlluRdrUUUddrruuulL
Runtime of bfs: 0.02 second.

$ python sokoban.py -l test7.txt -m bfs
LUUUluRddddLdlUUUUluR
Runtime of bfs: 1.25 second.

$ python sokoban.py -l test8.txt -m bfs
llDDDDDDldddrruuLuuuuuuurrdLulDDDDDDlllddrrUdlluurRdddrruuLUUUUUUluRdddddddrddlluUdlluurRdrUUUUUU
Runtime of bfs: 0.30 second.

$ python sokoban.py -l level1.txt -m bfs
RurrddddlDRuuuuLLLrdRDrddlLdllUUdR
Runtime of bfs: 35.04 second.
```

* DFS：

```
$ python sokoban.py -l test1.txt -m dfs
rrUrdllluRRlldrrrUlllururrDLrullldRldrrUruLrdllldrrdrUlllurrurDluLrrdllldrrdrUU
Runtime of dfs: 0.09 second.

$ python sokoban.py -l test2.txt -m dfs
rrrUlldlUrrrUlldrrdllluU
Runtime of dfs: 0.01 second.

$ python sokoban.py -l test3.txt -m dfs
rrdldrdllDRlldlUrrrdrruLrdllLrrrululldRllldRlurrrdrruLrdllUrrdllLrrrullllldRRRlllurrrrrdLrulllllUdrrrrrdlLrrullllldrRRlllurrrrrdLrullluRldrrrdlLrrullllldrRRlllurrrrrdLrulllururulluLrrrdlddldrrrdlLrrullllldrRRlllurrrrrdLrulUlldrrrdlLrrullllldrRRlllurrrrrdLrulllurrUldrdrdlLrrullllldrRRlllurrrrrdLrulllurrululurrDDldldrrrdlLrrulllururDlldrdrruLrdllLrrrululldRllldRlurrrdLrrruLrdlllulldRRRlllurrurrdrdLrulL
Runtime of dfs: 0.36 second.

$ python sokoban.py -l test4.txt -m dfs
rrrdllllLrrrrrdllllllluRRRR
Runtime of dfs: 0.01 second.

test5.txt: more than 1 minute.

$ python sokoban.py -l test6.txt -m dfs
rrdlllluRRlldrrrruLrdllUUUddrrdlllluuuurRlldddrrrruuuLL
Runtime of dfs: 0.02 second.

$ python sokoban.py -l test7.txt -m dfs
rdllllurRlldrrrruulLrrdLrdllllurRlldrrrruullLrrrdLrdllllurRlldrrrruulluulldDrrrrdLrdllllUrdrrrulLrrdlllluUrrrrdllLrrrullllUdrrrrdllldlUrrrrulluululldRRllurrrrrdddllldrrrdlllluUrrrruuullllldrDDrrrrdllldlUrrrrulluUlllurrRllldrrrddrrdllllUrrrruuuLrdddllllUdrruuluRllldRRllurrrDllddrrrruuuLrdddlllluurrDDrrdlLrrdlllluRRlldrrrruulllluuruRllldrrrddrrdLrdllllurRlldrrrruuuuuLrdddlllldrrdrUrdllllurrulluuruRllldrrrddlldrrrruLrdllllurRlldrrrruuuuLrdddLrdlllluuuruRllldrrrdDrruuuLrdddlllluuruRllldrrrddrrdlLrrdlllluurrrruuuLrdddllllddrrrrullLrrrdllllUrrrrulluulldDrrrruuulLrrdddlllluulurRRllldrrrddrrdllldlUrrrruuuuLrdddllldrrrdlllluUrrrruuulLrrdddlluulllurRRllldrrrddrrdlllluUdrrrruuuLrdddlllluUruRldrddrrdlllluuuluR
Runtime of dfs: 0.78 second.

$ python sokoban.py -l test8.txt -m dfs
llDlurrrdLrullldRDDDDDlllddrrdrruuLrddllulluurrruuuuulurrrdLrullldRdddddlllddrrUruLruuuuulurrrdLrullDDDDDDlddlluuRRllddrrdrruuLrddllulluurrDrUldrrddllUlluurrrUdlllddrrUruLruUddldrrddllulluuRlddrrdrruuluLruuUdddldrrddllulluuRlddrrdrruuluLruuuUddddldrrddllulluuRlddrrdrruuluLruuuuUluRldrdddddldrrddllulluuRRllddrrdrruulUUUUUU
Runtime of dfs: 0.11 second.

level1.txt: more than 1 minute.
```

* UCS：

```
$ python sokoban.py -l test1.txt -m ucs
rURdrUUlLdlU
Runtime of ucs: 0.09 second.

$ python sokoban.py -l test2.txt -m ucs
UUddrrrUU
Runtime of ucs: 0.01 second.

$ python sokoban.py -l test3.txt -m ucs
LrdrddDLdllUUdR
Runtime of ucs: 0.17 second.

$ python sokoban.py -l test4.txt -m ucs
llldRRR
Runtime of ucs: 0.01 second.

test5.txt: more than 1 minute.

$ python sokoban.py -l test6.txt -m ucs
dlluRdrUUUddrruuulL
Runtime of ucs: 0.02 second.

$ python sokoban.py -l test7.txt -m ucs
LUUUluRddddLdlUUUUluR
Runtime of ucs: 0.94 second.

$ python sokoban.py -l test8.txt -m ucs
llDDDDDDldddrruuLuuuuuuurrdLulDDDDDDlllddrrUdlluurRdddrruuLUUUUUUluRdddddddrddlluUdlluurRdrUUUUUU
Runtime of ucs: 0.31 second.

$ python sokoban.py -l level1.txt -m ucs
RurrddddlDRuuuuLLLrdRDrddlLdllUUdR
Runtime of ucs: 33.22 second.
```

* A star

```
$ python sokoban.py -l test1.txt -m astar
rUUdRdrUUluL
Runtime of astar: 0.01 second.

$ python sokoban.py -l test2.txt -m astar
UUddrrrUU
Runtime of astar: 0.01 second.

$ python sokoban.py -l test3.txt -m astar
LrdrddDLdllUUdR
Runtime of astar: 0.01 second.

$ python sokoban.py -l test4.txt -m astar
llldRRR
Runtime of astar: 0.00 second.

$ python sokoban.py -l test5.txt -m astar
uruLdlUURUdRdrUUllLdlU
Runtime of astar: 0.11 second.

$ python sokoban.py -l test6.txt -m astar
dlluRdrUUUddrruuulL
Runtime of astar: 0.02 second.

$ python sokoban.py -l test7.txt -m astar
LUUUluRddddLdlUUUUluR
Runtime of astar: 0.16 second.

$ python sokoban.py -l test8.txt -m astar
llDDDDDDldddrruuLuuuuuuurrdLulDDDDDDlllddrrUdlluurRdddrruuLUUUUUUluRdddddddrddlluUdlluurRdrUUUUUU
Runtime of astar: 0.33 second.

$ python sokoban.py -l level1.txt -m astar
RurrdLLLrrrdddlDRlLdllUUdRRurruuulldRDrddL
Runtime of astar: 0.85 second.
```
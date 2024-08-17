# La partie écossaise

```chess
fen: rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1
moves: e4 e5 Nf3 Nc6 d4
```


#### La première régle

Il faut obligatiore prendre la pion centrale. 
``` chess
fen: r1bqkbnr/pppp1ppp/2n5/4p3/3PP3/5N2/PPP2PPP/RNBQKB1R b KQkq - 0 3
lastMove: d2 d4
arrows: e5->d4
```

Sinon il vient une mauvaise position pour les noirs:

``` chess
fen: r1bqkb1r/pppp1ppp/2n2n2/3Pp3/4P3/5N2/PPP2PPP/RNBQKB1R b KQkq - 0 4
lastMove: d4 d5
```

## La variante Steinitz  (Система Стейница) 
``` chess
fen: r1b1kbnr/pppp1ppp/2n5/8/3NP2q/8/PPP2PPP/RNBQKB1R w KQkq - 1 5
lastMove: d8 h4
arrows: b1->c3 f8->b4
```

Il faut répondre Nc3. Sinon les Noires ont d'avantage. Voici 2 examples:

``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Qh4 5. Qd3 Nf6 6. Nd2 Ng4 7. g3 Qf6 8. N4f3 Nce5 9. Qc3 Bb4 10. Qxb4 Nxf3+
```

``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Qh4 5. Be2 Bc5 6. Be3 Bxd4 7. Bxd4 Qxe4 8. Bxg7 Qxg2 9. Bxh8 Qxh1+ 10. Bf1 d6
```

### Les variantes rares

#### Nd4 Qd4 Qf6 Echange les reines

``` chess
fen: r1bqkbnr/pppp1ppp/8/8/3nP3/8/PPP2PPP/RNBQKB1R w KQkq - 0 5
lastMove: c6 d4
arrows: d1->d4 d8->f6
```

Les noirs tendent echanger les pieces. Par example:
``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Nxd4 5. Qxd4 Qf6 6. e5 Qb6 7. Qxb6 axb6 8. Nc3 Bb4 9. Bd2 f6 10. Nd5 Bxd2+ 11. Kxd2 Kd8 12. exf6 Nxf6 13. Nxf6 gxf6 14. a3
```
Les blancs ont mieux structure de pions.

#### Nge7
``` chess
fen: r1bqkb1r/ppppnppp/2n5/4p3/3PP3/5N2/PPP2PPP/RNBQKB1R w KQkq - 1 4
lastMove: g8 e7
```

Par example:

``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Nge7 5. Nc3 Nxd4 6. Qxd4 Nc6 7. Qd2 Bb4 8. a3 Ba5 9. b4 Bb6 10. Nd5 O-O 11. Bb2 Re8 12. O-O-O d6 13. Qf4
```
Les Blancs gardent l'initiative. On peut déplacer après le fou sur c4 et faire h4. 


#### d5
ход Кереса?

``` chess
fen: r1bqkbnr/ppp2ppp/2n5/3p4/3NP3/8/PPP2PPP/RNBQKB1R w KQkq - 0 5
lastMove: d7 d5
```

``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 d5 5. Bb5 dxe4 6. Nc3 Bd7 7. O-O f5 8. Bxc6 bxc6 9. f3 c5 10. Nb3 Bd6 11. fxe4 Qh4 12. g3 Bxg3 13. Qe2 Bd6 14. e5 Be7 15. Nd5
```

#### g6
``` chess
fen: r1bqkbnr/pppp1p1p/2n3p1/4p3/3PP3/5N2/PPP2PPP/RNBQKB1R w KQkq - 0 4
lastMove: g7 g6

```
``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 g6 5. Nxc6 bxc6 6. Bc4 Bg7 7. O-O Ne7 8. Nc3 d6 9. Be3 O-O 10. Bd4 c5 11. Bxg7 Kxg7 12. f4 Be6 13. Bd3 f5 14. Qd2 Qd7 15. Rae1 Rab8 16. b3
```

#### d6
C'est mais très passive
``` chess
fen: r1bqkbnr/ppp2ppp/2np4/4p3/3PP3/5N2/PPP2PPP/RNBQKB1R w KQkq - 0 4
lastMove: d7 d6
```

``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 d6 5. Nxc6 bxc6 6. Bd3 Nf6 7. O-O Be7 8. c4 O-O 9. Nc3 Re8 10. Qa4 Bb7 11. c5 dxc5 12. Rd1 Qc8 13. h3
``` 
### Des truces

#### 1. Manger la reine
``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Bc5 5. Be3 Qf6 6. Nb5 Bxe3 7. fxe3 Qxb2 8. N1c3 Kd8 9. Rb1
```

#### 2. Double coup
``` pgn
1. e4 e5 2. Nf3 Nc6 3. d4 exd4 4. Nxd4 Nf6 5. Nxc6 bxc6 6. Nc3 Bb4 7. Bd3 O-O 8. O-O d5 9. exd5 cxd5 10. Bg5 h6 11. Bxf6 Qxf6 12. Nxd5 Qd6 13. Nxb4 Qxb4 14. Qe1 Qxb2 15. Qe4 Rb8 16. Qh7#
```
### Des erreures

#### 1. Erreur
``` chess
fen: r1b1kb1r/pp1pqppp/5n2/2p1P3/3Q4/4B3/PPP2PPP/RN2KB1R w KQkq - 0 8
lastMove: c7 c5
```

#### 2. Erreur
``` chess
fen: r1bqk2r/pppp1ppp/2n2n2/2b5/3NP3/4B3/PPP2PPP/RN1QKB1R w KQkq - 3 6
lastMove: g8 f6
```

#### 3. Erreur 
``` chess
fen: r1bqk1nr/ppp2ppp/2np4/2b5/3NP3/4B3/PPP2PPP/RN1QKB1R w KQkq - 0 6
lastMove: d7 d6
```
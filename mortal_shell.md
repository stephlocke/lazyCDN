```mermaid
graph BT
  class A cssClass

  1(["
    <b>Temple</b>

    💬
    Genessa
    Forge
    "])
  2("
    <b>Chamber</b>

    👿
    Zelots (4)
    Sword and Shield Knight (1)
    
    🎁
    Weltcap (1)
    ")
  3("
    <b>Crypt 1</b>

    👿
    Shades (2)

    🎁
    Crypt (Glimpses?)
    
    💬
    Inscription
    ")
  4("
    <b>Bridge</b>
    
    👿
    Skull Knight (1)
    Zelots (2)

    💬
    Inscription
    ")
  5(Cages)
  6(Corridor)
  7{{Locked}}
  8(Maidens)
  9(Spike Pit)
  10(Carved Stones)
  11(Stairs)
  12(Crypt 2)
  13(Path)
  14(Crypt 3)
  15[/Boss 1\]

  1 --- 2
  2 --- 3
  2 --- 4
  4 --- 5
  subgraph "Monument of Ash"
    5 --- 6
    6 --- 7
    6 --- 8
    8 --- 9
    9 --- 10
    10 --- 12
    10 --- 11
    10 --- 13
    13 --- 14
    13 --- 15
  end

```
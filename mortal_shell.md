```mermaid
graph BT
  class A cssClass

  1(["
    <b>Entrance</b>

    💬
    Genessa
    Anvil
    Book

    🎁
    Smouldering Mace
    "])
  2("
    <b>Chamber</b>

    👿
    Acolyte of Ash (4)
    Herald of Faith (1)
    
    🎁
    Weltcap (1)
    ")
  3("
    <b>Tomb 1</b>

    👿
    Ashen Wraith (3)

    🎁
    Glimpse of Affection (1)
    Foundry Stone (1)
    
    💬
    Tomb
    Inscription
    ")
  4("
    <b>Bridge</b>
    
    👿
    Acolyte of Ignis (1)
    Acolyte of Ash (2)

    💬
    Inscription
    ")
  5("
    <b>Cages</b>

    👿
    Acolyte of Ignis (1)
    Acolyte of Ash (2)
    ")
  6(Corridor)
  7{{Locked}}
  8(Maidens)
  9(Spike Pit)
  10(Carved Stones)
  11(Stairs)
  12(Tomb 2)
  13(Path)
  14(Tomb 3)
  15[/Boss 1\]

  subgraph "Temple Grounds"
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
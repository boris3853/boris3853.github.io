# Logic Gates
## AND
![AND_COMPARE](https://user-images.githubusercontent.com/60434800/147720168-66cb2216-b74c-4399-af62-d54a6ed93a58.png)
https://www.ti.com/lit/ds/symlink/sn74ls09.pdf?ts=1640783088049&ref_url=https%253A%252F%252Fen.wikipedia.org%252F

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## OR
![OR_COMPARE](https://user-images.githubusercontent.com/60434800/147720187-13045d72-005a-4814-9fe0-1ba28479712c.png)
https://www.ti.com/lit/ds/symlink/sn74ls32.pdf?ts=1640831188320&ref_url=https%253A%252F%252Fen.wikipedia.org%252F

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

## NOT
![NOT_COMPARE](https://user-images.githubusercontent.com/60434800/147720196-e20039f9-6094-4f11-9a97-3972d2170a92.png)
https://www.ti.com/lit/ds/symlink/sn74ls04.pdf?ts=1640835721752&ref_url=https%253A%252F%252Fen.wikipedia.org%252F

| A | B |
|---|---|
| 0 | 1 |
| 1 | 0 |

## NAND
![NAND_COMPARE](https://user-images.githubusercontent.com/60434800/147720200-2dcccf0f-e523-4946-bd4f-f50c769adc7a.png)
https://www.ti.com/lit/ds/symlink/sn54ls03.pdf?ts=1640783174878&ref_url=https%253A%252F%252Fen.wikipedia.org%252F

| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## NOR
![NOR_COMPARE](https://user-images.githubusercontent.com/60434800/147720194-bc67c8e7-d33e-4e58-9d5c-3623f394ac33.PNG)
https://www.ti.com/lit/ds/symlink/sn74ls02.pdf?ts=1640825635069&ref_url=https%253A%252F%252Fen.wikipedia.org%252F

| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

## XOR && XNOR

XOR : A ⊕ B = AB' + A'B 로 구현
| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

XNOR : (A ⊕ B)' = AB + A'B' 로 구현
| A | B | Y |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

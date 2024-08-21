# Abstract Data Type

## ADT Titik
**Type** POINT: 
- **X**: integer, {absis}
- **Y**: integer, {ordinat}

**Function** `MakeTitik(x: integer, y: integer)`
- **Kamus Lokal**:
  - `T: Titik`
- **Algoritma**:
  - `T.absis <- x`
  - `T.ordinat <- y`

Contoh: `T1 <- MakeTitik(3,2)`

**Function** `GetAbsis(T: Titik)`
    -> `T.absis`
# Abstract Data Type

## ADT Titik
<u>type</u> POINT : < X : integer, { absis }
               Y : integer, { ordinat }>

<u>function</u> MakeTitik(x: integer, y: integer)
    { kamus lokal }
        T: Titik
    { algoritma }
        T.absis <- x
        T.ordinat <- y

contoh: T1 <- MakeTitik(3,2)

<u>function</u> GetAbsis(T: Titik)
    -> T.absis
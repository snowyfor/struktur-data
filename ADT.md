# Abstract Data Type

## ADT Titik
_type_ POINT : < X : integer, { absis }
               Y : integer, { ordinat }>

_function_ MakeTitik(x: integer, y: integer)
    { kamus lokal }
        T: Titik
    { algoritma }
        T.absis <- x
        T.ordinat <- y
        
contoh: T1 <- MakeTitik(3,2)

_function_ GetAbsis(T: Titik)
    -> T.absis
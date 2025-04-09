# Actuador_colector
Movimiento automatizado d
; Unidades en milímetros
G90          ; Posicionamiento absoluto

G1 F80       ; Velocidad de avance: 80 mm/min

G1 X200      ; Movimiento hacia adelante 200 mm (ida, 150 s)
G4 P1        ; Pausa de 1 segundo

G1 X0        ; Regresa al punto inicial (150 s)
G4 P1        ; Pausa de 1 segundo

M2           ; Fin del programa

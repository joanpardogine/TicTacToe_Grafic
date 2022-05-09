# TicTacToe_Grafic

``` java
private void tenimGuanyador() {
      // Verticals
      // 0,0 + 1,0 + 2,0
      // 0,1 + 1,1 + 2,1
      // 0,2 + 1,2 + 2,2

      // Horitzontals
      // 0,0 + 0,1 + 0,2
      // 1,0 + 1,1 + 1,2
      // 2,0 + 2,1 + 2,2

      // Diagonals
      // 0,0 + 1,1 + 2,2		
      // 0,2 + 1,1 + 2,0

      if ((taulell[0][0].getText().equals(jugadorActual) &&
            taulell[1][0].getText().equals(jugadorActual) &&
            taulell[2][0].getText().equals(jugadorActual)
         ) || (
            taulell[0][1].getText().equals(jugadorActual) &&
            taulell[1][1].getText().equals(jugadorActual) &&
            taulell[2][1].getText().equals(jugadorActual)
         ) || (
            taulell[0][2].getText().equals(jugadorActual) &&
            taulell[1][2].getText().equals(jugadorActual) &&
            taulell[2][2].getText().equals(jugadorActual)
         )
         ) {
         JOptionPane.showMessageDialog(null, "El jugador " +
               jugadorActual + " ha guanyat!");
         tenimGuanyador = true;
      }
   }
```
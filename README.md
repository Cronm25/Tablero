# Tablero
for(let i=0; i < tablero.length; i++)
{
	for(let j=0; j < tablero[i].length; j++)
	{
        if(i % 2 === 0) {
            if(j % 2 === 0) {
            tablero[i][j] = "rojo"
        }
            else {
            tablero[i][j] = "azul"
        }
        }
            else {
            if(j % 2 === 0) {
            tablero[i][j] = "azul"
        }
            else {
            tablero[i][j] = "rojo"
        }
        }
	}
}

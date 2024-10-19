# Primeiro projeto teste
Conversor de escala termométricas

package main
import "fmt"

const ebulicaoK = 373

func main() {
    var tempK = ebulicaoK
    var tempC = (tempK - 273)
    
  fmt.Println("A temperatura de ebulição da água em °K = ", tempK)
  fmt.Println("A temperatura de ebulição da água em °C = ", tempC)
}

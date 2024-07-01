# desafio-dio

import UIKit

let constantName = "Steve"

var optionalVariable: String? = "Jobs"

print("Constante: \(constantName), Variavel desembrulhada: \(optionalVariable ?? "Wozniak") ")

if let unwrapperVariable = optionalVariable{
    print("Constante: \(constantName), Variavel desembrulhada: \(unwrapperVariable)")
} else{
    print("Constante: \(constantName), Variavel: Wozniak")
}

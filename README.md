import Foundation 

var Number1 = 1
var Number2 = 9

let operation = "multiplication"

switch operation {
    case "addition":
    let result = Number1 + Number2
    print("Ergebnis: \(result)")
    case "substraction":
     let result = Number1 - Number2
     print("Ergebnis: \(result)")
    case "multiplication":
     let result = Number1 * Number2
     print("Ergebnis: \(result)")
    case "division":
    let result = Number1 / Number2
    print("Ergebnis: \(result)")


    default:
    print("Ungültige Operation ausgewählt.")
    }

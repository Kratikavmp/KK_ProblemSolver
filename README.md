# KK_ProblemSolver
Solve the plusMinus function

func plusMinus(arr: [Int]) -> Void {
var a = 0
var b = 0
var c = 0
let d = arr.count

for i in 0..<d{
    if arr[i] > 0{
        a = a+1
    }
    else if arr[i] < 0{
        b = b+1
    }
    else if arr[i] == 0{
        c = c+1
    }
}

print("\(String(format:"%.6f", Double(a) / Double(d)))")
print("\(String(format:"%.6f", Double(Double(b) / Double(d))))")
print("\(String(format:"%.6f", Double(Double(c) / Double(d))))")

}

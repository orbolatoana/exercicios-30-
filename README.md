# exercicios-30-

## ex 1:

fun main() {
    
    var entrada_celsius = 30
    
    // F = C * 9/5 + 32
    var F = entrada_celsius * 9 / 5 + 32
    
    print(F)
    
}

## ex 2:

fun main() {
    
    var entrada_fahrenheit = 100
    
    // F = C * 9/5 + 32
    var F = (entrada_fahrenheit - 32) * 5 / 9
    
    print(F)
    
}

## ex 3:

fun main() {
    
    var raio = 5f
    var altura = 10f
    val PI = 3.14159f
    
    var vol = PI * raio * raio * altura
    
    println(vol)
    
}

## ex 4:

fun main() {
    
    var dist = 240
    var cons = 12
    
    var litros = dist / cons
    
    print(litros)
    
}

## ex 5

fun main() {
    
    var orig = 1000
    var atras = 3
    var taxa = 1f
    
    var valor = orig * (1 + (taxa/100) * atras)
    
    print(valor)
    
    
}

## ex 6:

fun main() {
    
    var a = 3
    var b = 2
    
    println("Antes da troca os valores: a váriavel A tem $a e váriavel B tem $b !\n")
    
    var troca = a
	a = b
	b = troca

    println("Com a troca de valores, agora: a váriavel A tem $a e váriavel B tem $b !")
    
}

## ex 7:

fun main() {
    
    var a = 1
    var b = 2
    var c = 3
    var d = 4
    
    println("Adições:")
	println(a+b)
    println(a+c)
    println(a+d)
    println(b+c)
    println(b+d)
    println(c+d)
    println("Multiplicações:")
    println(a*b)
    println(a*c)
    println(a*d)
    println(b*c)
    println(b*d)
    println(c*d)
    
    
}

## ex 8:

fun main() {
    
    var comp = 5
    var larg = 3
    var alt = 2
    
    var vol = comp * larg * alt
    
    println(vol)
    
}

## ex 9:


import kotlin.math.pow

fun main() {
    
    var valor = 5.0
    
    val exp = valor.pow(2)
    
    println(exp)
    
}

## ex 10:

import kotlin.math.pow

fun main() {
    
    var a = 10
    var b = 5
    
    var sub = a - b
    
    println(sub)
    
}

## ex 11:

import kotlin.math.pow

fun main() {
    
    var dol = 50f
    
    var reais = dol * 5.21
    
    println("R$" + reais)
    
}

## ex 12:

import kotlin.math.pow

fun main() {
    
    var reais = 50f
    
    var dol = reais / 5.21
    
    println("R$" + dol)
    
}

## ex 13:

import kotlin.math.pow

fun main() {
    
    val lista = listOf(2f, 3f, 4f)
    
    var form = (lista[0].pow(2)) + (lista[1].pow(2)) + (lista[2].pow(2))
    
    println(form)
    
}

## ex 14:

import kotlin.math.pow

fun main() {
    
    val lista = listOf(2f, 3f, 4f)
    
    var form = (lista[0] + lista[1] + lista[2]).pow(2)
    
    println(form)
    
}

## ex 15:

import kotlin.math.pow

fun main() {
    
    var a = 2
    var b = 3
    var c = 4
    var d = 5
    
    var mult = a * c
    var soma = b + d
    
    println("Multiplicação: $mult \nAdição: $soma")
    
}

## ex 16:

import kotlin.math.pow

fun main() {
    
    var sal = 1000f
    var porcent = 10f
    
    var aumento = sal * (porcent/100)
    sal += aumento
    
    print("Salário pós-aumento: R$$sal \nAumento: R$$aumento")
    
}

## ex 17:

import kotlin.math.pow

fun main() {
    
    val PI = 3.141
    
    var raio = 5f
    
    var area = PI * raio.pow(2)
    
    println("$area cm²!")
    
}

## ex 18:

import kotlin.math.pow

fun main() {
    
    var cand1 = 200f
    var cand2 = 150f
    var cand3 = 100f
    var nulo = 50f
    var branco = 30f
    
    var total = cand1 + cand2 + cand3 + nulo + branco
    
    var porcent1 = cand1*100/total
    var porcent2 = cand2*100/total
    var porcent3 = cand3*100/total
    var porcentN = nulo*100/total
    var porcentB = branco*100/total
    
    print("Percentual votos válidos:")
    print("\n  candidato 1 = $porcent1%")
    print("\n  candidato 2 = $porcent2%")
    print("\n  candidato 3 = $porcent3%")
    println("\nPercentual votos nulos: $porcentN%")
    println("Percentual votos em branco: $porcentB%")
    
}

## ex 19:

import kotlin.math.pow

fun main() {
    
    var cand1 = 200.0
    var cand2 = 150.0
    var cand3 = 100.0
    var nulo = 50.0
    var branco = 30.0
    
    var total = cand1 + cand2 + cand3 + nulo + branco
    
    var porcent1 = cand1*100/total
    var porcent2 = cand2*100/total
    var porcent3 = cand3*100/total
    var porcentN = nulo*100/total
    var porcentB = branco*100/total
    
    print("Percentual votos válidos:")
    print("\n  candidato 1 = $porcent1%")
    print("\n  candidato 2 = $porcent2%")
    print("\n  candidato 3 = $porcent3%")
    println("\nPercentual votos nulos: $porcentN%")
    println("Percentual votos em branco: $porcentB%")
    
}

## ex 20:

import kotlin.math.pow

fun main() {
    
  	var dist = 50f
    var tempo = 1f
    
    var vel = dist / tempo / 3.6
    
    println("$vel m/s !")
    
}

## ex 21:

import kotlin.math.pow

fun main() {
    
  	var base = 2f
    var expo = 3f
    
    var potencia = base.pow(expo)
    
    println("Potência = $potencia")
    
}

## ex 22:

import kotlin.math.pow

fun main() {
    
    val PI = 3.14
    
  	var raio = 5f
    var vol = (4/3f) * PI * raio.pow(3)
    
    println("Volume: $vol")
    
}

## ex 23:

import kotlin.math.pow

fun main() {
    
    var pes = 10
    
    var metros = pes * 0.3048
    
    println("Metros: $metros")
    
}

## ex 24:

import kotlin.math.pow

fun main() {
    
    var base = 16f
    var ind = 2f
    
    var raiz = base.pow(1/ind)
    
    println("Raiz: $raiz")
    
}

## ex 25:

import kotlin.math.pow

fun main() {
    
    var a = 5
    
    var suc = 5+1 
    var ant = 5-1
    
    println("Sucessor: $suc \nAntecessor: $ant")
    
}

## ex 26:

import kotlin.math.pow

fun main() {
    
    var a = 10f
    var b = 2f
    
    var form = (a/b).pow(2)
    
    println("Resultado: $form")
    
}

## ex 27:

import kotlin.math.pow

fun main() {
    val num1 = readLine()!!.toInt()
    val num2 = readLine()!!.toInt()

    val diferenca = if (num1 > num2) num1 - num2 else num2 - num1

    println(diferenca)
}

## ex 28:

import kotlin.math.pow

fun main() {
    val numero = readLine()!!.toInt()

    if (numero > 0) {
        println("Positivo")
    } else if (numero < 0) {
        println("Negativo")
    } else {
        println("Neutro (Zero)")
    }
}




## ex 29:

import kotlin.math.pow

fun main() {
    val nota1 = readLine()!!.toDouble()
    val nota2 = readLine()!!.toDouble()
    val nota3 = readLine()!!.toDouble()
    val nota4 = readLine()!!.toDouble()

    val media = (nota1 + nota2 + nota3 + nota4) / 4

    if (media >= 5) {
        println("Média: $media, Aprovado")
    } else {
        println("Média: $media, Reprovado")
    }
}


## ex 30:

import kotlin.math.pow


fun main() {
    val nota1 = readLine()!!.toDouble()
    val nota2 = readLine()!!.toDouble()
    val nota3 = readLine()!!.toDouble()
    val nota4 = readLine()!!.toDouble()

    val media = (nota1 + nota2 + nota3 + nota4) / 4

    if (media > 7) {
        println("Média: $media, Aprovado")
    } else if (media >= 5) {
        println("Média: $media, Exame")
    } else {
        println("Média: $media, Reprovado")
    }
}












































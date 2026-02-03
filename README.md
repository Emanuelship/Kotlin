# Kotlin
fun main() {
    val valor_original = 1000.0
    val meses_atraso = 3
    val taxa_juros = 1.0

    val valor_final = valor_original * (1 + (taxa_juros / 100) * meses_atraso)

    println(valor_final)
}

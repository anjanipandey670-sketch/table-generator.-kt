fun main() {
    print("enter your number: ")
    val num = readLine()!!.toInt()

    for (i in 1..10) {
        println("$num x $i = ${num * i}")
    }
}

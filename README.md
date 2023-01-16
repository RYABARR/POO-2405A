# POO-2405Afun main() {
   //POO-programação orientada a objetivos - simular coisas da realidade na programação
   //
   //objetos - possui estado (nome,idade,altura e etc),
   //comportamento(andar,correr,dormir,come etc)
   //
   //a POOa dividida
   //
   //classes - são modelos que servem para a construção de objs derivadas deles mesmo (ex classe pessoa)
   //as classem recebem atributos(os estado)
   //
   //metodos - sera as distancia da classe, as formas de agir
   //estrutura de uma classe
   //   clos nome () {ocorridos de um obj}
   /*
   var ricardo = pessoa () // instanciando um obj
   ricardo.nome = "ricardo franco de oliweira"
   ricardo.altura = 2.15 
   ricardo.cordosolhos = "verdes"
   ricardo.peso = 100.00
   println(ricardo altura) //para exibir um atributo em especifico
   */
    val convidado1 =pessoa("claudio", 1.79,"castanhos",183.0)
    println(convidado1.peso)
    val convidado2 =pessoa("juliana",1.5, "azul",53.5)
    val convidado3 =pessoa("guilherme",1.76,"castanho",63.9)
    val convidado4 =pessoa("thago",1.71,"azul",57.4)
    val convidado5 =pessoa("isabella",1.63,"azul",56.6)
    val convidado6 =pessoa("luiz",2.0,"castanho",54.9)
    println("convidado")
    println("convidado") 
    println("convidado") 
    println("convidado")
}
class pessoa(val nome : String, 
             val altura :  Double,
             val cordosolhos: String, 
             val peso: Double){}
    //declarando atributos para a classe
    /*
    var nome =""
    var altura = 0.0 
    var cordosolhos =""
    var peso =0.0
    /*
     

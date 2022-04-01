public class calculadora {
	
	String nome;
	
	public int soma(int x, int y) {
		return x+y;
	}

	public static void main(String[] args) {
		Calculadora calculadoraSimples = new Calculadora();
		calculadoraSimples.nome = "Calculadora simples"
	    System.out.println(calculadoraSimples.nome);
		System.out.println("Resultado da soma; " + calculadoraSimples.soma(2, 3));
	
	}

}

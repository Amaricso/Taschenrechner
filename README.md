
public class Taschenrechner {

	static int Division(int zahl1, int zahl2) {
		return (zahl1 / zahl2);
	}

	static int Multiplikation(int zahl1, int zahl2) {
		return (zahl1 * zahl2);
	}

	public static void main(String[] args) {
		final int zahl1 = 18;
		final int zahl2 = 6;
		int mu;
		int di;

		di = Division(zahl1, zahl2);
		mu = Multiplikation(zahl1, zahl2);

		System.out.println("Die Multiplikation von 18 und 6 ist =" + mu);
		System.out.println("Die Division von 18 und 6 ist =" + di);
		
	}
}

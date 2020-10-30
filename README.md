# Programmering-EC
Skolrelaterade projekt mm
public class Biljett {
	
	private int prisGrupp1Biljett = 35;
	private int prisGrupp2Biljett = 20;
	private int prisgrupp1Månadskort = 600;
	private int prisGrupp2Månadskort = 450;
	
	//måste in med getters och setters här då
	
	if(age >= 18 && age <= 65){
		//blir problem om namn slutar s...
		System.out.println(name +"s biljett kostar: " +biljett.prisGrupp1Biljett); //var hämtar metoden priserna? I samma klass?
		System.out.println(name +"s månadskort kostar: " +biljett.prisgrupp1Månadskort);
	} 
	else {
		System.out.println("Namn: " +name + " pris: " +biljett.prisGrupp2Biljett); //här vill jag då sätta in en metod som hämtar prisGrupp1 tex
		System.out.println("Namn: " +name + " pris: " +biljett.prisGrupp2Månadskort); //här vill jag ha en metod som hämtar prisGrupp2
	}

}

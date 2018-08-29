package demoArrayList;

import java.util.ArrayList;

public class Application {
	

	public static void main(String[] args) {
		//on cree une ArrayList de type Personne nommee listePersonne
		ArrayList<Personne> listePersonne = new ArrayList<Personne>();
		
		//on cree une instance de la Class Personne
		Personne p1 = new Personne();
		
		//on donne les valeurs au variables de instance p1
		p1.setNom("Poulouin");
		p1.setPrenom("Pierre");
		p1.setAge(23);
		p1.setTelephone("rouge");
		p1.setEmail("pierremail@mail.com");
		
		//on ajoute dans ArrayList listePersonne l'objet avec la methode ".add()"
		listePersonne.add(p1);
		
		Personne p2 = new Personne();
		
		p2.setNom("Bordes");
		p2.setPrenom("Constance");
		p2.setAge(26);
		p2.setTelephone("0666666666");
		p2.setEmail("constancemail@mail.com");
		
		listePersonne.add(p2);
		
		for (int i=0; i < listePersonne.size(); i++) {
			System.out.print(listePersonne.get(i).getPrenom());
			System.out.print(" ");
			System.out.print(listePersonne.get(i).getNom());
			System.out.print(" ");
			System.out.print(listePersonne.get(i).getEmail());
			System.out.print(" ");
			System.out.print(listePersonne.get(i).getAge());
			System.out.print(" ");
			System.out.print(listePersonne.get(i).getTelephone());
			System.out.print(" ");
		}

	}

}

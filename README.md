package org.edu;
public class Education {
	public Education() {
		System.out.println("cources offered by the collage");
		
	}
	public void ug() {
		System.out.println("ug department");
	}
	public void pg() {
		System.out.println("pg department");
	}
	public static void main(String[] args) {
		Arts b=new Arts();
		b.bSc();
		b.bEd();
		b.bA();
		b.bBa();
		Engineering e=new Engineering();
		e.ug();
		e.bE();
		e.bTech();
		Medicine a=new Medicine();
		a.physiyo();
		a.dental();
		a.mbbs();
	

	}

}

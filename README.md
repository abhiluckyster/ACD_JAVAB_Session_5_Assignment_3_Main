# ACD_JAVAB_Session_5_Assignment_3_Main
package OOPsPart3;
public class Area {
	Area(){
		int side1=10;
		System.out.println("Area of square is "+(side1*side1));
	};
	Area(int side1, int side2){
		System.out.println("Area of rectangle is "+(side1*side2));
	}
}

package OOPsPart3;
public class ConstructorOverloading {
	public static void main(String[] args) {
		Area square = new Area();
		Area rectangle = new Area(10,20);
	}
}


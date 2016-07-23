# JavaSess8Ass1

package Session8;

import java.util.ArrayList;
import java.util.ListIterator;

public class Sess8Ass1 {
	public static void main(String[] args) {
		ArrayList<String> arr=new ArrayList<>();
		arr.add("Jonny");
		arr.add("Dolly");
		arr.add("Jack");
		arr.add("Hill");
		arr.add("John");
		
		ListIterator<String> itr=arr.listIterator();
		while(itr.hasNext()){
			String obj=itr.next();
			System.out.println(obj);
		}
	}
}

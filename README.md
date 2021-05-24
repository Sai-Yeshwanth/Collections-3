import java.util.HashSet;
import java.util.Iterator;

public class Jala {
	public static void main(String[] args){
		HashSet<String> set = new HashSet<String>();
		

		set.add("Sai");
		set.add("Yesh");
		set.add("Jala");
		set.add("Yuvraj");
		set.add("Rishabh");
		set.add("Ram");
		set.add("Anu");
		set.add("Nithin");
		set.add("Khanna");
		set.add("Ram");
		set.add("Nani");
		
		// add a value into set
		set.add("John");
		
		//fetch the values of the set
		System.out.println(set);
		
		//create a clone/copy of hashset
		System.out.println(set.clone());
		
		//check whether set contains a particular name or not
		System.out.println(set.contains("Sai"));
		
		//check whether set is empty or not
		System.out.println(set.isEmpty());
		
		//print size of set
		System.out.println("Size of map is : "+set.size());
		
		//remove a specific name in set
		set.remove("Sai");
		
		//iterating
		Iterator<String> it = set.iterator();
		while(it.hasNext())
		{
			System.out.println(it.next());
		}
  
    //Removing all elements in set
		set.removeAll(set);
  
    //Clear
    set.clear();
	}
}

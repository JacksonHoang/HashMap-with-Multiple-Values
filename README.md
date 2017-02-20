# HashMap-with-Multiple-Values


import java.util.*;

class AceTester
{

	   public static void main(String args[]) {

		   Map<String, List<String>> hashMapMultValues = new HashMap<String, List<String>>();
		   List<String> vals = new ArrayList<String>();
		   List<String> vals2 = new ArrayList<String>();
		   vals.add("1st Value");
		   vals.add("2nd Value");
		   vals.add("3rd value");
		   vals.add("4th value");
		   vals.add("5th value");
		   vals.add("6th value");
		   vals.add("7th value");
		   vals2.add("1st Value");
		   vals2.add("2nd Value");
		   vals2.add("3rd value");
		   vals2.add("4th value");
		   vals2.add("3rd value");
		   vals2.add("2nd value");
		   vals2.add("1st value");
		   
		   hashMapMultValues.put("Key1", vals);
		   hashMapMultValues.put("Key2", vals2);
		   
		   System.out.println("Key 1 values are:" + hashMapMultValues.get("Key1"));
		   System.out.println("Key 2 values are:" + hashMapMultValues.get("Key2"));

		   }
       
}

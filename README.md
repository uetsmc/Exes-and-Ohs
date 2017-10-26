# Exes-and-Ohs
CodeWars Exes and Ohs Java Solution

public class XO {
  
      public static boolean getXO(String str) {

        int xcount = 0;
        int ocount = 0;
        str.toLowerCase();
        char[] checkingArray = str.toCharArray();
        for (int i = 0; i < checkingArray.length; i++) {
            if (checkingArray[i] == 'x') {
                xcount++;
            } else if (checkingArray[i] == 'o') {
                ocount++;
            }          
}
if (ocount == xcount){
                return true;
            }
return false;
}
}

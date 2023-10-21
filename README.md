public class stringmethod {
    public static void main(String[] args){

        String name = "Birendra";
        System.out.println(name);

//.lenght help to find out the length of the string
        int length = name.length();
        System.out.println(length);

//.tolowerCase use to convert into lowercase
        String lstring = name.toLowerCase();
        System.out.println(lstring);

//.toUpperCase use to convert into UpperCase
        String ustring = name.toUpperCase();
        System.out.println(ustring);

        String nontrimmedString= "    Birendra      ";
        System.out.println(nontrimmedString);

//.trim used to remover space(blank space) before and after the string 
        String trimmedString = nontrimmedString.trim();
        System.out.println(trimmedString);

//.substring indicate beginning to end of the displayed string
//Returns a substring from start to end
//Indexing start from always with 0
        System.out.println(name.substring(1));
        System.out.println(name.substring(1,5));

//.replace used to replace the word 
// ('a','p')/("a","ies")
        System.out.println(name.replace('a','i'));

//.startsWith and .endsWith check the string is start and end to the given prefiz and suffix 
//if true it return true otherwise fasle 
        System.out.println(name.startsWith("Bir"));
        System.out.println(name.endsWith("yyy"));

//.charAt return the index position of sting
        System.out.println(name.charAt(7));

//.equal return true if the given string is equal to "birendra" false otherwise  
//check the case i.e upper or lower
        System.out.println(name.equals("birendra"));
        
//.equalsIgnoreCase return trure if two string is equal, ignoring teh case of character
        System.out.println(name.equalsIgnoreCase("birendra"));

    }
}

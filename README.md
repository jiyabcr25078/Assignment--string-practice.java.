class StringMethod
{
    public static void main(String args[])
    {
        String s1 = "Hello";
        String s2 = "Harry";

        System.out.println("Length of string:");
        System.out.println(s1.length());

        System.out.println("Concatenation:");
        System.out.println(s1 + "*" + "  " + s2);

        System.out.println("Upper case:");
        System.out.println(s1.toUpperCase());

        System.out.println("Lower case:");
        System.out.println(s2.toLowerCase());

        System.out.println("Substring:");
        System.out.println(s1.substring(0,3));
        System.out.println(s2.substring(1));

        System.out.println("Equals:");
        System.out.println(s1.equals(s2));

        System.out.println("Replace:");
        System.out.println(s2.replace("Harry","World"));

        System.out.println("CharAt:");
        System.out.println(s1.charAt(4));
    }
}

# CONVERSION-OF-ARRAY-TO-STRINGS-AND-CHECKING-EQUAL-OR-NOT
class HelloWorld {
    public static void main(String[] args) {
        String []s1={"a","bc"};
        String []s2={"ab","c"};
        int n=s1.length;
        int m=s1.length;
        String str="",str1="";
        for(int i=0;i<n;i++){
            str+=s1[i];
        }
       for(int i=0;i<n;i++){
            str1+=s2[i];
        }
        System.out.println(str.equals(str1));
    }
}

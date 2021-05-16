# Play-with-OR

class Complete{
public static int[] game_with_or(int arr[], int n) 
{
int r[] = new int[n];
for(int i=0;i<=arr.length-2;i++)
{
int a=arr[i]|arr[i+1];
r[i]=a;
}
r[n-1]=arr[n-1];
return r;
}
}
public static void main(String[] args)
{
    game_with_or(int arr[], int n);
int arr[]={10,11,1,2,3};
int n=arr.length;
 System.out.println(r);
                                

}

import java.util.Arrays;
public class Main {
  public static void main(String[] args) {
    int ans[]={100,2,3,90,4,5};
   Arrays.sort(ans);
    int n=ans.length;
    int count =0;
    int ansa=ans[0];
    for(int i=0; i<n; i++){
      if(ansa+i==ans[i]){
        count++;
      }

    }
      System.out.println(count);
  }
}

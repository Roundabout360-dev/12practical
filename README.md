# 12practical

import java.util.Random;
import java.util.Scanner;


public class Main{
    public static void main(String[]args){


        int n=20;
        int[] X=new int [n];

        X=[Random.rand(1,n)*(-1)];
        for(int k=0;k<=n;++k){
            int countP=0;
            int countM=0;

            for(int x:X){
                if (int x<0){
                countM += 1;
                }
                else{
                countP+=1;
                }
            }




            }
        }
    }



private int mcsOn3(X){
    int n=;
    int maxofar=0;
    for(int low=0;low<=X.length;++low){
        int sum=0;
        for(){
            sum+=X[r];
            if(sum>maxofar);
            maxofar=sum;
        }
        return maxofar;

    }
}
private int mcson(X){

     int n = len(X);
     int sumTo = [0]*(n+1);
     for (int i=0;i<=n;++i){
         sumTo[i] = sumTo[i-1] + X[i];
         int maxsofar = 0;
    }

    for (int low=0;low<n;++low {
    for (int high=low;high<n;++high){
        int sum = sumTo[high] − sumTo[low−1];
        for(int low:high){}
        sum of all elements in X[low..high);
        if (sum > maxsofar){
            int maxsofar = sum;}
    }
    }
     
    return maxsofar;

}

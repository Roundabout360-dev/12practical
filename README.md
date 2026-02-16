# 12practical

import java.util.Random;
import java.util.Scanner;

import static com.sun.tools.javac.main.Option.X;
import static com.sun.tools.javac.main.Option.values;


public class Main{
    public static void main(String[]args){


        int n=20;
        int[] X=new int [n];

        X=[Random(1,n)*(-1)];
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
    int n= values().length;
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

     int n = values().length;

     int sumTo = [0]*(n+1);
     for (int i=0;i<=n;++i){
         sumTo[i] = sumTo[i-1] + X[i];
         int maxsofar = 0;
    }

    for (int low=0;low<n;++low ){
    for (int high=low;high<n;++high){
        int sum = sumTo[high] - sumTo[low−1];
        if (sum > maxsofar){
            int maxsofar = sum;}
    }
    }

    return maxsofar;


}
private int mcsOnlogn(int X,int low,int high){}
int sum=0;
int maxoffarleft=0;
for(int){
    sum+=X{middle+1];

    }
        }

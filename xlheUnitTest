import com.sun.org.apache.bcel.internal.generic.NEW;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;
import java.util.Random;

public class xlheUnitTest {
    public static void main (String[] args) {
        long startTime= System.nanoTime();
        List<Integer> list = new ArrayList<Integer>();
        Random random = new Random();
        int[] values = new int[1000];
        for (int i=0;i<1000;i++){
            values[i] = i*10+random.nextInt(9);
        }
        long endTime = System.nanoTime();
        long Time = endTime-startTime;
        boolean flag=true;
        for (int n=0;n<999;n++) {
            if (values[n + 1] - values[n] > 1) {
                flag = true;
            } else {
                break;
            }
        }
        System.out.println("数组是连续且有序的" + Arrays.toString(values));
        if ((endTime-startTime)<5) {
            System.out.println("时间小于5毫秒" + Time);
        }
        else {
            System.out.println("时间大于5毫秒"+Time);
        }
    }
}

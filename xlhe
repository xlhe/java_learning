import com.sun.org.apache.bcel.internal.generic.NEW;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;
import java.util.Random;

public class xlhetest {
    public static void main (String[] args) {
        long startTime= System.nanoTime();
        List<Integer> list = new ArrayList<Integer>();
        Random random = new Random();
        int[] values = new int[1000];
        for (int i=0;i<1000;i++){
            values[i] = i*10+random.nextInt(9);
        }
        long endTime = System.nanoTime();
        System.out.println(Arrays.toString(values));
        System.out.println("时间"+(endTime-startTime));


    }
}

import java.util.Scanner;
public class heap {
	public static void main(String args[]) {
        Scanner obj=new Scanner(System.in);				
        int in1, in2, in3, in4, in5, in6, in7, in8, in9, in10, in11, in12, in13, in14, in15, in16, in17, in18, in19, in20, in21, in22, in23, in24, in25;
        
        System.out.println("  _    _                     _____            _   \r\n" + 
        		" | |  | |                   / ____|          | |  \r\n" + 
        		" | |__| | ___  __ _ _ __   | (___   ___  _ __| |_ \r\n" + 
        		" |  __  |/ _ \\/ _` | '_ \\   \\___ \\ / _ \\| '__| __|\r\n" + 
        		" | |  | |  __/ (_| | |_) |  ____) | (_) | |  | |_ \r\n" + 
        		" |_|  |_|\\___|\\__,_| .__/  |_____/ \\___/|_|   \\__|\r\n" + 
        		"                   | |                            \r\n" + 
        		"                   |_|                            ");
        
        
        
        System.out.println("Enter 25 numbers to sort");
        in1 = obj.nextInt();							
        in2 = obj.nextInt();
        in3 = obj.nextInt();
        in4 = obj.nextInt();
        in5 = obj.nextInt();
        in6 = obj.nextInt();
        in7 = obj.nextInt();
        in8 = obj.nextInt();
        in9 = obj.nextInt();
        in10 = obj.nextInt();
        in11 = obj.nextInt();
        in12 = obj.nextInt();
        in13 = obj.nextInt();
        in14 = obj.nextInt();
        in15 = obj.nextInt();
        in16 = obj.nextInt();
        in17 = obj.nextInt();
        in18 = obj.nextInt();
        in19 = obj.nextInt();
        in20 = obj.nextInt();
        in21 = obj.nextInt();
        in22 = obj.nextInt();
        in23 = obj.nextInt();
        in24 = obj.nextInt();
        in25 = obj.nextInt();
															
		int arr[] = {in1, in2, in3, in4, in5, in6, in7, in8, in9, in10, in11, in12, in13, in14, in15, in16, in17, in18, in19, in20, in21, in22, in23, in24, in25};
        int n = arr.length;										
        System.out.println("Numbers before sorting");
        System.out.println("");
        printArray(arr);
        System.out.println("");
        heap ob = new heap();
        ob.sort(arr);
        int grr[] = {arr[24], arr[23], arr[22], arr[21], arr[20], arr[19], arr[18], arr[17], arr[16], arr[15], arr[14], arr[13], arr[12], arr[11], arr[10], arr[9], arr[8], arr[7], arr[6], arr[5], arr[4], arr[3], arr[2], arr[1], arr[0]};
        System.out.println("Numbers sorted ascending:");
        System.out.println("");
        printArray(arr);
        System.out.println("");
        System.out.println("Numbers sorted descending:");
        System.out.println("");
        printArray(grr);
    }
	
	public void sort(int arr[]) {
        int n = arr.length;
        
        for (int i = n / 2 - 1; i >= 0; i--)
            heapSort(arr, n, i);
        
        for (int i=n-1; i>=0; i--) {
            
            int temp = arr[0];
            arr[0] = arr[i];
            arr[i] = temp;
 
            heapSort(arr, i, 0);
        }
    }
  
    void heapSort(int arr[], int n, int i) {
        
    	int largest = i;
        int l = 2*i + 1;  
        int r = 2*i + 2;  
 
        if (l < n && arr[l] > arr[largest])
            largest = l;
  
        if (r < n && arr[r] > arr[largest])
            largest = r;
        
        if (largest != i) {
            int swap = arr[i];
            arr[i] = arr[largest];
            arr[largest] = swap;
            
            heapSort(arr, n, largest);
        }
    }
   
    static void printArray(int arr[]) {
        int n = arr.length;
        for (int i=0; i<n; ++i)
        System.out.print(arr[i]+" ");
        System.out.println();
    } 

}

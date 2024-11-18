package operaciones;

public class resta {
		

			public static void main(String[] args) {
				// TODO Auto-generated method stub
				int[] sumArray = {4,36,4,23,867};
				int[] subArray = {785675, 56, 5675, 56544, 234};
				int[] prodArray = {6, 8, 20, 23, 12};
	
	
	int resta = 0;

	for(int i = 0; i < subArray.length; i++) {
	resta -= subArray[i];
	}
	System.out.println(" La resta da" + resta);
}
}

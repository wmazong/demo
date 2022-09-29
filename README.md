dempublic static int numberOfSteps (int number) {
			
			Scanner myObj = new Scanner(System.in);
			
			myObj = sc.nextInt();
			
	          int count = 0;
	          while(number > 0){
	              if(number%2 == 1)number--;
	              else number/=2;
	              count++;

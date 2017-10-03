public class product {
		
	        String code;
			
			String description;
			
			int price;
			
			public product()
			{
				price = 0;
				
				code = "no code set";
				 
				description = "no description set";
				
			}
			
			public product(String a,int p,String d) {
				
				code = a;
				
				price = p;
				
				description = d;
				
				}
			
			public int scan(String code)
			{
				System.out.println(price);
				
				return price;
			}
			public static void main(String[] args) {
				
				product car = new product("abc", 200, "new car");
				
				//System.out.println(car.price);
				
				//System.out.println(car.code);
				
				//System.out.println(car.description);
				
				int a = car.scan("abc");
				
				System.out.println(a);
				
			}
		}

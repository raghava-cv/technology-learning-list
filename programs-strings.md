<h2>String Programs</h2>

<ol>
<li><a href="#ReverseStringPreserveSpace">ReverseStringPreserveSpace</a></li>
  <li><a href="#spring-home">Spring</a></li>
  <li><a href="#spring-boot-home">Spring Boot</a></li>
  <li><a href="#microservices-home">Microservices</a></li>
  <li><a href="#hibernate-home">Hibernate</a></li>
  <li><a href="#html-home">HTML</a></li>
  <li><a href="#css-home">CSS</a></li>
  <li><a href="#javascript-home">Javascript</a></li>
  <li><a href="#reactjs-home">Reactjs</a></li>
</ol>

<h2 id="ReverseStringPreserveSpace">ReverseStringPreserveSpace</h2>
<div>
  public class ReverseStringPreserveSpace {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		reverses("I am Raghava Chattada V");

	}
	
	static void reverses(String str) {
		System.out.println(str);
		char[] input = str.toCharArray();
		char[] result = new char[input.length];

    //insert spaces in new array(i.e result for the same positions of input array
		for(int i=0;i<input.length;i++) {
			
			if(input[i] == ' ') {
				result[i] = ' ';
			}
		}
		
		int j = result.length-1;
		for(int i=0;i<input.length;i++) {
			
			if(input[i] != ' ') {
				if(result[j] == ' ') {
					j--;
				}
				result[j] = input[i];
				j--;
			}
		}
		
		System.out.println(String.valueOf(result)); //output : V ad attahCa vahgaRma I
		
	}

}

</div>
<b><u>Result Output :</u></b><br>
<div>
  I am Raghava Chattada V<br>
  V ad attahCa vahgaRma I
</div>
<hr>

<h2 id="spring-home">Spring</h2>

<h2 id="spring-boot-home">Spring Boot</h2>
<h2 id="microservices-home">Spring Boot</h2>
<h2 id="spring-boot-home">Microservices</h2>
<h2 id="hibernate-home">Hibernate</h2>
<h2 id="html-home">HTML</h2>
<h2 id="css-home">CSS</h2>
<h2 id="javascript-home">Javascript</h2>
<h2 id="reactjs-home">Reactjs</h2>



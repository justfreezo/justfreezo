<h1 style="line-height: 1;">
  Bonjour !
  <img src="https://media.giphy.com/media/kdQF3hmlKMqVOhsoAv/giphy.gif" width="50" style="vertical-align: middle;">
</h2>
<h3>I'm a college student in computer science</h3>
<img a1 align='right' src="https://media.giphy.com/media/TEuni0nmeOaFhhvNUw/giphy.gif" width="125">
<br><br>
<p><b><i>Here is something if you want to get to know me better</i></b></p>
<br><br>


```java
package justfreezo.readMe;

import java.util.HashMap;
import java.util.Map;

public class Me {
	private String name;
	private int age;
	private String[] hobbies;
	private String[] languagesSpoken;
	private String[] programmingLanguages;
	private HashMap<String, String> socialMedias;
	
	public Me() {
		this.name = "Paulo Martins";
		this.age = 20;
		this.hobbies = new String[] {"Computer Science", "Music", "Photography"};
		this.languagesSpoken = new String[] { "French", "English", "Portuguese", "Spanish"};
		this.programmingLanguages = new String[] {"Java", "Python", "VB.NET", "C", "C++"};
		this.socialMedias = new HashMap<>(Map.of("Linkedin","paulo-martins1","Discord", "8fu", "Instagram","justfreezo"));
	}
	
	public String hello() {
		StringBuilder sb = new StringBuilder();
		sb.append("Hello welcome to my profile, my name is ").append(name);
		sb.append(System.lineSeparator());
		sb.append("I hope you enjoy my profile, have a nice day!");
		
		return sb.toString();
	}
	
	public static void main(String[] args) {
		Me justfreezo = new Me();
		justfreezo.hello();
	}
}
```

### Basic comparison with Java syntax.

```java
package com.codewithme.java;

import java.util.Date;

public class ClassName{
	
  private String prop; 
	
	public Classname(){
		
	}
	
	public void method(String args) throws Exception{
		OtherClass otherClass = new OtherClass();
    Date d = new Date();
		otherClass.otherMethod(passphrase);	
	}
  
  public String getProp(){
    return this.prop;
  }
  
  public void setProp(String p){
    this.prop = p;
  }

}
```

```groovy
package com.codewithme.java

import org.springframework.beans.factory.annotation.Autowired

public class ClassName{
	
  private String prop
	
	public Classname(){
		
	}
	
	def method(String args) throws Exception{
		OtherClass otherClass = new OtherClass()
    d = new Date()
		otherClass.otherMethod(passphrase)
	}

}
```

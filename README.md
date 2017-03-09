
### [Unit testing Groovy](http://docs.groovy-lang.org/next/html/documentation/core-testing-guide.html)

### Basic comparison with Java syntax.


**Java**
```java
package com.codewithme.pkg;

import java.util.Date;

public class ClassName{
	
  private String prop;
  
  int protectedProp;
	
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

**Groovy**
```groovy
package com.codewithme.pkg

import org.springframework.beans.factory.annotation.Autowired

public class ClassName{
	
  private String prop
		
	def method(String args) throws Exception{  //access modifier means public
		OtherClass otherClass = new OtherClass()
  	d = new Date()
		otherClass.otherMethod(passphrase)	
	}
}
```

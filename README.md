A Maven repository for public projects maintained or supported by [Mike Mitterer](http://www.mikemitterer.at)

Repository params:

    <repository>
        <id>public.maven.repository</id>
        <name>public.maven.repository on GitHub</name>
        <url>https://raw.github.com/MikeMitterer/public.maven.repository/master</url>
        <layout>default</layout>
    </repository>

If you use it in Gradle:

	maven {
		url uri("https://raw.github.com/MikeMitterer/public.maven.repository/master")
	}

Avaliable artifacts:

*	**[BeanValidate](https://github.com/MikeMitterer/gradle-texen-plugin)** 
	Helps creating all sort of text output
	
	    <dependency>
	        <groupId>com.google.gitkit</groupId>
	        <artifactId>gitkit</artifactId>
	        <version>1.1</version>
	    </dependency>
	    	
*	**[TexenPlugin](https://github.com/MikeMitterer/gradle-texen-plugin)** 
	Helps creating all sort of text output
	  
*	**[GitKit](https://github.com/MikeMitterer/public.maven.repository)**   
	Maven-Repo for GitKit (1.1) The java client library for Google Identity Toolkit (GITKit).
	[GitKit](http://code.google.com/p/gitkit-java-client-library/)
	
	This Repo is here on GitHub because Google was not able to provide a Maven-Repo for this.

	    <dependency>
	        <groupId>com.google.gitkit</groupId>
	        <artifactId>gitkit</artifactId>
	        <version>1.1</version>
	    </dependency>
	
If this sample is helpful for you - please [(Circle)](http://gplus.mikemitterer.at/) me.
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

*	**[BeanValidator](https://github.com/MikeMitterer/https://github.com/MikeMitterer/BeanValidator)** 
	Lightweight validator library
	
	    <dependency>
	        <groupId>at.mikemitterer</groupId>
	        <artifactId>beanvalidator</artifactId>
	        <version>0.4</version>
	    </dependency>
	
	Gradle:
	
		compile group: 'at.mikemitterer',       name: 'beanvalidator',           version: '0.4'
		    	
*	**[TexenPlugin](https://github.com/MikeMitterer/gradle-texen-plugin)** 
	Helps creating all sort of text output
	
* 	**Google GUICE NO_AOP**

	I added a NO_AOP-Version of Guice to my public repo because I hope it helps someone else
	to solve the dependency problems with Guice on Android.
	
	GUICE 3.0
	
	    <dependency>
	        <groupId>com.google.inject</groupId>
	        <artifactId>guice</artifactId>
	        <version>3.0-no_aop</version>
	    </dependency>
	
	Gradle:
	
		compile group: 'com.google.inject',       name: 'guice',           version: '3.0-no_aop'
	
	GUICE 4.0 BETA
	
	    <dependency>
	        <groupId>com.google.inject</groupId>
	        <artifactId>guice</artifactId>
	        <version>4.0-beta-no_aop</version>
	    </dependency>
	
	Gradle:
	
		compile group: 'com.google.inject',       name: 'guice',           version: '4.0-beta-no_aop'		
		  
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
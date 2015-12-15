# mvn-repo

How to use
--------

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://raw.githubusercontent.com/lijy91/mvn-repo/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile 'org.blankapp.sdk:library:0.0.1-SNAPSHOT@aar'
    }

Notes:

- empty

License:
--------
The licenses are provided by the individual libary owner. This "mvn-repo" utilizes these libaries and
won´t provide any support, responsibility or licenses itself.
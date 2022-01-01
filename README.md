# External-Lib-Example
Welcome to Northwood Robotics External Lib, in 3 easy steps, be on your way to our cheesecake pathfollowing, Funny swerve tech, and extra stupid stupidity. 

First, Copy Paste this into your settings.gradle under plugin management: 
  plugins {
        id 'com.github.johnrengelman.shadow' version '5.2.0'
           id 'net.ltgt.errorprone' version '1.1.1'
             id 'edu.wpi.first.GradleRIO' version '2020.1.2'
    }
    
    
    
    Step 2: Add these IDs to your build.gradle under plugins: 
        id 'java-library'
    id 'maven-publish'
    id 'net.ltgt.errorprone'

Step 4: Drop this into your dependencies under build.gradle: 

    compileOnly group: 'com.google.errorprone', name: 'error_prone_annotations', version: '2.3.4'

    api group: 'org.ejml', name: 'ejml-simple', version: '0.38'
    api group: 'com.google.code.gson', name: 'gson', version: '2.8.6'

    testImplementation group: 'junit', name: 'junit', version: '4.12'
    testImplementation group: 'org.hamcrest', name: 'hamcrest-library', version: '1.3'
    testImplementation group: "com.github.sh0nk", name: "matplotlib4j", version: '0.4.0'

    errorprone group: 'com.google.errorprone', name: 'error_prone_core', version: '2.3.4'
    
    Happy Coding. 
    

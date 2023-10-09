# Hi, I'm David Heredia 

App Developer

     🥇 Android Development
     🥈 Hybrid Development
     🥉 iOS Development
#
### A few things to know about me...
```kotlin
abstract class Person(name: String = "")

abstract class Developer(job: String = "", name:String): Person(name)

abstract class AndroidDeveloper(mainJob: String = "", name: String): Developer(name, mainJob)

open class Me(var hobbies: List<String>? = arrayListOf(),
              var currentlyLearning: List<String>? = arrayListOf(),
              var wantLearn: List<String>? = arrayListOf(),
         	  open var name: String = "", open var job: String = "", 
              open var mainJob: String = ""): AndroidDeveloper(job, mainJob){
    
    override fun toString():String{
        return "{"+
        "'name':$name,"+
        "'job': $job,"+
        "'mainJob': $mainJob,"+
        "'hobbies':$hobbies,"+
        "'currentlyLearning': $currentlyLearning,"+
        "'wantLearn': $wantLearn"+
        "'}'"
    }
}

fun main() {
    val me = Me()
    val myHobbies: List<String> = arrayListOf("Coding", "Animation", "Music", "Gaming", "TV", "Movies", "Some Anime")
    val thingsToLearn: List<String> = arrayListOf("Clean architechture", "UX design", "DI", "Kotlin")
    val wantLearnList: List<String> = arrayListOf("Android compose", "Flutter", "Machine Learning", "Artificial Intelligence")
    me.name = "David Heredia Tartajo"   
    me.job = "Developer"
    me.mainJob = "Android Developer"
    me.hobbies = myHobbies
    me.currentlyLearning = thingsToLearn
    me.wantLearn = wantLearnList
    
    println(me)
    
}
```

``` js
{
    'name': "David Heredia Tartajo",
    'job': "Developer",
    'mainJob': "Android Developer",
    'hobbies': ["Coding, Animation", "Music", "Gaming", "TV", "Movies"],
    'currentlyLearning': ["Clean architechture", "UX design", "DI", "Kotlin"],
    'wantLearn': ["Android compose", "Flutter", "Machine Learning", "Artificial Intelligence"]
}
```

## What I'm into
#### Android development
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![OkHTTP](https://img.shields.io/badge/OKHTTP-262626?style=for-the-badge&logo=square&logoColor=blue) 
![Retrofit](https://img.shields.io/badge/Retrofit-262626?style=for-the-badge&logo=square&logoColor=blue) 
![JetPack Compose](https://img.shields.io/badge/JetPack%20Compose-Green)

### iOS development
![Objetive C](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white) 
![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white) 
 
### Hybrid development
#### Ionic v2>=
![Ionic](https://img.shields.io/badge/Ionic-02569B?style=for-the-badge&logo=ionic&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

#### Ionic v1
![Ionic](https://img.shields.io/badge/Ionic-02569B?style=for-the-badge&logo=ionic&logoColor=white)
![Angular JS](https://img.shields.io/badge/AngularJS-E23237?style=for-the-badge&logo=angularjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)


#### Back and front-end
![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![JQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Node.JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-212121?style=for-the-badge&logo=socket.io&logoColor=white)

#### Machine learning)
![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white) 
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

#### IoT
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Raspberry PI](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)


### Misc
![LaTeX](https://img.shields.io/badge/LaTeX-1f425f.svg)


### Trust me, acording with Github API, these are my "Most Used Languages":


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dherediat97&theme=vue&layout=compact)

If you wanna see more about me, such as Past projects and stuff, you can check my ["Portfolio"](https://dherediat97.github.io/SlimPortoflio/)
 yet in progress


### My "hobbie work" about this year

![Github Stats](https://github-readme-stats.vercel.app/api?username=dherediat97&theme=vue)

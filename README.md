### [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Sixtyfour+Convergence&color=%236b1117&multiline=true&repeat=false&size=25&height=75&width=800&duration=5000&lines=I'm+David+Heredia!;Mobile+Application+Developer)](https://git.io/typing-svg)
     
     🥇 Android Development
     🥈 Hybrid Development
     🥉 iOS Development
     
### My profile Response Data Class

```kotlin
package this.is.my.profile

data class Profile (
    val person: Person,
    val job: String,
    val jobDetail: JobDetail,
    val hobbies: List<String>,
    val wantLearn: List<String>
)

data class JobDetail (
    val currentJob: String,
    val lastJobs: List<String>
)

data class Person (
    val name: String
)

fun main() {
    val myProfile = Profile()
    myProfile.name = "David Heredia Tartajo"   
    myProfile.job = "Developer"
    myProfile.jobDetail = JobDetail(
     currentJob= "Mobile Developer", 
     lastJobs = arrayListOf(
        "Ingenico Developer",
        "Web Developer",
        "Backend Developer",
        "Front Developer"
    )
    myProfile.hobbies =  arrayListOf("Coding", "Animation", "Music", "Gaming", "TV", "Movies", "Anime")
    myProfile.wantLearn =  arrayListOf("Animation", "3D Design", "Robotics")
}
```

### My profile request

``` http
GET https://david.heredia.dev/profile HTTP/1.1
Host: www.github.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.0.0 Safari/537.36 OPR/113.0.0.0
Accept: text/html, application/xhtml+xml, application/xml;q=0.9, image/webp, */*;q=0.8
```

### My profile request response
```http
HTTP/1.1 200 OK
Content-Type: application/json
Date: Mon, 14 Oct 2024 12:00:00 GMT
Last-Modified: Mon, 14 Oct 2024 12:00:00 GMT
Content-Length: 355
{
    "name": "David Heredia Tartajo",
    "currentJob":"Mobile Developer", 
    "lastJobs":[
        "Ingenico Developer", 
        "Web Developer", 
        "Backend Developer", 
        "Front Developer"
    ],
    "hobbies": ["Coding", "Animation", "Music", "Gaming", "TV", "Movies", "Anime"],
    "wantLearn": ["Animation", "3D Design", "Robotics"]
}
```

## What I'm into
### Programming Languages
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#)
[![Objective-C](https://img.shields.io/badge/Objective--C-%233A95E3.svg?&logo=apple&logoColor=white)](#)
[![Kotlin](https://img.shields.io/badge/Kotlin-%237F52FF.svg?logo=kotlin&logoColor=white)](#)
[![Swift](https://img.shields.io/badge/Swift-F54A2A?logo=swift&logoColor=white)](#)
[![PHP](https://img.shields.io/badge/php-%23777BB4.svg?&logo=php&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=fff)](#)
[![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?logo=dart&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=fff)](#)
[![Sass](https://img.shields.io/badge/Sass-C69?logo=sass&logoColor=fff)](#)


#### Android development
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#)
[![Kotlin](https://img.shields.io/badge/Kotlin-%237F52FF.svg?logo=kotlin&logoColor=white)](#)
![OkHTTP](https://img.shields.io/badge/OKHTTP-262626?style=for-the-badge&logo=square&logoColor=blue) 
![Retrofit](https://img.shields.io/badge/Retrofit-262626?style=for-the-badge&logo=square&logoColor=blue) 
![JetPack Compose](https://img.shields.io/badge/JetPack%20Compose-Green)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

### iOS development
[![Swift](https://img.shields.io/badge/Swift-F54A2A?logo=swift&logoColor=white)](#)
[![Objective-C](https://img.shields.io/badge/Objective--C-%233A95E3.svg?&logo=apple&logoColor=white)](#)
[![Xcode](https://img.shields.io/badge/Xcode-007ACC?logo=Xcode&logoColor=white)](#)

### Hybrid development
![Ionic](https://img.shields.io/badge/Ionic-02569B?style=for-the-badge&logo=ionic&logoColor=white)
![Framework7](https://img.shields.io/badge/framework7-%23EE350F.svg?style=for-the-badge&logo=framework7&logoColor=white)
![Apache Cordova](https://img.shields.io/badge/Apache%20Cordova-Green)
![Angular JS](https://img.shields.io/badge/AngularJS-E23237?style=for-the-badge&logo=angularjs&logoColor=white)

![Ionic](https://img.shields.io/badge/Ionic-02569B?style=for-the-badge&logo=ionic&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-Green)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

### Flutter development
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
[![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?logo=dart&logoColor=white)](#)

### Windows development
[![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?logo=Eclipse&logoColor=white)](#)
[![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white)](#)
[![Visual Studio](https://custom-icon-badges.demolab.com/badge/Visual%20Studio-5C2D91.svg?&logo=visual-studio&logoColor=white)](#)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)

### Backend Stack
![Node.JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-212121?style=for-the-badge&logo=socket.io&logoColor=white)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=fff)](#)
[![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff)](#)
![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)
![Apache Ant](https://img.shields.io/badge/Apache%20Ant-A81C7D?style=for-the-badge&logo=Apache%20Ant&logoColor=white)

### TPV Stack
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=fff)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
![Ingenico](https://img.shields.io/badge/Ingenico-Green)


### CI & CD
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white)](#)
[![Dependabot](https://img.shields.io/badge/Dependabot-025E8C?logo=dependabot&logoColor=fff)](#)
[![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?logo=gitlab&logoColor=fff)](#)

### App Stores SDK
![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)
![Play Store](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)


### Cloud Systems
[![Heroku](https://img.shields.io/badge/Heroku-430098?logo=heroku&logoColor=fffe)](#)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?logo=Firebase&logoColor=white)](#)

### Code Coverage
[![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?logo=sonarcloud&logoColor=fff)](#)

### Collaboration Tools
[![Asana](https://img.shields.io/badge/Asana-F06A6A?logo=asana&logoColor=fff)](#)
[![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=fff)](#)
[![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=fff)](#)
[![Trello](https://img.shields.io/badge/Trello-0052CC?logo=trello&logoColor=fff)](#)

### Databases
[![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white)](#)
[![MariaDB](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-039BE5?logo=Firebase&logoColor=white)](#)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff)](#)

### Documentation
[![Sphinx](https://img.shields.io/badge/Sphinx-000?logo=sphinx&logoColor=fff)](#)

### Package Managers
[![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff)](#)
[![Yarn](https://img.shields.io/badge/Yarn-2C8EBB?logo=yarn&logoColor=fff)](#)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?logo=pypi&logoColor=fff)](#)
[![NuGet](https://img.shields.io/badge/NuGet-004880?logo=nuget&logoColor=fff)](#)

### ORM
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)

### Front End
![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![JQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=fff)](#)

### Machine learning)
![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white) 
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

### IoT
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Raspberry PI](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)
![Espressif](https://img.shields.io/badge/espressif-E7352C.svg?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Mosquitto](https://img.shields.io/badge/mosquitto-%233C5280.svg?style=for-the-badge&logo=eclipsemosquitto&logoColor=white)

### Version Control
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![Bitbucket](https://img.shields.io/badge/bitbucket-%230047B3.svg?style=for-the-badge&logo=bitbucket&logoColor=white)

### Misc
![LaTeX](https://img.shields.io/badge/LaTeX-1f425f.svg)

### Some data about my GitHub projects
<img height="49%" align="left" src="https://github-readme-stats.vercel.app/api?username=dherediat97" />
<img height="49%" align="right" src="https://github-readme-stats.vercel.app/api/top-langs?username=dherediat97&layout=compact&langs_count=8&card_width=320" />

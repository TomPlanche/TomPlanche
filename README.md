<p align="center">
    <img src="https://github.com/TomPlanche/TomPlanche/blob/main/gifPerso.gif" alt= "MyNameGif">
</p>

---
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tomPlanche&bg_color=071A2C&theme=tokyonight&layout=compact" align="right" height="200" />
<img src="https://github-readme-stats.vercel.app/api?username=TomPlanche&bg_color=071A2C&icon_color=4194FD&show_icons=true&count_private=true&theme=tokyonight&line_height=27&text_color=FFFFFF" align="right" height="178" />

<div style="height: auto;">
    <div>
        <ul>
            <li>
                <p>
                    Tom Planche, <strong>19</strong> ans.
                </p>
            </li>
            <li>
                <p>
                    🧑‍💻 à l'<a href="https://www.iutbayonne.univ-pau.fr">IUT de Bayonne et du Pays-Basque</a>.
                </p>
            </li>
            <li>
                <p>Passionné par les drones, la technologie et la programmation.</p>
            </li>
        </ul>
    </div>
</div>


--- 

<p align = "center">
    <img src = "https://img.shields.io/badge/-Kali-2777FF?logo=Linux&style=for-the-badge&logoColor=white">
    <img src = "https://img.shields.io/badge/-Mac_OS%20-%23121011.svg?logo=Apple&style=for-the-badge&logoColor=white">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/swift%20-red.svg?&style=for-the-badge&logo=swift&logoColor=white"/>
    <img src="https://img.shields.io/badge/c++%20-%2300599C.svg?&style=for-the-badge&logo=c%2B%2B&ogoColor=white"/>
    <img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/html5%20-red.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
    <img src="https://img.shields.io/badge/css3%20-%2300599C.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Adobe-red??&style=for-the-badge&logo=adobe&logoColor=white"/>
</p>

---

<p align = "center">
    <img src = "https://img.shields.io/badge/-tomplanche@icloud.com-c14438?style=flat-square&logo=ICloud&logoColor=white&link=mailto:tomplanche@icloud.com&color=blue">
</p>

<pre>
    <code>
        /**
        * @file   me.cpp
        * @author T.PLANCHE
        * @brief  My Resume
        * @date   30 sept. 2021
        **/

        #include <iostream>
        #include <string>
        #include <vector>
        #include <ctime>

        class Tools {
            public:
                std::vector<std::string> hardware;
                std::vector<std::string> softwares;
        };

        class Person {
            public:
                signed short int dateOfBirth;
                std::string firstName;
                std::string lastName;
                std::vector<std::string> files;
                Tools tools;
                std::vector<std::string> passions;

                signed short int age() {
                    time_t now = time(0);
                    tm *ltm = localtime(&now);

                    return (
                        ltm->tm_year - dateOfBirth + 1900
                    );
                }
        };


        int main(void)
        {
            Person me;

            me.dateOfBirth = 2002;
            me.firstName = "Tom";
            me.firstName = "Planche";

            me.files = {
                ".cpp",
                ".swift",
                ".py",
                ".html",
                ".css",
                ".ai",
                ".ps",
                ".aep"
            };

            me.tools.hardware = {
                "m1 mac mini 16Gb",
                "m1 macBook pro 8Gb",
                "ipad pro 12,9\" 2020",
                "iphone 12 pro",
            };

            me.tools.softwares = {
                "vscode",
                "xcode",
                "pycharm",
                "clion",
                "github",
                "sketch",
                "after effects",
                "illustrator",
                "affinity photo",
                "photoshop",
                "final cut pro"
            };

            me.passions = {
                "drones",
                "cars",
                "technology",
                "programming"
            };
            
            return 0;
        }
    </code>
</pre>
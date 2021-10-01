<p align="center">
    <img src="https://github.com/TomPlanche/TomPlanche/blob/main/gifPerso.gif" alt= "MyNameGif">
</p>

<h4>

```cpp
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

using std::vector;
using std::string;

struct Tools {
    vector<string> hardware;
    vector<string> softwares;
};

struct Person {
    signed short int dateOfBirth;
    string firstName;
    string lastName;
    string mail;
    string school;
    vector<string> files;
    Tools tools;
    vector<string> passions;

    signed short int age() {
        time_t now = time(0);
        tm *ltm = localtime(&now);

        return (ltm->tm_year - dateOfBirth + 1900);
    }
};


int main(void)
{
    Person me;

    me.dateOfBirth = 2002;
    me.firstName = "Tom";
    me.firstName = "Planche";

    me.mail = "tomplanche@icloud.com";

    me.school = "University Institute of Technology of Bayonne.";

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
        "iphone 12 pro"
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

    std::cout << me.age() << std::endl;

    return 0;
}

```

</h4>

<p align = "center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tomPlanche&bg_color=071A2C&theme=tokyonight&layout=compact" height="177" align="left"/>
<img src="https://github-readme-stats.vercel.app/api?username=TomPlanche&bg_color=071A2C&icon_color=4194FD&show_icons=true&count_private=true&theme=tokyonight&line_height=27&text_color=FFFFFF" height="177" align="right"/>
</p>
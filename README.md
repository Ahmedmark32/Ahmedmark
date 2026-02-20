<h1 align="center">Hi there, I'm [Your Name] 👋</h1>
<h3 align="center">💻 C++ Learner | 📚 Data Structures Enthusiast | 🌱 Always Growing</h3>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=25&pause=1000&color=2F81F7&center=true&vCenter=true&width=435&lines=C%2B%2B+Learner;OOP+Completed!;Next+Stop%3A+Data+Structures;100%2B+Problems+Solved" alt="Typing SVG" />
</div>

<!-- Animated C++ Banner -->
<p align="center">
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="200px">
</p>

## 🧠 My Programming Journey

```cpp
#include <iostream>
#include <string>
#include <vector>

class ProgrammingJourney {
private:
    std::string name = "Your Name";
    std::string currentFocus = "Data Structures";
    std::vector<std::string> completedTopics;
    std::vector<std::string> learningNow;
    
public:
    ProgrammingJourney() {
        completedTopics = {
            "✅ C++ Basics",
            "✅ Object Oriented Programming",
            "✅ Basic Problem Solving",
            "🎯 100+ Coding Problems"
        };
        
        learningNow = {
            "📚 Arrays & Strings",
            "📚 Linked Lists",
            "📚 Stacks & Queues",
            "📚 Trees & Graphs",
            "📚 Sorting Algorithms"
        };
    }
    
    void displayJourney() {
        std::cout << "🎯 Current Goal: Master " << currentFocus << std::endl;
        std::cout << "\n📖 What I've Learned:" << std::endl;
        for (const auto& topic : completedTopics) {
            std::cout << "  " << topic << std::endl;
        }
        std::cout << "\n🔥 What I'm Learning Now:" << std::endl;
        for (const auto& topic : learningNow) {
            std::cout << "  " << topic << std::endl;
        }
    }
};

int main() {
    ProgrammingJourney myJourney;
    myJourney.displayJourney();
    return 0;
}

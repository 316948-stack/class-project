# class-project
music headphones recommendation 
print("Wireless Headphone Recommendation Program 🎧")

# Ask questions
hours = int(input("How many hours per day will you use the headphones? "))
use = input("What will you mainly use them for? (music/gym/studying): ").lower()
comfort = input("Is comfort very important to you? (yes/no): ").lower()
eq = input("Do you like adjustable bass or EQ settings? (yes/no): ").lower()

# Decision rules
if use == "studying" and hours >= 4 and comfort == "yes":
    print("Based on your answers, you should consider the Sony WH-1000XM5 for comfort and long study sessions.")
elif use == "gym" and eq == "yes":
    print("Based on your answers, the Beats Fit Pro would be a great choice for workouts and strong bass.")
elif use == "music" and eq == "yes":
    print("Based on your answers, the Sony WH-1000XM5 is a great option for music with customizable sound.")
elif comfort == "yes" and hours >= 2:
    print("Based on your answers, Bose QuietComfort headphones would suit your needs well.")
else:
    print("Based on your answers, standard wireless headphones should work fine for your needs.")

Project Title

Wireless Headphone Recommendation Program 🎧

Problem

Choosing the right wireless headphones can be confusing because different people have different needs (comfort, usage time, gym vs studying, sound preferences). This project matters because it helps users quickly get a recommendation without researching dozens of options.

Solution

The program asks users a few simple questions about how they plan to use their headphones, how long they’ll wear them, and what features they care about (comfort and EQ).
Based on their answers, the program uses conditional logic (if/elif/else) to recommend a suitable wireless headphone model that best matches their needs.

Tools

Language: Python

Libraries: None (built-in Python only)

Concepts Used: Input/output, conditionals, variables, string handling

Results

The program successfully provides personalized headphone recommendations.
For example:

A student studying for 4+ hours gets recommended Sony WH-1000XM5 for comfort.

A gym user who likes bass gets Beats Fit Pro.

Users who want comfort but don’t fit specific cases get Bose QuietComfort.

Learning

One important thing learned from this project was how to use conditional statements to make decisions based on user input and create a simple rule-based recommendation system.
Built a Python-based recommendation program that suggests wireless headphones based on user preferences using conditional logic and user input, resulting in personalized and useful headphone recommendations.

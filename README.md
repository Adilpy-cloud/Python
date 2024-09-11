# Python
For presentation 

      def greet(name):
    """Greets the user with a personalized message."""
    print(f"Honorable {name}, it is a pleasure to meet you.")

     def describe_school():
    """Describes the school with key elements."""
    print("Name: Adamjee Cantonment Public School\n"
          "Students: More than 8000\n"
          "Established: 1960\n"
          "Situated by: Gul Mohammad Adamjee\n"
          "Library: There is a beautiful library in our school that helps us in study and learning.\n"
          "Playground: There is a big playground in our school.\n"
          "Teachers: The teachers of ACPS are very kind and helpful. They always teach us about new things and how to be honest in life.\n"
          "Number of teachers: More than 230\n"
          "Clubs: There are more than 20+ clubs in our school.\n"
          "Current Principal: Ltc Md. Habibur Rahman, SGP, PPM, afwc, psc, Inf")

      def describe_it_club():
    """Describes the IT club with key elements."""
    print("Established: 2015\n"
          "Members: 700+\n"
          "Achievements: A lot of achievements in various sectors such as AIUB present CS Fest 2024, BAFSK Tri school event 2023, Xenon Science Congress present science booster 3.1, Techrivia 2.0 best institute.\n"
          "Current Moderator: B.M Alamgir Badsha\n"
          "Founder: Tarek Mahmud_Fatin bin fereous\n"
          "Session: Generally held on Saturdays of every week in the computer lab.\n"
          "Topics: Graphic design, programming, animation, Microsoft Word, Microsoft Excel, PowerPoint presentation, etc.\n"
          "Future topics: Cyber security and AI (artificial intelligence)")

    def main():
    """Main function to get user input and call the greet and description functions."""
    name = input("Please enter your name: ")
    greet(name)

    print("If you may, can I describe about our school and our IT club?")
    choice = input("Please enter 'yes' or 'no': ")

    if choice.lower() == "yes":
        print("Sir, which topic do you want to know about?\n"
              "1) About School\n"
              "2) About IT Club\n")
        topic = input("Please enter your choice (1 or 2): ")

        if topic == "1":
            describe_school()
        elif topic == "2":
            describe_it_club()
        else:
            print("Invalid choice. Please enter 1 or 2.")

    else:
        print("Thank you for your time. It was a pleasure meeting you.")

    print("I hope this information was helpful. Please feel free to ask any further questions.")
    print("Thank you for your interest in our school and IT club.")
    print("We are very garteful to meet you.")
    print("Have a wonderful day!")

    if __name__ == "__main__":
    main()


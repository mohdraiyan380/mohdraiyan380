class MohdRaiyan:
    def __init__(self):
        self.name = "Mohd Raiyan"
        self.location = "India"
        self.profession = "Aspiring Data Data Analysis & Tech Entrepreneur"
        self.skills = ["Python", "SQL", "Data Analysis", "Problem Solving", "Business Thinking"]
        self.focus = [
            "Building a SaaS-based School Management System",
            "Learning Data Analysis & SQL",
            "Creating data-driven solutions"
        ]
        self.values = ["Creativity", "Growth", "Smart Risk-Taking", "Innovation"]
    
    def say_hello(self):
        print(f"Hi, I'm {self.name} — passionate about tech, business, and turning ideas into reality!")

    def current_mission(self):
        return "Helping schools go digital with a smart SaaS platform"

    def future_goals(self):
        return [
            "Work as a Data Analyst",
            "Launch impactful tech products",
            "Keep learning & growing"
        ]

# Create an instance and introduce
raiyan = MohdRaiyan()
raiyan.say_hello()

# Hi there, I'm Chaitali! (Pronounced as Choitali) 👋

class AboutMe:
    def __init__(self):
        self.name = "Chaitali"
        self.pronunciation = "Choitali"
        self.title = "CS-PhD Student"
        self.affiliation = "DGIST"
        self.lab = "CELL Lab"
        self.roles = ["AI Researcher", "LLMs Enthusiast"]

    def research_focus(self):
        return {
            "main_areas": ["Efficient AI", "Large Language Models (LLMs)"],
            "past_experience": ["Vision Models", "Generative Models", 
                                "Data Generalization", "Classification"]
        }

    def interests(self):
        return [
            "Knowledge Distillation for smaller, faster models",
            "Model pruning, quantization, and fine-tuning",
            "Exploring AI scalability while optimizing performance"
        ]

    def connect(self):
        return "Visit my website: https://cv-chaitali.github.io/myvision.github.io/"

# Create an instance
me = AboutMe()

# Display information
print("🎓 Title:", me.title)
print("🌟 Research Focus:", me.research_focus())
print("🌱 Current Interests:", me.interests())
print("🔗 Connect with me:", me.connect())

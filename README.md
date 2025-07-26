## Hi there 👋

#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Mugisha Gemimah Gloire"
        self.role = "Full-Stack Developer | Co-founder at PrismShop"
        self.language_spoken = ["en_US", "rw_RW", "fr_FR"]
        self.current_projects = [
            "Sign Language Translator using AI & 3D Avatar",
            "Smart Agriculture Platform",
            "PrismShop – Revolutionizing E-commerce in Africa"
        ]

    def say_hi(self):
        print(f"👋 Hi, I'm {self.name} — {self.role}.")
        print("🚀 I'm passionate about building impactful tech that bridges innovation and inclusion.")
        print("🌍 Languages I speak:", ", ".join(self.language_spoken))
        print("\n📌 Current Projects:")
        for project in self.current_projects:
            print(f"   - {project}")
        print("\nThanks for stopping by! Feel free to explore my work and reach out for collaboration.")


me = SoftwareEngineer()
me.say_hi()


# 🔧 OxkzToolz GitHub Profile

class OxkzToolz:

    username: str = "OxkzToolz"
    status: str = "Beta tools dropping soon."
    active_projects: int = 5

    @staticmethod
    def skills() -> dict:
        return {
            "generators": ["Instagram", "Facebook", "TikTok"],
            "automation": ["Follow bots", "Captcha solvers", "Platform tools"],
            "current_focus": "EzSolverV2 (ReCaptcha V2 API)"
        }

    @staticmethod
    def tech_stack() -> list:
        return [
            "Python", "Flask", "JavaScript", "Docker",
            "Git", "Linux", "SQLite"
        ]

    @staticmethod
    def contact() -> dict:
        return {
            "discord": "ComingSoon#0000",
            "status": "Discord server launching soon",
            "github": "https://github.com/OxkzToolz"
        }


class Projects(OxkzToolz):

    @staticmethod
    def showcase() -> list:
        return [
            {"name": "Instagram Generator", "features": ["Email", "Proxy Support"]},
            {"name": "Facebook Generator", "features": ["Realistic Test Accounts"]},
            {"name": "TikTok Generator", "features": ["Bypass Techniques"]},
            {"name": "EzSolverV2", "status": "Beta", "type": "Captcha Solver API"},
            {"name": "Follow Bots", "targets": ["Instagram", "TikTok", "More"]}
        ]

    @staticmethod
    def coming_soon() -> list:
        return [
            "Discord support hub",
            "Admin credit system",
            "Tool marketplace"
        ]


if __name__ == "__main__":
    dev = OxkzToolz()
    print(f"Welcome to {dev.username}'s GitHub!")
    print("Explore bots, tools, and automation projects 💻")


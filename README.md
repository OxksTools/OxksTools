# ⚙️ OxkzToolz GitHub Profile

class OxkzToolz:
    """Builder of automation tools, generators, and APIs."""

    username: str = "OxkzToolz"
    origin: str = "Self-taught"
    active: bool = True
    focus: str = "Fast & creative problem-solving"

    @staticmethod
    def contact() -> dict:
        return {
            "discord": "Launching soon...",
            "status": "Discord server in development",
            "github": "https://github.com/OxkzToolz"
        }

    @staticmethod
    def tech_stack() -> list:
        return [
            "Python", "Flask", "JavaScript", "Docker", "Linux", "Git"
        ]

    @staticmethod
    def tools_built() -> list:
        return [
            "Instagram Generator",
            "Facebook Generator",
            "TikTok Generator",
            "Follow Bots",
            "EzSolverV2 (Captcha Solver API)"
        ]

    @staticmethod
    def projects() -> dict:
        return {
            "generators": {
                "Instagram": "Email + Proxy Supported",
                "Facebook": "Realistic testing accounts",
                "TikTok": "Includes bypass routines"
            },
            "bots": ["Follow automation", "Utility tools", "Test kits"],
            "captcha_solver": {
                "name": "EzSolverV2",
                "status": "Beta",
                "price_per_1k": "$0.50 (0.5 credits/solve)",
                "free_credits": 5
            }
        }

    @staticmethod
    def roadmap() -> list:
        return [
            "Launch Discord Hub",
            "Drop early access tools",
            "Add payment + credit system",
            "Release full EzSolverV2 API docs"
        ]


if __name__ == "__main__":
    dev = OxkzToolz()
    print(f"🚀 Welcome to {dev.username}'s GitHub!")
    print("Explore tools, APIs, and automation projects.")

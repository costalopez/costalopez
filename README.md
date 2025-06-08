# Hi, I'm Costa

A bit about me and what I’m up to:

```python
from life import Creativity

class Life(Creativity):
    def __init__(self):
        self.education = "Based in Georgia, lifelong learner"
        self.current_job_title = "Software Engineer"
        self.current_company = "BrightTech Solutions (Atlanta, GA)"
        self.user = self.getUser() or None
        self.visitedUser = User

    # ... 26 lines hidden

    def current_projects(self) -> None:
        self.currently_learning = "Improving TypeScript skills"
        self.currently_working_on = "Work projects and some side coding"
        self.excited_for = "Experimenting with AI and blockchain stuff when I can"

    def contact_me(self) -> str:
        self.email = "costalopez@gmail.com"
        return self.email

    def follow_me(self) -> None:
        if self.user not in self.visitedUser.getWhoTheyFollowing():
            print(f"Hey {self.user.getUserName()}, looks like you're not following Costa yet 😐")
        else:
            print("Thanks for following Costa!")

if __name__ == '__main__':
    life = Life()
    life.follow_me()

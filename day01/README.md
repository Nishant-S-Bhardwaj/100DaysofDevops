🛠️ Day 01: Getting My Hands Dirty with Git & GitHub
📖 What I Did

Today officially marked Day 1 of my DevOps journey, and honestly, it completely changed the way I think about Git and GitHub.

Before today, I used to see Git as nothing more than a tool to save my code online after finishing a project. My workflow was basically:

git add .
git commit -m "done"
git push

And that's it.

But after spending the day learning and experimenting, I realized Git is much more than a backup tool—it's the foundation of how modern development teams collaborate without stepping on each other's toes.

I split my learning into two parts:

Understanding the concepts behind Git and version control.
Getting my hands dirty with practical labs and intentionally breaking things to learn how to fix them.
🧠 Key Things I Learned
🌿 Feature Branching = A Safe Playground

One of the biggest lessons was understanding why branches exist.

Instead of making changes directly to the main codebase, developers create separate branches to work on new features or bug fixes. This keeps the production code safe while allowing experimentation.

If something breaks? No problem. The main branch remains untouched.

🔄 How Code Actually Moves Around

I finally understood the complete journey of code:

Working Directory
        ↓
Staging Area (git add)
        ↓
Local Repository (git commit)
        ↓
Remote Repository (git push)

And how teams stay in sync using:

git push
git pull
git fetch
git merge
⚔️ Merge Conflicts Aren't That Scary

Merge conflicts always sounded intimidating.

Today I learned they're simply Git's way of saying:

"Two people changed the same piece of code. Please tell me which version you want."

I practiced resolving conflicts manually by:

Opening the conflicted file
Reading the conflict markers
Choosing the correct code
Removing the markers
Committing the final result

Seeing the merge complete successfully felt incredibly satisfying.

🔍 Fetch vs Pull

This was one of my favorite takeaways.

git pull immediately downloads and merges changes.
git fetch downloads changes without modifying my current work.

I like thinking of git fetch as a reconnaissance mission—it lets me inspect what's happening upstream before bringing those changes into my branch.

🚀 How I Learned

Instead of hopping between random tutorials, I followed:

Rahul Wagh's Git and GitHub: Beginner to Pro course

The explanations were structured and easy to follow, which helped me build a strong foundation.

But I also learned something important:

Watching videos doesn't build skills. Typing commands does.

So after every lesson, I immediately jumped into hands-on practice.

💻 Hands-on Practice (KodeKloud Labs)

Most of my day was spent inside KodeKloud's Git Labs, where I practiced real-world Git workflows.

✅ Repository Setup

Created repositories from scratch and configured Git globally.

git init
git config --global user.name
git config --global user.email
✅ Branching & Switching

Created and switched between branches to safely experiment with changes.

git checkout -b feature-branch
✅ Working with Remotes

Connected local repositories to remote servers and practiced pushing and pulling code.

git remote add origin <repo-url>
git push
git pull
✅ Resolving Merge Conflicts

The lab intentionally created merge conflicts for practice.

At first, the error screen looked terrifying.

But after carefully reading the conflict markers and fixing the file manually, I successfully completed the merge and committed the changes.

Definitely one of the most rewarding moments of the day.

🎯 Day 01 Reflection

Today wasn't about memorizing Git commands.

It was about understanding why Git exists and how developers use it to collaborate, track changes, and ship software safely.

The biggest lesson?

Don't be afraid to break things. Some of the best learning happened when I made mistakes and figured out how to recover from them.

Looking forward to Day 02. 🚀

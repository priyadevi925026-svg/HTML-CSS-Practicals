# Assignment 2: Pushing and Cloning a Repository

**Course:** HTML and CSS Introduction Lab (BCS352)  
**Institution:** Invertis University, Bareilly  
**Degree:** B.Tech CSE - Second Year  

---

### Aim
Send your commits to a second repository on your computer and make a copy of it with clone.

---

### Tasks
1. Run git init --bare ../html-remote inside html-lab to create an empty repository next to it. Then add it as origin with git remote add origin ../html-remote, and run git remote -v.
2. Push your commits to origin with git push origin main. If git status shows On branch master, use git push origin master instead.
3. Go up one folder from html-lab (cd ..) and clone html-remote into a new folder named html-copy with git clone html-remote html-copy. Then go into html-copy and run git log --oneline.

---

### Sample Expected Output
git remote -v lists origin for fetch and for push. The push ends with a line that shows the branch, such as main -> main. The same commits appear in html-copy as in html-lab.

---

### Submission Guidelines
**Submit:** A copy of the terminal output of each task.  
*Remember to include your Name, Roll Number, and Assignment Number (2) at the top of each file.*

---

### Directory Contents
- `index.html` - Primary or index HTML document for the assignment.
- `style.css` - Associated CSS styles.
- `images/` - Folder containing screenshots (`screenshot.png`) and lab image assets.

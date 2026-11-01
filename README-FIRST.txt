BCS554 – HTML & CSS Development Lab: Solutions
Student name used in file comments: Aditya Sharma
IMPORTANT: Replace "ENTER YOUR ROLL NUMBER" in each source file with your actual university roll number.
Also replace placeholder email addresses and image filenames where instructed.

HOW TO USE
1. Extract this ZIP file.
2. Open the extracted folder in VS Code (File > Open Folder).
3. Each assignment has its own folder. Open the named HTML file in a browser (double-click it, or use VS Code Live Server).
4. HTML files with embedded CSS are self-contained. For linked stylesheets, keep the HTML and CSS files in the same assignment folder.
5. For Assignments 5 and 15, put the image provided by your instructor in the relevant images folder and update the image filename in the HTML.
6. Capture your own browser screenshot for each task and keep it with your submission. The assignment brief asks for screenshots; screenshots are not fabricated or included in this source-code pack.

GIT TASKS – ASSIGNMENT 1
Open VS Code Terminal / PowerShell in the folder where you want html-lab to be created, then run:

mkdir html-lab
cd html-lab
git init
git config --local user.name "Aditya Sharma"
git config --local user.email "YOUR_EMAIL@example.com"
git config user.name
git config user.email

Create index.html (the starter file is in Assignment-01-Git/index.html; copy it into this html-lab folder), then run:
git status
git add index.html
git commit -m "Add home page"

Edit index.html and add this heading below the first h1:
<h2>Next Meeting</h2>

Then run:
git add index.html
git commit -m "Add next meeting heading"
git log --oneline

If Git says your branch is master rather than main, use master in the later push command.

GIT TASKS – ASSIGNMENT 2
Run these commands from inside html-lab:
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
git push origin main
(If your branch is master, run: git push origin master)

Then:
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline

EXPECTED CHECKS
- Assignment 1: git config commands print the configured name/email; git log shows two commits.
- Assignment 2: git remote -v shows origin for fetch and push; clone contains the same two commits.
- Assignment 3: first.html tab title is "My First Page"; headings.html has h1/h2/h3 and paragraph; text-format.html demonstrates strong, em and br.
- Assignment 4: attendance-fixed.html has a closed h1 and properly closed paragraphs.
- Assignment 5: links navigate between home.html and portfolio.html; replace placeholder image.
- Assignment 6: unordered, nested ordered and description lists are used as required.
- Assignment 7: About and Contact anchors point to #about and #contact; replace placeholder email.
- Assignment 8: labels are associated with inputs; radio buttons share one name; required fields are marked required.
- Assignment 9: two-student averages are Maths 71 and Science 77.5.
- Assignment 10: linked.html loads style.css from the same folder.
- Assignment 11: variables use the exact values specified in the lab sheet.
- Assignment 12: content-box outer width is 250px; border-box outer width is 200px.
- Assignment 13: flex navigation, centred cards and wrapping cards are implemented.
- Assignment 14: grid columns, auto-fill gallery and named grid areas are implemented.
- Assignment 15: mobile-first layout changes at 600px; image scales; heading size changes at 600px.

SUBMISSION
Submit the exact files requested by each assignment, plus screenshots captured after opening the pages in a browser. For Assignments 1 and 2, copy the actual terminal output into a document or screenshots. Do not submit made-up terminal output; run the commands on your own computer.

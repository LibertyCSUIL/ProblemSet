HOWTO Submit problem sets
--------------------------------

Step One, clone and cd into directory:

(don't clone if you've already done so previously)
git clone https://github.com/LibertyCSUIL/ProblemSet.git
cd ~/Programming\ Team/Github\ repos/ProblemSet/


Step Two, update the repository:

git pull


Step Three, create and enter into your named working directory:

EXAMPLE: mkdir 2017/GavinD/

(don't create the directory if it already exists)

mkdir <year>/<name>/
cd <year>/<name>/

Step Four, complete assignment.

Step Five, add the problems folder to the repository:

git add <folder>


Step Six, commit the name of the problem set with the date and time:

EXAMPLE: git commit -m "Region2010, 07/02/2017 06:27PM"

git commit -m "<assignment>, <date> <time>"


Step Seven, push changes:

git push origin master



REPEAT EVERY TIME 

(Grades will be posted as <assignment.txt> in your named directory)

These are the commands I used to add new file and commit into git

git init
git clone https://github.com/Skanda09118/Envision2025_tasks
# I modified one of the file, then want to commit the file into git
git add .
git commit -m "First change"
git push origin main

#NOW Adding movie to fun branch

git branch fun
git checkout fun
echo "John Wick" > movie.env
git add .
